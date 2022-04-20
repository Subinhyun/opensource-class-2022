# opensource-class-2022

Hugo Site

```
hugo new site 프로젝트 이름
themes 폴더에 선택한 테마를 다운 - git clone 테마 깃허브 주소
상위 폴더로 돌아와 config.toml 파일에 theme = '테마이름' 추가
hugo server 명령어로 사이트 확인 - localhost:1313
(개발하면서 바로바로 볼 수 있다.)
개발이 완료되면
hugo -t 테마이름 을 입력한다 !!! (입력해야 public 폴더에 빌드 결과가 나온다.)
public 폴더에 있는 내용을 github repository에 올린다.
(public 폴더 외에 상위 폴더에 있는 파일도 넣는다면 build에 오류가 생겨 404페이지가 나온다.)
```
