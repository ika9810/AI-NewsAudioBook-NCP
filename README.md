# 네이버 클라우드와 클로바를 활용한 인공지능 서비스 만들기

네이버 클라우드 플랫폼을 활용해 [멋쟁이사자처럼 강의](https://classlion.net/class/detail/22)의 커리큘럼을 보고 따라해보는 프로젝트

---

# 강의 커리큘럼 파악하기

![https://codelion-curriculum.s3.ap-northeast-2.amazonaws.com/images/%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3_%E1%84%8B%E1%85%A9%E1%84%91%E1%85%B3%E1%86%AB%E1%84%8A%E1%85%A5%E1%86%B7%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%86%AF_%E1%84%85%E1%85%B5%E1%84%82%E1%85%B2%E1%84%8B%E1%85%A5%E1%86%AF.png](https://codelion-curriculum.s3.ap-northeast-2.amazonaws.com/images/%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3_%E1%84%8B%E1%85%A9%E1%84%91%E1%85%B3%E1%86%AB%E1%84%8A%E1%85%A5%E1%86%B7%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%86%AF_%E1%84%85%E1%85%B5%E1%84%82%E1%85%B2%E1%84%8B%E1%85%A5%E1%86%AF.png)

네이버 클라우드 플랫폼과 멋쟁이 사자처럼이 공동 기획한 강의

---

### 강의 소개

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled.png)

---

### 멋사 강사님의 서비스 목록

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled%201.png)

---

### 강의 내용

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled.jpeg)

---

### 강의 전반적으로 보고 느낀점

1. 전반적인 NAVER CLOUD PLATFORM 설명
2. API 활용해보기(뉴스 수집)
3. DB 저장
4. 웹 크롤링
5. 클로바 세줄 요약 API
6. CLOVA Voice API
7. Flask를 통한 웹 배포

### 강의 목표

인공지능 성우로 뉴스를 오디오북으로 만들자 with CLOVA 인공지능 API

---

# 무작정 따라해보기

실제로 강의가 흥미롭게 다가왔지만 시즌제이기 때문에 이 강의를 발견했을 때는 이미 모집종료 인 상태였다.

따라서 강의 커리큘럼과 내용을 보고 유추해서 무작정 따라해보기로 한다.

실제로 강사님이 CLOVA API를 활용하여 만든 세줄 요약 봇 서비스이다.

[https://tmi-bot.com/](https://tmi-bot.com/)

---

## NAVER CLOUD PLATFORM

[NAVER CLOUD PLATFORM](https://www.ncloud.com/)

이번 강의의 핵심인 NAVER CLOUD PLATFORM 이다.

이전에 구글의 GCP, Microsoft의 Azure, Oracle Cloud, AWS는 사용해본 경험이 있는데 굉장히 친숙한 NAVER 임에도 불구하고 NAVER CLOUD PLATFORM에 접할 기회가 없었다.

[NAVER CLOUD PLATFORM](https://www.ncloud.com/product)

이번 계기로 다루면서 정말 다양한 기능들이 있는 것을 알 수 있었다.

이 중에서 사용할 API는 

- [네이버 뉴스 API](https://developers.naver.com/docs/search/news/)
- [CLOVA Summary API](https://www.ncloud.com/product/aiService/clovaSummary)
- [CLOVA Voice API](https://www.ncloud.com/product/aiService/clovaVoice)
- [KAKAO Speech API](https://speech-api.kakao.com/#speechCompose)

를 사용했다는 것을 알 수 있었다.

하지만 CLOVA Voice API의 가격이 월 9만원으로 토이 프로젝트를 진행하기에는 비싼 비용 임을 파악했다. 강의 특전을 보니 30만 크레딧을 지급하는 이유가 있었다. 따라서 경쟁사인 KAKAO의 Speech API를 활용해 보도록 하겠다.

[](https://console.ncloud.com/dashboard)

실질적으로 개발에 필요한 정보들이 담겨 있는 곳인 console 창 이었고 타 서비스와 비슷한 느낌으로 이루어져 있었다. 

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled%202.png)

다음과 같은 순서를 통해 Application 을 등록할 수 있다.

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled%203.png)

Application 이름, Service 선택, 서비스 환경 등록 순으로 진행하면 된다.

---

## 네이버 뉴스 API

[검색 API 뉴스 검색 개발가이드](https://developers.naver.com/docs/search/news/)

검색어를 입력하면 해당 뉴스를 전달하는 API이다.

신기하게 이 API는 NAVER CLOUD PLATFORM에 있는 API가 아니라 [네이버 개발자 사이트](http://developers.naver.com) 에 있는 API 이다.

동생의 군대 편지 매크로 프로그램에도 사용했던 경험이 있다.

네이버 뉴스 API 파이썬 이라고 검색해보면 많은 예제들을 찾아 볼 수 있다. ([예제1](https://koreanfoodie.me/118), [예제2](https://brightnightsky77.tistory.com/66))

예제들을 통해 뉴스 API를 사용하기위해 등록해야되는 과정들에 대한 정보를 얻을 수 있다.

그중에서 Python3로 짜진 가장 기본이 되는 코드이다.

```python
import urllib.request
client_id = "발급받은 값"
client_secret = "발급받은 값"
encText = urllib.parse.quote("코로나") # 검색할 키워드

url = "https://openapi.naver.com/v1/search/news?query=" + encText # json 결과가 필요할 때 사용
# url = "https://openapi.naver.com/v1/search/news.xml?query=" + encText # xml 결과가 필요할 때 사용

request = urllib.request.Request(url)
request.add_header("X-Naver-Client-Id", client_id)
request.add_header("X-Naver-Client-Secret", client_secret)
response = urllib.request.urlopen(request)
rescode = response.getcode()
if(rescode == 200):
    response_body = response.read()
    print(response_body.decode('utf-8'))
else:
    print("Error Code:" + rescode)
```

4번째 줄의 encText에서 quote안의 값에는 검색하고 싶은 검색어를 입력하면 url에 쿼리 형태로 붙게 된다.

---

## CLOVA Summary API

[NAVER CLOUD PLATFORM](https://www.ncloud.com/product/aiService/clovaSummary)

이번 강의 내용을 통해 처음 알게된 API이다. NAVER CLOUD PLATFORM에도 NEW 라는 표시가 있을 정도로 최근에 출시한 것 같다.

CLOVA Summary API는 말 그대로 긴문장을 요약하여 핵심 문장을 알려주는 문서 요약 API 인데

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled%204.png)

이러한 형태로 뉴스기사 원문을 CLOVA Summary API에 넣으면 문서 요약 결과를 반환해준다.

이 강의에서는 웹크롤링이나 네이버 뉴스API를 활용해 얻은 기사 내용들을 DB에 저장하고,

저장된 데이터들을 CLOVA Summary API에 넣어 문서요약결과를 다시 DB에 저장하는 형태로 보여진다.

실제 이 API를 활용해서 강사님이 [세줄 요약 봇](https://tmi-bot.com/)을 만들어 웹으로 공개했고 그것을 소개하는 [NAVER CLOUD PLATFORM 공식 블로그 자료](https://medium.com/naver-cloud-platform/%EC%9D%B4%EB%A0%87%EA%B2%8C-%EC%82%AC%EC%9A%A9%ED%95%98%EC%84%B8%EC%9A%94-clova-summary%EB%A1%9C-%EB%89%B4%EC%8A%A4-%EC%9A%94%EC%95%BD-%EC%84%9C%EB%B9%84%EC%8A%A4-%EB%A7%8C%EB%93%A4%EA%B8%B0-%EC%9D%B4%EA%B1%B4-%EB%A7%88%EC%B9%98-%EC%84%B8%EC%A4%84-%EC%9A%94%EC%95%BD-%EB%B4%87-dac29e97d1e4)도 찾아볼 수 있었다.

```python
#!/usr/bin/env python3
#-*- codig: utf-8 -*-
import sys
import requests
import json
client_id = " X-NCP-APIGW-API-KEY-ID"
client_secret = " X-NCP-APIGW-API-KEY"
headers = {
    "X-NCP-APIGW-API-KEY-ID": client_id,
    "X-NCP-APIGW-API-KEY": client_secret,
    "Content-Type": "application/json"
}
language = "ko" # Language of document (ko, ja )
model = "news" # Model used for summaries (general, news)
tone = "2" # Converts the tone of the summarized result. (0, 1, 2, 3)
summaryCount = "3" # This is the number of sentences for the summarized document.
url= "https://naveropenapi.apigw.ntruss.com/text-summary/v1/summarize" 
title= "'하루 2000억' 판 커지는 간편송금 시장"
content = "간편송금 이용금액이 하루 평균 2000억원을 넘어섰다. 한국은행이 17일 발표한 '2019년 상반기중 전자지급서비스 이용 현황'에 따르면 올해 상반기 간편송금서비스 이용금액(일평균)은 지난해 하반기 대비 60.7% 증가한 2005억원으로 집계됐다. 같은 기간 이용건수(일평균)는 34.8% 늘어난 218만건이었다. 간편 송금 시장에는 선불전자지급서비스를 제공하는 전자금융업자와 금융기관 등이 참여하고 있다. 이용금액은 전자금융업자가 하루평균 1879억원, 금융기관이 126억원이었다. 한은은 카카오페이, 토스 등 간편송금 서비스를 제공하는 업체 간 경쟁이 심화되면서 이용규모가 크게 확대됐다고 분석했다. 국회 정무위원회 소속 바른미래당 유의동 의원에 따르면 카카오페이, 토스 등 선불전자지급서비스 제공업체는 지난해 마케팅 비용으로 1000억원 이상을 지출했다. 마케팅 비용 지출규모는 카카오페이가 491억원, 비바리퍼블리카(토스)가 134억원 등 순으로 많았다."
data = {
    "document": {
    "title": title,
    "content" : content
    },
    "option": {
    "language": language,
    "model": model,
    "tone": tone,
    "summaryCount" : summaryCount
    }
}
print(json.dumps(data, indent=4, sort_keys=True))
response = requests.post(url, data=json.dumps(data), headers=headers)
rescode = response.status_code
if(rescode == 200):
    print (response.text)
else:
    print("Error : " + response.text)
```

이 코드는 공식 블로그에 있는 Python 예제 코드이며 API 사용을 위해 필요한 등록과정 역시 블로그에 자세히 나와 있다.

---

## KAKAO Speech API

[kakao API](https://speech-api.kakao.com/)

카카오 개발자 사이트에 있는 API들은 2019년 삼성전자 Bixby Crew 활동을 진행하면서 개최했던 Bixby Crew Hands-on&Seminar 에서 같이 [카카오톡 프로필 사진을 불러오는 빅스비 캡슐(앱)](https://github.com/BixbyCrew/KakaoProfile)을 만드는 강의를 진행할 때 접하게 되었다.

2019년도 말에 카카오 개발자 사이트에 존재하는 모든 카카오 API를 활용하여 "카카오 로봇"을 기획했던 적이 있었다. 그때 당시 접했던 API 이다.

이때 당시 과목으로 듣던 인터렉션 디자인 수업에서 음성 합성 API를 찾다가 발견했던 API 이기도 했다. 그때 당시 결국 배경음과 완성도 있지 않았던 목소리 탓에 지금의 [솔트룩스 음성합성 API](https://www.saltlux.ai/portal/api_detail?id=category27)를 활용해 작품을 완성 시킨 경험도 있다. 여담으로 그때 당시에는 솔트룩스가 아니고 아담이라는 이름을 사용하고 있었다. [솔트룩스](https://www.saltlux.ai/)에는 다양한 무료 API를 제공하니 참고해보는 것도 좋다.

이번 프로젝트에서 KAKAO Speech API의 음성합성을 사용하는 이유는 금전적인 문제가 크다. CLOVA Voice API의 성능이 훨씬 좋고 좀 더 다양한 성우들이 있지만 월 9만원이라는 가격을 지불해야하기 때문에 서비스의 지속성을 위해서 카카오의 API를 활용하기로 했다.

[카카오 개발자 공식 사이트](https://developers.kakao.com/docs/latest/ko/voice/rest-api#text-to-speech)에 API에 대한 설명이 자세히 나와있다. 내가 필요한 것은 Python을 활용한 예제 코드임으로 조금더 레퍼런스를 찾아보았다.

KAKAO Speech API에 대해 자세히 설명해놓은 [블로그](https://park-duck.tistory.com/entry/python-%EC%B9%B4%EC%B9%B4%EC%98%A4-%EC%9D%8C%EC%84%B1API-TTS-feat-Postman)를 찾을 수 있었다.

```python
import os, requests, json, wave
url = "https://kakaoi-newtone-openapi.kakao.com/v1/synthesize"
key = '[REST API KEY]'
headers = {
	"Content-Type": "application/xml",
    "Authorization": "KakaoAK " + key,
}

data = "<speak>하이</speak>"
res = requests.post(url, headers=headers, data=data)
f= open('temp.wav', 'wb')
f.write(res.content)
f.close()
```

이는 해당 블로그에서 찾을 수 있었던 Python을 활용한 예제 코드 이다. 음성인식 부분이나 API Key를 발급받는 방법에 대해서도 나와있다.

---

## CLOVA Voice API

[NAVER CLOUD PLATFORM](https://www.ncloud.com/product/aiService/clovaVoice)

역시 AI의 대가 CLOVA이다. 지금까지 보았던 어떤 음성합성보다 깔끔했고 다양한 언어,성별,억양 이 제공되므로 필요한 서비스의 특징마다 다르게 사용이 가능한 점이 엄청난 장점으로 다가왔다. 최대 단점은 월 9만원이라는 가격으로 스타트업이나 지원 사업에서 진행하는 프로젝트에는 적용이 가능해도 토이프로젝트나 개인 공부용으로는 부적합하다는 점이다. 그래도 원리와 호출에 대해서 공부해보았다.

```python
import os
import sys
import urllib.request
client_id = "YOUR_CLIENT_ID"
client_secret = "YOUR_CLIENT_SECRET"
encText = urllib.parse.quote("반갑습니다 네이버")
data = "speaker=nara&volume=0&speed=0&pitch=0&format=mp3&text=" + encText;
url = "https://naveropenapi.apigw.ntruss.com/tts-premium/v1/tts"
request = urllib.request.Request(url)
request.add_header("X-NCP-APIGW-API-KEY-ID",client_id)
request.add_header("X-NCP-APIGW-API-KEY",client_secret)
response = urllib.request.urlopen(request, data=data.encode('utf-8'))
rescode = response.getcode()
if(rescode==200):
    print("TTS mp3 저장")
    response_body = response.read()
    with open('sample.mp3', 'wb') as f:
        f.write(response_body)
else:
    print("Error Code:" + rescode)
```

이 코드는 [NAVER CLOUD PLATFORM 공식 블로그](https://m.blog.naver.com/PostView.nhn?isHttpsRedirect=true&blogId=n_cloudplatform&logNo=222097441109)에 있던 Python 기반 기본 코드 이다. NAVER CLOUD PLATFORM에서 블로그나 공식 문서를 통해 사용 가이드를 잘 제시해주는 점이 장점이다.

---

## 배포

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled%205.png)

위 사진은 강의의 세부 커리큘럼이다. 활용한 API들을 Flask를 활용해 웹 어플리케이션을 제작해서 클라우드로 배포하는 과정을 볼 수 있다. 무작정 따라하기를 시작한 만큼 웹에 배포하는 과정까지 프로젝트를 진행해보겠다. 챗봇에 대한 언급이 있는데 이번 프로젝트에서는 우선 다루지 않는 방향으로 진행할 것이다. 

*챗봇 관련 공식문서는 [여기](https://www.ncloud.com/product/aiService/chatbot)*

---

## FLASK

Flask는 오픈 소스 웹 “마이크로 프레임워크”입니다. 작성자가 “마이크로 프레임워크”라는 용어를 사용하는 경우 프레임워크가 웹 프레임워크의 필수 작업을 수행하지만 애플리케이션이 올바르게 작동하기 위해 따라야 하는 다른 특정 요구 사항이나 고급 기능은 포함하지 않는다는 의미입니다. (라고 [Microsoft](https://docs.microsoft.com/ko-kr/learn/modules/python-flask-build-ai-web-app/2-flask-fundamentals)에서 그러네요)

```python
from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"

if __name__ == "__main__":
    app.run()
```

가장 기본이 되는 Flask의 예제 코드이다.

이제 Flask를 활용해 각각의 기능에 해당하는 API를 제작할 것 이다.

이전에 Flask를 활용해서 API를 만든 경험은 다수 있다. 내가 만든 예제 코드는

```python
from flask import Flask, request, Response
import json

app = Flask(__name__)

@app.route('/', methods = ['POST'])

def API():
    params = request.get_json()
    print(params,type(params))
    return params

if __name__ == "__main__":
    app.run(debug=True, host='0.0.0.0', port=80)
```

이 코드를 기반으로 이제 개발을 진행할 것이다.

---

## 기획

지금까지 사용할 기술 스택에 대해서 예제를 통해 알아보았다. 지금부터는 하나의 프로젝트를 진행함에 있어 생각했던 인사이트들이나 예상 결과물에 대해 얘기해보도록 하자.

우선 프로젝트의 목표는 

인공지능 성우로 뉴스를 오디오북으로 만들자 with CLOVA 인공지능 API

이기 때문에 크게 2가지 컨텐츠를 가지고 있다.

- 뉴스
- 오디오북

여기서 내가 떠올렸던 것은 **뉴스** 라고 하면 **신문 1면** 이 떠올랐고 오디오북 이라고 하면 책을 떠올랐다.

이거와 관련해서 레퍼런스들을 찾아 보았고 내 생각과 유사한 템플릿 두 개를 찾을 수 있었다.

- [뉴스 1면 관련 예제](https://codepen.io/silkine/pen/jldif)
- [오디오북 관련 예제](https://tympanus.net/Development/FlipboardPageLayout/?page=0)

우선 1차적으로 해당 예제들을 활용해서 AI 뉴스 오디오북을 제작하려고 한다.

우선 메인 컨텐츠는 "뉴스" 이기 때문에 평소 뉴스를 보는 기준에 대해서 생각을 해보았다.

대부분의 경우 네이버의 실시간 검색어를 통해 많은 사람들이 뉴스를 접하는 경향이 있다. 따라서 뉴스 선정 기준을 "실시간 검색어"로 잡으려고 했지만 2021년 2월 25일 네이버에서 더이상 실시간 검색어 기능을 제공하지 않는다. 따라서 이에 대한 대안으로 많은 사람들은 Google 트렌드를 이용하고 있었다.

[Google 트렌드](https://trends.google.co.kr/trends/trendingsearches/daily?geo=KR)

나는 실제로 이번 프로젝트를 진행하면서 알게되었지만 꽤 괜찮게 구성된 것 같았다. 한가지 아쉬운 점은 일별 검색어 트렌드는 지원하는데 대한민국에서는 실시간 검색어 기능을 지원하지 않았다. 일별 검색어 트렌드로도 충분하다고 판단하여 Google 트렌드를 활용하여 현재 화두가 되고있는 키워드를 뽑아낼 것이다.

### Career Goals

What direction do you see your career going in the next few years? If you’re not sure of where you’d like to take your career, what are some career paths or target roles that interest you or that you want to explore?

- 

What types of work do you want to learn more about or seem intriguing?

- 

---

# What to focus on: Strengths and areas to improve