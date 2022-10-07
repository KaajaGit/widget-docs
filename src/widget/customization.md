# Customization
Kaaja widget can be customized, as per client needs, modifying the following parameter:

## Floating vs embedded
Kaaja widget comes out of the box as a floating widget. If the client needs the widget functionalities to be embedded in the page, a new component needs to be created into the page that wraps the Kaaja iFrame with the parameters included in query string. An example of this is provided in the following snippet:

```html
<iframe width="100%" height="100%" src="https://www.kaajab.com/it/widget/property-widget?api_key=4eb895d00c9a3752ba88db30eb3f68f1&amp;property_code=MAC-FM-4-B2&amp;integration_url=https%3A%2F%2Fdfm745fopjvgu.cloudfront.net%2F%3F"></iframe>
```

The parameters are the same as the ones used for the floating widget, as described in the [installation parameters section](installation.md#parameters).

## Height and width
it is possible to set a different height and width according to the needs. Height and width suggested: 400x500px
