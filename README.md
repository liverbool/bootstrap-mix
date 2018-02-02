# Bootstrap-mix
Just combine bootstrap's classes to short in use.

##### Before
```html
<button class="btn btn-primary btn-lg w-100">Wide Button Large</button>
<button class="btn btn-outline-primary btn-lg w-100">Wide Outline Button Large</button>
```

##### After
```html
<button class="x-btn-w-primary--lg">Wide Button Large</button>
<button class="x-btn-o-w-primary--lg">Wide Outline Button Large</button>
```

### Mixed Components
  - [x] Buttons

### Limitations
  - Increment of css file size!
    - `bootstrap.min.css 122k`
    - `bootstrap-mix.min.css 556k`

### TODO
  - Reduce css file size!
