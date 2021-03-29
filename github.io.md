# 🦕 make github blog
github blog



## 만들기까지

(username).github.io 로 repository 이름을 정한다.

ruby 설치 위해서 hombebrew 설치.

- ruby 설치

```swift
$ brew install rbenv ruby-build
$ rbenv install (version)
```

- jekyll 설치

`$ sudo gem install jekyll bundler` 

- make local repository

`$ git clone https://github.com/hyun99999/hyun99999.github.io.git`

- 클론받은 폴더 내에서 jekyll 생성

```swift
$ jekyll new ./
$ bundle install
```
- 생성된 사이트 실행
`$ bundle exec jekyll serve`

- 개발용 서버 확인
http://localhost:4000 에 접속

## 테마적용
https://github.com/topics/jekyll-theme 에서 테마 다운로드.

내가 고른 테마

https://github.com/mmistakes/minimal-mistakes

- jekyll 설치한 폴더로 복사

- 플러그인 설치

`$ bundle install`

- 서버 실행
`$ bundle exec jekyll serve`

- 적용된 테마 local 서버를 통해서 확인
<img src ="https://user-images.githubusercontent.com/69136340/112668639-17cba400-8ea2-11eb-98e7-a325eaad4930.png" width="600">

- 배포하기(github 에 올린다.)
```swift
$ git add .
$ git commit -m "..."
$ git push origin master
```

- build fail
<p>
<img src="https://user-images.githubusercontent.com/69136340/112755848-8123f200-901d-11eb-9744-d2f229c24605.png" width="500">
<img src="https://user-images.githubusercontent.com/69136340/112755873-9731b280-901d-11eb-8fdc-ade4a84798bb.png" width="500">
</p>

https://github.com/mmistakes/minimal-mistakes#remote-theme-method

로 해결.

<img src = "https://user-images.githubusercontent.com/69136340/112839786-89416780-90d9-11eb-8733-829b575560fc.png" width ="500">

### 출처
출처ㅣhttps://jetalog.net/87?category=808871

출처ㅣ[choi2]https://iamcho2.github.io/2020/09/16/make-my-own-github-blog
