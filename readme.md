External CSS: External CSS contains a separate CSS file with a .css extension which contains only style property with the help of tag attributes.

´´´css
selector{
property1: value1;
property2: value2;
}
´´´
Include external CSS file: The external CSS file is linked to the HTML document using a link tag.

´´´html
<link rel="stylesheet" type="text/css" href="/style.css" />
´´´

Internal CSS or Embedded: CSS is embedded within the HTML file using a style HTML tag when a single HTML document must be styled uniquely.
´´´html
<style type="text/css">
div { color: #444;}
</style>
´´´
Inline CSS: It contains CSS properties in the body section specified within HTML tags using the style attribute.

´´´html
<tag style="property: value"> </tag>
´´´

Clearfix: It is used to clear floats to select or keep control of your margins and padding.

.clearfix::after {
 content: "";
 clear: both;
 display: block; 
}
Selectors: CSS selectors are used to find or selecting the HTML elements you want to style. These are categorized as follows: