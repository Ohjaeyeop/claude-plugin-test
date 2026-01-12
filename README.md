# claude-plugin-test

Claude Code용 플러그인으로, 프로젝트 분석을 통해 README.md 파일을 자동으로 생성합니다.

## 주요 기능

- `/readme` 커맨드를 통한 README 자동 생성
- 프로젝트 구조 자동 분석
- 다양한 프로젝트 타입 지원 (Node.js, Python, Go 등)

## 설치 방법

Claude Code에서 플러그인을 설치합니다:

```bash
claude plugin marketplace add Ohjaeyeop/claude-plugin-test
```

```bash
claude plugin install readme-plugin@my-plugins
```

## 사용 예시

Claude Code에서 `/readme` 커맨드를 실행하면 현재 프로젝트를 분석하여 README.md 파일을 생성합니다:

```
/readme
```

커맨드 실행 시 다음 작업이 자동으로 수행됩니다:

1. 프로젝트 구조 파악 (타입, 소스 파일, 설정 파일 등)
2. 핵심 파일 분석 (이름, 설명, 의존성, 스크립트 등)
3. README.md 파일 생성

## 프로젝트 구조

```
claude-plugin-test/
├── .claude-plugin/
│   ├── plugin.json       # 플러그인 메타데이터
│   └── marketplace.json  # 마켓플레이스 설정
├── commands/
│   └── readme.md         # /readme 커맨드 정의
└── README.md
```

## 작성자

Ohjaeyeop
