# Character clipart

Add image files to this folder and commit them with the site. Add each image
to `manifest.json` once, with a display name and its path:

```json
{ "name": "My Character", "path": "characters/my-character.png" }
```

The image will then be available in the clipart dropdown when adding a
character or updating an existing character. Use browser-supported image
formats such as PNG, JPG, or WebP. The selected character roster is saved in
this browser; image files are served from the repository after deployment.
