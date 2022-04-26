# 🚀 Upload

A neat little monorepo that demonstrates file uploads with an Angular front end and an Express back end. This repo also uses [npm workspaces](https://docs.npmjs.com/cli/v8/using-npm/workspaces) and [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) for absolutely glorious developer ergonomics.

![upload](https://user-images.githubusercontent.com/2646053/165409699-1b597516-1ae9-48a4-b6ce-4f84271c9276.gif)

## Getting Started

Clone this repo using the `--recursive` flag to also clone the submodules
```
git clone https://github.com/bobbyg603/upload.git
```

In the cloned repo, install the node dependencies using `--legacy-peer-deps` because Angular dependencies can be finicky
```
npm i --legacy-peer-deps
```

Start both the client and the server
```
npm start
```

## Developing

If you'd like to modify the server, you may find it useful for the server to reload when changes are made
```
npm run watch
```

More coming soon!
