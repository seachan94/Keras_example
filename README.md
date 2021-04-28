# Keras_example   
      
#Movie   

## [2021-02-12]   
[Update] Create Keras_example Repository   
[Update] Start Moive_Review_classification   
[Update] Model / Draw
   
   
#Reuter   
## [2021-02-22]   
[feature]Start Reuter   
[Update] Model / Draw   
   
   
   
#Bostion_housing   
## [2021-02-24]   
[feature] start   
[update] study fin- code   

   
   
#CNN Basic   
## [2021-03-07] data path setting   
## [2021 - 03 - 14] updata code & feature Network & feature generator   
## [2021 - 04 - 10] [feature] data Augmentation   

      데이터가 적은양일 때 Augmetation을 통해 정규화를 진행 할 수 있다.   
      하지만 정확도를 올리는 것은 한계가 있으며 이를 해결하기 위해서는 parameter 조정이 같이 병행되어야 한다.


#NLP Basic  [2021 -04 - 28] 
      

      딥러닝 문서는 수치형 텐서만 다룰 수 있다 
      (텍스트 -> 수치형 = vectorizing text)

      - 텍스트를 단어로 나누고 각 단어를 하나의 벡터로 변환
      - 텍스트를 문자로 나누고 각 문자를 하나의 벡터로 변환
      - 텍스트 or 단어에서 문자의 n-gram을 추출 하여 하나의 벡터로 변환
      - n-gram은 연속된 단어나 문자의 그룹으로 텍스트에서 단어나 문자를 하나씩 이동하면서 추출
      
      1. n-gram /단어/ 문자 = token

      2. token으로 나누는 작업 = tokenization

      3. vetorizing text = tokenization 적용 -> 생성된 토큰에 수치형 벡터를 연결하는 것(ex - one_hot / token embedding)

      n-gram
      word n-gram 문장에서 추출한 N 개 혹은 이하의 연속된 단어 그룹(문자 적용 가능)

      EX ) Hi nice to meet u

      2-gram : {Hi, Hi nice , nice, nice to , to , to meet , meet, meet u, u}

      3-gram : { Hi, Hi nice, nice, nice to , Hi nice to , to , to meet, meet, nice to meet, meet u, u, to meet u}

      = BoW (Bag - of - words) 

         - BoW는 순서가 없는 학습 법이다 = 문장의 구조가 없다 
              따라서 딥러닝 모델보다 얕은 학습 방법의 언어 처리 모델에 사용 됨
