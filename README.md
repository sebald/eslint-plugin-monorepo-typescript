# eslint-plugin-monorepo-typescript

> See https://github.com/azz/eslint-plugin-monorepo/issues/8

Executing `yarn lint` will cause the following error:

```
/<path>/eslint-plugin-monorepo-typescript/packages/foo/index.ts
  1:1  error  Resolve error: unable to load resolver "node"  monorepo/no-relative-import
```


Adding `eslint-plugin-import` as dependency will resolve this issue.
