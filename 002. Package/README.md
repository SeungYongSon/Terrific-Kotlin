# 패키지

코틀린 소스 파일은 package 의 선언으로 시작한다.
소스 파일의 모든 내용(클래스와 함수 등)은 선언된 패키지에 포함된다.  

package foo.bar

fun baz() {}

class Goo {}

// ...

위 예의 경우 baz() 의 전체 이름은 foo.bar.baz 이고  
Goo 의 전체 일므은 foo.bar.Goo 이다.  

패키지를 지정하지 않으면, 파일의 내용은 이름 없는 "디폴트" 패키지에 속한다.  

코틀린에서의 패키지에 대한 좀 더 자세한 내용은 main.kt 파일 내용을 봐주길 바란다.  