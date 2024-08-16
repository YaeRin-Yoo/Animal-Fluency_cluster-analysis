# Animal-Fluency_cluster-analysis


## 논문
***동물 유창성 검사의 채점 및 군집 기준 재확립과 자동 분석의 타당성 및 효과성 검증 연구 (유예린 외., 2024)***

## 프로젝트 목적


***동물 유창성 검사의 채점 및 군집 기준 재확립과 자동 분석의 타당성 및 효과성 검증 연구 (유예린 외., 2024)*** 에서는 연구자마다 다르게 적용하고 있던 동물 유창성 검사의 질적 분석을 위한 동물 군집 분류 기준을 한국인의 동물 인식을 반영하여 재확립하였다. 본 연구에서는 재확립한 동물 군집 분류 기준을 바탕으로 동물 유창성 검사의 전환 수 (switching), 평균 군집 크기 (mean cluster size)를 python 코드를 사용하여 분석할 수 있는 자동 분석 코드를 설계하였다. 이에 실제 임상 및 연구 현장에서 누구나 손쉽게 대상자의 동물 유창성 검사 질적 분석을 수행할 수 있도록 자동 분석 코드와 분석에 필요한 Inventory file을 공개한다.


## 사용 방법

1. [Animal Inventory File_240813.csv](https://github.com/YaeRin-Yoo/Animal-Fluency_cluster-analysis/blob/d00cac9f206837b5399093cb23a90726184f9b52/Animal%20Inventory%20File_240813.csv) 다운 받기 

  + Cluster analysis를 위한 자동 분석은 해당 Animal Inventory File에 기반해 이루어진다.
    
  + 해당 파일에는 ***유예린 외., 2024*** 의 649명 대상자들이 산출한 동물 389개가 표준어를 기준으로 정리되어있다.
    
  + 파일은 새로운 연구 대상자의 추가에 따라 ***이화여자대학교 언어병리학과 신경언어연구실 유예린***에 의해 업데이트 될 예정이다.
 
  + 분석하려는 동물이 해당 파일 내에 존재하지 않는다면 코드 실행에 오류가 발생할 가능성이 있다.

    + 파일을 다운한 후, 분석에 필요한 동물을 직접 추가하여 사용할 수 있다. (추가 시, 논문 본문의 동물 군집 분류 기준을 참고해야 한다.)
   
    + 파일을 다운한 후, 분석하려는 동물 이름을 파일 내에 있는 동물 명과 일치하게 바꾸어 사용할 수 있다.
   
      + 예) 분석하려는 동물 명 '팬더' , 파일 내에 존재하는 동물 명 '판다' : 팬더 --> 판다 교체 후 분석 시행.
      
2. [Cluster analysis] (https://github.com/YaeRin-Yoo/Animal-Fluency_cluster-analysis/blob/c8c94a7a5e5f616e7e2d4bc567ef2de3854d973f/Cluster_analysis_open.ipynb) 코드 실행

  + Cluster analysis의 자세한 분석 방법은 ***유예린 외., 2024*** 에서 소개하고 있다.

  + 대상자가 발화한 동물들을 List 형태로 마지막 함수 final_score 에 넣으면 총 4가지의 값을 return 받을 수 있다.

    + c3_cn_f : Total number of clusters
    + c3_s_f : Total number of switchings
    + c3_cs_f : Total cluster size
    + c3_mcs_f : Mean clsuter size
   
    + 예시 결과는 아래와 동일하다.
   
    + <img width="986" alt="image" src="https://github.com/user-attachments/assets/9aff48eb-ff9a-4ac4-ab8b-5a0253a21266">


3. 저작권 및 사용권 정보

   + 동물 유창성 검사 수행력 분석을 위해 해당 동물 분류 군집 기준이나, 자동 분석 방법을 활용할 때는 ***유예린 외., 2024*** 인용 및 언급이 필요하다.


4. 업데이트 정보

   + Last Update : 2024.08.16


5. FAQ

   + 이화여자대학교 언어병리학과 신경언어연구실 유예린 (leader9390@ewhain.net or leader9390@naver.com)


감사합니다.
