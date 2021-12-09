**1 - Crawling (크롤링)**
* 아나콘다(https://www.anaconda.com/products/individual )’를 설치하여 파이썬과 라이브러리를 한번에 사용 할 수 있는 가상환경을 만들고 
주피터 노트북(https://jupyter.org/ )으로 실행
* Pandas 라이브러리를 통해 필요한 데이터만을 담은 data frame을 선언하고 이를 통해 머신러닝에 적용시킬 수 있음. 인덱스가 있어 행과 열로 구성된 프레임에 데이터가 저장되는 테이블 형태의 data frame을 이용할 예정
* BeautifulSoup은 html 코드를 파이썬이 인식 할 수 있는 객체 구조로 변환하는 Parsing을 담당
* selenium은 브라우저 자동화도구로서 웹브라우저를 통해 동적페이지에서도 데이터 수집  가능

1) Anaconda Prompt

![1](https://user-images.githubusercontent.com/76679270/145396988-751b64cb-a10d-4afe-8854-5d2307d3e0b5.jpg)


2) 크롬드라이버 저장 경로 ,자신의 네이버 ID/PW입력

![2](https://user-images.githubusercontent.com/76679270/145397347-f68db065-170e-4a00-aed6-33135de8972b.jpg)
 

3) 데이터를 저장하려는 엑셀파일의 절대 경로를 입력

![3](https://user-images.githubusercontent.com/76679270/145397369-611f6349-8f61-4233-a045-7c063fada459.jpg)


4) 크롤링 되는 과정

![4](https://user-images.githubusercontent.com/76679270/145397412-f6a52c56-0aca-4205-9ad4-32f9f713dd5d.jpg)

  
5) 크롤링 완료 후 엑셀파일에 저장된 데이터 모습

![5](https://user-images.githubusercontent.com/76679270/145397428-777021fd-bb56-4170-b1de-4c3f4739c990.png)


**2 - Preprocessing (전처리)**


**3 - LSTM**

<LSTM으로 E vs I 분류하기>

1) mbti_train.xlsx와 mbti_test.xlsx를 다운받고, 둘다 구글 스프레드로 열어준 후 구글 드라이브에 저장해준다.

2) google colab을 켜서 '파일'>'새 노트' 로 새 노트를 만들어주고 'LSTM으로 E vs I 분류' 코드를 복사, 붙여넣기 해준다.

3) 주석으로 #훈련 데이터가 담긴 엑셀 파일의 구글 드라이브 경로라고 적힌 라인에는 train 이라는 변수에 mbti_train.xlsx 파일의 구글 드라이브 경로를 적어준다.

4) 주석으로 #훈련 데이터가 담긴 엑셀 파일의 구글 드라이브 경로라고 적힌 라인에는 test 라는 변수에 mbti_test.xlsx 파일의 구글 드라이브 경로를 저장해준다.

5) 그리고 '런타임'>'모두 실행' 하고, 구글에 로그인하게끔 하는 팝업창이 뜨는데, 그 팝업창을 통해 로그인을 한다.
(그리고 만약 팝업창에서 암호코드가 나오면 복사해서 콘솔창에 뜨는 필드에 붙여넣기 한다.)




<LSTM으로 긍정적 vs 부정적 영화 리뷰 분류하기>

1) 코랩을 켜서 '파일'>'새 노트' 로 새 노트를 만들어주고 'LSTM으로 긍정적 vs 부정적 영화 리뷰 분류' 코드를 복사, 붙여넣기 해준다.
2) 데이터가 많아서 전처리와 학습, 정확도 도출 등이 오래걸릴 수 있다.




