# rsync #

* 同步/share/aa/下所有new開頭的資料夾與子資料夾
```
rsync -avP --include='new*' --include='new*/*' --exclude='*' /share/aa/ /share/bb/
```
