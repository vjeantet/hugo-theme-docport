+++
title = "icon"
description = "Display an icon."
+++

Display an icon like {{% icon cloud %}}

It uses :

* materialize icons library .[more info here](https://material.io/resources/icons/)

This `icon` shortcode will display an icon in your page. 

## Usage

| Parameter | Default | Description |
|:--|:--|:--|
| name | **required** | name of icon (see bellow) |
| size | none | size of icon, medium, xx-small, x-small, small, large, x-large, xx-large, 11px, 2em, 20%.... |

{{%alert info%}}
**Tips :**
setting only the name as argument works too : `{{</*icon film*/>}}` instead of `{{</*icon name="film"*/>}}`
{{%/alert%}}

## Demo
```
	{{</* icon name="save" size="64px" */>}}
```
{{<icon name="save" size="64px">}}

.


## icons available
* https://material.io/resources/icons/?icon=attach_file&style=baseline