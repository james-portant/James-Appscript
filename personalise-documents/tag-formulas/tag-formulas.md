---
description: >-
  Sometimes you might need to calculate values within your document template.
  Within Portant you can add calculations directly within tags simply by include
  = at the beginning of the tag.
---

# Tag Formulas

For example you may have the field "Line Item Price" from your source and you would like to display the value in your document with a 10% percent tax applied. This can be calculated by multiplying (`*`) the Line Item Price field by 1.1. The Tag formula to do so would look like this:

```
{{= Line Item Price * 1.1}}
```

### Arithmetic

The follow arithmetic operations can can be used in Tag Formulas:

<table><thead><tr><th width="111">Symbol</th><th>Operation</th></tr></thead><tbody><tr><td><code>+</code></td><td>Addition</td></tr><tr><td><code>*</code></td><td>Multiplication</td></tr><tr><td><code>-</code></td><td>Subtraction</td></tr><tr><td><code>/</code></td><td>Division</td></tr></tbody></table>

Multiple operators and parentheses `(` and `)` can be used to make more complex expressions.

### Builtin Formulas

Similar to tools like Google Sheets and Excel. Certain pre-made formulas can be used within tags. For example the `ROUND` formula can be used to limit a numeric value to set number of decimal places.

```
{{Line Item Price}} -> 24.1234
{{=ROUND(Line Item Price, 2) -> 24.12
{{=ROUND(Line Item Price) -> 24
```

The following builtin formulas exist within Portant

<table><thead><tr><th width="349">Formula</th><th>Description</th></tr></thead><tbody><tr><td><code>ROUND(Tag, [Places])</code></td><td>Rounds the numeric value of <code>Tag</code> to the number of decimal <code>Places</code> specified. The second variable can be omitted to round the value to a whole number.</td></tr><tr><td><code>DEFAULT(Tag, Default Value)</code></td><td>Provide a value to be used in the case that the value of the provided tag is blank.</td></tr><tr><td><code>ADD(Tag 1, Tag 2, [...])</code></td><td>Adds the numeric value of two or more tags together. This formula is the same as simply using "+".</td></tr><tr><td><code>MULTIPLY(Tag 1, Tag 2, [...])</code></td><td>Multiplies the numeric value of two or more tags together. This formula is the same as simply using "*".</td></tr><tr><td><code>TRUNCATE(Tag, Length)</code></td><td>Shortens the text based value of <code>Tag</code> by the specified <code>Length</code>. </td></tr><tr><td><code>LOWER(Tag)</code></td><td>Converts the value of tag to lowercase text.</td></tr><tr><td><code>UPPER(Tag)</code></td><td>Converts the value of tag to UPPERCASE text.</td></tr></tbody></table>



```
[ ] Specifies that this paramater is optional.
```

Note, direct values can be used in the place of all tags and vice versa.

## Numeric

### Numeric Aggregated Formulas

Particular builtin formulas are specifically designed to work with [Data Grouping](../../sources/google-sheets/data-grouping.md) workflows in Portant and will aggregate all the grouped values of the specified tag. A particular useful formula is `SUM` which will add together all values for the specified tag. This is an effective way to calculate totals within your template.

```
Within a Data Grouping Table:
+-----------------------------+
|1. {{Line Item Price}} -> 10 |
+-----------------------------+
|2. {{Line Item Price}} -> 20 |
+-----------------------------+
|3. {{Line Item Price}} -> 30 |
+-----------------------------+

{{=SUM(Line Item Price)}} -> 60
```

The follow numeric aggregated formulas exits within Portant:

<table><thead><tr><th width="286">Formula</th><th>Description</th></tr></thead><tbody><tr><td><code>SUM(Tag)</code></td><td>Adds together all the values for <code>Tag</code> provided</td></tr><tr><td><code>PRODUCT(Tag)</code></td><td>Multiplies together all the values for <code>Tag</code> provided</td></tr><tr><td><code>AVG(Tag)</code></td><td>Calculated the average of all values for <code>Tag</code></td></tr><tr><td><code>MAX(Tag)</code></td><td>Finds the largest of all values for <code>Tag</code></td></tr><tr><td><code>MIN(Tag)</code></td><td>Finds the smallest of all values for <code>Tag</code></td></tr></tbody></table>

Aggregated formulas can also be used anywhere within the document to make more complex formulas. For example you could calculate the percentage a certain Line Item Price is of the total.

```
{{= (Price / SUM(Price)) * 100 | 2}}%
```

For the line items in the table example above this would create the following result:

```
+-------------------+------------------------------------------------+
|1. {{Price}} -> 10 | {{= (Price / SUM(Price)) * 100 | 2}}% -> 0.16% |
+-------------------+------------------------------------------------+
|2. {{Price}} -> 20 | {{= (Price / SUM(Price)) * 100 | 2}}% -> 0.33% |
+-------------------+------------------------------------------------+
|3. {{Price}} -> 30 | {{= (Price / SUM(Price)) * 100 | 2}}% -> 0.50% |
+-------------------+------------------------------------------------+
```

### Decimal Place Modifier

By including the symbol `|` followed by the number of decimal places you would like to limit the result to an expression can be rounded similar to the ROUND formula itself.

For example we can round the following arbitrary expression to 3 decimal places like so:

```
{{1.1234 + 1.0 | 3}} -> 2.123
```

### **Date/Time Arithmetic**

Using one of the formulas listed below you can perform arithmetic (`+` and `-`) on date fields.

`{{= Date + DAYS(30)}}` -> \<The value will be 30 days from the value of `Date`>

The formula will work with the following where `N` is amount to increase by:

* `MINUTES(N)`
* `HOURS(N)`
* `DAYS(N)`
* `WEEKS(N)`

### Formula Glossary

### ‍**Sum**‍

Returns the sum of a series of field values, including all field values within a Data Grouping tag.

#### Syntax

`{{=SUM(tag1, tag2, ...)}}`

* `tag1` - The first tag to add together.
* `tag2`, ... - **\[** OPTIONAL **]** - Additional tags to add to tag1.

> The tags included in the brackets don't need to be accompanied by "\{{" and "\}}"

### **Average**‍

The AVERAGE function returns the numerical average value in a group of tags, including all field values within a Data Group tag

#### Syntax

`{{=AVG(tag1, tag2, ...)}}`

* `tag1` - The first tag or Data Group tag to consider when calculating the average value.
* `tag2`, ... - **\[** OPTIONAL **]** - Additional tags to consider when calculating the average value.

> The tags included in the brackets don't need to be accompanied by "\{{" and "\}}"

### **Maximum**‍

Returns the Maximum value from a group of tags, including all field values within a Data Group tag

#### Syntax

`{{=MAX(tag1, tag2, ...)}}`

* `tag1` - The first tag or Data Group tag to consider when calculating the maximum value.
* `tag2`, ... - **\[** OPTIONAL **]** - Additional tags to consider when calculating the maximum value.

> The tags included in the brackets don't need to be accompanied by "\{{" and "\}}"

### **Minimum**‍

To find the Minimum value from a group of tags, including all field values within a Data Group tag

#### Syntax

`{{=MIN(tag1, tag2, ...)}}`

* `tag1` - The first tag or Data Group tag to consider when calculating the minimum value.
* `tag2`, ... - **\[** OPTIONAL **]** - Additional tags to consider when calculating the minimum value.

> The tags included in the brackets don't need to be accompanied by "\{{" and "\}}"

### **Round**

Rounds the numeric value of a field to a certain number of decimal places.

#### Syntax

`{{=ROUND(tag, [places])}}`

* `Tag` - The value to round to `places` number of places.
* `places` - **\[** OPTIONAL - `0` by default **]** - The number of decimal places to which to round.

#### **Sample usage**

`{{=ROUND(1.234, 2)}}` -> 1.23

`{{=ROUND(1.234)}}` -> 1

### **Multiply**‍

Returns the product of two fields or numeric values. Equivalent to the \`\*\` operator.

#### Syntax

`{{=MULTIPLY(tag1, tag2)}}`

* `tag1` - A field containing a numeric value or a direct numeric value e.g. `6`.
* `tag2` - A field containing a numeric value or a direct numeric value e.g. `7`.

### **Add**

Returns the sum of two fields or numeric values. Equivalent to the \`+\` operator.

#### Syntax

`{{=ADD(tag1, tag2)}}`

* `tag1` - A field containing a numeric value or a direct numeric value e.g. `19`.
* `tag1` - A field containing a numeric value or a direct numeric value e.g. `23`.

## Text

### Concatenate

Appends strings to one another.

#### Sample usage

`{{=CONCATENATE('Hello', ' ', 'World')}}`->  "Hello World"

`{{=CONCATENATE(Line Item Name)}}` -> "Item AItem BItem C" (no spaces)

`CONCATENATE(A2:B7)`

#### Syntax

`CONCATENATE(tag_name_1, [tag_name_2, ...])`

* `string1` – Any field or data grouping field from the source or a literal string in quotes.
* `string2 …` - Any amount of other fields, data grouping fields or literal strings.

### Text Join

Combine text of multiple fields or a data grouping field containing multiple values with a specifiable delimiter between each item.&#x20;

#### Sample Usage

`{{=TEXTJOIN(“ | “, "Hello", "World")}}`  ->  "Hello | World"

`{{=TEXTJOIN(“, ”, Line Item Name)}}` -> "Item A, Item B, Item C"

#### Syntax

`{{=TEXTJOIN(delimiter, tag_name_1, [tag_name_2, ...])}}`

* `delimiter` - A string, possibly empty, or another field. If empty, text will be simply concatenated.
* `tag_name_1` - Any field or data grouping field from the source or a literal string in quotes.
* `tag_name_2, ...` - Any amount of other fields, data grouping fields or literal strings.

{% hint style="info" %}
You can also use \{{=TEXTJOINNONEMPTY(...)\}} to skip empty values in the result.
{% endhint %}

### **Truncate**

Shortens the value of a field or literal text string by the specified length.&#x20;

**Syntax**&#x20;

`{{=TRUNCATE(tag, length)}}`

* `tag` - The text to be truncated.
* `length` - The number of characters to to limit the text to.

If length is greater than the number of characters in value, value is returned without modification.

**Example**\
`{{Message}} -> "Hello World"`\
`{{=TRUNCATE(Message, 5)}} -> "Hello"`



### **Filter and Sum (SUMIF)**

Sum values based on a certain condition

**Syntax**&#x20;

`{{=SUMIF(Condition Tag = "Something", Numeric Data Grouped Field)}}`



### **Feedback and feature suggestions**

We created Portant in 2021 and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at contact@portant.co

Thanks,

Blake and James
