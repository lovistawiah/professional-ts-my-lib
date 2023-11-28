# my_lib

``` bash
npx gitignore node
```

``` bash
yarn eslint --init
```

```json
extends: [

    "plugin:@typescript-eslint/recommended-requiring-type-checking"
]
```

A tutorial on how to setup a large scale project using typescript and its ecosystem

## api documentation using api extractor

```bash
yarn add -D @microsoft/api-extractor @microsoft/api-documenter
```

- **Initializer**

- always build project before running the script below

``` bash
yarn api-extractor init
```

``` bash
yarn api-documenter markdown -i temp -o docs
```

this generates a markdown file for the api documentation
