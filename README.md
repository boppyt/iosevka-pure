# Iosevka Pure

## How can I use this?
You can either get prebuilt fonts in `truetype` directory, or built it yourself.
Since the iosevka repo is 18G+, I strongly recommend getting a prebuilt fonts.

If you still want to build from source, here's how:
```
# Cloning Iosevka repository
$ git clone --depth 1 https://github.com/be5invis/Iosevka

# Move private build plans
$ mv build-plans.toml Iosevka/private-build-plans.toml

# Install dependency (this assumes that you have node.js, npm and ttfautohint installed)
$ npm install

# Build font
npm run build -- contents::iosevka-pure

# Enjoy! Fonts should be in dist/ once the build is done.
```

