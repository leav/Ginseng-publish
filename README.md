# Ginseng-publish

Play on the web: https://leav.github.io/Ginseng-publish/

## Publishing web build

- Make sure the compression format is `Gzip` within the `Player Settings`, since Github Pages does not support `Brotli` as of now: https://github.com/orgs/community/discussions/21655.
- Have Unity output the build under the `web` folder. The `index.html` path should be `./web/index.html`.
- A Github action should take care of publishing the content to github pages under https://leav.github.io/Ginseng-publish/.