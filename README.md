# Manito42 API DOCS

[api 주소](https://manito42.github.io/api-docs/)


# API_DOCS

- backend repository에 있는 api-docs.yml을 github page를 통해 배포하는 레포지토리입니다.
- backend repository에서 api-docs.yml의 변화를 감지해 api-docs repository의 download-api-docs를 작동시킵니다.
  - 이 과정에서 **api-docs repository 접근권한을 가진 github persnal access token**이 필요하며 현재는 제 계정에 연결되어있습니다.
- download-api-docs에서 backend repository의 api-docs.yml을 다운로드해 commit/push하여 api-docs를 최신화한 후 github page가 build되게됩니다.



<br>


# swagger

- swagger는 openapi spec에 맞게 작성된 yml/json파일을 뷰어로 생성합니다.  
- 프론트엔드와 백엔드를 연결하는 통로이고, restapi를 지원합니다.
- 웹소켓관련해서는 async-api 등으로 옮겨가야합니다.
