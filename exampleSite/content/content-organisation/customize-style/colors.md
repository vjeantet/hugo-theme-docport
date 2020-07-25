+++
title="Colors"
+++

This theme use 1 main color to compute other colors and colorize all elements.
You can choose this main color by editing the `config.toml` file.

## Main color

This color is mainly used for menu.

{{% alert theme="warning" %}}When omited, a random value is computed on each build {{%/alert%}}
```toml
	[params]
	color_main = "#B0B0B0"
```

## 2nd color (optional)
{{% alert theme="warning" %}}When omited, this color is computed from main color with a saturated version{{%/alert%}}

This color is mainly used for links.

```toml
	[params]
	color_over = "red"
```
