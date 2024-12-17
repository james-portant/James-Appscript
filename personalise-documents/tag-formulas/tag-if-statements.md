# Tag IF Statements

Sometimes you might need to insert content inside your document output depending on a source value. To achieve this you can use the IF formula.

### =‍**IF() - formula**

Returns one value if a logical expression is \`TRUE\` and another if it is \`FALSE\`.

#### Sample Usage

\{{=IF(_tag name_ = "Hello", "Tag says hello!", "Tag is something else")\}} -> Tag says hello!

\{{=IF(_tag name_, "Tag was true", "Tag was false")\}} -> "Tag was false"

\{{=IF("TRUE", 4, 5)\}} -> 4

#### Syntax

\{{=IF(logical\_expression, value\_if\_true, value\_if\_false)\}}

* logical\_expression - An expression or reference to a cell containing an expression that represents some logical value, i.e. TRUE or FALSE.
* value\_if\_true - The value the function returns if logical\_expression is TRUE.
* value\_if\_false - **\[** OPTIONAL - blank by default **]** - The value the function returns if logical\_expression is FALSE.

> The tags included in the brackets don't need to be accompanied by "\{{" and "\}}"

#### ‍**Contains**

You can use `~` in place of the `=` and the condition will be true as long as the variable text is contained within the comparison text (or vice versa). e.g.

\{{=IF(_tag name \~_ "foo","Tag contains foo", "Tag does not contain foo")\}}

This formula would be true if the tag contained "foo"

### =SUMIF() - Filter and SUM values

By using the `SUMIF` formula in a data grouping workflow, you can SUM values based on specific conditions. e.g.

<pre class="language-html"><code class="lang-html"><strong>{{=SUMIF(Product Type = "Service", Product Cost)}}
</strong></code></pre>

### **IF Formulas and Data Grouping**

#### =IF() - Find if a value is true per item&#x20;

By using the `=IF()` formula within a data grouping table, a condition can be evaluated against each  value of a varying field.  e.g.

`{{=IF(Data Group Value = "Wally", "Found him!", "Nada!")}}`

For example

<table><thead><tr><th width="224">Data Group Value</th><th>Formula</th></tr></thead><tbody><tr><td>{{Data Group Value}}</td><td><code>{{=IF(Data Group Value = "Wally", "Found him!", "Nada!")}}</code></td></tr></tbody></table>

Would produce

<table><thead><tr><th width="223">Data Group Value</th><th>Formula</th></tr></thead><tbody><tr><td>Wally</td><td>Found him!</td></tr><tr><td></td><td>Nada!</td></tr><tr><td>Waldo</td><td>Nada!</td></tr></tbody></table>

#### =IF() - Only display text if there is a value

You can also only display a value if there is any data present by not adding a condiditon to the IF formula, like this\
`{{=IF(Data Group Value, ”Data present”, “”)}}`

For example

<table><thead><tr><th width="249">Data Group Value</th><th>Formula</th></tr></thead><tbody><tr><td>{{Data Group Value}}</td><td><code>{{=IF(Data Group Value, ”Data present”, “”)}}</code></td></tr></tbody></table>

Would produce

<table><thead><tr><th width="250">Data Group Value</th><th>Formula</th></tr></thead><tbody><tr><td>Wally</td><td>Data present</td></tr><tr><td></td><td></td></tr><tr><td>Waldo</td><td>Data present</td></tr></tbody></table>



#### =IFANY() - Find if a value is included in the whole data set&#x20;

By using the `IFANY` formula in a data grouping workflow, a condition can be evaluated against all the values of a varying field.  e.g.\
`{{=IFANY(Data Group Value = "Wally", "Found him!", "Nada!")}}`

### **Feedback and feature suggestions**

We created Portant in 2021, and the feedback we have received since then has been very helpful and greatly appreciated. If you have any feedback, please feel free to send us an email at contact@portant.co

Thanks,

Blake and James
