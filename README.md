# Flowmaker

Flowmaker는 다른 레벨의 코드 흐름을 보여주기 위해 SVC 형식의 자바 스크립트 코드로 순서도를 생성하는데 사용되는 VSCode 확장입니다.

[![Flowmaker features](https://i.imgur.com/FIacJUP.gif)](https://youtu.be/ySW2ejs6f84)

[![onBrowser demo](https://i.imgur.com/k77hQLy.png)](https://youtu.be/ySW2ejs6f84)

**주의:**
참고 : onEditor SVG 생성 만 사용하려면 livepreview  <a href="https://github.com/aryaminus/flowmaker/tree/livepreview" target="_blank">livepreview</a> 지점 코드를 따르십시오.

For showing in both Browser and Editor follow the <a href="https://github.com/aryaminus/flowmaker/tree/onBrowser" target="_blank">onBrowser</a> branch code.

## Instructions
- Write Javascript.
- Select a function or object or entire file.
- Hit ctrl-f1.
- Choose either 'Flowmaker: Preview' or 'Flowmaker: Save'.
- 'Flowmaker: Preview' generates the SVG layout in side column of editor itself.
- 'Flowmaker: Save' allows the user to download the SVG code in the same directory as the file.

## Installation

From [VS Code](https://code.visualstudio.com) Market [Install Flowmaker](https://goo.gl/yRmQNk):
**Install Flowmaker extension:**
```
Launch VS Code Quick Open (Ctrl+P), paste the following command:
ext install speks.flowmaker
```
Then,
```
Open any .js file
hit Fn+f1 or F1
choose Flowmake onEditor or Flowmake onBrowser
```
***or,***
Clone the source locally:
```
$ git clone https://github.com/aryaminus/flowmaker
$ cd flowmaker
$ npm install
```
***and,***
**Start the application in development mode**
```
hit Ctrl+f5
hit Fn+f1 or F1
choose Flowmaker: Save or Flowmaker: Preview
```

## Packages:
1. <a href="https://github.com/Bogdan-Lyashenko/js-code-to-svg-flowchart" target="_blank">js2flowchart</a>
2. <a href="https://github.com/GramParallelo/atom-js-code-to-svg-to-preview" target="_blank">atom-js-code-to-svg-to-preview</a>

## Features

[![onEditor demo](https://i.imgur.com/F3LC8LA.png)](https://youtu.be/ySW2ejs6f84)

### TODO:
- [ ] JSX support
- [ ] Flow,CLI and Typescript support
- [ ] Chrome extension for dev-tools
- [ ] Fetching SVG to generate and manipulate code to genrate code from flowchart

-----------------------------------------------------------------------------------------------------------

## Contributing

1. Fork it (<https://github.com/aryaminus/flowmaker/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

**Enjoy!**
