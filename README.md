# 📽️영화 리뷰 사이트



## 🧑‍💻개발 환경

- **언어**

  > HTML5, CSS, JavaScript(ES6), Python

- **프레임워크**

  > Django, Bootstrap

- **DB**

  > SQLite

- **IDE**

  > Git Bash, VS Code

- **PIP**

  > django 3.2.13 | black | etc





## 🌈프로젝트 설명

### 목표

> django를 활용하여 modelform, static 요소를 응용한 영화 리뷰 사이트를 제작한다.

### 주요 기능

> `메인페이지` `영화 리뷰 목록` `리뷰 작성` `리뷰 수정` `리뷰 삭제`

#### 1. 메인 페이지 ( main )

> navbar와 aside를 제작하였다. 메인 페이지에는 이전에 프로젝트로 만든 영화 순위 페이지 양식을 그대로 재현했다.

![스크린샷(185)](https://velog.velcdn.com/images/hvvany/post/308fcf3d-9bcf-451b-9faa-8278d77da691/image.png)



---

#### 2. 영화 리뷰 목록 페이지 ( index )

> 영화 리뷰 목록을 띄워준다. 조회수 및 평점 정보도 함께 띄워준다. 영화 리뷰 제목을 클릭하면 상세 정보 페이지로 이동한다.
>
> 조회수는 정수형DB를 생성하여 views에서 request를 받을 때마다 카운트를 해준다.

![스크린샷(186)](https://velog.velcdn.com/images/hvvany/post/432bfd12-e095-4017-9a60-97949530610b/image.png)



---

#### 3. 리뷰 작성 페이지 ( create )

> 리뷰를 새롭게 작성한다. 유효성 검사를 통해 올바른 데이터를 입력하는지 확인한다.

![스크린샷(190)](https://velog.velcdn.com/images/hvvany/post/2f4b1748-9ba7-4303-bc53-fb9fc2fe975e/image.png)



---

#### 4. 리뷰 상세 페이지 ( detail )

> 상세 정보 페이지에서는 작성한 리뷰의 본문을 읽을 수 있다. 수정 및 삭제 기능도 있다.

![스크린샷(187)](https://velog.velcdn.com/images/hvvany/post/c0ee1cc0-c5ed-41c7-8dd4-baecaa0322f8/image.png)



---

#### 5. 리뷰 수정 페이지 ( update )

> 이미 작성한 리뷰글을 수정을 할 수 있다. get으로 원래 데이터를 가져와서 채워준다. 수정을 완료하면 post로 DB에 새로 저장한다.

![스크린샷(188)](https://velog.velcdn.com/images/hvvany/post/61e801b7-1422-469d-a466-0ce0b34e6ab4/image.png)



---

#### 6. 리뷰 삭제 기능

> 삭제 버튼을 누르면 모달 팝업을 띄워 한 번더 확인 후 삭제를 한다. 

![스크린샷(189)](https://velog.velcdn.com/images/hvvany/post/908b80fc-8f20-4ea7-ace8-1688bbd7812c/image.png)



