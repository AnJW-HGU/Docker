# Docker
<br>
* [노마드 코더 - Docker가 왜 좋은지 5분만에 설명해줌](https://youtu.be/chnCcGCTyBg) <br>
<br>
"모든 사람이 배울 필요는 없지만, 대신에 사람들이 docker가 무엇인지 이해해야 한다고 생각한다" <br>
<br>
도커는 environment disparity라는 문제를 해결함 <br>
<br>
Environment disparity 예시 <br>
> 코드를 서버로 올려야하는데 안 올려짐 <br>
> 왜냐하면 코드는 윈도우고 서버는 리눅스니까! <br>
<br>
Docker -> 다른 머신에서도 같은 환경 구현 가능 <br>
<br>
1. 서버와 나의 머신에 Docker 설치 <br>
2. Dockerfile에 구현하고 싶은 환경 설정 <br>
3. Docker는 설정한 해당 환경과 같은 버츄얼 컨테이너를 만들어줌 <br>
4. 잘 작동~! <br>
<br>
Docker Container : 독립적 <br>
그래서 한 서버에 여러개의 각기 다른 컨테이너가 독립적으로 존재 가능 <br>
Docker가 관리 해줌, 트래픽 조정 <br>
<br>
추가적으로 공부하려면 <br>
> 버츄얼 머신, 컨테이너 차이점, swarms, volume <br>
<br>
정리 <br>
> 1. 원하는 개발 환경을 파일에 저장하면, docker는 이를 원하는 어떤 머신이든 해당 환경을 시뮬레이션 해준다 <br>
> 2. 이러한 환경들은 각기 독립적으로 존재하기 때문에 원하는 무슨 환경이든 모듈식으로 관리 가능하다 <br>
<br>
