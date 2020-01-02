# Resume Static Site

My resume is created using the [JSON Resume Schema](https://jsonresume.org/schema/) and hosted in an S3 static site.

## Install

Installation of the dependencies can be handled through NVM running node `lts/erbium`.

```bash
npm config set puppeteer_skip_chromium_download true -g
npm install -g resume-cli jsonresume-theme-elegant

# Initialize
resume init
```
