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

