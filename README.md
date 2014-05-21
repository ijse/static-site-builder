static-site-builder
===================

Create static site with templates and mock data.

Integrated with grunt, support: 

* Freemarker templates compilation
* Less and coffee-script support
* Watch file changing and livereload
* Output project files with grunt build



## Start

```
git clone https://github.com/ijse/static-site-builder.git
cd static-site-builder
grunt server
grunt build
```

## Description

`/mocks` folder: 

```
module.exports =[{
  view: "/simple.ftl",
  out: "/index.html",
  data: {
    name: "ijse"
  }
}];
```

 - view: template file relative to `/templates`
 - out: output html file
 - data: mock data to the template

`/templates` folder: contain template files



## License

(The MIT License)

Copyright (c) 2014 ijse <i@ijser.cn>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
