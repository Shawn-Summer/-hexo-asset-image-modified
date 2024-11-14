# hexo-asset-image-modified

This is a modified version of the hexo-asset-image.
I fix the bug unable to load image in hexo 5 or the  newer version and change its usage too.

Give asset image in hexo a absolutely path automatically

# Usege

```shell
npm install hexo-asset-image --save
```

# Example

```shell
MacGesture2-Publish
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
MacGesture2-Publish.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](logo.jpg)` to insert `logo.jpg`.

# History

2018-04-18: support hexo-abbrlink
