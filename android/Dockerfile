FROM debian:12

# 安装flutter
RUN apt update && apt install snapd && snap install flutter --classic

RUN yes | flutter doctor --android-licenses \
    && flutter doctor
