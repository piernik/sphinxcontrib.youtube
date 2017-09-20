# sphinxcontrib.youtube
sphinx extrension to embed youtube video

I've added div wrapper to iframe so can implement own styles

To make it responsive add styles

```css
.youtube-iframe {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 */
    padding-top: 25px;
    height: 0;
}
.youtube-iframe iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
```
