# auto-package-version

### Foreword

每次打包，寻找最新 npm 包版本，自动更新版本号

### Installation

```
npm install auto-package-version
```

### Usage

```
const AutoPackageVersion = require('auto-package-version')
new AutoPackageVersion({
    path: path.resolve(__dirname, '..', 'package.json')
})
```
