# endeploy
endeploy发布系统测试

URL编码表%20Base64编码表%20HTTP消息含义

URL编码表
backspace 	8% 	A 	41% 	a 	61% 	§ 	%A7 	Õ 	%D5 	 
tab 	9% 	B 	42% 	b 	62% 	« 	%AB 	Ö 	%D6 	 
linefeed 	%0A 	C 	43% 	c 	63% 	¬ 	%AC 	Ø 	%D8 	 
creturn 	%0D 	D 	44% 	d 	64% 	¯ 	%AD 	Ù 	%D9 	 
space 	20% 	E 	45% 	e 	65% 	º 	%B0 	Ú 	%DA 	 
! 	21% 	F 	46% 	f 	66% 	± 	%B1 	Û 	%DB 	 
" 	22% 	G 	47% 	g 	67% 	ª 	%B2 	Ü 	%DC 	 
# 	23% 	H 	48% 	h 	68% 	, 	%B4 	Ý 	%DD 	 
$ 	24% 	I 	49% 	i 	69% 	µ 	%B5 	Þ 	%DE 	 
% 	25% 	J 	%4A 	j 	%6A 	» 	%BB 	ß 	%DF 	 
& 	26% 	K 	%4B 	k 	%6B 	¼ 	%BC 	à 	%E0 	 
' 	27% 	L 	%4C 	l 	%6C 	½ 	%BD 	á 	%E1 	 
( 	28% 	M 	%4D 	m 	%6D 	¿ 	%BF 	â 	%E2 	 
) 	29% 	N 	%4E 	n 	%6E 	À 	%C0 	ã 	%E3 	 
* 	%2A 	O 	%4F 	o 	%6F 	Á 	%C1 	ä 	%E4 	 
+ 	%2B 	P 	50% 	p 	70% 	Â 	%C2 	å 	%E5 	 
, 	%2C 	Q 	51% 	q 	71% 	Ã 	%C3 	æ 	%E6 	 
- 	%2D 	R 	52% 	r 	72% 	Ä 	%C4 	ç 	%E7 	 
. 	%2E 	S 	53% 	s 	73% 	Å 	%C5 	è 	%E8 	 
/ 	%2F 	T 	54% 	t 	74% 	Æ 	%C6 	é 	%E9 	 
0 	30% 	U 	55% 	u 	75% 	Ç 	%C7 	ê 	%EA 	 
1 	31% 	V 	56% 	v 	76% 	È 	%C8 	ë 	%EB 	 
2 	32% 	W 	57% 	w 	77% 	É 	%C9 	ì 	%EC 	 
3 	33% 	X 	58% 	x 	78% 	Ê 	%CA 	í 	%ED 	 
4 	34% 	Y 	59% 	y 	79% 	Ë 	%CB 	î 	%EE 	 
5 	35% 	Z 	%5A 	z 	%7A 	Ì 	%CC 	ï 	%EF 	 
6 	36% 	  	  	  	  	  	  	ð 	%F0 	 
7 	37% 	? 	%3F 	{ 	%7B 	Í 	%CD 	ñ 	%F1 	 
8 	38% 	@ 	40% 	| 	%7C 	Î 	%CE 	ò 	%F2 	 
9 	39% 	[ 	%5B 	} 	%7D 	Ï 	%CF 	ó 	%F3 	 
: 	%3A 	\ 	%5C 	~ 	%7E 	Ð 	%D0 	ô 	%F4 	 
; 	%3B 	] 	%5D 	¢ 	%A2 	Ñ 	%D1 	õ 	%F5 	 
<  	%3C 	^ 	%5E 	£ 	%A3 	Ò 	%D2 	ö 	%F6 	 
= 	%3D 	_ 	%5F 	¥ 	%A5 	Ó 	%D3 	÷ 	%F7 	 
>  	%3E 	` 	60% 	| 	%A6 	Ô 	%D4 	ø 	%F8 	 
  	  	  	  	  	  	  	  	ù 	%F9 	 

Base64编码表

HTTP消息
1xx: 信息
消息:	描述:
100 Continue 	服务器仅接收到部分请求，但是一旦服务器并没有拒绝该请求，客户端应该继续发送其余的请求。
101 Switching Protocols 	服务器转换协议：服务器将遵从客户的请求转换到另外一种协议。
2xx: 成功
消息:	描述:
200 OK 	请求成功（其后是对GET和POST请求的应答文档。）
201 Created 	请求被创建完成，同时新的资源被创建。
202 Accepted 	供处理的请求已被接受，但是处理未完成。
203 Non-authoritative Information 	文档已经正常地返回，但一些应答头可能不正确，因为使用的是文档的拷贝。
204 No Content 	

没有新文档。浏览器应该继续显示原来的文档。如果用户定期地刷新页面，

而Servlet可以确定用户文档足够新，这个状态代码是很有用的。
205 Reset Content 	没有新文档。但浏览器应该重置它所显示的内容。用来强制浏览器清除表单输入内容。
206 Partial Content 	客户发送了一个带有Range头的GET请求，服务器完成了它。
3xx: 重定向
消息:	描述:
300 Multiple Choices 	多重选择。链接列表。用户可以选择某链接到达目的地。最多允许五个地址。
301 Moved Permanently 	所请求的页面已经转移至新的url。
302 Found 	所请求的页面已经临时转移至新的url。
303 See Other 	所请求的页面可在别的url下被找到。
304 Not Modified 	

未按预期修改文档。客户端有缓冲的文档并发出了一个条件性的请求

（一般是提供If-Modified-Since头表示客户只想比指定日期更新的文档）

。服务器告诉客户，原来缓冲的文档还可以继续使用。
305 Use Proxy 	客户请求的文档应该通过Location头所指明的代理服务器提取。
306  Unused 	此代码被用于前一版本。目前已不再使用，但是代码依然被保留。
307 Temporary Redirect 	被请求的页面已经临时移至新的url。
 4xx: 客户端错误
消息:	描述:
400 Bad Request 	服务器未能理解请求。
401 Unauthorized 	被请求的页面需要用户名和密码。
402 Payment Required 	此代码尚无法使用。
403 Forbidden 	对被请求页面的访问被禁止。
404 Not Found 	服务器无法找到被请求的页面。
405 Method Not Allowed 	请求中指定的方法不被允许。
406 Not Acceptable 	服务器生成的响应无法被客户端所接受。
407 Proxy Authentication Required 	用户必须首先使用代理服务器进行验证，这样请求才会被处理。
408 Request Timeout 	请求超出了服务器的等待时间。
409 Conflict 	由于冲突，请求无法被完成。
410 Gone 	被请求的页面不可用。
411 Length Required 	"Content-Length" 未被定义。如果无此内容，服务器不会接受请求。
412 Precondition Failed 	请求中的前提条件被服务器评估为失败。
413 Request Entity Too Large 	由于所请求的实体的太大，服务器不会接受请求。
414 Request-url Too Long 	

由于url太长，服务器不会接受请求。当post请求被转换为带有很长的查询信

息的get请求时，就会发生这种情况。
415 Unsupported Media Type 	由于媒介类型不被支持，服务器不会接受请求。
416  	服务器不能满足客户在请求中指定的Range头。
417 Expectation Failed 	 
5xx: 服务器错误
消息:	描述:
500 Internal Server Error 	请求未完成。服务器遇到不可预知的情况。
501 Not Implemented 	请求未完成。服务器不支持所请求的功能。
502 Bad Gateway 	请求未完成。服务器从上游服务器收到一个无效的响应。
503 Service Unavailable 	请求未完成。服务器临时过载或当机。
504 Gateway Timeout 	网关超时。
505 HTTP Version Not Supported 	服务器不支持请求中指明的HTTP协议版本。
