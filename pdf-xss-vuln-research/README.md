# XSS Research

 * 사용 가능한 키워드로 XSS가 가능한지 테스트합니다.

 * Test if XSS is available within the range of available keywords.
 
------------------------------------
~~~
함수를 사용해서 app.alert(1)를 호출시킬 수 있다.
I can use user-defined functions.
~~~
------------------------------------
~~~
while(1){print(1)}로 Chrome이 터진다.
정확히 PDF Viewer가 작동 중지한다.
~~~
------------------------------------
~~~
Math.random() 사용이 가능하다는 점에서
Math 객체에 접근이 가능하다.
~~~
------------------------------------
~~~
document와 location 객체 접근이 안된다.
따라서 document.write, location.href 와 같은
페이지에 영향을 주는 행위가 안된다.
~~~
