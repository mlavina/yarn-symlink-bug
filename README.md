To reproduce:
```
git clone git@github.com:mlavina/yarn-symlink-bug.git
cd yarn-symlink-bug/
yarn
yarn run mybin
```

expected output is `b-dependency-bin`

actual output is `sub-dependency-bin`
