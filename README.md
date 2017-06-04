# Tangent modal
A modal that can show your content easily.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Demo
![image](https://github.com/lukkiddd/tangent-modal/blob/master/demo/demo-gif.gif?raw=true)

## How to use
```html
<tangent-modal id="modal">
  <div class="title">
    Title goes here
  </div>
  <div class="subtitle">
    Subtitle goes here
  </div>
  <div class="content">
    Content goes here...
  </div>
</tangent-modal>
```

To show modal you need to set `active` properties to be true

```js
document.getElementById('modal').active = true;
```
