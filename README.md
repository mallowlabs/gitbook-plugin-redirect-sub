# gitbook-plugin-redirect-sub

This GitBook plugin can redirect gitbook page.

## Usage

Add to your `book.json` plugin list:
```json
{
    "plugins" : [ "redirect-sub@https://github.com/mallowlabs/gitbook-plugin-redirect-sub.git#0.0.1" ],
    "pluginsConfig": {
        "redirect_sub" : {
            "root" : "your-redirect-url-root",
            "bookname" : "your-book-name"
        }
    },
}
```

For example, when you write below config in `book.json`,

```json
"redirect_sub" : {
    "root" : "https://books.example.com",
    "bookname" : "my-book"
}
```

and you access to `https://exmaple.gitbook.io/my-book/xxx/yyy.html` , you will be redirected to `https://books.example.com/my-book/xxx/yyy.html`.


## Credits
This plugin reuses many codes of [gitbook-plugin-redirect](https://github.com/ketan/gitbook-plugin-redirect) Plugin. Many thanks to ketan.

