# Gimhae_CCTV

외부 데이터셋 종류 및 출처
a. 외부데이터 : 총 1종 (경찰청_경찰관서 위치, 주소 위경도 현황_20210924.xlsx)
b. 출처 : 공공데이터포털
(https://www.data.go.kr/data/15054711/fileData.do?recommendDataYn=Y)
c. 데이터 다운로드 후 구글 스프레드시트 내 지오코딩 응용프로그램을 이용해
주소를 위경도 변환 수행함
2. 실행방법
a. COMPAS 내 Notebook 환경에 위의 외부데이터를 업로드 (파일명 : 
경찰청_경찰관서 위치, 주소 위경도 현황_20210924.xlsx)
b. Model.ipynb 파일을 업로드
c. Model 파일을 열고 Cell -> Run All을 누르고 실행
d. 실행시간 약 10분
e. PPT/PDF 파일 내 각 지수의 그림을 클릭하면 시각화 파일을 열람 가능
3. 시각화 파일 이름
a. cctv 설치 가능 지역 (총 2,174개 Grid) : result_grid_map.html
b. 감시취약지수 : cctv_map.html
c. 범죄발생지수 : call_map.html
d. 풍속업소지수 : business_map.html
e. 유동인구지수 : moving_map.html
f. 부양인구지수 : popu_map.html
g. 외국인위험지수 : foreigner_map.html
h. 건물특성지수 : Building_map.html
i. 아동시설지수 : kid_map.html
j. 공적감시취약지수 : police_map.html
k. 대체감시취약지수 : security_map.html
l. 최종지수 : final_map.html
m. 최종 50개 우선지역 : final_50_map.html
n. 최종 5개 우선지역 : final_5_map.html
