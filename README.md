# vscode

{
    "prettier.singleQuote": false,
    "prettier.trailingComma": "all",
    //没有分号
    "prettier.semi": false,
    // 开启 eslint 支持
    "prettier.eslintIntegration": true,
    // 保存时自动fix
    "eslint.autoFixOnSave": true,
    // 添加 vue 支持
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        {
            "language": "vue",
            "autoFix": true
        }
    ],
    // 使用插件格式化 html
    "vetur.format.defaultFormatter.html": "js-beautify-html",
    // 格式化插件的配置
    "vetur.format.defaultFormatterOptions": {
        "js-beautify-html": {
            // 属性强制折行对齐
            "wrap_attributes": "force-aligned"
        }
    },
    "vetur.format.defaultFormatter.js": "vscode-typescript",
    "javascript.format.insertSpaceAfterFunctionKeywordForAnonymousFunctions": true,
    "editor.formatOnSave": true,
}
