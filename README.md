# 🌡️ 기후 변화와 지구 온난화 (Climate Change & Global Warming)

<div align="center">
<a href="https://hits.seeyoufarm.com"><img width = "15%" src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FJo-Minseok%2Fglobal-warming-100year&count_bg=%23FF0000&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
</div>

## CONTENTS

- [Team](#Team)
  - [Intro](#Intro)
  - [Composition](#Composition)
- [PROJECT INFORMATION](#PROJECT-INFORMATION)
  - [Mean](#Mean)
  - [Goal](#Goal)
  - [Explain](#Explain)
- [STACKS](#STACKS)
  - [Collaboration](#collaboration)
  - [Development](#Development)
  - [Language](#Language)
  - [Library](#Library)
  - [Function](#Function)
- [SOURCE](#source)

## TEAM

### Intro

- NAME : <strong><em>하바나온난화</em></strong>
- MEAN : Camila Cabello - Havana 노래의 가사 일부분과 '온난화' 단어를 합쳐 만들어진 팀명입니다.

### Composition

<table align="center">
    <th>역할</th>
    <th>이름</th>
    <th>Github</th>
    <th>수행 내용</th>
    <tr>
        <td>팀장</td>
        <td>전진호</td>
        <td><a href="https://github.com/right5625">@right5625</a></td>
        <td>
            <ul>
                <li>소스코드 작성</li>
                <li>CSV 데이터 가공</li>
                <li>scikit-learn 학습</li>
                <li>ARIMA-MODEL 학습</li>
                <li>중간 발표</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>팀원</td>
        <td>조민석</td>
        <td><a href="https://github.com/Jo-Minseok">@Jo-Minseok</a></td>
        <td>
            <ul>
                <li>CSV 데이터 가공</li>
                <li>COLAB 입력 UI 작성</li>
                <li>소스코드 주석 작성</li>
                <li>데이터 간의 상관관계 분석</li>
                <li>최종 발표</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>팀원</td>
        <td>채승룡</td>
        <td><a href="https://github.com/chaeseungryong">@chaeseungryong</a></td>
        <td>
            <ul>
                <li>발표 자료 제작</li>
                <li>CSV 데이터 획득</li>
                <li>서류 작성</li>
                <li>온도 변화 결과 출력</li>
                <li>데이터 분석과 시각화</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>팀원</td>
        <td>원현준</td>
        <td></td>
        <td>
            <ul>
                <li>발표 자료 제작</li>
                <li>CSV 데이터 획득</li>
                <li>서류 작성</li>
                <li>자료 수집</li>
            </ul>
        </td>
    </tr>
</table>

## PROJECT INFORMATION

> 동의대학교 2022학년도 데이터과학 프로그래밍 </br>
> PERIOD: 2022.03.02 - 2022.06.20 (15 Week)</br>

### Mean

📃 과거에 비해 지구의 평균 기온이 상승하여 극지방의 빙하가 녹고 있으며, 빙하가 녹음으로 해수면이 상승하고 있다. 해수면 상승으로 지구 전역에 피해가 발생하고 있으며, 우리나라의 해안가 지역에 영향을 끼칠 수 있다. 지금 당장 우리가 살고 있는 부산의 데이터들을 이용하여 프로젝트를 진행했다.

### Goal

🥇 2100년의 탄소 총 배출량, 평균 기온, 부산 해수면 상승 양, 북극 빙하 면적, 북극 빙하 해빙 범위

### Explain

📃 탄소 배출량 데이터를 이용하여 미래 탄소 총 배출량을 예측하고 2100년까지의 지구 평균 온도를 구한 후, 지구 온도에 따라 바뀌게 될 부산 해수면 상승 양과 북극 빙하 해빙 범위와 북극 빙하 면적을 예측한다.

## STACKS

### Collaboration

<img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">

### Development

<img src="https://img.shields.io/badge/google%20colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">

### Language

<img src="https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white">

### Library

<img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"> <img src="https://img.shields.io/badge/scikit%20learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"> <img src="https://img.shields.io/badge/seaborn-007ACC?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/matplotlib-FF6A00?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/arima%20model-9146FF?style=for-the-badge&logoColor=white">

### Function

<details>
    <summary><strong>💡 2100년 탄소 총배출량 예측</strong></summary>
    <ul>
        <li>ARIMA 모델을 이용하여 시계열 분석법을 통해 예측</li>
    </ul>
</details>
<details>
    <summary><strong>💡 2100년 최고 기온, 평균 기온 추세 예측</strong></summary>
    <ul>
        <li>선형회귀 모델에서 단항 회귀 방식을 이용하여 기온 예측 </li>
    </ul>
</details>
<details>
    <summary><strong>💡 2100년 부산 해수면 상승양 예측</strong></summary>
    <ul>
        <li>부산 해수면 높이에 평균기온 회귀 선을 대입하여 예측</li>
    </ul>
</details>
<details>
    <summary><strong>💡 2100년 북극 빙하 양, 해빙 범위 예측</strong></summary>
    <ul>
        <li>북극 빙하 양과 해빙 범위는 반비례 관계로, 평균기온 회귀 선을 대입하여 예측</li>
    </ul>
</details>

## SOURCE

<ul>
  <li>으뜸 데이터 분석과 머신러닝(박동규, 강영민 지음), 생능출판</li>
</ul>
