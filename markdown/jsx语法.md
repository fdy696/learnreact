## jsx语法


### jsx基本语法

```
import React from 'react'
import ReactDOM from 'react-dom'

let content = <h1>jsx...</h1>

ReactDOM.render(jsx,document.getElementById('root'))

```
#### jsx样式
```
// style样式要写成对象形式
let jsx = <div style={{fontSize: 14px;}}></div>

// 当是真实项目中还是使用className='jsx'

import './index.css'

```

### ReactDOM

### 样式处理

### 数据逻辑处理