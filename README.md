1. init project

```
yarn init
echo "node_modules" >> .gitignore
git init
```

2. Add dependencies

```
# add runtime dependencies
yarn add react react-dom prop-types axios

# add dev dependencies
yarn add itg-react-scripts eslint-config-adorable --dev
```

3. add start script to `package.json`

```json
"scripts": {
  "start": "itg-react-scripts start"
}
```

4. add eslint config to `package.json`

```json
"eslintConfig": {
  "extends": [ "adorable" ]
}
```

5. create `public/index.html` file
6. create `src/` files
7. run `yarn start`
