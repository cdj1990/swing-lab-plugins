# Swing Lab Pilot — GitHub 설치 검증 패키지

기존 Swing Lab Sites 서버의 등록된 App을 참조하는 Codex 데스크톱용 플러그인입니다. **다른 개인 Plus 계정의 인증 성공은 아직 검증되지 않았습니다.** GitHub 배포가 비공개 App 접근 권한을 부여하지 않습니다.

## 설치

저장소에 접근할 수 있는 사용자의 로컬 Codex CLI에서:

```sh
codex plugin marketplace add cdj1990/swing-lab-plugins
codex plugin add swing-lab-pilot@swing-lab-plugins
```

데스크톱 앱을 재시작한 뒤 새 대화에서 Swing Lab Pilot · GitHub Test를 선택합니다. CLI 설치를 지원하지 않는 버전에서는 마켓플레이스 등록 후 앱의 Plugins에서 Swing Lab Plugins 소스를 선택해 설치합니다.

## 연결 및 검증

1. 본인 ChatGPT 계정으로 https://swing-lab-pilot-1028.regalfrost25.chatgpt.site 에 로그인합니다.
2. 본인 프로필과 채를 만들고 테스트 자료 한 묶음을 업로드한 뒤 해당 스윙의 Codex 접근을 허용합니다.
3. 플러그인을 설치/연결하고 새 대화에서 허용된 요청 목록 조회를 요청합니다.
4. 도구가 보이지 않거나 연결 거절이면 정확한 오류를 확인합니다. 기존 App의 사용자 접근 제한일 수 있습니다. 같은 계정 재로그인을 반복하거나 소유자 연결을 복사하지 마세요.
5. 두 계정이 각각 자기 기록만 조회하고, 외부 기록 ID 요청이 거부되는지 별도로 확인해야 전체 연결 검증이 됩니다.

## 범위와 제한

- 이 저장소는 플러그인 manifest, marketplace, 지침과 자체 아이콘만 포함합니다. 사용자 영상·분석·DB·사이트 소스·인증 비밀은 포함하지 않습니다.
- 기존 App 등록 ID는 공개 설정값이며 인증 수단이 아닙니다. App 사용 권한은 플랫폼이 확인합니다.
- 이 패키지는 공개 디렉터리 심사·게시가 아닙니다. apps/.app.json 참조형 패키지는 현재 공개 디렉터리 제출 형식이 아닙니다.
- 유료 AI API 호출, ChatGPT/Codex 토큰 복사, 로그인 우회, 자동 분석 실행을 추가하지 않습니다. 웹 업로드 후 연결된 대화에서 분석합니다.
- 사이트 접근 설정 및 개인 자료 권한은 변경하지 않습니다.

## 검증 상태

배포 시 패키지 JSON·경로·등록 App 일치 및 로컬 Codex 마켓플레이스 설치 결과를 확인합니다. GitHub 설치 성공과 다른 계정 인증 성공을 구분합니다. 실제 결과는 VALIDATION.md를 참조하세요.

## 업데이트

```sh
codex plugin marketplace upgrade swing-lab-plugins
```

## 공식 문서

- https://developers.openai.com/plugins/build/plugins
- https://learn.chatgpt.com/docs/extend/mcp

로컬/repo marketplace는 지원되는 로컬 클라이언트의 배포 경로입니다. GitHub에서 자동으로 ChatGPT 웹 전체 사용자에게 게시되지는 않습니다.
