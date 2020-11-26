+++
weight = 40
+++

### File System

If you are using an existing theme and you want to a specific CSS class or add a dynamic function using javascript. It is possible to extend existing layout.

---

### Node Module

You can use `partials` or you can specify `custom_css` in your configuration :

```toml
[reveal_hugo]
custom_css = "css/custom.css"
```
<small>
The `custom.css` can be present in `static/css/custom.css`
</small>

---

### Build & Deploy

Same as CSS you can extend your presentation with javascript using `partials` or with `custom_js` in your configuration:

```toml
[reveal_hugo]
custom_js = "js/custom.js"
```

<small>
The `custom.js` can be present in `static/js/custom.js`
</small>