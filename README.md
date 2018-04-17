# isHistoryPathEqual

判断history的路径是否相同

使用方式

```js
import isHistoryPathEqual from "ishistorypathequal";
let path1 = "/about";
let path2 = "/about";
isHistoryPathEqual(path1,path2);
//true
path2 = "/home";
isHistoryPathEqual(path1,path2);
//false
```  
**参数**
```js
/**
*@desc object是history中的location对象
*@param {string|object} path1
*@param {string|object} path2
*@return boolean
*/
isHistoryPathEqual(path1,path2);
```  

