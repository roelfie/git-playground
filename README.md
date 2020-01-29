# Git Playground

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
