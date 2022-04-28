# jest-28-bug-reporter-default

1. `git clone https://github.com/ext/jest-28-bug-reporter-default.git`
2. `npm install`
3. `npm test`

## Workaround

`jest-preset.js`:

```diff
 module.exports = {
-	reporters: ["default"]
+	reporters: [["default"]]
 }
```
