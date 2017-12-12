# Prettierrc Setting For React

``` Prettierrc
{
  "printWidth": 120,
  "tabWidth": 2,
  "useTabs": false,
  "semi": false,
  "singleQuote": true,
  "trailingComma": "es5",
  "bracketSpacing": true,
  "jsxBracketSameLine": false,
  "parser": "babylon",
  "overrides": [
    {
      "files": ".prettierrc",
      "options": { "parser": "json", "trailingComma": "none" }
    },
    {
      "files": "*.json",
      "options": { "trailingComma": "none" }
    }
  ]
}

```
