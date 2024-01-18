# FC-BERT(Filtering Clinical BERT) with Web Application

## FC-BERT (Filtering Clinical BERT) with Web Application
FC-BERT 모델 기반의 웹 어플리케이션 개발
> 자발적 부작용 보고제도의 낮은 데이터를 보완하기 위해 소셜미디어 데이터로부터 약물 부작용 표현을 탐지하기 위한 방법을 제시한다. 
> 리뷰데이터에서 목표 약물에 대한 부작용 표현을 추출하는 이전 연구에서는 약물을 복용하기 전의 증상이나 
> 목표약물이 아닌 다른 약물에 대한 부작용 표현을 제거하지 못한다는 한계점이 있다. 이런 한계점을 보완하기 위해서 
> SPARK-NLP에서 제공하는 4개의 모델과 단계의 필터링을 활용하여 ADE 말뭉치의 ADE 유무를 판단하는 모델을 개발하였다. 
> 최종적으로 FC-BERT를 웹 어플리케이션으로 구현하였다. 해당 웹 어플리케이션은 약물 리뷰 사이트의 리뷰 데이터에 FC-BERT를 적용한 결과를 
> 빈도 그래프와 워드 클라우드로 시각화하여 보여준다. 제안한 웹 어플리케이션은 사람마다 다르게 나타나는 다양한 약물 이상 반응을 
> 사용자에게 좀 더 접근성이 좋게 제공할 수 있을 것으로 보인다.
</br>

## 사용언어 or 사용 툴, 사용 기술
+ 구글 Colab
+ sparknlp 3.4.1 
+ BioBERT, Clinical BERT
+ Django
</br>

## 데이터
약물 리뷰 사이트인 Drugs.com 사이트에서 사용자가 입력하거나 선택한 약물명을 기반으로 리뷰를 크롤링한 데이터이다.
<br></br> 

## 논문
+ 약물 이상 반응 탐지를 위한 Filtering Clinical BERT (FC-BERT) 기반의 웹 어플리케이션 개발
+ https://koreascience.kr/article/CFKO202319360803635.page 
