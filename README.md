1. Install git-lfs
2. Init git repository: `git init`
3. Init git-lfs in repo: `git lfs install`
4. Track lfs files: `git lfs track ../path/to/file.format`
5. update .gitattributes: `git add .gitattributes && git commit -m 'up'`
6. commit files: `git add ../path/to/file.format && git commit -m 'up'`

### .lfsconfig
В lfs указывается не путь к репозиторию, а "<url>/info/lfs"
```ini
[lfs]
url = https://wonderland.taki/gitea/TakiMoysha/git-test-lfs.git/info/lfs
```
