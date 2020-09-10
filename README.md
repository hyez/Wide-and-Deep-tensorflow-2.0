# Wide & Deep Model for Recommendations
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/scikit-daisy) [![Version](https://img.shields.io/badge/version-v1.0.0-orange)](https://github.com/HYEZ/Wide-and-Deep-tensorflow) ![GitHub repo size](https://img.shields.io/github/repo-size/HYEZ/Wide-and-Deep-tensorflow)


## Overview
구글에서 발표한 '구글 플레이스토어'에 사용된 추천 모델입니다.
- linear 모델의 장점과 neural network(신경망)의 장점을 합쳤습니다.
- 즉, 선형 모델의 저장법(memorization)과 신경망의 일반화(generalization)의 강점을 합친 모델입니다.

## The spectrum of Wide & Deep models
![The spectrum of Wide & Deep models.](https://user-images.githubusercontent.com/21326503/92676863-7180dc80-f35d-11ea-904c-fb54545a756a.png)


## Wide & Deep model structure for recommendations
![Wide & Deep model structure for recommendations](https://user-images.githubusercontent.com/21326503/92676978-a725c580-f35d-11ea-9476-7425a00f2601.png)

## 환경 설정
1. get pip
```
# Ubuntu/Linux 64-bit
$ sudo apt-get install python-pip python-dev

# Mac OS X
$ sudo easy_install pip
$ sudo easy_install --upgrade six
```

2. pandas 설치
```
 $ sudo pip install pandas
```

## Frameworks
- tensorflow 2.3.0

## References
- [구글에서 발표한 논문](https://arxiv.org/pdf/1606.07792.pdf)
- [텐서플로우 튜토리얼](https://tensorflowkorea.gitbooks.io/tensorflow-kr/content/g3doc/tutorials/wide_and_deep/)
- [참고 블로그](https://bcho.tistory.com/tag/wide%20and%20deep%20model)