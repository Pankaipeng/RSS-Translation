# RSS-Translation

rss translate any to any

![](https://github.com/Pankaipeng/RSS-Translation/workflows/circle_translate/badge.svg)
![](https://github.com/Pankaipeng/RSS-Translation/workflows/Deploy/badge.svg)

you can edit [test.ini](https://github.com/Pankaipeng/RSS-Translation/edit/main/test.ini) to add orginal rss url. [help](https://github.com/Pankaipeng/RSS-Translation/issues/2)

next find the translated link in [https://Pankaipeng.github.io/RSS-Translation/](https://Pankaipeng.github.io/RSS-Translation/)

## 20230814 update
- support proxy mode. you can set `action = "proxy"` in test.ini like [source010](https://github.com/Pankaipeng/RSS-Translation/blob/f6648c5262f4fa0926310dbe43fff820bf727ac7/test.ini#L67)

## 20230702 update 
- use [main2.py](https://github.com/Pankaipeng/RSS-Translation/blob/main/main2.py) in [circle_translate.yml](https://github.com/Pankaipeng/RSS-Translation/blob/aeb61bc36eb1a22fd003677b5209291cf7cb4a87/.github/workflows/circle_translate.yml#L38)
- atom is bad now base on an atom paraser to find. NOW SUPPORT
        use [feedparser](https://pythonhosted.org/feedparser/)
- fix google translate limit . NOW SUPPORT

## rss translate links

 - source001 [https://feedx.net/rss/economist.xml](https://feedx.net/rss/economist.xml) -> [economist_latest.xml](rss/economist_latest.xml)
 - source002 [https://feedx.net/rss/economistp.xml](https://feedx.net/rss/economistp.xml) -> [economist_print.xml](rss/economist_print.xml)
 - source003 [https://feedx.net/rss/newyorker.xml](https://feedx.net/rss/newyorker.xml) -> [newyorker.xml](rss/newyorker.xml)
 - source004 [https://feedx.net/rss/hbr.xml](https://feedx.net/rss/hbr.xml) -> [hbr.xml](rss/hbr.xml)
 - source005 [https://feedx.net/rss/nasa.xml](https://feedx.net/rss/nasa.xml) -> [nasa.xml](rss/nasa.xml)
