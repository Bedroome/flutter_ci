FROM hcr.io/cirruslabs/flutter:3.10.6

# 安装flutter
# RUN apt update && apt install snapd && snap install flutter --classic

RUN yes | flutter doctor --android-licenses \
    && flutter doctor
