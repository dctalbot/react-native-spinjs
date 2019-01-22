# react-native-spinjs

Loading indicator inspired by the smart people over at spin.js.org

***NOTE: this project is incomplete, and only dots are supported at the moment***

### Download & Installation

```shell
$ yarn add react-native-spinjs
```

### Usage

```javascript
import Spin from 'react-native-spinjs'

// Put a default spinner
<Spin />

// Pass in a config object
<Spin config={configObject}/>

// For convenience, pass in just a config
<Spin color="white"/>
```

Configurable props include:

| name   | default     |
| ------ | ----------- |
| lines  | 12          |
| width  | 5           |
| radius | 50          |
| color  | 'gainsboro' |
| speed  | 100         |

### Contributing

Welcome, encouraged, and needed if this is to become a closer reimplementation of spin.js

PR's, issues, and discussion are welcome at https://github.com/dctalbot/react-native-spinjs

### License

This project is licensed under the MIT License
