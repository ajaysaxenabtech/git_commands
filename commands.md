
```bash
git add --all

git status

git commit -m "<commit message>"

git push origin main

```


make directory

```bash
mkdir <directoryname>
```

Rename or delete the existing directory if you don't need it
```bash
mv <directoryname>
```

if you want to remove it completely
```bash
rm -rf <directoyname>
```

You can **manually delete the `index.lock` file** if you're sure no other Git process is currently running:

```bash
rm -f .git/index.lock
```

Then try your Git command again:

```bash
git add --all
```

