---
title: Project sketches
---


<details>
  <summary>SECRET DO NOT OPEN!</summary>
  <img src="Screenshot 2026-04-11 at 12.37.46 PM.png">
  Something small enough to escape casual notice.
</details>


<div class="grid grid-cols-3">
  <div class="card"><h1><div class="yellow">A</div></h1></div>
  <div class="card"><h1><div class="red">B</div></h1></div>
  <div class="card"><h1><div class="blue">C</div></h1></div>
   <div class="card grid-colspan-3"><h1>D</h1></div>
  <div class="card"><h1>E</h1></div>
  <div class="card"><h1>F</h1></div>
  <div class="card"><h1>G</h1></div>
</div>

```js
const text = "foo bar baz hello help dataviz graph chart bar".split(" ");
```

```js
const x = view(Inputs.range([0,9], {step: 1}));
```

```js
const elements = text.slice(0, x);
```

```js
const val = elements.join(" ");
display(val);
```


```js

const org = FileAttachment("/scr/data/gapminder.zip").zip();

const gapname = org.filenames;

display(gapname);

//const gapfile = org["Contients"].file();

//const gapdata  = gapfile.csv();

//display(gapdata);

```

```js

//const org = FileAttachment("");

```














