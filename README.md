# 사고 발생 도로 유형 및 인구 데이터 분석을활용한 교통사고 위험도 예측

## 👨‍👩‍👦‍👦 팀원 역할

| 민윤기 (조선대학교) | 배강빈 (순천대학교) |
| --- | --- |
| 프로젝트 총괄
예측 모델 구축
데이터 전처리
데이터 수집
데이터 시각화 | 데이터 수집
데이터 전처리
발표 자료 준비
프로젝트 발표 |
| https://github.com/minyoongi96 | https://github.com/gunbamkim |

![1.png](./images/1.png)

![24.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/24.png)

![3.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/3.png)

![4.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/4.png)

![5.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/5.png)

![6.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/6.png)

![7.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/7.png)

![8.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/8.png)

![9.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/9.png)

![11.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/11.png)

![12.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/12.png)

![13.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/13.png)

![14.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/14.png)

![15.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/15.png)

![16.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/16.png)

![17.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/17.png)

![19.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/19.png)

![20.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/20.png)

![21.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/21.png)

![22.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/22.png)

![23.png](%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%87%E1%85%A1%E1%86%AF%E1%84%89%E1%85%A2%E1%86%BC%20%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9%20%E1%84%8B%E1%85%B2%E1%84%92%E1%85%A7%E1%86%BC%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%80%E1%85%AE%20%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%20%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%E1%84%92%206c0f6a5e666b4651bc7642de0267256c/23.png)
