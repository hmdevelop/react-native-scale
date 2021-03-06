# react-native-scale

> https://github.com/hmdevelop

## Install

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i react-native-scale --save-dev
```

## Usage

 
```js
import {wp,hp,ael,rel,normalize} from "react-native-scale"

const styles = StyleSheet.create({
  container: {
    width:wp("75") ,
    height:hp("25"),
    backgroundColor:"green",
    alignItems: 'center',
    justifyContent: 'center',
  },
  text: {
    fontSize: normalize(12),
    color:"white"
 }})

```
## Usage with styledComponents

 
```js
import {wp,hp,ael,rel,normalize} from "react-native-scale"
import styled from 'styled-components/native'
   

   const Container = styled.View`
   width: ${wp("98") } ;
    height: ${hp("15")} ;
    background-color: #FFFFFF;
`

const StyledText = styled.Text`
    align-items: 'center';
    background-color: '#DDDDDD';
    font-size : ${normalize(18)};
 
`


```


## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/hmdevelop/react-native-scale/issues)

## Author

**mustafa topal**

* [github/](https://github.com/)
* [twitter/](http://twitter.com/)

## License

Copyright © 2018 [mustafa topal](#mustafa topal)
Licensed under the ISC license.

***

_This file was generated by [readme-generator](https://github.com/jonschlinkert/readme-generator) on September 22, 2018._
