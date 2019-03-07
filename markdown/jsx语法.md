## jsx语法


## jsx基本语法


### ReactDOM

```
import React from 'react'
import ReactDOM from 'react-dom'

let content = <h1>jsx...</h1>

ReactDOM.render(jsx,document.getElementById('root'))

```

### 样式处理

```
// style样式要写成对象形式
let jsx = <div style={{fontSize: 14px;}}></div>

// 当是真实项目中还是使用className='jsx'

import './index.css'

```

### 数据逻辑处理
```
let name = 'Rosen'
let name = ['Rosen','Jack','xiaolong']

let flag = true
// 条件判断
let jsx = (
  <div>
    {/*  条件判断 */}
    {
       flag?<p>I am {name}</p>:<p> I am not {name}</p>
    }
    {/* 数组循环 */}
    {
      names.map((name,index)=><p key={index}>Hello I am {name}</p>)
    }

  </div>
)
```