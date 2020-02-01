# directline-token

## This project is used for generating a direct line token for Bot Framework applications.

This can be run locally or from a Linux-based web app. (It doesn't seem to play nice on a Windows-based web app and I haven't given time to figure it out, yet.)

The secret used in the dl.js file is passed in from a .env file

```
directLineSecret=[YOUR DIRECT LINE SECRET]
```

Any port can be used. But, whichever port you choose is the port you will reference when making your API call against this token generator (see the [index.html](./index.html)).

The webchat CSS is set at 100% and will, accordingly, take up the entire window. In some cases, this will create a scrolling effect where the chat will push down the page as dialog entries are made. Setting a fixed height "corrects" this.