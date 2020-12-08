# DrupalCon Europe Web Performance Workshop Notes
Links and notes for DrupalCon Europe Web Performance


## General Links
- Slide deck : https://docs.google.com/presentation/d/1fgAXlpHa4e8iXoxiBlSBruWMNoLR0eB16c0EdyU_Uac/edit?usp=sharing
- Session node: https://events.drupal.org/europe2020/sessions/front-end-web-performance-clinic-2020-workshop

## JavaScript
- https://v8.dev/blog/cost-of-javascript-2019

## WebPageTest
- https://webpagetest.org/
- https://andydavies.me/blog/2018/02/19/using-webpagetest-to-measure-the-impact-of-3rd-party-tags/
- https://github.com/WPO-Foundation/webpagetest-docs/blob/master/user/Scripting.md
- https://nooshu.github.io/blog/2019/10/02/how-to-read-a-wpt-waterfall-chart/
- https://nooshu.github.io/blog/2019/12/30/how-to-read-a-wpt-connection-view-chart/

## Lab demo links (that introduce performance regressions)
Previews are provided by [Tugboat](https://www.tugboat.qa), which can create automatic "previews" for each PR or git branch.

- Remove resource hints from Lullabot.com 
  - Tugboat Demo: https://no-merge-no-font-preload-l77tf264i5frkoh0qq8p6u1ueusxjtqe.tugboat.qa/
  - WPT waterfalll:  https://webpagetest.org/result/201208_DiR9_fdf10f3c6ab2da400c1c110228607374/2/details/#waterfall_view_step1
  - WPT filmstrip: https://webpagetest.org/video/compare.php?tests=201208_DiR9_fdf10f3c6ab2da400c1c110228607374-r:2-c:0
- Use external fonts with Lullabot.com
  - Tugboat Demo: https://no-merge-external-fonts-i0gb5vvpukuirpjpckalwtydzbgga4wp.tugboat.qa/
  - WPT waterfall: https://webpagetest.org/result/201208_DiBP_94747775893bcda4f4aaef189bcf655c/2/details/#waterfall_view_step1
  - WPT filmstrip: https://webpagetest.org/video/compare.php?tests=201208_DiBP_94747775893bcda4f4aaef189bcf655c-r:1-c:0
- Layout thrashing 🤘 on scroll with Lullabot.com
  - Tugboat Demo: https://no-merge-layout-thrashing-yotskzylkejoavfbttzvlal54k8rfpnx.tugboat.qa/
  - WPT Result:
