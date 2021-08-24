# Compose Multiplatform Application

## 参考にした資料
- 公式ドキュメント
  - https://github.com/JetBrains/compose-jb/tree/master/tutorials/Getting_Started
- このプロジェクトは以下をダウンロードして修正してビルドできた
  - https://github.com/JetBrains/compose-jb/tree/master/templates/multiplatform-template

**Desktop**
- `./gradlew run` - run application
- `./gradlew package` - package native distribution into `build/compose/binaries`

<img src=https://user-images.githubusercontent.com/8417910/130621260-243a8930-2863-4bff-8427-b9782f07c063.png  width=60%>

**Android**
- `./gradlew installDebug` - install Android application on an Android device (on a real device or on an emulator)

<img src=https://user-images.githubusercontent.com/8417910/130621409-c63ea668-aadd-421e-b578-d034147fcb99.png  width=30%>