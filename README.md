# Valentine Mini Website

Single-file romantic mini-site with:
- Playful Yes/No interaction (`No` dodges, `Yes` grows)
- Press button transition
- 12 heart reasons reveal + finale
- After-hearts experience:
  - 6 “Open When…” envelopes
  - 5-question mini quiz
  - Secret code unlock
- Back-to-top floating button

## Customization

### Change names (Başak / Metin)

In `index.html`, edit these strings:
- `Happy Valentine’s Day, Başak ❤️`
- `Press if you love Metin`
- `Forever your Metin.`

### Edit the 12 reasons

In `index.html`, update:

```js
const reasons = [ ... ];
```

### Edit the 6 envelopes

In `index.html`, update:

```js
const envelopes = [ ... ];
```

Each item has:
- `title`
- `message`

### Change the secret code + hint

In `index.html`:
- Update the code value in:

```js
const secretCode = "DUBLIN";
```

- Update the hint text in the Secret Code module markup:
  - `Hint: the city we’re building our next chapter in.`

## Deploy on GitHub Pages

1. Push `index.html` and `README.md` to your GitHub repo (usually on `main`).
2. Open GitHub repo → **Settings** → **Pages**.
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Click **Save**.
5. Wait for build to finish, then open:
   - `https://username.github.io/repo-name`
