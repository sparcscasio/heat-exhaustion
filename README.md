# How to run this project

Flask server (Google colab) : [https://colab.research.google.com/drive/1SE7KX33Yq420xssk9NwnGYXP30T0p7XS?authuser=0#scrollTo=iVP_AWoz-fi-](https://colab.research.google.com/drive/1NhuLvCAjmEO1DIiC2euL5DhqygVSEtUv?usp=sharing#scrollTo=EQKE-GXD46TK)
1) 'data set - data.csv' 업로드
2) 모든 셀 실행하기
3) 마지막 셀 실행 결과로부터 ngrok tunnel 링크 얻기 (https://{id}.ngrok-free.app/ 형식)
4) App.jsx 23번 line 수정 -> "https://{id}.ngrok-free.app/calc"
5) terminal에서 git add . -> git commit -m "new commit" -> git push -u origin main -> npm run deploy
6) https://sparcscasio.github.io/heat-exhaustion/ 재접속
