# auto-complete
Polymer paper autocomplete
## Synopsis

A html auto-complete component to use in polymer-projects

## Installation

Add the following dependency in bower.json

"auto-complete":https://github.com/anandanand84/auto-complete.git#latest

Import the element in html.

```html
    
    <link rel="import" href="bower_components/auto-complete/auto-complete.html">
    
    <tlab-data id="dataprovider" method="getAvailableScrips" last-response="{{choices}}"> </tlab-data>
    <auto-complete close-on-select id="autocomplete" on-filter="filterchange" delay="200" data="{{choices}}"     placeholder="[[placeholder]]">
    </auto-complete>
```

## Demo

For demo.

Clone the project.

bower install

npm install -g polyserve

polyserve -p 9998.

demo.html will be available.


