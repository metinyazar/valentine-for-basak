# Valentine Mini Website (GitHub Pages Ready)

Suggested repo name: **valentine-for-basak**

## Deploy On GitHub Pages

1. Create a new GitHub repository (for example: `valentine-for-basak`).
2. Add these files to the repo root:
   - `index.html`
   - `README.md`
3. Push to the `main` branch.
4. In GitHub, go to **Settings** -> **Pages**.
5. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
6. Save, wait for deployment, then visit the generated Pages URL.

## Customize

### Change the names "Başak" and "Metin"

Edit these text values inside `index.html`:

- `"Happy Valentine’s Day, Başak ❤️"`
- `"Press if you love Metin"`
- `"Forever your Metin."`

### Edit the reasons list

In `index.html`, find:

```js
const reasons = [ ... ];
```

Update the 12 strings in that array.
