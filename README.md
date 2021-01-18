# kor_handwritten_ocr
This repository for korean handwritten ocr

# Tesseract - 보류
"2021/01/05"
1. 환경
- 필기체(한국어)를 인식하기 위한 OCR opensource 및 도구 선택
-  OS  : ubuntu(20.04 focal)
- tool : tesseract(5.0.0 alpha), jTessBoxEditor(for trainning)

2. train handwritten and test
- 로컬서버에서 모델 훈련 및 훈련데이터 수집
- 인식률 30% 미만, 오차율 60% 이상


"2021/01/12"
1. Tesseract는 한글 필기체에 적합하지 않다고 판단
- [.traineddata] 파일 병합이 불가능 혹은 불안정
- 새로운 데이터 훈련에 많은 비용 소모
