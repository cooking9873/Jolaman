# 졸라맨 키우기 : 공부의 전사 — Android APK 빌드용

이 프로젝트는 Android Studio 없이 GitHub Actions에서 APK를 자동으로 빌드하도록 준비되어 있습니다.

## 가장 간단한 사용법

1. GitHub에서 새 저장소(repository)를 하나 만듭니다.
2. 이 프로젝트의 파일 전체를 저장소에 업로드합니다.
3. `Actions` 탭으로 들어갑니다.
4. `Build APK` 워크플로를 선택합니다.
5. `Run workflow`를 누릅니다.
6. 빌드가 끝나면 해당 실행 화면의 `Artifacts`에서 `JolamanStudyWarrior-debug-apk`를 다운로드합니다.
7. ZIP 안의 `app-debug.apk`를 휴대폰으로 옮겨 설치합니다.

### 참고
- PC에 Android Studio를 설치할 필요가 없습니다.
- APK 빌드는 GitHub의 서버에서 진행됩니다.
- 이 프로젝트에는 현재 HTML 게임이 앱 내부에 포함되어 있습니다.
- Debug APK이므로 개인 테스트/설치용입니다.
