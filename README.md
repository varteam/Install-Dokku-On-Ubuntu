#사전 작업
우분투 설치 [https://github.com/varteam/Install-Ubuntu14.04]

도커 설치 [https://github.com/varteam/Install-Docker-On-Ubuntu]

# Install-Dokku-on-ubuntu
도쿠 설치 방법

Dokku 의 깃허브 [https://github.com/progrium/dokku]

설치 관련 DOC Link [http://progrium.viewdocs.io/dokku/installation]

    # This may need to be run twice
    $ wget -qO- https://raw.github.com/progrium/dokku/v0.3.16/bootstrap.sh | sudo DOKKU_TAG=v0.3.16 bash


명령어를 하면... 뭔가 막 된다...
근데 웃긴건...
한번 더 해야 한다. (왠지 모름... 설명에도 두번하라고 써있음)

    $ wget -qO- https://raw.github.com/progrium/dokku/v0.3.16/bootstrap.sh | sudo DOKKU_TAG=v0.3.16 bash


결과 확인

    $ dokku version
    v0.3.16
