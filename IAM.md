# IAM
IAM 은 기본적으로 글로벌 리전이 디폴트로 되어있습니다.

## IAM - 사용자
기본적으로 루트 사용자는 계정에 대한 모든 권한을 가지고 있기 때문에 보안상의 이유로 별도의 사용자를 추가해서 관리를 하는 것이 좋습니다.

> 루트 계정은 모든 권한이 있기 때문에 위험한 계정을 뜻합니다.
그렇기 때문에 루트 계정은 반드시 필요할 때만 사용하는 것을 권장드립니다.

- 사용자 이름 , 사용자 지정 암호, 초기화 체크 비활성화
<img width="1123" alt="스크린샷 2023-07-09 11 31 03" src="https://github.com/Hoonology/aws_study/assets/105037141/6aa92e1d-b78e-4a0e-bcee-562e723a8151">

- 그룹 생성 
<img width="1136" alt="스크린샷 2023-07-09 11 32 09" src="https://github.com/Hoonology/aws_study/assets/105037141/d84d60f0-5dca-46a1-8339-f5157584e1c5">

- 사용자 그룹 - admin - 아래 체크 확인 ( 계정의 관리자 역할 )
<img width="899" alt="스크린샷 2023-07-09 11 33 07" src="https://github.com/Hoonology/aws_study/assets/105037141/e027ef69-6a6b-488d-aa24-6441e389198a">



- AWS의 다양한 리소스에 태그 추가 가능
<img width="1114" alt="스크린샷 2023-07-09 11 36 01" src="https://github.com/Hoonology/aws_study/assets/105037141/b479e624-1241-4fc4-a748-6587e37234dd">

- csv 파일로 다운로드
<img width="1124" alt="스크린샷 2023-07-09 11 39 12" src="https://github.com/Hoonology/aws_study/assets/105037141/f997c4b5-79ed-4812-886f-98dfc81c290e">

- 대시보드에서 AWS 계정 alias를 설정할 수 있다.
<img width="1152" alt="스크린샷 2023-07-09 11 42 29" src="https://github.com/Hoonology/aws_study/assets/105037141/5d043cb8-a031-48ac-a67e-24aa8b72ffd4">

- 위 사진에서 계정 별칭 아래 가려진 URL을 통해 접속을 한다.
  - 꼭, 시크릿 창 혹은 다른 브라우저에서 열어야한다.
  
<img width="1070" alt="스크린샷 2023-07-09 11 47 25" src="https://github.com/Hoonology/aws_study/assets/105037141/b331e11f-48cf-4f13-947e-dd8a7ad06b47">
