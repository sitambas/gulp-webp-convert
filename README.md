# gulp-webp-convert
Convert multi folder jpg file to webp format in one go with gulpConvert multi folder jpg file to webp format in one go with gulp


## What is WebP, and Why Should I Even Care?
WebP is an image format developed and first released by Google in 2010. It supports encoding images in both lossless and lossy formats, making it a versatile format for any type of visual media, and a great alternative format to both PNG or JPEG.


## What’s the browser support?
Image format that supports lossy and lossless compression, as well as animation and alpha transparency.
![alt text](https://cdn-images-1.medium.com/max/1200/1*CH6hoT3s0P-jdIIf41YQ3Q.jpeg)


## Steps
- Pull Repository
- Update tasks.json


```
{
    "webp-dest1": {
        "sourcePath": "./dest/dest1",
        "destPath": "./dest/webp",
        "watchPath": "dest/dest1"
    },
    "webp-dest2": {
        "sourcePath": "./dest/dest2",
        "destPath": "./dest/dest2",
        "watchPath": "dest/dest2"
    }
}

```

## Command

```
npm run webp-convert
```
## Command With forever
```
forever start -c "npm run webp-convert" index.js
```

### Feedback

Pull requests, feature ideas and bug reports are welcome

### License

MIT
