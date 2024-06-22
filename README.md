이것은 [`@react-native-community/cli`](https://github.com/react-native-community/cli)를 사용하여 부트스트랩된 새로운 [**React Native**](https://reactnative.dev) 프로젝트입니다.

# 시작하기

> **참고**: "새로운 애플리케이션 생성" 단계까지 [React Native - 환경 설정](https://reactnative.dev/docs/environment-setup) 지침을 완료했는지 확인하세요.

## 1단계: Metro 서버 시작하기

먼저, React Native와 함께 제공되는 JavaScript 번들러인 **Metro**를 시작해야 합니다.

React Native 프로젝트의 루트 디렉토리에서 다음 명령어를 실행하여 Metro를 시작합니다:

```bash
# npm 사용 시
npm start

# 또는 Yarn 사용 시
yarn start
```

## 2단계: 애플리케이션 시작하기

Metro Bundler를 별도의 터미널에서 실행시키고 두세요. React Native 프로젝트의 루트 디렉토리에서 새로운 터미널을 열고 다음 명령어를 실행하여 _Android_ 또는 _iOS_ 앱을 시작합니다:

### Android 용

```bash
# npm 사용 시
npm run android

# 또는 Yarn 사용 시
yarn android
```

### iOS 용

```bash
# npm 사용 시
npm run ios

# 또는 Yarn 사용 시
yarn ios
```

모든 설정이 올바르게 되어 있다면, 설정한 에뮬레이터/시뮬레이터에서 곧 새로운 앱을 볼 수 있을 것입니다.

애플리케이션을 실행하는 또 다른 방법은 Android Studio와 Xcode에서 직접 실행하는 것입니다.

## 3단계: 앱 수정하기

이제 앱을 성공적으로 실행했으므로, 앱을 수정해봅시다.

1. 선택한 텍스트 편집기에서 `App.tsx` 파일을 열고 몇몇 줄을 수정합니다.
2. **Android**: <kbd>R</kbd> 키를 두 번 누르거나 **개발자 메뉴**에서 **"Reload"**를 선택합니다 (<kbd>Ctrl</kbd> + <kbd>M</kbd> (Windows 및 Linux) 또는 <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (macOS)). 그러면 변경사항을 확인할 수 있습니다.

   **iOS**: iOS 시뮬레이터에서 <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> 키를 눌러 앱을 리로드하고 변경사항을 확인합니다!

## 축하합니다! :tada:

성공적으로 React Native 앱을 실행하고 수정하였습니다. :partying_face:

### 이제 무엇을 할까요?

- 이 새로운 React Native 코드를 기존 애플리케이션에 추가하려면, [통합 가이드](https://reactnative.dev/docs/integration-with-existing-apps)를 확인하세요.
- React Native에 대해 더 알고 싶다면, [React Native 소개](https://reactnative.dev/docs/getting-started)를 참고하세요.

# 문제 해결

작동하지 않을 경우, [문제 해결](https://reactnative.dev/docs/troubleshooting) 페이지를 참조하세요.

# 더 알아보기

React Native에 대해 더 알아보려면, 다음 리소스를 참고하세요:

- [React Native 웹사이트](https://reactnative.dev) - React Native에 대해 더 알아보기.
- [시작하기](https://reactnative.dev/docs/environment-setup) - React Native 개요 및 환경 설정 방법.
- [기본 학습](https://reactnative.dev/docs/getting-started) - React Native 기본 사항을 안내하는 투어.
- [블로그](https://reactnative.dev/blog) - 최신 공식 React Native 블로그 게시물 읽기.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - React Native 오픈 소스 GitHub 저장소.

---

# 웹뷰 만들기 
- [React Native 웹뷰](./doc/Webview.md) - 웹뷰 만들기 문서.
