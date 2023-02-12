$ npm init

React 설치
$ npm i react
$ npm i react-dom 

Babel 설치
$ npm i @babel/core -D
$ npm i @babel/preset-env -D
$ npm i @babel/preset-react -D

Webpack 설치
$ npm install webpack -D
$ npm install webpack-cli -D
$ npm install webpack-dev-server -D

npm i babel-loader


[Babel 이란?]


[webpack 이란?]


[webpack.config.js]
Entry
: 웹팩에서 웹 자원을 변환하기 위해 필요한 최초 진입점.
- https://webpack.js.org/concepts/entry-points/
- https://joshua1988.github.io/webpack-guide/concepts/entry.html
- Entry 속성에 지정된 파일에는 웹 애플리케이션의 전반적인 구조와 내용이
담겨져 있어야 하며, 웹팩이 해당 파일을 가지고 웹 애플리케이션에서 
사용되는 모듈들의 연관 관계를 이해하고 분석하기 때문에 애플리케이션을 
동작시킬 수 있는 내용들이 담겨져 있어야한다.
 
