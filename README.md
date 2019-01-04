# bdpimage guide

1. "CPU" 케이스필요조건 [docker image link](https://cloud.docker.com/u/shcardbdp/repository/docker/shcardbdp/dl-base-cpu)
 - os : Ubuntu 16.04 
 - Shinhancard base util

2. "GPU" 케이스필요조건 [docker image link](https://cloud.docker.com/u/shcardbdp/repository/docker/shcardbdp/dl-base-gpu)
 - Ubuntu 16.04
 - cuda 9.0
 - cudnn 7.0
 - Shinhancard base util

3. 기본이미지는 위의 두 조건에 맞춰 이미지를 다운로드 하여 작업을 진행합니다.

4. 반입시, dockerfile과 image를 같이 반인해야 합니다. (설치한 프로그램들은 버젼이 명시되어야 합니다.)

5. 반입시, 프로그램들은 테스트를 완료하고 반입해야 합니다.

6. 런 코드 뒤 tmp로 만들어지는 공간에 대해 삭제를 하여 image 크기를 줄여야 합니다. (Recommended)

7. 반입시, 사전 담당자를 확인, 연락하여 주의사항에 대하여 문의 부탁드립니다.
