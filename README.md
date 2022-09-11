참고영상 : Kenu Heo - 🚀GitHub으로 시작하는 CI/CD
https://www.youtube.com/watch?v=Np64aq4AlLg

- 개념
  workflows : 작업 뭉치
  events : 작업 뭉치를 동작하게 하는 이벤트 / push, release, pull request 등
  jobs : 동시 수행 가능한 작업 단위
  runners: Job이 실행되는 곳. GitHub이 제공하는 가상 머신(Linux, macOS, Windows)
  steps : 순서대로 실행되는 쉘 커맨드 또는 action
  actions : 재사용할 수 있는 job의 step. 공유된 action은 github marketplace에서 구할 수 있음
