# Zola Deploy Action
Github action for building a Zola site and deploying to Github Pages By BUILDING Zola with features, or use pre-build Zola.


Based on [shalzz/zola-deploy-action](https://github.com/shalzz/zola-deploy-action "Thx")

# Environment Variables (Additional)
* `ZOLA_BUILD_FEATURES`: Features will be used when building Zola. DO NOT set `PREBUILD_FEATURES`.
* `PREBUILD_FEATURES`: Use PRE build Zola from my obs. Only `indexing-zh` available for now.