# Register

## Info

- [리액트를 다루는 기술](https://search.daum.net/search?w=bookpage&bookId=5056576&tab=introduction&DA=LB2&q=%EB%A6%AC%EC%95%A1%ED%8A%B8%EB%A5%BC%20%EB%8B%A4%EB%A3%A8%EB%8A%94%20%EA%B8%B0%EC%88%A0) 도서를 공부하면서 진행한 실습 예제입니다.

## Install

```bash
yarn
```

## Run (development mode)

```bash
yarn start
```

## Build

```bash
yarn build
```

## 결론(개인 생각)

- immer / immer + useState 함수형 업데이트 적용 전/후의 성능차이는 크게 발생하지는 않았습니다.
- 하지만 전반적으로 코드가 간결해진 느낌은 받았습니다.
- produce의 장점으로는 push, splice와 같이 직접적으로 수정이 가능한 함수를 사용할 수 있다는 점입니다.
