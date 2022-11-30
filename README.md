# 유레카 프로젝트 Git Blog만들기

국민대학교 소프트웨어학부 20223066 김혜원

## Contents

- [Jekyll](#jekyll)
- [Github Pages](#github-pages)
- [Local Repository](#local-repository)
  - [jekyll serve](#jekyll-serve)
- [Remote Repository](#remote-repository)
- [Themes](#themes)
- [Posts](#posts)
  - [Welcome to Git Blog!](#welcome-to-git-blog!)
  - [How To Solve Errors](#how-to-solve-errors)


## Jekyll

Ruby 기반 정적 웹사이트 생성기  
- **Markdown**을 활용

## Github Pages

Github Repo를 Webpage로 만들어준다.  
- **1. Jekyll과 Ruby, Github Pages로 블로그를 만들 준비를 한다.**


## Local Repository  

**2. 로컬 저장소에 Jekyll과 Ruby를 설치**
- 완료 후 생성된 `_config.yml`의 내용을 수정해서 웹사이트의 내용을 변경했습니다

### jekyll serve  

**3. `jekyll serve`로 기본테마로 된 Jekyll 사이트를 생성**
- `_config.yml`을 변경한 내용이 반영된 웹사이트가 생성됨을 확인했습니다

## Remote Repository

**4. `git add` `git commit` `git push`로 로컬 저장소의 변경사항을 Github Repo에도 반영**
- *setting* - *pages*에서 `localhost:4000`으로 접속했던 웹사이트와 동일한 웹사이트가 만들어진 것을 확인했습니다
- OS에 따라 계행문자를 다르게 처리하는 문제 때문에 사소한 오류가 있었으나 해결했습니다


## Themes

**5. Lanyon테마로 웹사이트 테마 변경**
- .zip파일로 테마를 적용했을 때 gem 중에 하나인 *jekyll-paginate*가 없어서 `jekyll serve`가 실행되지 않는 오류가 발생했습니다.   


- 그래서 이 방법 대신 `git fork`로 Lanyon테마의 원격 저장소를 저의 원격 저장소로 fork했습니다.
  * `git clone`을 통해 로컬 저장소에 받아온 후 `_config.yml`의 내용을 변경하고 `_posts`폴더에 dummy 정보를 삭제하고 새로 .md파일을 만들었습니다.
  * `jekyll serve`로 테마와 웹사이트 변경 내용이 잘 적용된 것을 확인한 뒤, 원격 저장소에 반영했습니다.
  * 원격 저장소 *setting* - *pages*에서 테마와 변경 사항이 똑같이 잘 적용된 것을 확인하여 Git Blog를 완성했습니다.

## Posts

제 웹사이트의 기능은 Git Blog 만드는 방법을 정리하고 공유하기 위함이기 때문에 그와 관련된 3개의 포스트를 업로드했습니다

### Welcome to Git Blog!

Git Blog 소개하는 내용입니다

### How To Solve Errors

만드는 과정에서 발생한 오류와 발생한 이유, 해결 방법을 정리하는 내용입니다.
특강에 다뤄졌던 내용 Topic 중 배운 내용에 관해 작성한 Post입니다.

### Markdown

마크다운 문법에 대해 정리한 내용입니다.
특강에 다뤄졌던 내용 Topic 중 배운 내용에 관해 작성한 Post입니다.