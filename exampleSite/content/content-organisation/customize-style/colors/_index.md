+++
title="Colors"
subpage=true

+++

This theme use 1 main color to compute other colors and colorize all elements.
You can choose this main color by editing the `config.toml` file.

## Main color

This color is mainly used for menu.

{{% notice primary %}}When omited, a random value is computed on each build {{%/notice%}}
```toml
	[params]
	color_main = "#B0B0B0"
```

## 2nd color (optional)
{{% notice primary %}}When omited, this color is computed from main color with a saturated version{{%/notice %}}

This color is mainly used for links.

```toml
	[params]
	color_second = "red"
```

## Random colors
{{%alert success%}}**Random colors** : comment theses two params in your config.toml, you will have random colors on each build... {{%/alert%}}