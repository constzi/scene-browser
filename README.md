# scene-browser

Phone player for previewing exported Bitwig scenes. One static page (`index.html`),
served by GitHub Pages at https://constzi.github.io/scene-browser/.

The page has the owner's Google OAuth client ID and Drive folder ID built in. Neither
is a secret: the client ID only works from this site, and the folder's audio and
ratings can only be read after the owner signs in with Google.

Source of truth: the private `hq` repo, `pipelines/bitwig-scenes/scene-browser-web/`.
Copy `index.html` here to publish a new version.
