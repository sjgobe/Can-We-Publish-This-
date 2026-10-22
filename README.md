# Can We Publish This?

A classroom game about checking what AI writes against library sources. Project it, let the class vote at each step, and click their answer.

Everything in the game is invented: the college, the people, the records, and the AI text.

## Run it

Open `index.html` in any browser. No install or internet connection is needed, except to load the fonts.

**Controls**
- Right arrow or **Next**: go forward
- Left arrow or **Back**: go back
- **N**: show or hide facilitator notes (script and answers)
- **F**: full screen

## Put it on GitHub Pages

1. Create a new repository and upload `index.html` and this README.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. After a minute, your game is live at `https://<your-username>.github.io/<repository-name>/`.

## Add your library's links

The last screen links to your library's real tools. Open `index.html`, find `LIBRARY` near the top, and fill in the names and URLs:

```js
const LIBRARY = {
  newspaper: { name: "Our newspaper database", url: "https://..." },
  catalog:   { name: "Our catalog and archives", url: "https://..." }
};
```

## How it plays (about 30–40 minutes)

1. Read the AI-written report.
2. Check four claims: choose where to look, read the evidence, and vote Supported, Contradicted, or Still unknown.
3. Answer the producer: "Can't we just ask AI to look it up?"
4. Choose the better prompt.
5. Find the sentence the AI still got wrong.
6. Choose an opening the podcast can publish.
7. Try your library's real tools.

The class score counts answers the class gets right on the first try.
