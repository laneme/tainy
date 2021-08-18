## Bug report for tinymce `autoresize` plugin

This demo is based on a barebones NextJS starter.
No styling, no deps other than `tinymce` and `tinymce-react`.

### Steps

-   Clone this repo
-   `yarn`
-   `yarn dev`
-   Visit `localhost:3000`

### Api key

-   Put your API key in .env.local file. Name it `NEXT_PUBLIC_TINYKEY`
-   Or edit the line pages/index.tsx `apiKey={process.env.NEXT_PUBLIC_TINYKEY}`

### Other branches

-   **with-cra** - CRA (create-react-app) demo

If you want, replace the `initialValue` to anything. Or just paste into the editor.

Make sure the texts are few pages long.

For best result, include different blocks including images.
