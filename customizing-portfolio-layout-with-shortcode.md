By default, the [portfolio] shortcode will display with the following with attributes:

* Two-column layout
* Portfolio Projects listed oldest to newest (determined by date/ time added to WordPress site)
* Featured Image (if added to Project)
* Type (if selected in Project)
* Tag (if selected in Project)
* Content (excerpt of text that accompanies the Portfolio Project)

You can add attributes to the `[portfolio]` shortcode to customize the layout of your Portfolio Page.

To use these attributes, add and define them within the brackets of the `[portfolio]` shortcode. (See Portfolio Shortcode examples.)

IMPORTANT: Never include a space after a comma when working with a comma-separated list in the `[portfolio]` shortcode. The `[portfolio]` shortcode must look like this:

`[portfolio include_type=iteme-one,item-two]`

Note the absence of a space after the comma in the example above. If you put a space after the comma, the `[portfolio`] shortcode won’t work.

The following attributes can be added to your `[portfolio]` shortcode. These attributes are from the Porfolio Shortcode page on WordPress.com.

* display_types: display Project Types. (true/false)
* display_tags: display Project Tags. (true/false)
* display_content: diplay Project content (true/false)
* include_type: display specific Project Types. Defaults to all. (Comma-separated list of Project Type slugs)
* include_tag: display specific Project Tags. Defaults to all. (Comma-separated list of Project Tag slugs)
* columns: number of columns in shortcode. Defaults to 2. (Number, 1-6)
* showposts: number of projects to display. Defaults to all. (Number)






