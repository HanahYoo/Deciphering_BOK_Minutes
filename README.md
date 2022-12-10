# Deciphering-BOK-Minutes
금융통화위원회 의사록에 담긴 어조를 추출하여 지수로 편제하고 기준금리 변동에 대한 예측력을 검정

## Technologies
![python3](https://img.shields.io/badge/python-3.10-blue)
![Crawling](https://img.shields.io/badge/Web-Crawling-important)

## Features
 - 분석 방법 : 2008.04.01~2022.11.15에 발생한  300건의 의사록에서 추출한 n-gram을 분석하여 감성사전*을 구축 
 
    * 특정 n-gram(예: 금리 인상)이 지닌 polarity을 규정한 사전 (예: 금리 인상 = 매파적)
