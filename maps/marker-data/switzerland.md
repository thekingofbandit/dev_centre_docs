---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: Switzerland

#### JavaScript Alias: maps/switzerland


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
                "id": "BE",
                "shapeid": "myCustomShape",
                "x": "160.21",
                "y": "151.45",
                "label": "Bern",
                "labelpos": "right"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "294.15",
                "y": "31.93",
                "label": "Schaffhausen",
                "labelpos": "right"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "327.12",
                "y": "63.87",
                "label": "Winterthur",
                "labelpos": "left"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "378.63",
                "y": "63.87",
                "label": "Sankt Gallen",
                "labelpos": "right"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape",
                "x": "281.78",
                "y": "76.24",
                "label": "Zurich",
                "labelpos": "left"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape",
                "x": "188.03",
                "y": "48.42",
                "label": "Basel"
            },
            {
                "id": "06",
                "shapeid": "newCustomShape",
                "x": "138.57",
                "y": "102",
                "label": "Biel"
            },
            {
                "id": "10",
                "shapeid": "newCustomShape",
                "x": "114.87",
                "y": "133.93",
                "label": "Neuchatel",
                "labelpos": "left"
            },
            {
                "id": "11",
                "shapeid": "newCustomShape",
                "x": "138.57",
                "y": "174.12",
                "label": "Fribourg",
                "labelpos": "right"
            },
            {
                "id": "12",
                "shapeid": "newCustomShape",
                "x": "87.06",
                "y": "211.21",
                "label": "Lausanne",
                "labelpos": "left"
            },
            {
                "id": "13",
                "shapeid": "newCustomShape",
                "x": "27.3",
                "y": "257.57",
                "label": "Geneva",
                "labelpos": "right"
            },
            {
                "id": "14",
                "shapeid": "newCustomShape",
                "x": "331.24",
                "y": "292.6",
                "label": "Lugano",
                "labelpos": "right"
            },
            {
                "id": "15",
                "shapeid": "newCustomShape",
                "x": "365.24",
                "y": "166.9",
                "label": "Chur",
                "labelpos": "left"
            },
            {
                "id": "16",
                "shapeid": "newCustomShape",
                "x": "246.75",
                "y": "128.78",
                "label": "Lucerne",
                "labelpos": "left"
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
                "id": "BE",
                "x": "160.21",
                "y": "151.45",
                "label": "Bern",
                "labelpos": "right"
            },
            {
                "id": "01",
                "x": "294.15",
                "y": "31.93",
                "label": "Schaffhausen",
                "labelpos": "right"
            },
            {
                "id": "02",
                "x": "327.12",
                "y": "63.87",
                "label": "Winterthur",
                "labelpos": "left"
            },
            {
                "id": "03",
                "x": "378.63",
                "y": "63.87",
                "label": "Sankt Gallen",
                "labelpos": "right"
            },
            {
                "id": "04",
                "x": "281.78",
                "y": "76.24",
                "label": "Zurich",
                "labelpos": "left"
            },
            {
                "id": "05",
                "x": "188.03",
                "y": "48.42",
                "label": "Basel"
            },
            {
                "id": "06",
                "x": "138.57",
                "y": "102",
                "label": "Biel"
            },
            {
                "id": "10",
                "x": "114.87",
                "y": "133.93",
                "label": "Neuchatel",
                "labelpos": "left"
            },
            {
                "id": "11",
                "x": "138.57",
                "y": "174.12",
                "label": "Fribourg",
                "labelpos": "right"
            },
            {
                "id": "12",
                "x": "87.06",
                "y": "211.21",
                "label": "Lausanne",
                "labelpos": "left"
            },
            {
                "id": "13",
                "x": "27.3",
                "y": "257.57",
                "label": "Geneva",
                "labelpos": "right"
            },
            {
                "id": "14",
                "x": "331.24",
                "y": "292.6",
                "label": "Lugano",
                "labelpos": "right"
            },
            {
                "id": "15",
                "x": "365.24",
                "y": "166.9",
                "label": "Chur",
                "labelpos": "left"
            },
            {
                "id": "16",
                "x": "246.75",
                "y": "128.78",
                "label": "Lucerne",
                "labelpos": "left"
            }
        ],
        "application": [
            {
                "id": "BE",
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
                "id": "10",
                "shapeid": "newCustomShape"
            },
            {
                "id": "11",
                "shapeid": "newCustomShape"
            },
            {
                "id": "12",
                "shapeid": "newCustomShape"
            },
            {
                "id": "13",
                "shapeid": "newCustomShape"
            },
            {
                "id": "14",
                "shapeid": "newCustomShape"
            },
            {
                "id": "15",
                "shapeid": "newCustomShape"
            },
            {
                "id": "16",
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
