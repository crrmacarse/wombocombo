# PROJECT WOMBOCOMBO
An attempt to combine multiple front-end libraries in one website!

## The Idea

Let jekyll be the main handler of routes that redirects to its designated frontend scripts build.

### Something like this:

- User visits "/" which is a jekyll build that display possible frontend libraries
- Given a User clicks the "React" version it should forward itself to -> /react
- Which in turns load the designated html to it with script tag at bottom.
- The script would go something like this:

```
<script type="text/javascript" src="/react/bundle-name.bundle.js"></script></body>
```

- "/react/" is a subfolder within the dist folder that contains bundled files specific for react build.

### Target builds
- React
- VueJS
- Svelte
- Lightweight version
- EJS(?)

### Structure

```
dist
dist/react <- bundles
dist/vuejs <- bundles
dist/svelte <- bundles
dist/lightweight <- bundles
dist/ejs <- bundles
dist/assets <- shared assets
dist/index.html <- entry point
react <- src
vue <- src
svelte <- src
lightweight <- src
ejs <- src
...
<standard root configs and values />
...
```

It'll be fun one for sure! 

---
Follow me at twitter: [🐔](https://twitter.com/pablongbuhaymo)
