# TSmanium snippets

Typescript and React snippets in ES6+ for [VS Code](https://code.visualstudio.com/).

> React components snippets are a work in progress.

<!--
## Installation
---
Visual Studio Marketplace
Launch Quick Open:

Linux: Ctrl+P
macOS: ⌘P
Windows: Ctrl+P
Paste the following command and press Enter:

ext install TODO: get install command
-->


## Supported languages (file extensions)
---
* TypeScript (.ts)
* TypeScript React (.tsx)

## Snippets information
---

### Basic snippets

|  Prefix | Method                                                                |
| ------: | --------------------------------------------------------------------- |
| `anfn→` | `(params: paramType): returnType => { }`                              |
|  `nfn→` | `const functionName = (params: paramsType): returnType => { }`        |
|   `fn→` | `function functionName(params: paramsType){ }`                        |
|  `imp→` | `import moduleName from 'module'`                                     |
|  `imd→` | `import { destructuredModule } from 'module'`                         |
|  `ima→` | `import { originalName as aliasName} from 'module'`                   |
|  `exa→` | `export { originalName as aliasName} from 'module'`                   |
|  `enf→` | `export const functionName = (params: paramsType): returnType => { }` |
|  `edf→` | `export default (params: paramsType): returnType => { }`              |
|  `fof→` | `for(let itemName of objectName { }`                                  |
|  `fin→` | `for(let itemName in objectName { }`                                  |
|  `dob→` | `const {propName}: { propType } = objectToDestruct`                   |
|  `dar→` | `const [propName]: [propType] = arrayToDestruct`                      |
---
### Console snippets

| Prefix | Method                              |
| -----: | ----------------------------------- |
| `clg→` | `console.log(object)`               |
| `clo→` | `` console.log(`object`, object) `` |
| `ctm→` | `` console.time(`timeId`) ``        |
| `cte→` | `` console.timeEnd(`timeId`) ``     |
| `cas→` | `console.assert(expression,object)` |
| `ccl→` | `console.clear()`                   |
| `cco→` | `console.count(label)`              |
| `cdi→` | `console.dir`                       |
| `cer→` | `console.error(object)`             |
| `cgr→` | `console.group(label)`              |
| `cge→` | `console.groupEnd()`                |
| `ctr→` | `console.trace(object)`             |
| `cwa→` | `console.warn`                      |
| `cin→` | `console.info`                      |

