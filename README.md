# Bootstrap-mix
Just combine bootstrap's classes to short in use.

##### Before
```html
<button class="btn btn-primary btn-lg w-100">Button</button>
<button class="btn btn-outline-primary btn-lg w-100">Button</button>
```

##### After
```html
<button class="x-btn-w-primary--lg">Button</button>
<button class="x-btn-o-w-primary--lg">Button</button>
```

### Limitations
  - Increment of css file size!
    - `bootstrap.min.css 122k`
    - `bootstrap-mix.min.css 556k`

### TODO
  - Reduce css file size!
