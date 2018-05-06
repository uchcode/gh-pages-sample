---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# layout: home
---

インデックスページです

```js
var Person = function (firstname, lastname, age) {
  this.firstName = firstname;
  this.lastName = lastname;
  this.age = age;
  
  this.setAge = function (age) {
    this.age = age;
  };
  
  this.toString = function () {
    return ["Hi ! I'm ", this.firstName, " ", this.lastName, " and I'm ", this.age, " year old."].join("");
  };
};
```
