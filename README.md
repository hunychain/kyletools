# [kyletools.neocities.org](https://kyletools.neocities.org/)

personal website hosted on neocities

## Develop & test

```
hugo server --config hugo.toml,local.toml
```

## Optimize images

- PNG, JPEG, WebP: [tinypng.com](https://tinypng.com/)
- GIF: [ezgif.com](https://ezgif.com/) or
```
gifsicle -O3 --colors 256 <INPUT>.gif -o <OUTPUT>.gif
```

## Build & Deploy

Just push to main! [neocities.yml](/.github/workflows/neocities.yml) takes care of it.

---

### License

The source code in this repository is licensed under [The Unlicense](https://unlicense.org/). 

All other content, unless otherwise stated, is © [hunychain](https://github.com/hunychain). Works by others are © their respective authors.
