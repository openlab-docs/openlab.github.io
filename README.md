# mobigen.github.com
mobigen.github.com

# 개발 환경 세팅

## Requirements ( Linux / OSX )
```
$ sudo gem install bundler jekyll
$ sudo pip install sphinx sphinx-autobuild
$ sudo pip install sphinxtogithub

$ brew install sphinx-doc            # for osx
$ brew link sphinx-doc --force       # for osx

$ sudo pip install recommonmark
```

## Requirements ( Windows )
- ruby 설치
    - http://rubyinstaller.org/downloads/
    - https://github.com/oneclick/rubyinstaller2/releases/download/rubyinstaller-2.4.4-2/rubyinstaller-devkit-2.4.4-2-x64.exe

- git 설치
    - https://desktop.github.com

- 필요 라이브러리를 설치한다.
```
$ gem install bundler jekyll
```
    

## Development
```
# code를 다운로드 받습니다.
$ git clone https://github.com/mobigen/mobigen.github.io.git

# 홈페이지 작업을 위해 다음과 같이 환경을 설정합니다.
$ cd mobigen.github.io
$ bundle install

# Jekyll Server를 실행합니다.
$ bundle exec jekyll serve

# 브라우저로 작업 내용을 확인합니다.
$ open http://localhost:4000
```

# 기타 사항

## Contact 요청 메시지 저장 URL
- https://docs.google.com/spreadsheets/d/1hjoWYjysMafr0EmSVbezrVpCArnyR3CBigqIUFCkiJA/edit#gid=0

## tutorial
- https://jekyllrb.com/tutorials/home/
- https://www.taniarascia.com/make-a-static-website-with-jekyll/   (READ-ME FIRST)
- https://www.hongkiat.com/blog/blog-with-jekyll/
- https://scotch.io/tutorials/getting-started-with-jekyll-plus-a-free-bootstrap-3-starter-theme

## site sample
- https://github.com/arpitmaheshwari/sass-template
- https://github.com/opentracing/opentracing.io

## theme 참고
- https://github.com/MvvmCross/MvvmCross/tree/master/docs

## sass 명령
- jekyll에서 내부적으로 다음과 같은 형태의 명령을 수행할것으로 유추합니다.
```
$ sass -I _sass --watch css/styles.scss:_site/css/main.css
```

## docx 문서 변환

```
$ pandoc -f docx a.docx -t rst -o a.rst
$ unzip a.docx
$ cd word/media/
$ mogrify -format png *
```

## markdown
- https://daringfireball.net/projects/markdown/syntax
- https://www.markdownguide.org/basic-syntax
- http://www.hakawati.co.kr/405


## reStructuredText
- http://www.incodom.kr/reStructuredText
- https://docs-korean-sphinx.readthedocs.io/ko/docs-korean/rest_ko.html
- https://veranostech.github.io/docs-korean-docutils/docutils/docs/ref/rst/restructuredtext_ko.html

## sendmail
- https://github.com/dwyl/learn-to-send-email-via-google-script-html-no-server
