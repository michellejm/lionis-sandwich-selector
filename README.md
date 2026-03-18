# Sandwich Selector (Lioni’s order helper)

A tiny, zero-dependency web app to select **main ingredients** and **side ingredients**, then generate a clean order summary you can copy.

## Run it

You can either open it directly (no server needed), or run a tiny local server.

### Option A: open the file directly

Double-click `index.html` (or drag it into your browser).

### Option B: local server

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Use it

- Select ingredients from **Mains** and **Sides**
- Use the search bar to filter (e.g., “pesto”, “chicken”)
- Click **Copy summary** to copy the formatted order text
- Click **Add custom** to add an ingredient not in the list (saved in your browser)

## Customize ingredients

Edit the `DEFAULT_INGREDIENTS` list in `index.html`.

