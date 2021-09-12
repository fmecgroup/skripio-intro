# What is skripio?
**Skripio** is a set of UI **components** designed and built for `1C:Enterprise` platform. 

These components allow `1C:Enterprise` developers to implement UI elements in `1C:Enterprise` forms that are not available as a part of the default platform toolkit.  

**Skripio components** are intended to help `1C:Enterprise` developers enrich user experience of their application through implementing native web technologies and open source libraries.

**Skripio components** are fully functional bundles that can be easily added into `1C:Enterprise` project with zero `JavaScript` code.

# Why skripio?

On _September 20th 2018_ **1C** [announced](https://wonderland.v8.1c.ru/blog/perevod-klientskikh-prilozheniy-dlya-windows-na-ispolzovanie-webkit-optimizatsiya-otobrazheniya-html/) webkit support as platform HTML generating engine. 

This platform feature technically allows `1C:Enterprise` developers to create custom UI element with help of modern technologies such as: `HTML5`, `CSS3`, `JavaScript ES6`.

However, such component development in most of the cases will require `HTML`, `CSS` or `JavaScript` coding to be done by developer which drastically extends development time frames.

Here are a few 1C - webkit limitations that require coding outside of `1C:Enterprise` platform environment:

- **Primitive types in function calls**. When calling a JS function or method from `1C:Enterprise` only primitive types can ba passed. Passing a collection of any kind results in `undefined` value upon argument receiving.
- **No JS prototype chain support**. If there is an object instantiated of a class that inherits another class then object's methods are located in it's parent object. In such case those methods are not accessible out of `1C:Enterprise` environment.
- **No async code support**. It is impossible to pass a `1C:Enterprise` method or procedure as a callback to `JavaScript` function. If `JavaScript` function or method requires a callback passed to it as an argument, that function can not be used directly out of `1C:Enterprise` environment. Going forward, no native `JavaScript` async code is accessible out of 1C. Such as: _Promises_, _async/await_, _callbacks_. A `JavaScript` wrapper is required to organize that type of interaction.

The aforementioned list of limitation have caused skripio components to emerge.

# Getting started with skripio

Step-by-step guide to implement skripio component in a `1C:Enterprise` project:  
TODO:

# Contribute

[Contribute 1C](https://github.com/fmecgroup/skripio-intro/blob/master/CONTRIBUTE1C.MD) - Guide to contribute to the project in case you are a `1C:Enterprise` developer.  
[Contribute JS](https://github.com/fmecgroup/skripio-intro/blob/master/CONTRIBUTEJS.MD) - Guide to contribute to the project in case you are a `JavaScript` developer.