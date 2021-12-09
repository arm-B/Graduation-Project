# Graduation-Project '멍수무강'
> 이화여자대학교 컴퓨터공학과 2021-2 캡스톤디자인프로젝트A 스타트 28조

### 멍수무강 Project: 펫 CCTV를 통한 반려견 건강 진단 서비스
*멍수무강: 강아지의 만수무강. 즉, 우리의 서비스를 통해 반려견의 건강을 보다 잘 챙겨 반려견이 만수무강할 수 있도록 도울 수 있다는 의미.*

---
### Google Colab을 활용한 YOLOv3 Custom Data 학습 및 객체 분석
+ yolov3.weights 파일: 사전에 YOLO.ipynb를 통해 강아지 사진 300장으로 2000회 학습 진행
  + [yolov3_final.weights / yolov3_2000.weights](https://drive.google.com/drive/folders/1T86ZiV2iG4nGRSR6-sAPZ54CFT00xTBp?usp=sharing)

#### YOLO.ipynb 실행 전 사전작업
1. darknet.zip 파일을 Google Drive 내의 Colab Notebook 안에 넣는다.
    
    ![이미지](https://media.vlpt.us/images/hannah0125/post/376cd8ac-0567-45bd-8e21-216b87e0e5d4/yolo%EC%82%AC%EC%A0%84%EC%84%A4%EC%A0%95.JPG)
2. Google Drive 내 드라이브에 YOLO > backup 폴더를 생성하여 위에서 받았던 가중치 파일인 yolov3.weights 파일을 넣어 준다.
    ![이미지](https://media.vlpt.us/images/hannah0125/post/a1af99f3-56e8-4cad-b33c-439f16a2aa8e/yolo%EC%82%AC%EC%A0%84%EC%84%A4%EC%A0%952.JPG)
    
**Colab에서 YOLO.ipynb를 실행하기 전 GPU를 사용하도록 런타임 유형을 변경해 주어야 한다.**
    ![이미지](https://media.vlpt.us/images/hannah0125/post/7ec95b4c-1969-4fe3-ba3c-ba3541e64325/image.png)
