# infra-subway-deploy-private-infos

## [추가] 설정 별도로 관리하기
* 키, 계정 정보, 접속 URL 등의 설정 정보를 소스코드와 함께 형상관리할 경우 보안 이슈가 발생할 수 있어 따로 관리할 것이 권장됩니다. 보통 Jenkins / Travis CI 등의 배포 서버에 파라미터를 지정하거나, Spring Cloud Config / AWS Service Manager 등의 외부 서비스를 활용하는 방안 등이 활용됩니다. 여기서는 저장소를 분리하여 private repository에서 설정을 관리하도록 합니다.
