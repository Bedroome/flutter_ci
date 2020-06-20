FROM cirrusci/flutter:latest

ENV PUB_HOSTED_URL=https://pub.flutter-io.cn
ENV FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn

RUN yes | android list sdk

RUN  yes | /home/cirrus/sdks/flutter/bin/flutter doctor
