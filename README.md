# mbcac_project2
<a name="top"></a> 
## 팀 프로젝트 안내
* 주제: 열심히 하자
* 기간: 3달
  + 1달: 분석
  + 1달: 설계
  + 1달: 구현
    - 1주: 로그인
    - 2주: 게시판
    - 3주: 뉴스
 
1. [로그인](#code1)  
2. [게시판](#code2)  
3. [뉴스](#code3)  
4. [로그인2](#code4)  
5. [게시판2](#code5)  
5. [뉴스2](#code6)  


## 아래의 코드를 참고하세요
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.jdbc.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.jdbc.BoardVO">
   <jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[github마크다운으로 색상 설정하기](https://gist.github.com/luigiMinardi/4574708d404cdf4fe0da7ac6fe2314db)  
$\color{#ff0000}{\textsf{색상 설정}}$  
<p>
   
<a name="code1">로그인</a>  
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.jdbc.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.jdbc.BoardVO">
   <jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[Top▲](#top)

<a name="code2">게시판</a>  
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.jdbc.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.jdbc.BoardVO">
   <jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[Top▲](#top)


<a name="code3">뉴스</a>  
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.jdbc.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.jdbc.BoardVO">
   <jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[Top▲](#top)


<a name="code4">로그인2</a> 
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.jdbc.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.jdbc.BoardVO">
   <jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[Top▲](#top)


<a name="code5">게시판2</a> 
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.jdbc.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.jdbc.BoardVO">
   <jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[Top▲](#top)


<a name="code5">뉴스2</a>  
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcac.jdbc.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcac.jdbc.BoardVO">
   <jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[Top▲](#top)

## Windows에서 자격증명 확인/github관련 자격증명 삭제
## github.com 회원가입
## github 사이트에서 Repository 생성
* Repository 주소 복사
* 
## git 다운로드 /설치
* user.name/user.email 등록
* git config--list : 등록된 항목 확인
* 
## github 토큰 신청/발급
* github.com 화면 우측 상단 아이콘 클릭 > Settings > 왼쪽 메뉴 하단 Developer settings > Personal access tokens >
* Tokens(classic) > Generate new token > Generate new token(classic) >
* Note:간단 설명 입력 > Generate token

## 로컬 Repository에 원격 리파지토리 복사
* 원격 저장소에 등록된 프로젝트를 최초로 로컬 저장소에 복제한다
* git init
* git clone [원격 저장소 주소]
* git config --list  <-- origin 이라는 이름으로 저장소의 주소가 등록된 것을 확인


someday

friend