# 🍀 Hello Nature 🍀

## 1. 프로젝트 요약
* 식품업계에서 성장하고 있는 온라인 푸드테크 기업 쇼핑몰인 헬로네이처를 클론하는 프로젝트
   * 소비자가 웹사이트를 이용하면서 겪을 불편함을 고려하여, 앱에 최적화 된 사이트를 웹버전으로 개발. 
      * 기존 헬로네이처 웹사이트 https://www.hellonature.co.kr/fcm000.do?goTo=main 
   * 소비자들에게 보다 편리한 서비스를 제공하는 것이 목표.
* 2021.07 ~ 2021.10 동안 진행
* Frontend(김성용, 김민지, 박소민, 이수지)와 Backend(정영훈, 이예솔) 총 6명의 팀원으로 구성


## 2. 기술 스택
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black"/>
<img src="https://img.shields.io/badge/Oracle-F80000.svg?style=for-the-badge&logo=Oracle&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot"/>
<img src="https://img.shields.io/badge/JPA-6DB33F.svg?style=for-the-badge&logo=spring-boot&logoColor=black"/>
<img src="https://img.shields.io/badge/Spring Security-6DB33F.svg?style=for-the-badge&logo=spring-security&logoColor=white"/>
<img src="https://img.shields.io/badge/Thymeleaf-005F0F.svg?style=for-the-badge&logo=Thymeleaf&logoColor=white"/>
<img src="https://img.shields.io/badge/axios-black.svg?style=for-the-badge&logo=axios&logoColor=white"/>

## 3. 사이트 구성
![sitemap](https://user-images.githubusercontent.com/86811852/152217372-379b0711-199b-4f5c-8b78-e8b66378fc0b.png)

## 4. 데이터 관계도
![dataModel](https://user-images.githubusercontent.com/86811852/152217508-4a009921-4a62-4fd8-ab5e-1d25deb37146.png)

## 5. 주요 기능
`ADMIN`
* 전체 상품 관리
   * 상품 카테고리 관리
      * 상품을 카테고리(1차 카테고리), 세부 카테고리(2차 카테고리)로 등록.    
   * 상품 관리
      * 상품을 등록
      * 상품조회 : 판매상태 / 카테고리 / 상품명을 검색하여 등록된 상품을 검색하고 조회할 수 있도록 함. 
   * 주문 관리
      * 주문관리 조회 : 구매일자 / 주문상태 / 주문번호를 검색하고 고객이 주문한 건을 검색하고 조회할 수 있도록 함. 
   * 상품 문의
      * 상품문의 조회 : 문의일자 / 답변여부/ 검색어(작성자 / 내용)를 검색하여 고객의 상품 문의건을 검색하고 조회할 수 있도록 함.  
   * 상품 후기 
      * 상품후기 조회 : 상품명을 검색하여 고객이 남긴 후기를 조회할 수 있도록 함.  
* 매거진 관리
   * 카테고리 관리
      * 매거진 카테고리 등록 
   * 매거진 목록
      * 매거진 목록 조회 : 카테고리 / 매거진명 / 등록기간을 검색하여 조회할 수 있도록 함.
   * 매거진 등록
      * 매거진(탐험노트, 라이프스타일, 키친가이드) 등록 
   * 레시피 등록
      * 레시피 등록 
   
* 헬로네이처 추천관리
   * 팝업스토어
      * 팝업스토어 등록 / 수정 
   * 기획전/이벤트
   * 브랜드관
      * 브랜드 등록 / 수정
      * 브랜드 조회 : 브랜드명 / 입접상태 / 입점기간을 검색하여 브랜드 목록을 조회할 수 있도록 함.
     
* 고객센터
   * 공지사항 관리
      * 공지사항 등록
      * 공지사항 조회 : 제목 또는 분류기준 또는 기간을 검색 후 목록을 조회할 수 있도록 함.  
   * 결제 내역 관리
      * 결제내역 조회 : 결제일 또는 고객번호를 검색 후 목록을 조회할 수 있도록 함.
   * 1:1 문의 내역
      * 1:1 문의 조회 : 등록일 또는 답변상태 / 문의유형 또는 회원 이메일을 검색 후 목록을 조회할 수 있도록 함.   
   * FAQ 관리
      * FAQ 등록
      * FAQ 조회 : FAQ 제목을 검색 후 목록을 조회할 수 있도록 함.      
   * 회원 관리
      * 회원조회 : 가입일 또는 이메일 / 이름 / 연락처를 검색 후 회원목록을 조회할 수 있도록 함.
      * 회원정보 수정 
   * 쿠폰 관리
      * 쿠폰 등록
      * 쿠폰조회 : 쿠폰명 또는 기간을 검색 후 쿠폰목록을 조회할 수 있도록 함. 
   * 주소지 관리 
      * 회원 주소지 조회 : 회원 이메일을 검색하여 조회할 수 있도록 함.
      * 회원 주소지 수정 

`USER`
* 로그인
* 회원가입
* 장바구니
* 상품구매
* 마이페이지
  * 주문내역
  * 배송지 관리
  * 구매 후기
  * 더그린배송
  * 상품 문의
  * 1:1 문의 
  * 개인정보수정 
    * 이메일 찾기
    * 비밀번호 찾기
 

## 6. 주요 API 명세
`ADMIN`
|**기능**|설명|URL|
|:---:|:---:|---|
| <img src="https://img.shields.io/badge/POST-75E6B9.svg?style=for-the-badge&logo=POST&logoColor=white"/> |상품등록|/api/product/create|
| <img src="https://img.shields.io/badge/PUT-FFD239.svg?style=for-the-badge&logo=PUT&logoColor=white"/>|상품수정|/api/product/update|
| <img src="https://img.shields.io/badge/DELETE-ED1C24.svg?style=for-the-badge&logo=DELETE&logoColor=white"/> |상품삭제|/api/product/delete/{idx}|
| <img src="https://img.shields.io/badge/GET-7DDEFF.svg?style=for-the-badge&logo=GET&logoColor=white"/> |상품 리스트 조회|/api/product/list|

`USER`
|**기능**|설명|URL|
|:---:|:---:|---|
| <img src="https://img.shields.io/badge/GET-7DDEFF.svg?style=for-the-badge&logo=GET&logoColor=white"/> |상품조회|/api/product/read/{idx}|
| <img src="https://img.shields.io/badge/GET-7DDEFF.svg?style=for-the-badge&logo=GET&logoColor=white"/> |메인 페이지 상품 리스트|/api/product/user/list|

## 7. 시연
* `Main`<br><br>
![Main](https://user-images.githubusercontent.com/86811852/152951728-95ab5478-6bea-472d-a1eb-ca0d14bb3274.gif)
* `Signup`<br><br>
![Signup](https://user-images.githubusercontent.com/86811852/153253034-b9c37f98-d6a6-4ad1-8df3-c9effcbe16d9.gif)
* `Login`<br><br>
![login](https://user-images.githubusercontent.com/86811852/153142716-2cfb0f15-71aa-475e-b0b0-9c0ef1b5d65c.gif)
* `Admin`<br><br>

