# IGRUS-INHA.github.io
## IGRUS Blog
인하대학교 SW 프로그래밍 동아리 아이그루스의 기술 블로그입니다.

## 글 작성 방법
### 1. 저자 등록
```_data``` 폴더의 ```authors.yml``` 파일에 작성하시는 분의 정보를 다음과 같이 추가해주시면 됩니다.
```yml
Yun-YeoJun: # github 아이디
  username: Yun-YeoJun # github 아이디
  name: 윤여준 # 본명
  url_full: https://github.com/Yun-YeoJun # 본인의 블로그나 github 주소
  url: github.com/Yun-YeoJun # url_full 에서 https:// 를 제외한 나머지 주소
  bio: INHA UNIV. ICE 22 & IGRUS President # 본인 소개
  picture: False # 프로필 사진 (assets/images 폴더에 사진을 넣고 assets/images/파일이름.확장자명 이런 식으로 작성 / 안 쓸 거면 False)
  cover: False # 프로필 커버 사진 (assets/images 폴더에 사진을 넣고 assets/images/파일이름.확장자명 이런 식으로 작성 / 안 쓸 거면 False)
```
### 2. 글 작성
```_post``` 폴더에 ```yyyy-mm-dd-title.md``` 파일 생성 (ex. 2022-06-27-welcome.md)

파일 이름은 영어로 작성해야하며 공백(' ') 대신 하이픈('-') 사용

파일 상단에 [Front Matter](https://jekyllrb.com/docs/front-matter/) 작성


## Copyright & License

Same licence as the one provided by Ghost's team. See Casper's theme [license](GHOST.txt).

Copyright (C) 2015-2021 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
