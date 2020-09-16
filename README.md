# Netlify CMS #4294

```bash
yarn dev
```

Open [http://localhost:5000/](http://localhost:5000/), create a new post, click "Publish and create new".

## Current behavior

After clicking "Publish and create new", the form fields are still populated with the previous entry's values.

## Expected behavior

After clicking "Publish and create new", the entry is saved, a new draft entry is created, and the form fields are cleared.
