```bash
npm i
git reset --hard
git update-index --skip-worktree dist/components/*
git update-index --skip-worktree dist/semantic.*
cd src
ln -s theme.config.dark theme.config
cd ..
gulp build
```

