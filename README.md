# wued-support

A solution for ie < 10 browser

- [CSS 兼容查询](https://caniuse.com/)

- [浏览器版本过低引导升级方案](https://support.dmeng.net)

## Usage

升级浏览器提示弹窗：

```html
<script>/*@cc_on document.write('\x3Cscript id="_iealwn_js" src="https://support.dmeng.net/ie-alert-warning/latest.js">\x3C/script>'); @*/</script>
```

直接跳转升级浏览器页面：

``` html
<script>/*@cc_on window.location.href="https://support.dmeng.net/upgrade-your-browser.html?referrer="+encodeURIComponent(window.location.href); @*/</script>
```
