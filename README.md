# qed-portfolio-data

Data source for the [QED internal portfolio site](https://github.com/Nerdifitronix). Edit `sites.json` and push; the portfolio site fetches from `main` on every load.

## Add a site

Append an object to the `sites` array. Shape:

```json
{
  "id": "unique-slug",
  "title": "Project Name",
  "subtitle": "One-line description",
  "url": "https://example.com",
  "category": "Platform",
  "status": "Live",
  "logo": { "type": "monogram", "text": "PN", "bg": "#01696F", "fg": "#F7F6F2" },
  "description": "Longer paragraph shown on the card."
}
```

Status values: `Live`, `In development`, `Planning`, `Deprecated`.
