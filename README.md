<h1 align="center">
  <br>
  <a href="https://www.coupang.com/np/categories/176860?page=1"><img src="https://user-images.githubusercontent.com/43984584/53936606-b9320280-40ed-11e9-9818-f498cfc7ddb2.png" alt="Markdownify" width=""></a>
  <br>
  
  <br>
</h1>

<h1 align="center"> 쿠팡 스킨케어 상품명, 가격 크롤링
</p>

# Overview

- 대상: 파이썬 기본 지식, HTML 초급 정도의 지식을 가지고 있는 분에게 권장합니다.
- 목표
  - 쿠팡 스킨케어 카테고리에 있는 화장품 상품명, 가격을 가져옵니다.
  - 1페이지부터 17페이지 까지

## 쿠팡 스킨케어 - 쿠팡 랭킹순

<img src="https://user-images.githubusercontent.com/43984584/53936606-b9320280-40ed-11e9-9818-f498cfc7ddb2.png">

- 화장품명, 가격을 가져옵니다.
- 홈페이지 변경에 따라 결과가 바뀔 수 있습니다.

## Step

### 1. 파이썬을 설치합니다.

### 2. `pip3 install requests` , `pip3 install bs4` 커맨드를 통해 모듈들을 설치합니다.

### 3.헤더값을 넣기 위해 아래 사이트에서 본인의 `User-Agent` 값을 가져와서 넣어줍니다.

- http://www.useragentstring.com/

<img src="https://user-images.githubusercontent.com/43984584/53936892-c4d1f900-40ee-11e9-9e71-4826738c6d50.png">

```bash
headers = {
    "User-Agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/537.36 ****(KHTML, like Gecko) Chrome/72.0.3626.109 Safari/537.36****"
}
```

### 4. 프로그램을 실행시킵니다.

## 결과물

- 총 1020개 상품을 가져오는데 37초가 걸렸습니다.

<img src="https://user-images.githubusercontent.com/43984584/53936758-4ffebf00-40ee-11e9-922a-d06cc15e0f9c.png">

## 비고

- 초보자들의 파이썬 크롤링 학습용으로 개발된 프로그램이며 영리 목적이 아님을 밝힙니다.
- 쉽게 따라하고 이해하기 위해 퍼포먼스는 고려 하지 않고 작성되었습니다.

## 기타 문의

- 블로그 : https://stophyun.tistory.com/
- 이메일: stophyuni@gmail.com
- 궁금한 사항은 이메일로 부담없이 보내주세요.
