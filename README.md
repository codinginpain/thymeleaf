

# Hello 
## mark down / spring-boot / thymleaf 

---

### to set spring-boot + thymleaf
 - use [Spring Initializr](start.spring.io)
 - snapshot(not official release) -> use none latest non-snapshot version
 - create -> download -> unzip -> open 'build.gradle' with IDE
 - add depencies -> web / lombok / Thymleaf
 - resouce/static/index.html -> automated index file
 - to activate lombok -> setting -> Annotation Processors -> Enable annotation
 - to use thymleaf -> use html tag: <html xmlns:th="http://www.thymeleaf.org">

### thyleaf
 - escape mode default
 - local variable is only used inside of its own tag


### fragment, layout
 - fragment는 조각조각으로 화면 안에 넣어 줄 수 있음(규모가 작을때, 간편하게)
 - layout은 여러 페이지를 1개의 layout안에 던져서 재조립(규모가 클때, 중복이 많을떄 용이하나 약간 복잡해짐)
