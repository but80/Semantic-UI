```bash
yes '' | npm i
git update-index --skip-worktree dist/components  # Use \ instead of / on Windows
git reset --hard
cd src
rm theme.config
ln -s theme.config.dark theme.config  # Do "copy" instead of "ln -s" on Windows
cd ..
gulp build
```

This theme includes Roboto font from Google Fonts
licensed under [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).
