https://github.com/facebook/create-react-app/issues/11809

run `yarn start`, again and again -> you'll get different

## expected

eslint always shows error

```
ERROR in src/App.tsx
  Line 5:1:  Unexpected var, use let or const instead  no-var
```

## actual

eslint sometimes doesnt show error on build

```
cached modules 1.37 MiB (javascript) 31.3 KiB (runtime) [cached] 121 modules
webpack 5.66.0 compiled successfully in 733 ms
Files successfully emitted, waiting for typecheck results...
Issues checking in progress...
No issues found.
```
