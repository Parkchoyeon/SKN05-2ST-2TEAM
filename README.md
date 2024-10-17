# SKN05-2ST-2TEAM
✅2차 프로젝트
허상호,신혜원,안태영,윤상혁,박초연<br>
개발기간: 2024.10.16-10.17

# 1. 팀 소개
<table align=center>
  <tbody>
    <tr>
      <td align="center">
        <div>
          <img src="https://st2.depositphotos.com/1072614/10046/i/450/depositphotos_100461182-stock-photo-cat-with-books-isolated-on.jpg"width="100px;"height="100px;" alt=""/>
          <a href="https://github.com/JUNGUIHEON"><div align=center>허상호</div></a>
        </div>
      </td>
      <td align="center">
        <div>
          <img
            src="https://st2.depositphotos.com/1072614/10046/i/450/depositphotos_100461182-stock-photo-cat-with-books-isolated-on.jpg"width="100px;" alt=""/>
          <a href="https://github.com/gigcot"><div align=center>신혜원</div></a>
        </div>
      </td>
      <td align="center">
        <img src="https://st2.depositphotos.com/1072614/10046/i/450/depositphotos_100461182-stock-photo-cat-with-books-isolated-on.jpg"width="100px;" alt=""/>
        <a href="https://github.com/yhoon3002"><div align=center>안태영</div></a>
      </td>
      <td align="center">
        <img src="https://st2.depositphotos.com/1072614/10046/i/450/depositphotos_100461182-stock-photo-cat-with-books-isolated-on.jpg"width="100px;" alt=""/>
        <a href="https://github.com/ih9511"><div align=center>윤상혁</div></a>
      </td>
      <td align="center">
        <img src="https://st2.depositphotos.com/1072614/10046/i/450/depositphotos_100461182-stock-photo-cat-with-books-isolated-on.jpg"width="100px;" alt=""/>
        <a href="https://github.com/heowooyoung"><div align=center>박초연</div></a>
      </td>
    </tr>
  </tbody>
</table>

# 2. 프로젝트 개요
- 프로젝트 명: 캘리포니아 지역 통신사 고객 이탈 예측
- 프로젝트 소개: 고객의 서비스 사용 데이터를 바탕으로 이탈 여부를 예측하는 머신러닝 모델 개발
- 프로젝트 필요성(배경): 고객 이탈은 통신사 매출에 큰 영향을 미치며, 고객 유치는 유지보다 비용이 높기 때문에 이탈 방지가 중요
- 프로젝트 목표: 고객 이탈 가능성을 예측하여 이탈 위험 고객을 식별하고, 고객 유지율을 높이는 것

# 3. 기술 스택
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/></a>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/></a>
<img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat-square&logo=Google Colab&logoColor=white"/></a>

# 4. 데이터분석 및 전처리
### :heavy_check_mark: 데이터 개요
- **컬럼 수**: 총 66개의 컬럼 중 불필요한 37개의 컬럼 제거 후 29개 사용
- **결측치 처리**: Offer, Total Charges 등(사진)
- **데이터의 특성을 고려하여 인코딩 진행**: Age, Number of Dependents4 등


### :heavy_check_mark: 전처리 
- 결측치 처리 Offer, Total Charges 등
- 이상치 및 결측치 확인, 연속형 데이터의 분포 확인(사진)
- 데이터 인코딩(사진)
- 상관관계 분석(사진)
- 주요 컬럼 및 최종 선정 컬럼
- 가설에 따른 이탈률

# 5. 모델 성능비교 및 해석
- 하이퍼파라미터 그리드 설정, Best Model 선정
- 하이퍼파라미터 튜닝 - GBM
- ROC 커브 시각화 함수
- Precision-Recall 커브 시각화 함수
- 박스플롯 비교 함수

# 6. 시사점
- 통신사 이탈에 가장 큰 영향을 미치는 주요 요인
- 통신사 시장 점유율
- 현재 통신사가 놓치고 있는 점
- 고객 만족도 향상 전략



# :smirk: 한줄 회고
<table align=center>



 
 
