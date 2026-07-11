# Adding Content

This site is plain static HTML and is ready for GitHub Pages.

## Add a new item

1. Create a new `.html` file in `content/left/`, `content/right/`, or `content/bottom/`.
2. Put only the content for that block in the file, not a full HTML document.
3. Add the file path to the matching `data-content-files` list in `index.html`.

Files listed in the bottom content section render as centered cards below the closing text.

Example:

```html
<h2 class="h5">New piece title</h2>
<p class="mb-0">Short text for this content block.</p>
```

## Add an image-only item

Use this shape inside a content file:

```html
<img class="content-image" src="img/example.jpg" alt="Describe the image">
```

The image path is relative to `index.html`, so images in the existing `img/` folder should use `img/file-name.jpg`.
