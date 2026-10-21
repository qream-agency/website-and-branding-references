# Website Catalog

A filterable gallery of reference websites and branding cases, tagged by industry, style and type.
Two tabs: **Website** and **Branding**. The Branding tab shows only the tags its cases use.

## Add a website
1. Put the cover in `media/` as `<id>.jpg` (about 900px wide). For a video cover, add `<id>.mp4` too.
2. In `index.html`, add a line to the `SITES` list:
   ```js
   {id:"example", name:"Example", url:"https://example.com/", v:1, t:["Technology","Clean","SaaS"]},
   ```
   Leave out `v:1` when there is no video.

## Add a branding case
1. Put the cover in `media/brand/` as `<id>.jpg`.
2. Add a line to the `BRANDS` list in `index.html`, same format as above.

Tags must match the names in `TAGS` exactly. Every line in a list ends with a comma.
