# JavaScript Globalization  

https://github.com/ufo-github/globalize/tree/master/Tutorial  
https://github.com/ufo-github/Intl.js  
https://github.com/ufo-github/i18next  


## ECMAScript Internationalization API Specification  
http://www.ecma-international.org/ecma-402/1.0/ECMA-402.pdf  
http://www.ecma-international.org/ecma-402/1.0/  

```js

let x = new Date();

window.Intl.DateTimeFormat('en-US').format(x);
Intl.DateTimeFormat('en-US').format(x);
// "12/18/2016"

window.Intl.DateTimeFormat('zh-CN').format(x);
Intl.DateTimeFormat('zh-CN').format(x);
// "2016/12/18"
``` 

## Compatibility implementation of (ECMA-402)
https://github.com/ufo-github/Intl.js  



## CLDR - Unicode Common Locale Data Repository  
http://cldr.unicode.org/  
![http://unicode.org/reports/tr35/animated-text.gif](http://unicode.org/reports/tr35/animated-text.gif)


## ICU Formatting Messages  
> ICU( the International Components for Unicode  libraries)  
http://userguide.icu-project.org/formatparse/messages  



## The main features of the library are: 库的主要功能包括：

+ Number formatting and parsing 数字格式化和解析
+ Date and time formatting and parsing 日期和时间格式化和解析
+ Relative time formatting 相对时间格式化
+ Currency formatting 货币格式化
+ Message formatting 消息格式化
+ Plural support 多/复数 支持
+ Unit support 单位/单元 支持


## Pluralization 多元化  


## i18next internationalization framework  
http://i18next.com/  
https://github.com/ufo-github/i18next  

https://github.com/i18next/react-i18next  

http://cldr.unicode.org/index/downloads/cldr-30  

http://rxaviers.github.io/globalize-modern-apps/#/0/17  


# JavaScript Globalization 
https://github.com/globalizejs/globalize  
https://github.com/rxaviers/javascript-globalization  
http://formatjs.io/github/  

```codes
let x = new Date();

// window (super global scope variable)

window.Intl.DateTimeFormat('en-US').format(x);
Intl.DateTimeFormat('en-US').format(x);
// "12/18/2016"

window.Intl.DateTimeFormat('zh-CN').format(x);
Intl.DateTimeFormat('zh-CN').format(x);

// "2016/12/18"

let date= new Date(),
    number= 1234567893.1415926927;

console.log(new Intl.NumberFormat('zh-CN').format(number));
console.log(new Intl.NumberFormat('en-US').format(number));
console.log(new Intl.NumberFormat('en-GB').format(number));
console.log(new Intl.NumberFormat('it-IT').format(number));

console.log(new Intl.DateTimeFormat('zh-CN').format(date));
console.log(new Intl.DateTimeFormat('en-US').format(date));
console.log(new Intl.DateTimeFormat('en-GB').format(date));
console.log(new Intl.DateTimeFormat('it-IT').format(date));

/*
"1,234,567,893.142"
"1,234,567,893.142"
"1,234,567,893.142"

"1.234.567.893,142"

"2016/12/18"

"12/18/2016"

"18/12/2016"
"18/12/2016"
 */

``` 

