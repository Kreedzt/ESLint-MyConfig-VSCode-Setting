# ESlint 配置 + VSCode 设置

*   [ESlint 配置 + VSCode 设置](#eslint-%E9%85%8D%E7%BD%AE-vscode%E8%AE%BE%E7%BD%AE)
    *   [ESlint 设置](#eslint%E8%AE%BE%E7%BD%AE)
    *   [VSCode 设置](#vscode%E8%AE%BE%E7%BD%AE)

## ESlint 设置

```json
{
    "parser": "babel-eslint",
    "parserOptions": {
        "ecmaVersion": 5
        // "sourceType": "module"
    },
    "extends": "airbnb",
    // "installedESLint": true,
    "plugins": [
        "react",
        "jsx-a11y",
        "import"
        // "prettier"
    ],
    "env": {
        "jquery": true
    },
    "rules": {
        "indent": ["error", 4],
        // "prettier/prettier": "error"
        "no-undef": 1,
        "no-unused-expressions": 1
    }
}
```

## VSCode 设置

TODO:

*   [ ] ~~设置~~
