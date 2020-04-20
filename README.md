# Israeli Campaign Ribbons in Pure CSS

* Demo: https://tomerlichtash.github.io/israeli-campaign-ribbons-css/
* CodePen: https://codepen.io/loremipsum/pen/GRgqMZw

### Ribbon HTML/CSS Structure
```
    <figure class="komemiut war">
        <span class="a1"></span>
        <span class="b1"></span>
        <span class="a1"></span>
    </figure>
```
```
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

### Color palette:
* blue: #184ea4
* light blue: #4d81ba
* cyan: #92c8e2
* red: #ab3122
* ornage: #e27e33
* light orange: #bd7755
* purple: #541a95
* green: #26972d
* off-white: #f4f4f4

Sources:
* https://www.mod.gov.il/Citizen_Service/clalim/otot/Pages/sing-war.aspx
* https://www.mod.gov.il/English/Campaign%20Ribbons/Pages/Service-Ribbons.aspx
* https://en.wikipedia.org/wiki/Orders,_decorations,_and_medals_of_Israel#Campaign_ribbons_and_medal