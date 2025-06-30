# JeonBOTdae
Autonomous Robot for Fire Detection in Traditional Markets

## Function
1. 로봇 설계
   - Jetson Orin 및 센서 부착을 위한 주행 로봇 제작
   - 서스펜션 시스템을 통한 주행용 로봇 설계
   - 주행 제어 패키지 설계
2. 자율주행
   - 3D LiDAR 센서를 이용해 SLAM 진행
   - SLAM(fast lio)로 3D mapping
   - 3D map을 만들고 저장 후 이를 topic으로 보내주는 node설계
3. 열감지
   - IR 카메라 어플리케이션 연결
   - 어플을 통한 데이터 추출
   - 특정 온도 이상일 때 경고음을 보내는 node 생성
   - 화재 감지 시 해당 node 활성화
    

   ! 그림

- Hardware : Jetson Orin, IR camera, 3D-LiDAR, Livox Mid 360 전용 커넥터, servo motor & driver, 이온 충전식 배터리팩, 로봇 
- IDE : VScode
- Software : Python, C (qt creator)
- 환경 : Linux Ubuntu 20.08

