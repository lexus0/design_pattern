# Factory-method pattern<br />

這個pattern講求是容易維護且容易擴充。<br />
<br />
以reference舉的飲料店例子來看, <br />
生成紅茶就要寫個 RedTea R;<br />
生成綠茶就要寫個 GreenTea G;<br />
這樣一來沒辦法因應動態產生不同的物件。<br />
例如根據使用者輸入產生不同的茶類, <br />
每次都要去改source code, 相當麻煩。<br />
如果可以做成根據不同設定產生不同的物件就會方便許多。<br />
例如: <br />
	R = generate_tea("RedTea");<br />
	G = generate_tea("GreenTea");<br />
(TBD)<br />
<br />
# Reference<br />

https://dotblogs.com.tw/joysdw12/archive/2013/06/23/design-pattern-simple-factory-pattern.aspx<br />
http://blog.amowu.com/2009/08/factory-pattern.html<br />
https://en.wikipedia.org/wiki/Open/closed_principle<br />
