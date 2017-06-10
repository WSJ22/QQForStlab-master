关于angularjs的特点

1.数据的双向绑定：这可能是其最激动人心的特性吧，view层的数据和model层的数据是双向绑定的，其中之一发生更改，另一方会随之变化，这不用你写任何代码！（想想jQuery方式下怎么做吧）

2.代码模块化，每个模块的代码独立拥有自己的作用域，model，controller等。

3.强大的directive可以将很多功能封装成HTML的tag,属性或者注释等，这大大美化了HTML的结构，增强了可阅读性；

4.依赖注入，将这种后端语言的设计模式赋予前端代码，这意味着前端的代码可以提高重用性和灵活性，未来的模式可能将大量操作放在客户端，服务端只提供数据来源和其他客户端无法完成的操作；

5.测试驱动开发，angularjs一开始就以此为目标，使用angular开发的应用可以很容易地进行单元测试和端对端测试，这解决了传统的js代码难以测试和维护的缺陷


使用：
1.  <script src="Js/angular.min.js"></script>
2.npm install angular   <script src="/node_modules/angular/angular.js"></script>
                        Or `require('angular')` from your code.
3.bower install angular   <script src="/bower_components/angular/angular.js"></script>


## Documentation

Documentation is available on the
[AngularJS docs site](http://docs.angularjs.org/).

## License

The MIT License

Copyright (c) 2010-2015 Google, Inc. http://angularjs.org

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.