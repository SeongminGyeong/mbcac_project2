# mbcac_project2
## 팀 프로젝트 안내
<a name="top"></a>
### 주제: 열심히 하자
* 기간: 3달
	* 1달: 분석
	* 1달: 설계
	* 1달: 구현
  
      		-1주: 로그인 <a name="log"></a>
      		-2주: 게시판
      		-3주: 뉴스
  
## 아래의 코드를 참고 하세요~

<a name="code1">code1</a> [로그인](#log)
	
```jsp

<%@page import="com.mbcac.board.BoardDAO2"%>
<%@ page language="java" contentType="text/html; charset=UTF-8" 
	trimDirectiveWhitespaces="true"
    pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.board.BoardDAO2" />

<jsp:useBean id="boa" class="com.mbcac.board.BoardVO2">
	<jsp:setProperty name="boa" property="*" />
</jsp:useBean>

<c:set var="bnum" value="${dao.add(boa)}"/>

{"added":${bnum>0}, "bnum" :${bnum}}

[github마크다운으로 색상 설정하기](https://gist.github.com/luigiMinardi/4574708d404cdf4fe0da7ac6fe2314db)
$\color{#ff0000}{\textsf{색상 설정}}$



<a name="code2">code2</a> 

```jsp
<%@page import="com.mbcac.board.BoardDAO2"%>
<%@ page language="java" contentType="text/html; charset=UTF-8" 
	trimDirectiveWhitespaces="true"
    pageEncoding="UTF-8"%>
<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.board.BoardDAO2" />

<jsp:useBean id="boa" class="com.mbcac.board.BoardVO2">
	<jsp:setProperty name="boa" property="*" />
</jsp:useBean>

<c:set var="bnum" value="${dao.add(boa)}"/>
[go to top](#top)
