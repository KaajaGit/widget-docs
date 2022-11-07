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

## Edit and delete appointments

The widget allows the user to book an appointment, edit it and delete it. To edit or delete an appointment, we need a **kaaja_booking_id** parameter from the url. This id is used to identify the appointment and it is needed to edit or delete it.

example: **https://www.kaaja.com/it/widget/property-widget?api_key=x123asdvderetest&property_code=MAC-FM-4-B2&integration_url=https%3A%2F%2Fdfm745fopjvgu.cloudfront.net%2F%3F&kaaja_booking_id=123456**

After the user has booked an appointment, the widget will send an email to the user with the link to edit or delete the appointment. The link will contain the **kaaja_booking_id** parameter.
