# MFC Optimal Location Selection for Logistic Centers
- Title :도심형 소형 물류센터(MFC)의 최적 입지 선정
- Period : 2022.09 ~ 2022.12
- Language : Python
- Technologies : Jupyter notebook, Jupyter lab, Orange3, QGIS, Excel
- Framework : Tensorflow, Keras, Pytorch, Matplotlib, folium, pycaret(AutoML)
- Key Method : Consensus Clustering, AHP, KaKao API

## Abstract
소비자의 유통업체와 소비자의 연계에서 새로운 부가가치를 창출할 수 있는 기업의 경쟁요소로 물류센터의 역할이 변화하였다. <br>
<br>
본 연구는 현재의 배송 속도가 기업의 경쟁력으로 부각되고 있는 상황에서 도시물류센터 입지선정에 영향을 미칠 수 있는 변수를 추출하고 데이터 마이닝 기법을 통해 도시물류센터 입지선정의 가이드라인을 제시하였다는 점에서 의미가 있다. 본 분석은 향후 서울시의 주유소들이 도시물류센터에 진입할 것인지를 연구하였다. 주유소와 소비자, 유통업체의 상생은 기대되는 효과라고 할 수 있다. 기존의 연구들은 주유소의 판매감소 요인이 전기차 수요 증가와 원유가격 상승인 반면 소매업체들은 빠른 배송이 경쟁력으로 둔화되고 있음을 발견하였다. <br>
<br>
첫째, 서울시 지역별 공시지가, 배송효율성, 생산가능인구 등 물류센터 수요에 영향을 미칠 수 있는 변수를 선정하여 군집화를 실시하였으며, 수요자의 관점에서 4개의 군집을 해석하였다. 해석된 군집은 도시물류센터가 필요한 지역의 우선순위를 결정하기 위해 합의하였다. 물류센터가 가장 필요한 지역은 동대문구, 양천구, 동작구, 송파구, 구로구, 서대문구, 영등포구 등으로 나타났다. <br>
둘째, 개별공시지가, 면적, 물류허브로부터의 거리, 인구, 학교 수, 상권규모 등을 변수로 선정하고 종속변수의 입지점수는 Analytical Hierarchy Process(AHP)을 이용하여 변수의 중요도를 계산하여 산출하였다. 입지적합성은 입지점수를 세분화하여 매우 적합, 적합, 부적합, 매우 부적합으로 범주화하였으며, ML기반 분류기법과 DNN을 통한 분석 결과 MFC 입지에 가장 적합한 주유소의 분류가 가능한 모델을 설계하였다.


![MFC_PPT_page-0001](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/10752db9-22c1-41e6-b053-e27689577fee)
![MFC_PPT_page-0002](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/4253b06f-04da-4e11-be88-fb6fdb6545e4)
![MFC_PPT_page-0003](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/5aa4e2dd-5688-483d-91fc-cf902d1c73ba)
![MFC_PPT_page-0004](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/447ce293-b972-4f1c-ac96-8d8dc64fae54)
![MFC_PPT_page-0005](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/c1056feb-3d76-478a-9936-4338ead566f5)
![MFC_PPT_page-0006](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/3f3341eb-e45e-4937-b6c6-be29ad7f6a40)
![MFC_PPT_page-0007](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/17ec9c67-4325-482e-bb35-830f35e52ea2)
![MFC_PPT_page-0008](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/47ef952f-8e76-45c6-b2ab-bba649a2f94b)
![MFC_PPT_page-0009](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/154e1011-15f0-4189-b11d-70ac15302c10)
![MFC_PPT_page-0010](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/a4da8c30-06d3-401d-82f7-fc8362bd3729)
![MFC_PPT_page-0011](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/4d6f5629-c842-4a95-a8ca-612e2a6a161c)
![MFC_PPT_page-0012](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/f6c32ab2-dcff-4a37-aebb-0c72aec57039)
![MFC_PPT_page-0013](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/fe6900f7-cb0d-4fa0-99d6-4a971c89c7af)
![MFC_PPT_page-0014](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/34318b4e-6f60-40fd-81a7-194b0cae66ad)
![MFC_PPT_page-0015](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/895cc926-4b40-47df-874b-bceed786e62d)
![MFC_PPT_page-0016](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/56c3e06d-6aeb-4533-a688-b38229768d52)
![MFC_PPT_page-0017](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/7dae26dd-77b4-4851-aa73-ff1fc6a11e5b)
![MFC_PPT_page-0018](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/bb908b46-5a80-4e4d-abae-7f0372d83cfa)
![MFC_PPT_page-0019](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/ac38b175-2da2-4e96-baa9-0502ea9bb499)
![MFC_PPT_page-0020](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/35932bbf-651d-4034-b269-51e2f01d8308)
![MFC_PPT_page-0021](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/8a91b163-087c-466d-9c10-1288a2c3932c)
![MFC_PPT_page-0022](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/c44a288c-b33c-41e7-a93b-535728679372)
![MFC_PPT_page-0023](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/6fb85bed-dbd4-4712-81b5-f9ea59e73e40)
![MFC_PPT_page-0024](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/abf173b2-4eca-4ff6-ba5b-9222acdd74df)
![MFC_PPT_page-0025](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/121df450-9c81-4d0b-b22f-85c34ad73999)
![MFC_PPT_page-0026](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/0fea82cb-2162-4e85-a95a-667365c20c84)
![MFC_PPT_page-0027](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/94db393a-a615-4663-aa88-e1c34ed3e4ab)
![MFC_PPT_page-0028](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/717c405d-0622-4ff1-b4dc-2769bc4f757c)
![MFC_PPT_page-0029](https://github.com/SS-yong/MFC-Optimal-Location-Selection-for-Logistic-Centers/assets/108441950/4a9470ed-84a1-4517-b209-c609dc246eba)
