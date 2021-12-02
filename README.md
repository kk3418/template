## Package.json set up

### Install

`yarn add --dev parcel autoprefixer` 

```json
{
  "source": "src/index.html",
  "browserslist": "last 5 versions, not dead",
  "scripts": {
    "start": "parcel",
    "build": "parcel build --no-source-maps --target --dist-dir public --public-url assets"
  },
  "devDependencies": {
    "autoprefixer": "^10.4.0",
    "parcel": "^2.0.1" // or `latest`
  }
}
```
