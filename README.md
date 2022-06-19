## **약쿠르트(Yakurt)**

33기 2차 프로젝트
필리 클론 - 영양소 정기구독 서비스

---

## **프로젝트 참여인원**

- **Frontend**
  - 김완영
  - 김혜수
  - 정재성
  - 천은별
- **Backend**
  - 최혜인
  - 박상연

## **프로젝트 기간**

- 2022.06.07 ~ 2022.06.17

## **기술스택**

- **tools**

<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"><img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"><img src="https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white"><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">

- **frontend**

<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"><img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"><img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"><img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">

- **backend**
 
 <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"><img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">

## **구현 목표**

- 각 유저마다 필요한 영양소 정기구독 서비스 제공
- <a href="https://github.com/wecode-bootcamp-korea/33-2nd-yakurt-backend">백엔드 레포지토리</a>

### 필수 구현 사항

- 메인, 네브, 푸터
- 로그인, 회원가입/소셜 로그인
- 마이페이지
- 설문 + 추천성분
- 제품리스트 보기, 상세페이지
- 리뷰, 리뷰작성(이미지 업로드), 삭제, 수정
- 장바구니
- 주문 / 구독

## **구현 파트**

- 김완영 (메인, 네브, 설문페이지, 설문결과 페이지, 주문페이지)
  ```
  1. 프론트엔드 ProjectManager
  2. 메인,네브 레이아웃
  3. 설문조사 구현
  4. 설문조사 결과에 따라 추천 영양소 페이지 구현
  ```
- 김혜수 (장바구니)
  ```
  1. 장바구니 레이아웃
  2. 장바구니 수량 수정 구현
  3. 수량에 따른 총 금액 구현
  ```
- 정재성 (로그인, 회원가입, 마이페이지)

  
  1. 로그인 및 마이페이지 레이아웃 구현
  
  
  2. REST API방식을 활용한 소셜 로그인 인가 구현
  
   - REST API를 사용한 로그인 구현   
   
   ![약쿠르트 로그인 gif](https://user-images.githubusercontent.com/102431470/174468510-37748d84-bc95-486f-87df-184bf3c7c1ca.gif)
   
      Step 1.인가 코드 받기
        서버가 카카오 인증 서버로 인가 코드 받기를 요청
        
      Step 2.토큰 받기
        Redirect URI를 통해 전달받은 인가 코드로 토큰 받기를 요청
        
      Step 3.사용자 로그인 처리
      서비스 회원 확인 결과에 따라 서비스 로그인 또는 회원 가입 과정을 진행
    
  3. 마이페이지 레이아웃 및 각 상품 결제내역서 작성


  
    - 중첩 라우팅을 활용한 마이페이지 내에서의 페이지네이션
       ![마이페이지 1](https://user-images.githubusercontent.com/102431470/174469607-5cece440-b9f3-4a4e-8d13-3af2433d7023.gif)

    
    - 각 상품의 결제 주문서에서 넘어온 데이터를 넘겨받아 결제내역서 구현
    
    
    - 각 상품 ID 값에 맞는 리뷰페이지로의 페이지 이동구현
  
 
      ![마이페이지2](https://user-images.githubusercontent.com/102431470/174469610-f18740fe-fc62-441f-9fd7-a5d1c22d8186.gif)

  
 
- 천은별 (리뷰,리뷰상세, 상품리스트, 상품 상세)
  ```
  1. 리스트페이지 및 리뷰 레이아웃
  2. 폼 데이터 이용 리뷰 작성 구현
  3. 각 상품 아이디에 따른 상세 페이지 구현
  4. 이전 리뷰, 다음 리뷰 버튼 구현
  ```

## **시연**

<a href="https://youtube.com/watch?v=517zoXHETO4&feature=share">시연 영상 보러가기!</a>

## **Build Installation**

```
# install dependencies
$ npm install
# serve with hot reload at localhost:3000
$ npm start
```

## **Reference**

- 이 프로젝트는 <a href="https://pilly.kr/">필리</a> 사이트를 참조하여 학습목적으로 만들어진 사이트입니다.
