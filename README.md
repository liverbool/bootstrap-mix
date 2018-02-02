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
| x-  | BS Classes |
| ------------- | ------------- |
| .x-btn-{$theme}  | .btn, .btn-{$theme}  |
| .x-btn-{$theme}--sm  | .btn, .btn-{$theme}, .btn-sm  |
| .x-btn-{$theme}--lg  | .btn, .btn-{$theme}, .btn-lg  |
| .x-btn-w-{$theme}  | .btn, .btn-{$theme}, .w-100  |
| .x-btn-w-{$theme}--sm  | .btn, .btn-{$theme}, .w-100, .btn-sm  |
| .x-btn-w-{$theme}--lg  | .btn, .btn-{$theme}, .w-100, .btn-lg  |
| .x-btn-o-{$theme}  | .btn, .btn-outline-{$theme}  |
| .x-btn-o-{$theme}--lg  | .btn, .btn-outline-{$theme}, .btn-lg  |
| .x-btn-o-{$theme}--sm  | .btn, .btn-outline-{$theme}, .btn-sm  |
| .x-btn-o-w-{$theme}  | .btn, .btn-outline-{$theme}, .w-100  |
| .x-btn-o-w-{$theme}--sm  | .btn, .btn-outline-{$theme}, .w-100, .btn-sm  |
| .x-btn-o-w-{$theme}--lg  | .btn, .btn-outline-{$theme}, .w-100, .btn-lg  |

### Limitations
  - Increment of css file size!
    - `bootstrap.min.css 122k`
    - `bootstrap-mix.min.css 995k`

### TODO
  - Reduce css file size!! (maybe make some bootstrap eg. `.btn, .btn-xx` to be abstraction with `%` placeholder, this mean `.btn, .btn-xx` will gone away!)
