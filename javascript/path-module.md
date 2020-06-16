# require('path') module

Provides utilities for working with file and directory paths.

```
const path = require('path');
```

The resolve method for example resolves an absolute path even for relative inputs. For example:

```
path.resolve('src/app');
// If the current working directory is /home
// it will return /home/src/app
```
