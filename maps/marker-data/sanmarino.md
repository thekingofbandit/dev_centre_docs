---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: SanMarino

#### JavaScript Alias: maps/sanmarino


<div class="code-wrapper">
<ul class='code-tabs'>
    <li class='active'>
        <a data-toggle='new-json'>New JSON Format</a>
    </li>
    <li>
        <a data-toggle='old-json'>Old JSON Format</a>
    </li>
</ul>
<div class='tab-content'>
    
<div class='tab new-json-tab active'>
<pre><code class="language-json">
{
    "map": {
        "showshadow": "0",
        "showlabels": "0",
        "showmarkerlabels": "1",
        "fillcolor": "F1f1f1",
        "bordercolor": "CCCCCC",
        "basefont": "Verdana",
        "basefontsize": "10",
        "markerbordercolor": "000000",
        "markerbgcolor": "FF5904",
        "markerradius": "6",
        "usehovercolor": "0",
        "hoveronempty": "0",
        "showmarkertooltip": "1",
        "canvasBorderColor": "375277",
        "canvasBorderAlpha": "0"
    },
    "markers": {
        "shapes": [
            {
                "id": "myCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,333333",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "4"
            },
            {
                "id": "newCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,000099",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "3"
            }
        ],
        "items": [
            {
                "id": "SM",
                "shapeid": "myCustomShape",
                "x": "120",
                "y": "238.94",
                "label": "San Marino",
                "labelpos": "right"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "268.42",
                "y": "44.21",
                "label": "La Dogana",
                "labelpos": "left"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "235.78",
                "y": "85.26",
                "label": "Serravalle"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "208.42",
                "y": "173.68",
                "label": "Domagnano"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape",
                "x": "127.36",
                "y": "210.52",
                "label": "Borgo Maggiore",
                "labelpos": "right"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape",
                "x": "26.31",
                "y": "196.84",
                "label": "Acquaviva",
                "labelpos": "right"
            },
            {
                "id": "06",
                "shapeid": "newCustomShape",
                "x": "269.47",
                "y": "273.68",
                "label": "Faetano",
                "labelpos": "left"
            },
            {
                "id": "07",
                "shapeid": "newCustomShape",
                "x": "137.89",
                "y": "346.31",
                "label": "Fiorentino",
                "labelpos": "right"
            },
            {
                "id": "08",
                "shapeid": "newCustomShape",
                "x": "50.52",
                "y": "355.78",
                "label": "Chiesanuova"
            }
        ]
    }
}
</code><button class='btn btn-outline-secondary btn-copy' title='Copy to clipboard'>COPY</button>
</pre>


<p class='text-success'>New JSON format for map marker data.</p>

</div>
<div class='tab old-json-tab'>
<pre><code class="language-json">
{
    "map": {},
    "markers": {
        "shapes": [
            {
                "id": "myCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,333333",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "4"
            },
            {
                "id": "newCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,000099",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "3"
            }
        ],
        "definition": [
            {
                "id": "SM",
                "x": "120",
                "y": "238.94",
                "label": "San Marino",
                "labelpos": "right"
            },
            {
                "id": "01",
                "x": "268.42",
                "y": "44.21",
                "label": "La Dogana",
                "labelpos": "left"
            },
            {
                "id": "02",
                "x": "235.78",
                "y": "85.26",
                "label": "Serravalle"
            },
            {
                "id": "03",
                "x": "208.42",
                "y": "173.68",
                "label": "Domagnano"
            },
            {
                "id": "04",
                "x": "127.36",
                "y": "210.52",
                "label": "Borgo Maggiore",
                "labelpos": "right"
            },
            {
                "id": "05",
                "x": "26.31",
                "y": "196.84",
                "label": "Acquaviva",
                "labelpos": "right"
            },
            {
                "id": "06",
                "x": "269.47",
                "y": "273.68",
                "label": "Faetano",
                "labelpos": "left"
            },
            {
                "id": "07",
                "x": "137.89",
                "y": "346.31",
                "label": "Fiorentino",
                "labelpos": "right"
            },
            {
                "id": "08",
                "x": "50.52",
                "y": "355.78",
                "label": "Chiesanuova"
            }
        ],
        "application": [
            {
                "id": "SM",
                "shapeid": "myCustomShape"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape"
            },
            {
                "id": "06",
                "shapeid": "newCustomShape"
            },
            {
                "id": "07",
                "shapeid": "newCustomShape"
            },
            {
                "id": "08",
                "shapeid": "newCustomShape"
            }
        ]
    }
}
</code><button class='btn btn-outline-secondary btn-copy' title='Copy to clipboard'>COPY</button>
</pre>


<p class='text-success'>Old JSON format for map marker data, using separate application and definition blocks.</p>

</div>
    
</div>
</div>
