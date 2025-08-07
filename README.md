# ToDo

## Project Structure

```
webpack-template/
├── package.json
├── webpack.common.js      # Shared configuration
├── webpack.dev.js         # Development-specific config
├── webpack.prod.js        # Production-specific config
├── src/
│   ├── html
│   │   ├── index.html     # HTML template
│   └── js
│   │   ├── index.html     # App entry point (JS and CSS imports)
└── dist/                  # Generated after build
```

## Usage

1. **Clone the repo**:
   ```bash
   git clone https://github.com/BASU4100/webpack-template.git
   cd webpack-template
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

## License
Licensed under the [MIT License](LICENSE).
