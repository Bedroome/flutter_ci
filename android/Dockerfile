FROM mobiledevops/flutter-sdk-image:latest

# ENV PUB_HOSTED_URL=https://pub.flutter-io.cn
# ENV FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn

# RUN yes | android list sdk

RUN yes | flutter doctor --android-licenses \
    && flutter doctor

# RUN yes | flutter doctor --android-licenses
