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
res = requests.post(url, headers=headers, data=data.encdoe('utf-8'))
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

*참고자료 : [점프 투 플라스크 위키독스 문서](https://wikidocs.net/book/4542), [Flask Requests 설명 블로그](https://dgkim5360.tistory.com/entry/python-requests)*

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

대부분의 경우 네이버의 실시간 검색어를 통해 많은 사람들이 뉴스를 접하는 경향이 있다. 따라서 뉴스 선정 기준을 "실시간 검색어"로 잡으려고 했지만 2021년 2월 25일 네이버에서 더이상 실시간 검색어 기능을 제공하지 않는다. 따라서 이에 대한 [대안](https://coconuts.tistory.com/465)으로 많은 사람들은 Google 트렌드를 이용하고 있었다.

나는 실제로 이번 프로젝트를 진행하면서 알게되었지만 꽤 괜찮게 구성된 것 같았다. 한가지 아쉬운 점은 일별 검색어 트렌드는 지원하는데 대한민국에서는 실시간 검색어 기능을 지원하지 않았다. 일별 검색어 트렌드로도 충분하다고 판단하여 Google 트렌드를 활용하여 현재 화두가 되고있는 키워드를 뽑아낼 것이다.

[Google 트렌드](https://trends.google.co.kr/trends/trendingsearches/daily?geo=KR)

뽑아낸 키워드들로 이제 위에서 언급한 [네이버 뉴스 API](https://developers.naver.com/docs/search/news/)를 활용해서 뉴스들을 받아올 것이다.

받아온 뉴스를 이제 해당 오디오북안에 파싱시켜 주고 각각의 뉴스들은 3줄 요약해서 첫 표지에서 썸네일 형식으로 보여 줄 것이다. 파싱된 정보들은 KAKAO Speech API를 통해 오디오북 형식으로 제작할 것이다.

정리하면

1. 구글 트렌드를 통한 키워드 분석
2. 네이버 뉴스 API를 통해 분석한 키워드에 해당하는 뉴스 불러오기
3. 받아온 뉴스 정보를 CLOVA Summary를 통한 세줄 요약
4. 세 줄 요약된 정보들은 오디오북 표지에 썸네일 형식으로 파싱
5. 세 줄 요약된 정보들은 한꺼번에 읽어주는 오디오를 표지에 배치
6. 뉴스 전체 내용은 오디오북 안쪽에 배치
7. 각각의 기사마다 해당 기사를 읽어주는 오디오 배치

각각의 단계별로 개발을 진행하도록 하겠다.

---

## Google Trend

[Google 트렌드](https://trends.google.co.kr/trends/trendingsearches/daily?geo=KR)

구글 트렌드에서 일별 인기 급상승 검색어를 추출 해야하는데 사용하기 쉬운 방법이 2가지가 있었다.

- [Python의 Pytrend 이용하기](https://98yejin.github.io/2020-11-02-google-trends/)
- [Node.js를 통한 RSS 파싱](https://brunch.co.kr/@joypinkgom/90)

이번 프로젝트의 대부분이 Python으로 진행되고 있지만 구글 트렌드에서는 RSS를 제공해주고 있었고 Node.js를 통한 API를 구축해본 경험이 없어서 Python의 라이브러리를 활용해서 간단하게 해결하는 것보다는 이번 기회를 통해 Node.js를 통한 간단한 API도 구축해보고 싶었다.

내가 찾은 자료에는 RSS Parser 라는 라이브러리를 활용하여 개발을 진행하였다.

### 설치

```bash
npm i --save lodash
npm install express --save
npm install q
npm install --save rss-parser
npm install moment-timezone
```

### 메인 코드 - google_trends_service.js

```jsx
'use strict';

const _ = require('lodash');
const Q = require('q');

const Parser = require('rss-parser');
const parser = new Parser({
    customFields: {
        item: ['ht:approx_traffic', 'ht:picture', 'ht:news_item']
    }
});

const moment = require('moment-timezone');
moment.locale('ko');
const TIMEZONE = "Asia/Seoul";
const DATE_FORMAT = "YYYY-MM-DD";

class GoogleTrendsService {

    constructor(options) {
        this._options = options || {};
        this.rss = 'https://trends.google.com/trends/trendingsearches/daily/rss?geo=KR';
    }

    getDailySearchTrends() {
        var deferred = Q.defer();

        parser.parseURL(this.rss)
            .then(feed => {
                let googleTrendsData = {
                    'items': []
                };

                feed.items.forEach(item => {
                    let today = moment().tz(TIMEZONE).format(DATE_FORMAT);
                    let trendsDate = moment(item.isoDate).tz(TIMEZONE).format(DATE_FORMAT);

                    if (today == trendsDate) {
                        googleTrendsData.items.push({
                            'title': item.title,
                            'count': item['ht:approx_traffic'],
                            'pubDate': item.pubDate,
                            'pubDateKor': moment(item.isoDate).tz(TIMEZONE).format("LLLL"),
                            'isoDate': item.isoDate,
                            'picture': item['ht:picture'],
                            'newsItemTitle': _.unescape(item["ht:news_item"]["ht:news_item_title"][0]),
                            'newsItemSnippet': _.unescape(item["ht:news_item"]["ht:news_item_snippet"][0]),
                            'newsItemUrl': item["ht:news_item"]["ht:news_item_url"][0],
                            'newsItemSource': _.unescape(item["ht:news_item"]["ht:news_item_source"][0])
                        });
                    }
                });

                deferred.resolve(googleTrendsData);
            }).catch(err => {
                deferred.reject(err);
            });

        return deferred.promise;
    }
}

module.exports = new GoogleTrendsService();
```

### API로 만들기 - api.js

```jsx
var express = require('express');
const trendsService = require('./google_trends_service');

var app = express();
 
app.get('/trend', function (req, res) {
    trendsService.getDailySearchTrends()
        .then(trendsList => {
            res.json(JSON.stringify(trendsList, null, 2));
        })
        .catch(err => console.err);
    ;
})
 
app.listen(3001, function(){
    console.log("Express server has started on port 3001")
})
```

파일 구조는 api.js 와 google_trends_service.js가 같은 경로에 있어야한다.

실행방법은 node api.js

---

## FLASK API

총 3가지 API를 Flask를 통해 구현할 것이다.

필요한 라이브러리는

```python
import firebase_admin
from firebase_admin import credentials
from firebase_admin import firestore
from flask import Flask, request, Response
from bs4 import BeautifulSoup
import urllib.request
import requests
import json
import time
```

으로 필요한 라이브러리를 pip install을 통해 설치하면 된다.

### 네이버 뉴스 링크 가져오기

```python
@app.route('/NaverNewsLink', methods = ['POST'])

def getNews():
    params = request.get_json()["keyword"]      #post로 전달받은 데이터를 json으로 파싱 {"keyword": "코로나"}으로 보냄
    
    client_id = "YOUR-ID"                       #네이버 개발자 사이트에 있는 ClientID를 입력하면 된다.
    client_secret = "YOUR-SECRET"               #네이버 개발자 사이트에 있는 Secret을 입력하면 된다.
 
    encText = urllib.parse.quote(params) # 검색할 키워드

    url = "https://openapi.naver.com/v1/search/news?query=" + encText + "&display=3&sort=sim"#display는 표시할 뉴스 개수,sort는 정렬 방법이다. 자세한건 네이버뉴스API 문서에 작성되어있다.

    requestURL = urllib.request.Request(url)
    requestURL.add_header("X-Naver-Client-Id", client_id)
    requestURL.add_header("X-Naver-Client-Secret", client_secret)
    response = urllib.request.urlopen(requestURL)
    rescode = response.getcode()
    if(rescode == 200):
        news_links = []
        response_body = response.read().decode('utf-8')     #type이 string이다
        #return response_body
        items = json.loads(response_body)["items"]          #json으로 불러와 item을 불러온다
        for item in items:
            link = item['link']
            if 'news.naver.com' in link:
                print(link)
                news_links.append(link)
        return {"link":news_links}
    else:
        return("Error Code:" + rescode)
```

POST 방식의 API로 입력받는 데이터의 형식은 `{"keyword": "코로나"}` 형식으로 데이터를 넣어주면 되고

Return되는 값은 키워드로 검색한 뉴스 중 네이버 뉴스(news.naver.com)으로 이루어진 링크만을 추출하여

```json
{
  "link": [
    "https://news.naver.com/main/read.naver?mode=LSD&mid=sec&sid1=102&oid=015&aid=0004604028",
    "https://news.naver.com/main/read.naver?mode=LSD&mid=sec&sid1=101&oid=056&aid=0011119205",
    "https://news.naver.com/main/read.naver?mode=LSD&mid=sec&sid1=102&oid=032&aid=0003097871"
  ]
}
```

와 같은 형식으로 Return한다. 네이버 뉴스로 추출하는 이유는 본문 내용은 직접 크롤링 해야하는데 형식이 정형화 되어있어야 용이하기 때문이다.

### 네이버 뉴스 본문 가져오기

```python
@app.route('/NaverNewsDetail', methods = ['POST'])

def getNewsDetail():
    params = request.get_json()["link"]      #post로 전달받은 데이터를 json으로 파싱 {"keyword": "코로나"}으로 보냄
    headers = {'User-Agent':'Mozilla/5.0 (Windows NT 6.3; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/63.0.3239.132 Safari/537.36'}
    res = requests.get(params,headers=headers)
    if res.status_code == 200:
        news_data = []
        try:
            if 'sports' in params:                                                                                #스포츠 기사인 경우
                soup = BeautifulSoup(res.text,"html.parser")
                title = soup.select_one('h4.title').text.strip()
                input_date = soup.select_one('div.info').text.strip().replace('\n',' ')
                article = soup.select_one('div#newsEndContents').text.strip().replace('\n','')
                # 간혹 flash오류가 발생하므로 이를 우회하기 위한 함수를 추가한다.
                article = article.replace('// flash 오류를 우회하기 위한 함수 추가\nfunction _flash_removeCallback() {}','')
                data = {"title":title, "input_date":input_date, "article":article}
            else:                                                                                                 #일반 기사인 경우
                soup = BeautifulSoup(res.text,"html.parser")
                title = soup.select_one('h3#articleTitle').text.strip()
                input_date = soup.select_one('span.t11').text.strip()
                article = soup.select_one('div#articleBodyContents').text.strip()
                # 간혹 flash오류가 발생하므로 이를 우회하기 위한 함수를 추가한다.
                article = article.replace('// flash 오류를 우회하기 위한 함수 추가\nfunction _flash_removeCallback() {}','')
                data = {"title":title, "input_date":input_date, "article":article}
            news_data.append(data)
        except:                                                                                                   #연예 기사인 경우
            soup = BeautifulSoup(res.text,"html.parser")
            title = soup.select_one('h2.end_tit').text.strip()
            input_date = soup.select_one('span.author').text.strip().replace('\n',' ')
            article = soup.select_one('div#articeBody').text.strip().replace('\n','')
            # 간혹 flash오류가 발생하므로 이를 우회하기 위한 함수를 추가한다.
            article = article.replace('// flash 오류를 우회하기 위한 함수 추가\nfunction _flash_removeCallback() {}','')
            data = {"title":title, "input_date":input_date, "article":article}
            news_data.append(data)
    else:
        return("Error Code:" + res.status_code)
    return {"detail" : news_data}
```

POST 방식의 API로 입력받는 데이터의 형식은 `{"link":"https://news.naver.com/~~~~~~"}` 형식으로 데이터를 넣어주면 되고 이때 스포츠 뉴스는 `https://sports.news.naver.com/~~~~~~`시작되고 

연예 뉴스 같은 경우는 형식이 같지만 막상 링크를 통해 접속하면 `https://entertain.news.naver.com/~~`  으로 연결되는 것을 확인했다

정리하면 일반뉴스, 스포츠 뉴스, 연예 뉴스 3가지 모두 다른 형식으로 이루어져 있음을 파악했고 이것에 대해 각각에 해당하는 코드로 크롤링을 진행하였다.

또한 크롤링을 진행할때 headers에 해당하는 내용이 포함되지 않아 크롤링이 진행되지 않는 이슈가 발생했었는데 그에 대한 설명을 열심히 공부해서 headers에 추가하여 해결했다.  아래는 그에 대한 내용이다.

[안티 크롤링](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/%E1%84%8B%E1%85%A1%E1%86%AB%E1%84%90%E1%85%B5%20%E1%84%8F%E1%85%B3%E1%84%85%E1%85%A9%E1%86%AF%E1%84%85%E1%85%B5%E1%86%BC%2091e658e7332748fca047583efd9753b1.md)

*[참고자료](https://ysyblog.tistory.com/49)*

### 결과

```json
{
  "detail": [
    {
      "article": "아이린. JTBC 예능 프로그램 ‘아는 형님’     모델 아이린(본명 김혜진)이 모델 정혁에게 고백했다고 털어놨다.    아이린은 지난 11일 방송된 JTBC 예능 프로그램 ‘아는 형님’에 출연해 재치 있는 입담을 드러냈다.    이날 씨름선수 출신 방송인 강호동은 “이걸 방송에서 얘기해도 되나?”라며 아이린과 정혁을 바라봤다.    이에 다른 출연진들은 “둘이 사귀었어?”라며 물었다.    그러자 강호동은 “심장박동수 테스트를 했는데 예능 하면서 그런 걸 처음 봤다”고 설명했다.   정혁의 인사에 아이린의 심장박동수가 높아졌던 것.   이를 들은 아이린은 “더워서 그랬어”라고 해명했다.   그러나 “둘이 뭐가 있었냐”는 출연진의 질문이 이어졌다.   결국 아이린은 “고백했는데 내가 차였다”고 실토했다.    이에 정혁은 “누나, 그렇게 말하면 내가 쓰레기가 되잖아요”라며 반응했다.   아이린은 “장난이다. 아무 일도 없었다”고 덧붙였다.",
      "input_date": "기사입력2021.09.12. 오전 11:36",
      "title": "아이린 \"정혁에게 고백했는데 차였다\""
    }
  ]
}
```

위와 같은 형식으로 결과를 Return한다. 기사 제목, 작성 날짜, 기사 내용 이라는 정보를 담아 저장한다.

### Firebase

[파이어베이스](https://firebase.google.com/)는 2011년 파이어베이스사가 개발하고 2014년 구글에 인수된 모바일 및 웹 애플리케이션 개발 플랫폼이다.

이번 프로젝트에서 Firebase를 사용하게 된 계기는 DB 때문이다. 사실 다루는 데이터의 양이 이렇게 방대할 줄을 몰라서 Flask를 사용해서만 데이터들을 처리하려고 했는데 데이터들이 씹히는 이슈가 발생했다.

따라서 데이터를 저장할 곳이 필요했고, 평소에 웹, 앱 개발할 때 백엔드 역할을 하던 Firebase가 떠올라서 관련 [자료](https://firebase.google.com/docs/firestore/manage-data/add-data?authuser=1#python)를 찾아봤고 Python으로도 Firebase의 Cloud Firestore(DB 역할)을 제어할 수 있다는 것을 알았다.

[Get started with Cloud Firestore | Firebase Documentation](https://firebase.google.com/docs/firestore/quickstart?authuser=1)

이곳에 하는 과정이 전부 나와있었고 가장 헷갈렸던 부분은 

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled%206.png)

json파일을 찾는 것이었는데 `톱니바퀴 → 프로젝트 설정 → 서비스 계정 → 새 비공개 키 생성`

을 통해 얻을 수 있다. 예제 코드도 같이 적용되니 참 편리한 것 같다.

```python
import firebase_admin
from firebase_admin import credentials
from firebase_admin import firestore

cred = credentials.Certificate('naver_auth.json')
firebase_admin.initialize_app(cred)

db = firestore.client()
a = 'hi'
doc_ref = db.collection(u'users').document(a)
doc_ref.set({
    u'level': 20,
    u'money': 700,
    u'job': "knight"
})
```

여러가지 테스트 해볼 때 사용했던 Firestore에 데이터를 추가할 때 사용했던 예제 코드이다.

### 네이버 뉴스 정보를 Firebase에 저장하기

```python
@app.route('/NaverNewsResult', methods = ['GET'])                   

def getNewsResult():                                               #전부 집대성한 API DB에 뉴스 저장
    db = firestore.client()
    today = time.strftime('%Y-%m-%d', time.localtime(time.time())) #YYYY-MM-DD

    news_link = "http://0.0.0.0:80/NaverNewsLink"     #NAVER 뉴스 링크 가져오기
    detail_link = "http://0.0.0.0:80/NaverNewsDetail" #NAVER 뉴스 본문 파싱하기
    trend_link = "http://220.149.85.18:8088/trend"    #nodejs Google Trend 코드
    trend_res = requests.get(trend_link)
    items = json.loads(trend_res.json())["items"]
    titles = []
    resultData = []
    for item in items:
        title = item["title"]
        titles.append(title)
        headers = {'Content-Type': 'application/json; charset=utf-8'} #header를 추가하지 않으면 json파일을 API 쪽에서 파싱이 불가능 했다.
        data = {"keyword": title}
        link_res = requests.post(news_link, data=json.dumps(data),headers=headers) #json.dumps를 활용해서 딕셔너리를 json 형식으로 변환해야한다.
        if link_res.status_code == 200:
            links = link_res.json()['link']                 #네이버 뉴스 링크 모음
            for link in links:
                headers = {'Content-Type': 'application/json; charset=utf-8'} #header를 추가하지 않으면 json파일을 API 쪽에서 파싱이 불가능 했다.
                data = {"link": link}
                detail_res = requests.post(detail_link, data=json.dumps(data),headers=headers)
                if detail_res.status_code == 200:
                    detail = detail_res.json()['detail']
                    doc_ref = db.collection(today).document(title)
                    doc_ref.set({
                        u'keyword': title,
                        u'link': link,
                        u'detail': detail
                    })
                    print('success')
    return 'success'
```

위에서 개발했던 

- node.js을 통한 구글 트렌드 API
- Flask를 통한 네이버 뉴스 링크 API
- Flask를 통한 네이버 뉴스 본문 내용 API

3가지 API를 전부 활용하여 얻을 내용을 Firebase에 저장하는 API이다.

코드의 흐름을 보면 순서대로 API들을 호출 하는 것을 알 수 있고

![Untitled](%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%AE%E1%84%83%E1%85%B3%E1%84%8B%E1%85%AA%20%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A9%E1%84%87%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%B5%E1%84%82%E1%85%B3%203e33b8211674448fb4070063bbfc3fa9/Untitled%207.png)

DB는 오늘날짜 → 키워드 → 뉴스 내용 의 Structure로 저장하였다.

### 전체 코드

```python
import firebase_admin
from firebase_admin import credentials
from firebase_admin import firestore
from flask import Flask, request, Response
from bs4 import BeautifulSoup
import urllib.request
import requests
import json
import time

cred = credentials.Certificate('naver_auth.json')
firebase_admin.initialize_app(cred)
db = firestore.client()

app = Flask(__name__)

@app.route('/NaverNewsLink', methods = ['POST'])

def getNews():
    params = request.get_json()["keyword"]      #post로 전달받은 데이터를 json으로 파싱 {"keyword": "코로나"}으로 보냄
    
    client_id = "YOUR-ID"
    client_secret = "YOUR-SECRET"

    encText = urllib.parse.quote(params) # 검색할 키워드

    url = "https://openapi.naver.com/v1/search/news?query=" + encText + "&display=3&sort=sim"# json 결과가 필요할 때 사용

    requestURL = urllib.request.Request(url)
    requestURL.add_header("X-Naver-Client-Id", client_id)
    requestURL.add_header("X-Naver-Client-Secret", client_secret)
    response = urllib.request.urlopen(requestURL)
    rescode = response.getcode()
    if(rescode == 200):
        news_links = []
        response_body = response.read().decode('utf-8')     #type이 string이다
        #return response_body
        items = json.loads(response_body)["items"]          #json으로 불러와 item을 불러온다
        for item in items:
            link = item['link']
            if 'news.naver.com' in link:
                print(link)
                news_links.append(link)
        return {"link":news_links}
    else:
        return("Error Code:" + rescode)

@app.route('/NaverNewsDetail', methods = ['POST'])

def getNewsDetail():
    params = request.get_json()["link"]      #post로 전달받은 데이터를 json으로 파싱 {"keyword": "코로나"}으로 보냄
    headers = {'User-Agent':'Mozilla/5.0 (Windows NT 6.3; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/63.0.3239.132 Safari/537.36'}
    res = requests.get(params,headers=headers)
    if res.status_code == 200:
        news_data = []
        try:
            if 'sports' in params:                                                                                #스포츠 기사인 경우
                soup = BeautifulSoup(res.text,"html.parser")
                title = soup.select_one('h4.title').text.strip()
                input_date = soup.select_one('div.info').text.strip().replace('\n',' ')
                article = soup.select_one('div#newsEndContents').text.strip().replace('\n','')
                # 간혹 flash오류가 발생하므로 이를 우회하기 위한 함수를 추가한다.
                article = article.replace('// flash 오류를 우회하기 위한 함수 추가\nfunction _flash_removeCallback() {}','')
                data = {"title":title, "input_date":input_date, "article":article}
            else:                                                                                                 #일반 기사인 경우
                soup = BeautifulSoup(res.text,"html.parser")
                title = soup.select_one('h3#articleTitle').text.strip()
                input_date = soup.select_one('span.t11').text.strip()
                article = soup.select_one('div#articleBodyContents').text.strip()
                # 간혹 flash오류가 발생하므로 이를 우회하기 위한 함수를 추가한다.
                article = article.replace('// flash 오류를 우회하기 위한 함수 추가\nfunction _flash_removeCallback() {}','')
                data = {"title":title, "input_date":input_date, "article":article}
            news_data.append(data)
        except:                                                                                                   #연예 기사인 경우
            soup = BeautifulSoup(res.text,"html.parser")
            title = soup.select_one('h2.end_tit').text.strip()
            input_date = soup.select_one('span.author').text.strip().replace('\n',' ')
            article = soup.select_one('div#articeBody').text.strip().replace('\n','')
            # 간혹 flash오류가 발생하므로 이를 우회하기 위한 함수를 추가한다.
            article = article.replace('// flash 오류를 우회하기 위한 함수 추가\nfunction _flash_removeCallback() {}','')
            data = {"title":title, "input_date":input_date, "article":article}
            news_data.append(data)
    else:
        return("Error Code:" + res.status_code)
    return {"detail" : news_data}

@app.route('/NaverNewsResult', methods = ['GET'])                   

def getNewsResult():                                               #전부 집대성한 API DB에 뉴스 저장
    db = firestore.client()
    today = time.strftime('%Y-%m-%d', time.localtime(time.time())) #YYYY-MM-DD

    news_link = "http://0.0.0.0:80/NaverNewsLink"     #NAVER 뉴스 링크 가져오기
    detail_link = "http://0.0.0.0:80/NaverNewsDetail" #NAVER 뉴스 본문 파싱하기
    trend_link = "http://220.149.85.18:8088/trend"    #nodejs Google Trend 코드
    trend_res = requests.get(trend_link)
    items = json.loads(trend_res.json())["items"]
    titles = []
    resultData = []
    for item in items:
        title = item["title"]
        titles.append(title)
        headers = {'Content-Type': 'application/json; charset=utf-8'} #header를 추가하지 않으면 json파일을 API 쪽에서 파싱이 불가능 했다.
        data = {"keyword": title}
        link_res = requests.post(news_link, data=json.dumps(data),headers=headers) #json.dumps를 활용해서 딕셔너리를 json 형식으로 변환해야한다.
        if link_res.status_code == 200:
            links = link_res.json()['link']                 #네이버 뉴스 링크 모음
            for link in links:
                headers = {'Content-Type': 'application/json; charset=utf-8'} #header를 추가하지 않으면 json파일을 API 쪽에서 파싱이 불가능 했다.
                data = {"link": link}
                detail_res = requests.post(detail_link, data=json.dumps(data),headers=headers)
                if detail_res.status_code == 200:
                    detail = detail_res.json()['detail']
                    #print(detail)
                    # #{"keyword":item,"link":link,"detail":detail}
                    # #resultData.append({"keyword":item,"link":link,"detail":detail})     #양이 너무 많아서 출력 조차 안된다 DB 연동이 시급하다
                    doc_ref = db.collection(today).document(title)
                    doc_ref.set({
                        u'keyword': title,
                        u'link': link,
                        u'detail': detail
                    })
                    print('success')
    return 'success'

if __name__ == "__main__":
    app.run(debug=True, host='0.0.0.0', port=80)
```

본인의 네이버 개발자 정보, 본인의 API 주소를 입력하는 것을 잊지말자
