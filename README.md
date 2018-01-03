# Template V3 - Job

[![Eclipse License](http://img.shields.io/badge/license-Eclipse-brightgreen.svg)](LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/dirigiblelabs/template-v3-job.svg)](https://github.com/dirigiblelabs/template-v3-job/graphs/contributors)


## Overview

Simple scheduled Job with a handler writing in the console every 5 seconds.
```javascript
{
	"expression":"0/5 * * * * ?",
	"group":"dirigible-defined",
	"handler":"{{projectName}}/{{fileName}}-handler.js",
	"description":"{{fileName}} Job"}
}
```

```javascript
console.log("Hello from the {{fileName}} Job");
```

## License

This project is copyrighted by [SAP SE](http://www.sap.com/) and is available under the [Eclipse Public License v 1.0](https://www.eclipse.org/legal/epl-v10.html). See [LICENSE](LICENSE) and [NOTICE.txt](NOTICE.txt) for further details.
