# Git Playground

GitHub Flavoured Markdown (GFM) [Specs](https://github.github.com/gfm/) and [Cheat Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) and [emoji](https://www.webfx.com/tools/emoji-cheat-sheet/)

## Configuration

Show the origin of configuration (you can do this inside a git project, or in a non-git folder to view only the global settings):
```
git config --list --show-origin
```

Use different name/email per project (--local is default hence optional):
```
cd <project>
git config [--local] user.name "John Doe"
git config [--local] user.email john@doe.com
```

:warning: It's recommended to use `--local` because it will help you prevent overwriting global configuration.