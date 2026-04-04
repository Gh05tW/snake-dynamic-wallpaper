English | [cn 中文文档](README_CN.md)
# Snake Dynamic Wallpaper

A snake game animation as your Windows desktop wallpaper.
![](https://cdn.jsdelivr.net/gh/Gh05tW/snake-dynamic-wallpaper@main/images/example.png)
## Installation

1. Install [Lively Wallpaper](https://www.microsoft.com/store/productId/9NTM2QC6QWS7) from Microsoft Store
2. Drag `lively/index.html` into Lively Wallpaper window
3. Done

## Customization

Edit `lively/index.html`:

```javascript
const CELL_SIZE = 15;      // Block size (px)
const GAP_SIZE = 5;        // Grid gap (px)
const INITIAL_LENGTH = 5;  // Initial snake length
const GROW_AMOUNT = 15;    // Growth per food
const FRAME_DELAY = 30;    // Speed (ms, lower = faster)
```

## File Structure

```
dynamic-wallpaper/
├── lively/
│   ├── index.html         # Wallpaper file
│   └── LivelyInfo.json    # Config
└── README.md
```

## License

MIT
