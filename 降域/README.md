通过修改document.domain来跨域，但条件是域名要相似，例如:`http://a.jrg.com/a.html`和`http://b.jrg.com/a.html`可以令`document.domain = "jrg.com"`进行降域达到跨域的目的。
