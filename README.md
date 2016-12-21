# mnml-spinner

Minimal one-element spinner/loader

HTML

```html
<div class="mnml-spinner"></div>
```

CSS

````css
.mnml-spinner {
    border: 0.25rem solid #eee;
    border-top-color: #333;
    border-radius: 100%;
    height: 5rem;
    width: 5rem;

    animation: basic 1s infinite linear;
}
    @keyframes basic {
        0%   { transform: rotate(0); }
        100% { transform: rotate(359.9deg); }
    }
