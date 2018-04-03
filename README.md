# web-component-loader
> Test your web component here

Simple page that let's you load up a web component from a cdn or unpkg.com 
on the fly and preview it.

This is just hacked together with jquery as a proof of concept.

## Installing / Getting started

Check it out here:

https://jpchip.github.io/web-component-loader/

### Example Components:

#### [ui-avatar](https://www.npmjs.com/package/ui-avatar)
- URL: `https://unpkg.com/ui-avatar@0.0.3/dist/uiavatar.js`
- Name: `ui-avatar`
- Key: `name`
- Value: `Your Name`

#### [stencil-voice2text](https://www.npmjs.com/package/stencil-voice2text)
- URL: `https://unpkg.com/stencil-voice2text@latest/dist/voice2text.js`
- Name: `st-voice2text`
- Content: `<input type="text"></input>`

## Developing

### Setting up Dev

Install some local web server. Recommend https://github.com/indexzero/http-server

```shell
git clone https://github.com/jpchip/web-component-loader.git
cd your-project/
http-server
```

Load up site at http://127.0.0.1:8080

## Todos

- [ ] Allow setting unlimited number of parameters
- [ ] Allow adding more than one component
- [ ] Add each component as a widget in a dashboard
- [ ] Store added components in local storage

## Licensing

MIT
