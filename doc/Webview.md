### 1. 프로젝트 생성

먼저, `npx`를 사용하여 TypeScript 기반의 React Native 프로젝트를 생성합니다:

```bash
npx react-native init WebViewExample --template react-native-template-typescript
cd WebViewExample
```

### 2. 웹뷰 라이브러리 설치

프로젝트 디렉토리로 이동한 후, `react-native-webview` 라이브러리를 설치합니다:

```bash
npm install react-native-webview
```

또는 Yarn을 사용하는 경우:

```bash
yarn add react-native-webview
```

### 3. `App.tsx` 수정

이제, `App.tsx` 파일을 열고 웹뷰를 사용하여 간단한 예제를 작성합니다:

```typescript
import React from 'react';
import { SafeAreaView, StyleSheet } from 'react-native';
import { WebView } from 'react-native-webview';

const App = () => {
  return (
    <SafeAreaView style={styles.container}>
      <WebView
        source={{ uri: 'https://www.example.com' }}
        style={{ flex: 1 }}
      />
    </SafeAreaView>
  );
};

const styles = StyleSheet.create({
  container: {
    flex: 1,
  },
});

export default App;
```

### 4. 프로젝트 실행

React Native 프로젝트를 실행합니다. iOS와 Android 환경에 따라 명령어가 다릅니다.

#### iOS

iOS에서 실행하려면 먼저 CocoaPods를 설치하고 `ios` 디렉토리에서 pod install을 실행해야 합니다:

```bash
cd ios
```
```bash
pod install
```
```bash
cd ..
```

```bash
npx react-native run-ios
```

#### Android

Android에서 실행하려면 다음 명령어를 사용합니다:

```bash
npx react-native run-android
```

이제 애플리케이션이 실행되면, 웹뷰를 통해 지정한 URL (`https://www.example.com`)이 표시됩니다.
