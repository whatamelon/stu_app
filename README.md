
# Prj_stuCardApp

### 개발자 : 길현준 , 김현기 , 홍승호
### 개발일자 : 2018.12.17 ~ 2018.12.20    
## 개발 스택  

  - 개발환경 : Eclipse Oxygen ver.2
  - Main 언어 : Java
  - 개발 기술 : JavaScript , Jsp , Ajax , Spring MVC pattern.1 , Mybatis
  - DB : Oracle

## 폴더 구조

    .metadata
    .settings
    .META-INF
    Servers
    WebContent
	    ㄴMETA-INF
	    ㄴWEB-INF
		    ㄴlib ( jar 파일 )
		    ㄴview ( jsp 파일 )
	    ㄴcss ( css 파일 )
	    ㄴfonts ( 추가된 font는 ttf만 적용 )
	    ㄴimg ( 기본 이미지 )
	    ㄴjs ( js 파일 )
	    ㄴscss ( scss 파일 )
	    ㄴstu_photo ( 학생 사진 파일 저장 경로 )
    src
	    ㄴ config ( DB와 Spring 연동 )
	    ㄴ poly
		    ㄴcontroller
		    ㄴdto
		    ㄴfilter
		    ㄴinterceptor ( 자동 로그인 구현 )
		    ㄴpersistance
		    ㄴservice
		    ㄴutil ( 사진 저장 구현 )
    target
    .classpath
    .project
    .pom.xml

  
## 설명  
학생 식권 및 모바일 학생증 카드 앱

## 개발과정

### UI ( 홍승호 )

	js 와 css3를 이용해서 UI를 구현함

### 기능 구현 ( 길현준 , 김현기 , 홍승호 )
	js와 java를 이용해서 기능을 구현함

### Back-End ( 길현준 , 김현기 )
	spring MVC pattern1 을 이용해서 백엔드를 구성함

### RDBMS ( 김현기 )
	MySQL을 이용하여 DB를 구성함
