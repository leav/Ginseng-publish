# Ginseng-publish

Play on the web: https://leav.github.io/Ginseng-publish/

## Publishing web build on github pages

- Make sure the compression format is `Uncompressed` within the `Player Settings`.
- Have Unity output the build under the `web` folder. The `index.html` path should be `./web/index.html`.
- A Github action should take care of publishing the content to github pages under https://leav.github.io/Ginseng-publish/.