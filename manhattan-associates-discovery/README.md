# Manhattan Associates — Discovery Deck

Static HTML discovery deck for a sales/discovery call with **Sanjeev Siotia** (EVP & CTO, Manhattan Associates).

## Run locally

Open the file directly:

```bash
open index.html
```

Or serve with any static server from this directory:

```bash
python3 -m http.server 8767
# or
npx --yes serve -l 8767
```

Then visit `http://localhost:8767`.

**Navigation:** `←` / `→`, Space, Page Up/Down, click left/right thirds of the slide, or progress dots. Swipe on mobile.

## Deploy to Vercel

From this directory:

```bash
npx vercel
```

Or connect the repo in the Vercel dashboard — framework preset **Other**, root directory with `index.html`. `vercel.json` is included for clean static hosting.

## Slide outline

1. **Cover** — Sanjeev Siotia · Manhattan Associates discovery framing  
2. **Agenda** — Company understanding → Strategic initiatives → Engineering buckets  
3. **Company understanding** — Manhattan Active, cloud mix, suite & market posture  
4. **Strategic initiatives** — Cloud conversion, growth mix, agentic AI, platform/GTM scale  
5. **Engineering lens** — Bridge into revenue / cost / risk  
6. **Three buckets** — Increase revenue · Decrease cost · Decrease risk (with live prompts)  
7. **Discovery questions** — Conversation prompts  
8. **Close** — Success criteria & assumption check  

## Notes

- Public spelling is **Siotia** (often mistyped “Sayota”). Role from Manhattan’s leadership page: EVP & CTO.
- Content is discovery-oriented (hypotheses + questions), not a product pitch.
- Brand-adjacent palette: deep navy `#003B5C` and accent orange `#FF6600`.
