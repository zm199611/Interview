## get 和 post请求的差别?
答:一般get请求都是查找请求，不会对服务端数据造成修改。而post请求一般都会对服务器数据造成修改，所以一般会对get请求进行缓存，但是很少对post请求进行缓存。

## 什么是跨域，如何解决跨域问题?
答:因为浏览器出于安全考虑，所以有同源策略。
同源策略是浏览器最核心也是最基本的安全功能，如果缺少了同源策略，浏览器很容易受到XSS，CSFR等攻击。
所谓同源是指“域名+协议+端口”三者相同 