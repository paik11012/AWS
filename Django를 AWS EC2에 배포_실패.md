# Django를 AWS EC2에 배포하기



참고페이지

https://yjucho1.github.io/django/django-deploy-aws/

https://ldgeao99.tistory.com/111

https://wayhome25.github.io/django/2018/03/03/django-deploy-03-ec2/

1. 아마존 로그인
2. IAM( Identity and Access Management ) 서비스 검색
3. 사용자 탭에 사용자 추가
   - 엑세스 유형: 프로그래밍 방식
   - 기존 정책 직접 연결: Amazon EC2 Full Access
   - credential 엑세스키, 비밀엑세스키 저장하기(csv)
4. EC2 서비스 이동

5. 인스턴스 생성
6. putty 접속(pem키 작업 사전에 해야 함)

```shell
sudo lsof -t -i tcp:8000 | xargs kill -9 # 포트 반환
sudo apt-get install zsh 

```

