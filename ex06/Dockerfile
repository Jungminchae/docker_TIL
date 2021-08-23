FROM ubuntu:18.04

# directory 없으면 생성임
WORKDIR /html
ADD index.html . 
# ['pwd'] 는 에러가 나네
RUN ["pwd"] 
RUN ls -al

WORKDIR /inside-html
COPY index.html .
RUN ["pwd"]
RUN ls -al
