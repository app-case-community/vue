# vue
    
    fork vue, 支持可以重写html组件

```js

var isHTMLTag = makeMap(
  'html,body,base,head,link,meta,style,title'
);

// this map is intentionally selective, only covering SVG elements that may
// contain child elements.
var isSVG = makeMap(
  'svg,animate,circle,clippath,cursor,defs,desc,ellipse,filter,font-face',
  true
);

```