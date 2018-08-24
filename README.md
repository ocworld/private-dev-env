# private-dev-env
개인 개발 환경

# code repository: git
- github private 계정으로 관리
- https://github.com/ocworld/

# ci: jenkins
- docker 기반
- image: jenkins/jenkins:lts
- host: 개인 NAS

# jenkins remote agent 0: macOS, iOS
## build-macos-0
- iMac

## build-macos-1
- MacBook Pro

# jenkins remote agent 1: python 
## build-conda-0
- docker 기반
- host: 개인 NAS
- image: continuumio/anaconda3

## build-conda-1
- docker로 운영 중
- host: iMac
- image: continuumio/anaconda3

# jenkins remote agent 2: scala
## build-sbt-0
- docker 기반
- host: 개인 NAS
- image: centos

# 산출물 개인 저장소: minio
- docker 기반
- host: 개인 NAS
- image: minio/minio

# Publish
## 앱
- 앱스토어

## 라이브러리/패키지
- cocoapods
- pypi
- jar는 미정

