[android-components](../../index.md) / [mozilla.components.browser.menu.item](../index.md) / [BrowserMenuCategory](./index.md)

# BrowserMenuCategory

`class BrowserMenuCategory : `[`BrowserMenuItem`](../../mozilla.components.browser.menu/-browser-menu-item/index.md) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/menu/src/main/java/mozilla/components/browser/menu/item/BrowserMenuCategory.kt#L24)

A browser menu item displaying styleable text, usable for menu categories

### Parameters

`label` - The visible label of this menu item.

`textSize` - : The size of the label.

`textColorResource` - : The color resource to apply to the text.

`textStyle` - : The style to apply to the text.

`textAlignment` - The alignment of text

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BrowserMenuCategory(label: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, textSize: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)` = NO_ID.toFloat(), textColorResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = NO_ID, textStyle: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = Typeface.BOLD, textAlignment: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = View.TEXT_ALIGNMENT_VIEW_START)`<br>A browser menu item displaying styleable text, usable for menu categories |

### Properties

| Name | Summary |
|---|---|
| [visible](visible.md) | `var visible: () -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Lambda expression that returns true if this item should be shown in the menu. Returns false if this item should be hidden. |

### Functions

| Name | Summary |
|---|---|
| [bind](bind.md) | `fun bind(menu: `[`BrowserMenu`](../../mozilla.components.browser.menu/-browser-menu/index.md)`, view: <ERROR CLASS>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Called by the browser menu to display the data of this item using the passed view. |
| [getLayoutResource](get-layout-resource.md) | `fun getLayoutResource(): <ERROR CLASS>`<br>Returns the layout resource ID of the layout to be inflated for showing a menu item of this type. |

### Inherited Functions

| Name | Summary |
|---|---|
| [invalidate](../../mozilla.components.browser.menu/-browser-menu-item/invalidate.md) | `open fun invalidate(view: <ERROR CLASS>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Called by the browser menu to update the displayed data of this item using the passed view. |