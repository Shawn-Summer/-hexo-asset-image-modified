# hexo-asset-image-modified

A hexo plugin to load local image . 
This is a modified version of the hexo-asset-image.
I fix the bug unable to load image in hexo 5 or the  newer version and change its usage too.

# Usege

```shell
npm install --save git+https://github.com/Shawn-Summer/hexo-asset-image-modified.git
```

# Example

```shell
test
└── logo.jpg
test.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](test\logo.jpg)` or HTML image insert version `<img src="test\logo.jpg"/>`  to insert `logo.jpg`.

