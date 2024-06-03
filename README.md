# useful-git-hooks

## pre-commit hook

File `validate_file_size.sh`.  Iterates over files in repository and check their sizes. If file size is greater than given `FILE_SIZE_LIMIT`, commit will be rejected. 

**Usage**

```sh
cp validate_file_size.sh /your/repository/path/
cd /your/repository/path/
```

```sh
cp validate_file_size.sh ./.git/hooks/pre-commit
```

```sh
chmod +x ./.git/hooks/pre-commit
```

---
