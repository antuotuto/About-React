# About-React

`王安安`

#### 1. React Start 开始

安装 React
> npm install-g create-react-app

新建 React 项目
> create-react-app anan

#### 2. What's React Components  组件

src/App.js
```


  import Home from './html/Home'

  class App extends Component {
    render() {
      return (
        <div className="App">
          <Home></Home>
      );
    }
  }

  export default App;


```

src/html/Home.js
```


  import React, { Component } from 'react';

  class Home extends Component {
      render() {
          return (
              <div className="Home">
                <p>王安安</p>

              </div>
          );
      }
  }

  export default Home;
```

#### 2. 
