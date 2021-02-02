# Automated Build System

## Builds
### Preview

Commits with changes in **/publications/** are triggering the [Build pm2-Guide Preview Action](./workflows/preview.yml).

Commit hash and date are included in the pdf. The filename is `pm2guide-#commithash.pdf`. 

### Release

**Commits tagged for release** are triggering [Build pm2-Guide Action](./workflows/build_pm2guide_release.yml)

Version number must follow [Semantic Versioning](https://semver.org/).

Version number and date are included in the pdf. The filename is `pm2guide-#version.pdf`. 

## Download

Preview & Release builds can be downloaded at the [Github Release Page](https://github.com/pm2alliance/opm2-en/releases)