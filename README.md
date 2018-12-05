# React Native Web Player
Run react native apps in your browser!

## Development

### Run

```
npm install
npm run start
=> localhost:8080
```

### Build

```
npm run build
```

### Publish

First publish to npm.

```
npm version (major|minor|patch)
npm publish
```

Then publish to gh-pages and make a special tagged release for hosting via CDN.

```
# Point to the latest release
make TAG=v2.0.0-alpha.3
```