## 마동석 유니버스 훈련 모델

- data안의 파일 ./data에 넣기 [다운로드](https://drive.google.com/drive/folders/1Zb2nYPsaxiohiie21JSnJ1i_sZIWYGcK?usp=sharing)
- checkpoint안의 파일 ./checkpoint 넣기 [다운로드](https://drive.google.com/drive/folders/1Zb2nYPsaxiohiie21JSnJ1i_sZIWYGcK?usp=sharing)

## 설치
[문서](https://docs.google.com/document/d/1n1KEwbeBekRbBLZCklwMa0bvlgvy7pfxDPHaJymYaN4/edit?usp=sharing)

## 결과
마동석 일론머스크 + cartoon
![madongseok_universe_transfer_0_test4_overview](https://github.com/AIKONG2024/dual_style_GAN/assets/154941894/ad5a1655-f54d-4bcf-b3b5-a15639c65941)

## 추론
python style_transfer.py --style_id 0 --content ./data/content/test5.jpg --align_face --style madongseok_universe --name madongseok_universe_transfer
