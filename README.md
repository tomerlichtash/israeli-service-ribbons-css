# Israeli Campaign Ribbons in Pure CSS

```
<figure class="komemiut war">
    <span class="a1"></span>
    <span class="b1"></span>
    <span class="a1"></span>
</figure>
```
```
/* common layout */

.war {
    position: relative;
    overflow: hidden;
    display: flex;
    justify-content: center;
    width: 151px;
    height: 38px;
    box-shadow: 0 0 15px rgba(0, 0, 0, .2);
    border: 1px solid rgba(0, 0, 0, 0.5);
    border-radius: 3px;
    z-index: 1;
}
```
```
/*  ribbon variant */

.some-war {
    background: #c0a;
}
.some-war .outer {
    border-right: 12px double #fa9;
    border-left: 8px double rgba(100, 150, 200, 0.9);
    max-width: 8px;
}
.some-war .inner {
    background: #349;
    max-width: 44px;
}
```

* Demo: https://tomerlichtash.github.io/israeli-campaign-ribbons-css/
* CodePen: https://codepen.io/loremipsum/pen/GRgqMZw
