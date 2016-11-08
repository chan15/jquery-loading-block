# jquery-loading-block

Nowdays we do a lot ajax on website, therefore we can see loading animation everywhere, this plugin is an easy one to show and hide loading overlay.

### Basic usage

```javascript

<script type="text/javascript" charset="utf-8">
$(function() {
    // imgPath almost nessarry
    $.loadingBlockShow({
        imgPath: 'assets/img/icon.gif'
    });

    setTimeout($.loadingBlockHide, 5000);
});
</script>
```

### options

```javascript
var defaults = {
    imgPath: 'img/icon.gif',
    imgStyle: {
        width: 'auto',
        textAlign: 'center',
        marginTop: '20%'
    },
    text: 'loading...',
    style: {
        position: 'fixed',
        width: '100%',
        height: '100%',
        background: 'rgba(255, 255, 255, .8)',
        left: 0,
        top: 0,
        zIndex: 10000
    }
};
```
