## Hello World

PageLogic removes all the boilerplate stuff, leaving only what's relevant for your app &mdash; rather than for the framework you're using.

<div class="md-row">
<div class="md-col md-col-1 app-sample">
<h3><i class="bi bi-chevron-left"></i><i class="bi bi-chevron-right" style="margin: 0 .5rem 0 -3px"></i>www/index.html<!--<i class="bi bi-1-circle right"></i>--></h3>

```html
<html>
  <body>
    <button :count=${0} :on-click=${() => count++}>
      Clicks: ${count}
    </button>
  </body>
</html>
```

</div>
<div class="md-col app-sample">
<h3><i class="bi bi-chevron-right"></i><span style="user-select: none">_</span><!--<i class="bi bi-2-circle right"></i>--></h3>

```bash
npm install -g pagelogic
pagelogic serve www
# http://127.0.0.1:3000
```

</div>
<div class="md-col">
<div class="md-col app-sample">
<h3><i class="bi bi-window" style="margin-left: .15rem"></i><!--<i class="bi bi-3-circle right"></i>--></h3>
<iframe title="Hello World Example" src="https://pagelogic.dev/samples/quick-start" loading="lazy"></iframe>
</div>
</div>
