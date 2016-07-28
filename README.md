#A jQuery Tap with WEUI

A hidden section of content activated by a Tab.

## Usage

```js
$('#J_Navbar').tab();
```

```html
<div class="navbar" id="J_Navbar">
    <div class="bd">
        <div class="weui_tab">
            <div class="weui_navbar">
                <div data-tab="first"  class="weui_navbar_item">选项一</div>
                <div data-tab="second" class="weui_navbar_item">选项二</div>
                <div data-tab="third"  class="weui_navbar_item weui_bar_item_on">选项三</div>
            </div>
            <div class="weui_tab_bd">
                <div id="first"  class="weui_tab_bd_item">First</div>
                <div id="second" class="weui_tab_bd_item">Second</div>
                <div id="third"  class="weui_tab_bd_item weui_tab_bd_item_active">Third</div>
            </div>
        </div>
    </div>
</div>
```

## With Callback

```js
$('#J_Navbar').tab(function(e) {
    console.log(e); // {index: 0, tab: "first", click: 1}
});
```
