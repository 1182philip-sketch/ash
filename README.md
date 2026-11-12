# ASH ISLAND 8th Debut Anniversary

팬이 만든 비공식 데뷔 8주년 축하 페이지입니다.

## 편지 추가하는 법
`letters.json`에 아래 형식으로 한 통씩 추가하면 페이지에 자동으로 나타납니다.

```json
{ "letters": [
  { "nickname": "닉네임", "instagram": "인스타그램 아이디", "message": "편지 내용" }
] }
```

hero.jpg는 첫 화면 사진이에요. 세 파일을 같은 폴더에 두어야 합니다.

## 배포
저장소 Settings → Pages → Branch: main / root 로 설정하면 `계정이름.github.io/저장소이름` 주소로 열립니다.

## 앨범 커버 넣는 법
`covers` 폴더를 만들고 아래 이름으로 정사각형 이미지를 넣으면 레코드 앞에 커버가 나타나요. 파일이 없으면 레코드만 보여요.

- covers/ash.jpg · covers/island.jpg · covers/rose.jpg · covers/voice-memo.jpg
- covers/burn-part1.jpg · covers/burn-part2.jpg

## 다른 언어 편지 번역
한국어가 아닌 편지에 `translation_ko` 항목을 넣으면 편지 창에 "한국어로 보기" 버튼이 생겨요. 없으면 Google 번역 링크만 보여요.

```json
{ "nickname": "オウブ", "instagram": "imobu328", "message": "日本語の原文", "translation_ko": "한국어 번역문" }
```
