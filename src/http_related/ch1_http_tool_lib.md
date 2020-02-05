# HTTP的工具和库
## HTTP开发和调试工具
### Postman
可用于服务器端和其他移动端等，调试接口数据返回是否正常

举例：比如用Postman去调试奶牛云的后台的登录接口：

![](../assets/img/38CFDEB6-8637-4C7C-AC2E-14C7F3AD9B5A.png)

更多内容详见另外的教程：[API开发利器：Postman](http://book.crifan.com/books/api_tool_postman/website/)

### Chrome的开发者工具Developer Tools
调试页面内容是否正常，包括布局，参数等等

详见：[【总结】浏览器中的开发人员工具（IE9的F12和Chrome的Ctrl+Shift+I）-网页分析的利器](https://www.crifan.com/browser_developer_tool_chrome_vs_ie9/)

### curl
模拟去请求服务器数据的命令行工具

### HTTPie
后来从[jobbole/awesome-python-cn: Python资源大全中文版](https://github.com/jobbole/awesome-python-cn)中知道了还有个`HTTPie`

* Github: [jakubroztocil/httpie: Modern command line HTTP client](https://github.com/jakubroztocil/httpie)
* 官网：[HTTPie – command line HTTP client](https://httpie.org)
* 简介：
    * > HTTPie is a command line HTTP client with an intuitive UI, JSON support, syntax highlighting, wget-like downloads, plugins, and more

看了下，比curl更好用，更方便。值得推荐。

### Httpbin
详见：[【整理】Httpbin免费提供HTTP请求和响应的测试网站](http://www.crifan.com/http_tool_free_httpbin_test_request_and_response_website)

## HTTP的代码方面的库
### iOS的swift／OC
* 第三方：
    * [Alamofire](https://github.com/Alamofire/Alamofire)
* swift
    * [SwiftHTTP](https://github.com/daltoniam/SwiftHTTP)

### Python
* 内置：
    * [urllib](https://docs.python.org/2/library/urllib.html)
    * [urllib2](https://docs.python.org/2/library/urllib2.html)
* 第三方：
    * [Requests](https://github.com/requests/requests)

### Javascript
* [Request](https://github.com/request/request)
* [axios](https://github.com/mzabriskie/axios)
* [Web API的Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
    * [window.fetch polyfill](https://github.com/github/fetch)
* [SuperAgent](https://github.com/visionmedia/superagent)

### C&#35;
- [HttpWebRequest](https://msdn.microsoft.com/en-us/library/system.net.httpwebrequest&#40;v=vs.110&#41;.aspx)
