# 입문자를 위한 Git과 HTML&CSS
## 1일차
### 환경설정
- Chrome 설치(확장프로그램)
- Git 설치
- VS Code 설치(확장프로그램)
### CLI 명령어
- 디렉토리 생성(mkdir)
- 디렉토리 이동(cd)
- 빈 파일 생성(touch)
- 내용이 있는 파일 생성(echo)
- 이름변경 및 이동(mv)
- 복사(cp)
- 디렉토리 삭제(rmdir)
- 비어있지 않은 디렉토리 및 파일 삭제(rm)
- 파일 및 디렉토리 목록 출력(ls)
- 화면 지우기(clear)
### Git 명령어
- 저장소 초기화(git init)
- 사용자 이름 등록(git config --global user.name "사용자이름")
- 사용자 이메일 등록(git config --global user.email "사용자이메일주소")
- 현재 상태 확인(git status)
- index 영역으로 이동(git add)
- 커밋 기록 생성(git commit -m "커밋메세지")
- 기본 에디터 수정(git config --global core.editor "code --wait")
- 커밋 기록 수정(git commit --amend)
- 커밋 로그 조회(git log)
- 되돌리기(git reset --hard 고유ID)
- 원격저장소(git remote add origin 원격저장소주소)
- 발행하기(git push origin master)
- 일반 저장소에서 호스팅 저장소로 변경하기
[Youtube 영상](https://youtu.be/SNnfbf-LJz4)
## 2일차
### HTML 기본구조
- DTD 선언(DOCTYPE html)
- HTML 요소(html lang="ko-KR")
- head 요소(문서 제목 및 메타데이터)
- 인코딩 선언(meta charset="utf-8")
- body 요소(본문 영역)

```html
<!DOCTYPE html>
<html lang="ko-KR">
<head>
    <meta charset="UTF-8">
    <title></title>
</head>
<body>
    
</body>
</html>
```
### HTML 요소
- 제목 요소(h1 ~ h6)
- 문단(단락)(p)
- 강조, 분위기 전환(b, i, strong, em)
- 줄바꿈, 수평선(br, hr)
- 목록 요소(비순서형 ul, 순서형 ol, 자식 li, 정의형목록(dl,dd)
- 하이퍼링크(a, href 속성 : 연결, target 속성 : 새창, 빈창, 특정창, title 속성 : 툴팁)
- 이미지(img, src 속성 : 이미지소스, alt 속성 : 대체텍스트)
### CSS의 개념 및 정의
- CSS는 Cascading Style Sheet의 약자로 스타일을 정의하기 위한 언어이다.
- 최신 표준은 CSS3라고 불리는 새로 추가된 모듈이다.
- CSS의 중요한 개념은 겹침, 상속, 우선순위이다.
- CSS를 이용해 레이아웃 설계를 하기 위해서는 float, position, flex 등의 속성이 필요하다.
- CSS의 기본 문법은 선택자와 선언부로 구성되어있다.

```CSS
  P {
    color:green;
    background-color:yellow;
  }
```

## 3일차
### CSS 선택자 
- 전체 선택자 (*)
- 요소 선택자 (tag 명)
- class 선택자 (.class 명)
- id 선택자 (#id 명)
### 박스 선택자
- width, height 속성(박스의 가로 및 세로 크기)
- 테두리(border)
- 여백(padding, margin[auto 키워드를 사용할 수 있음])
- box-sizing 속성(content-box:전체 면적 계산, border-box:보더와 패딩을 포함시켜 계산)
### OVERFLOW 속성
- 박스의 크기와 콘텐츠의 크기를 비교해서 보여줄 영역 결정(hidden, auto, scroll)
### 배치관련 속성
- float 속성
> float 속성은 left와 right 값을 사용 할 수 있으며, 일반적인 흐름을 벗어나서 화면위에 떠있는 상태로 만들 수 있다. left나 right 값은 부모 영역을 기준으로 배치되며 각각 라인박스 안에서 배치된다는 특징이 있다.또한 float된 요소의 부모는 float 된 요소의 높이를 잃어버리기 때문에 부모요소에 overflow: hidden 을 지정하여 문제를 해결 할 수 있다.
- display: flex => [CSS Triks 참고자료](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
> 유연한 박스 모델로 배치하고자 하는 요소의 부모 요소에 display 속성의 값으로 flex를 지정할 수 있다. 이때 flex가 지정된 요소의 자식 요소는 flex item의 역할을 담당하게 되고 flex-direction 속성에 지정된 방향으로 배치된다.
### 배경관련 속성
- background color(배경색)
- background image(배경 이미지)
- background-repeat(배경 이미지 반복 여부)
- background-position(배경 이미지 위치 조절)
- background-attachment(배경 이미지 고정 여부)
- background-size(배경 이미지의 크기 조정)
- background 속성(배경관련 단축 속성)

## 4일차
### position 속성
- static(기본값)
- relative(상대배치)
- absolute(절대배치)
- fixed(고정배치 - 뷰포트 기준)
- sticky(relative + fixed 효과 - IE11 지원하지 않음)
### animation 관련 속성
- animation
    + animation-name(필수)
    + animation-duration(필수)
    + animation-fill-mode
    + animation-delay
- transform
    + translate(이동)
    + scale(크기)
    + rotate(회전)
- transition
    + transition-property
    + transition-duration
    + transition-delay

