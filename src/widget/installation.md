# Installation
The widget is simply a web component that can be embedded in any website. Only two steps are required to install the widget:

1. Add the following script tag to the page where you want to embed the widget:

```html
<script src="https://widget.kaaja.com/kaaja-property-widget.js"></script>
```
2. Configure the Web component parameters by adding the following tag to the page where you want to embed the widget:

```html
<kaaja-property-widget api-key="1ec815dxxc9a375abcd123fghj" property-code="H2P-MI-25-1" locale="en" />
```

## Parameters
To invoke correctly Kaaja functionalities through the widget, three parameters are needed, as mentioned below:

* **API Key**: each partner receives from Kaaja IT team an API Key based on each specific domain. If the API Key and the specific domain does not match, no API invocation could be performed.
* **Property code**: to get the functionalities related to the correct property, the Kaaja property code must be used. This code is unique for each property and it is provided by Kaaja through the data flows used for property information sharing.
* **Language**: as of now, Kaaja widget manages two languages, italian "it" and english "en". If the language is not specified, the widget will be displayed in italian.