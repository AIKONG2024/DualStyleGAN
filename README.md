## DualStyleGAN 마동석 유니버스 훈련 모델
DualStyleGAN을 fine-tunning해서 얼굴 이미지 마동석화 하는 모델 생성

## 훈련
[설치 문서](https://docs.google.com/document/d/1n1KEwbeBekRbBLZCklwMa0bvlgvy7pfxDPHaJymYaN4/edit?usp=sharing)  
[fine tuning 방법 - DualStyleGAN 참조](https://github.com/williamyang1991/DualStyleGAN?tab=readme-ov-file)

## 추론  

pretained model , data
- data안의 파일 ./data에 넣기 [다운로드](https://drive.google.com/drive/folders/1Zb2nYPsaxiohiie21JSnJ1i_sZIWYGcK?usp=sharing)
- checkpoint안의 파일 ./checkpoint 넣기 [다운로드](https://drive.google.com/drive/folders/1Zb2nYPsaxiohiie21JSnJ1i_sZIWYGcK?usp=sharing)
  
python style_transfer.py --style_id 0 --content path/to/input_image.jpg --align_face --style ma --name ma_transfer

## 결과
![ma_0_test4_overview](https://github.com/AIKONG2024/dual_style_GAN/assets/154941894/bd6cbb15-4f48-4efe-9d7c-9f04bbca5c00)
![ma_0_test5_overview](https://github.com/AIKONG2024/dual_style_GAN/assets/154941894/7742ce22-26a2-420c-b479-9b8eef9b669a)
![ma_0_test6_overview](https://github.com/AIKONG2024/dual_style_GAN/assets/154941894/ca92cc54-c23e-4b2b-842a-c7db035fd336)
![ma_0_test7_overview](https://github.com/AIKONG2024/dual_style_GAN/assets/154941894/f5b6cb26-8b1b-42ff-a458-d14c051bba08)
