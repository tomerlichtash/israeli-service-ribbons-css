# Israeli Service Ribbons in Pure CSS

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

## Resources

### Demos:
* Demo: https://tomerlichtash.github.io/israeli-service-ribbons-css/
* CodePen: https://codepen.io/loremipsum/pen/GRgqMZw

### Israeli Ministry of Defence - About Service Ribbons:
* EN: https://www.mod.gov.il/English/Campaign%20Ribbons/Pages/Service-Ribbons.aspx
* HE: https://www.mod.gov.il/Citizen_Service/clalim/otot/Pages/sing-war.aspx

### Resource for Service Ribbon SVG (Wikipedia)
* EN: https://en.wikipedia.org/wiki/Orders,_decorations,_and_medals_of_Israel#Campaign_ribbons_and_medal
* HE: https://he.wikipedia.org/wiki/%D7%A2%D7%99%D7%98%D7%95%D7%A8%D7%99_%D7%A6%D7%94%22%D7%9C

#### About Service Ribbons (Wikipedia, Hebrew):
* HE: https://he.wikipedia.org/wiki/%D7%90%D7%95%D7%AA_%D7%9E%D7%A2%D7%A8%D7%9B%D7%94_(%D7%99%D7%A9%D7%A8%D7%90%D7%9C)
