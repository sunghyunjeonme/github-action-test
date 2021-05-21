# TIL

> Today I Learned

A collection of concise write-ups on small things I learn day to day across a
variety of languages and technologies. These are things that don't really
warrant a full blog post.


_21 TILs and counting..._

---

### Categories

* [React](#React)
* [Algorithm](#algorithm)
* [Book](#book)
* [Css](#css)
* [Git](#git)
* [Hooks](#hooks)
* [Html](#html)
* [Http](#http)
* [Images](#images)
* [Test](#test)
* [Test2](#test2)
* [Testing](#testing)

---

### React

- [test](React/test.md)
- [test2323](React/test2.md)

### Algorithm


### Book

- [프로그래머의 길, 멘토에게 묻다.](book/apprenticeship-patterns.md)

### Css

- [:root 가상 클래스로 CSS 전역 변수 설정하기](css/root-selector.md)
- [CSS block, inline, inline-block 요소의 차이](css/210404_block-inline-inline-block.md)
- [CSS 기본 선택자 정리](css/210408_css-basics.md)
- [CSS 박스 모델(Box Model)](css/210409_css-box-model.md)
- [CSS 속성 순서 컨벤션](css/210504-css-property-order.md)
- [CSS 애니메이션(Animation)](css/210429_css-animations.md)
- [CSS 초기화 전략(Reset.css vs Normalize.css)](css/210405_reset-css.md)
- [CSS 플렉스 박스(Flex Box)](css/2104030_css-flex.md)
- [미디어 쿼리를 이용한 반응형 작업](css/210514-css-media-query-basics.md)

### Git

- [나만의 커밋 메시지 가이드](git/my-commit-guide.md)

### Hooks


### Html

- [DOCTYPE](html/210404_doctype.md)
- [Emmet 플러그인 사용법](html/210406_emmet.md)
- [script 태그와 script async, script defer의 차이](html/210520_script-async-defer.md)
- [근원이 되는 시맨틱 마크업](html/semantic.md)

### Http

- [HTTP 기본 내용 정리](http/210410_http-basics.md)

### Images


### Test

- [test4](test/test.md)

### Test2

- [test](test2/test.md)

### Testing

- [test](testing/test.md)

## Usage

After creating a new entry, run `./createReadme.py > README.md` to regenerate
the readme with the new data.

If you are using git, you can install this script as a pre-commit git hook so
that it is autogenerated on each commit.  Use the following command:
    cd .git/hooks/ && ln -s ../../createReadme.py pre-commit && cd -


## About

I shamelessly stole this idea from
[jbranchaud/til](https://github.com/jbranchaud/til) who claims to have stolen
it from others.

## Other TIL Collections

* [jbranchaud/til](https://github.com/jbranchaud/til) who claims to have stolen
* [Today I Learned by Hashrocket](https://til.hashrocket.com)
* [jwworth/til](https://github.com/jwworth/til)
* [thoughtbot/til](https://github.com/thoughtbot/til)

## License

&copy; 2017-2018 Jim Anderson

This repository is licensed under the MIT license. See `LICENSE` for
details.