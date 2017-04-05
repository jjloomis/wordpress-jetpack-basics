# Customizing Portfolio layout with shortcode attributes

By default, the \[portfolio\] shortcode will display your portfolio with the following with attributes:

* Two-column layout
* Portfolio Projects listed oldest to newest \(determined by date/ time added to WordPress site\)
* Featured Image \(if added to Project\)
* Type \(if selected in Project\)
* Tag \(if selected in Project\)
* Content \(excerpt of text that accompanies the Portfolio Project\)

You can add attributes to the `[portfolio]` shortcode to customize the layout of your Portfolio Page.

To use these attributes, add and define them within the brackets of the `[portfolio]` shortcode. \(See Portfolio Shortcode examples.\)

IMPORTANT: Never include a space after a comma when working with a comma-separated list in the `[portfolio]` shortcode. The `[portfolio]` shortcode must look like this:

`[portfolio include_type=iteme-one,item-two]`

Note the absence of a space after the comma in the example above. If you put a space after the comma, the `[portfolio`\] shortcode won’t work.

The following attributes can be added to your `[portfolio]` shortcode. These attributes are from the Porfolio Shortcode page on WordPress.com.

| Customization | Shortcode attribute | Set to |
| :--- | :--- | :--- |
| Display Project Types \(defaults to true\) | display\_types | true or false |
| Display Project Tags \(defaults to true\) | display\_tags | true or false |
| Display initial text of Project \(defaults to true\) | display\_content | true or false |
| Display only specific Project Types \(defaults to all\) | include\_type | Comma-separarted list of Project Type slugs |
| Display only specific Project Tags \(defaults to all\) | include\_tag | Comma-separated list of Project Tags |
| Number of columns \(defaults to two\) | columns | Number 1 - 6 |
| Number of Projects to display \(defaults to all\) | showposts | Number |
| Order based on date/ timestamp \(defaults to ascending order\) | oder | ASC or DESC |
| Sort by specific |  |  |



