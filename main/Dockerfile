# Dockerfile
#이미지명
FROM python:3
#pyhton 컨테이너에서 사용되는 경로: 컨테이너 내에서 실행되는 경로
WORKDIR /usr/src/app

#현재 local 경로에 있는 폴더를 컨테이너 내부로 복사: 현재 디렉토리 파일 -> workdir에서 정의한 경로로 복사
COPY . .

#CMD 파이썬 파일 실행
CMD [ "python", "./main.py" ]