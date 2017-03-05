Tawk.to messaging for GitBook
==============

You can use install it via **NPM**:

```
$ npm install gitbook-plugin-tawk
```

Add the plugin to your `book.json`:

```
{
    "plugins": ["tawk"]
}
```

Configuration in the `book.json`:

```
{
    "plugins": ["tawk"],
    "pluginsConfig": {
        "tawk": {
        	"siteID": "REPLACE_WITH_SITE_ID",
			"widgetID": "default", // optional
			"charset": "UTF-8", // optional
			"crossorigin": "*" // optional
        }
    }
}
```