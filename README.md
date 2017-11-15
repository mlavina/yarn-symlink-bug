To reproduce:
```
git clone git@github.com:anders-advisa/yarn-symlink-bug.git
cd yarn-symlink-bug/project/
yarn
yarn run mybin
```

expected output is `b-dependency-bin`

actual output is `sub-dependency-bin`
