# stop using webpack 🎉

```
return require('@embroider/compat').compatBuild(app, null, {
    staticAddonTestSupportTrees: true,
    staticAddonTrees: true,
    staticHelpers: true,
    staticModifiers: true,
    staticComponents: true,
    staticEmberSource: true,
    skipBabel: [
      {
        package: 'qunit',
      },
    ],
  });
```

note: |
  Let's write some notes!