# Initialize actions

```
npm init -y
npm i @actions/core
npm i @actions/exec
```

## Compile

```
npm i -g @vercel/ncc
ncc build index.js -o action
```

## Create tag command

```
git tag -a -m "increment git tag" v1
git push --follow-tags
```
