<br />
<p align="center">
  <a href="https://github.com/Gaepodong/Your-True-Review">
    <img src="https://fontmeme.com/permalink/200910/109ba0996778b6d9b99ce3ec7deee89e.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Your-True-Review</h3>

  <p align="center">
    감정분석 및 텍스트랭크를 이용한 영화 대표 리뷰 추출과 평점 부여 서비스
    <br />
    <a href="https://github.com/Gaepodong/Your-True-Review"><strong>Explore the Github »</strong></a>
    <br />
  </p>
</p>

## Table of Contents

- [개요](#개요)
- [About The Project](#about-the-project)
    - [데이터 수집](#데이터-수집)
    - [감정 분석](#감정-분석)
    - [모델 설계](#모델-설계)
    - [웹 서비스](#웹-서비스)
- [실행 방법](#실행-방법)

    
# 개요

 __감정 분석 기법을 이용한 영화 평점 자동 부여 및 TextRank를 이용한 대표 리뷰 추출 시스템__  
>  본 프로젝트는 영화 리뷰 댓글 데이터를 수집하여 댓글이 나타내는 긍/부정에 따라 평점을 매기고, 각 영화를 대표할 수 있는 리뷰를 보여주는 서비스입니다.

# About The Project

<p align="center">
    <img src="1599393108835.png" alt="Logo" width="" height="500">
</p>

## 데이터 수집

## 감정 분석

## 모델 설계

## 웹 서비스

# 실행 방법

## 필요 사항

- python3
- python3-pip
- python venv

## 설치

1. Clone the repository
```
git clone https://github.com/Gaepodong/Your-True-Review.git
```
2. Activate Virtualenv
```
source .venv/bin/activate
```
3. Set the environment variables
```
export FLASK_APP="true_review" FLASK_ENV="development" API_SERVER="http://13.124.240.211:55637/predict"
```
4. Change the directory and Install the requirements.
```
cd Your-True-Review/web && pip install -r requirements.txt
```
5. Run the Server
```
flask run
```
## 구조
```
.
├── README.md
├── data
│   ├── wordcloud
│   └── output
├── get_model.py
├── macro.py
├── pytorch_flaskapp.ipynb
├── rawdata
├── tagging_rating.ipynb
├── textrank.py
└── web
    ├── README.md
    ├── config.py
    ├── init_db.sh
    ├── migrations
    ├── nohup.out
    ├── ranked_reviews
    ├── requirements.txt
    ├── true_review
    └── true_review.db

17 directories, 13 files
```

