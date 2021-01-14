# wiki_preprocessing
위키백과 데이터 전처리

# Detail
한글 자연어처리에 앞서 위키백과 데이터를 간단한 전처리를 진행하기 위한 노트북입니다.

위키덤프파일을 위키페이지에서 다운로드받은 후 WikiExtractor 오픈소스를 활용하여 위키덤프파일을 파싱합니다.

Colab에서 데이터를 다루기 때문에 리눅스 명령어를 통해 텍스트파일을 합치고,

허킹페이스 트랜스포머의 토크나이저를 활용하여 토큰 모델을 생성합니다.

---
This repo is Colab notebook for Korean NLP preprocessing with WIKI dump files. 

I used an WikiExtractor that open source.

And You can make a Token model for Hugging Face model

#Reference
https://github.com/attardi/wikiextractor
