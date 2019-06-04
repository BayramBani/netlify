# Git
---

- create a new repository on the command line

```bash
echo "# Project Name" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/BayramBani/react-starter.git
git push -u origin master
```

- push an existing repository from the command line

```bash
git remote add origin https://github.com/BayramBani/react-starter.git
git push -u origin master
```

- delete all

```bash
git rm -r * -f -q
git commit -m 'Delete all the stuff'
git push -u origin master
```

- Tags

```
git tag <tagname>
git push origin --tags
```
