# ax5.info

## ax5.info.version
Version of ax5
```js   
console.log(ax5.info.version);
```
---
## ax5.info.eventKeys
eventKeys object key map
```js   
console.log(ax5.info.eventKeys);
/*
{ "BACKSPACE": 8, "TAB": 9, "RETURN": 13, "ESC": 27, "LEFT": 37, "UP": 38, "RIGHT": 39, "DOWN": 40, "DELETE":
46, "HOME": 36, "END": 35, "PAGEUP": 33, "PAGEDOWN": 34, "INSERT": 45, "SPACE": 32 }
*/
```
---
## ax5.info.browser
It is user browser infomation
```js
console.log(ax5.info.browser);
// {"name": "chrome", "version": "46.0.2490.86", "mobile": }
```
---
## ax5.info.urlUtil
Return current page's URL Infomation
```js
console.log(ax5.info.urlUtil());
/*
{
"href":"http://ax5ui:2028/ax5core/info/ax5-info.html",
"param":"",
"referrer":"http://ax5ui:2028/ax5core/util/ax5-util.html",
"pathname":"/ax5core/info/ax5-info.html",
"hostname":"ax5ui",
"port":"2028",
"url":"http://ax5ui:2028/ax5core/info/ax5-info.html",
"baseUrl":"http://ax5ui:2028"
}
*/
```
---
## ax5.info.errorMsg
When an error occurs in the UI Class, the error message can be customized.
```js
// reset user error message
ax5.info.errorMsg["UI name"]["100"] = "my error 100";
ax5.info.errorMsg["UI name"]["200"] = "my error 200";

// or reset all
ax5.info.errorMsg["UI name"] = {
   "100": "is 100 error",
   "200": "is 200 error"
};
```
---
## ax5.info.ETC
```js
ax5.info.isBrowser; // is borwser ?
ax5.info.wheelEnm; // Current browser whell event name
console.log(ax5.info.weekNames);
/*
[
{label: "SUN"},
{label: "MON"},
{label: "TUE"},
{label: "WED"},
{label: "THU"},
{label: "FRI"},
{label: "SAT"}
]
*/
```
