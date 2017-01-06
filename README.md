# mnml-spinner

Minimal one-element spinner/loader

Demo: [https://rawksteady.github.io/mnml-spinner/](https://rawksteady.github.io/mnml-spinner/)

HTML

```html
<div class="mnml-spinner"></div>
```

CSS

````css
.mnml-spinner {
    border-radius: 100%;
    border-style: solid;
    border-width: 0.25rem;
    height: 5rem;
    width: 5rem;

    animation: mnmlSpinner 1s infinite linear;
}
    .mnml-spinner.light {
        border-color: rgba(255, 255, 255, 0.2);
        border-top-color: rgba(255, 255, 255, 1);
    }
    .mnml-spinner.dark {
        border-color: rgba(0, 0, 0, 0.2);
        border-top-color: rgba(0, 0, 0, 1);
    }
    @keyframes mnmlSpinner {
        0%   { transform: rotate(0); }
        100% { transform: rotate(359.9deg); }
    }
