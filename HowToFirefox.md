#How to - Firefox

Put this code in the bookmark tool bar.
```
javascript:void%20window.open('http://www.example.com/blogthis/blogthis.html?url='+encodeURIComponent(location.href)+'&title='+encodeURIComponent(document.title)+'&selection='+encodeURIComponent(document.getSelection()),'blogthis');
```