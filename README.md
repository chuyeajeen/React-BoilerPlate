## React BoilerPlate
React, Vite, Typescript 를 기반으로 프로젝트를 빠르게 시작할수 있도록 구성되었습니다. 

### Skill set

- TypeScript
- React
- Vite
- Eslint
- Prettier (airbnb rule)
- pnpm
- nodejs V20.18.3

### 추가 설치 사항
필요에따라 상태관리 패키지, 스타일 패키지, 개발도구 추가하여 사용할 수 있습니다. 

### 개발도구 설정
prettier, eslint Extension 설치 
VS Code(Cursor AI) 사용 시 view → command prompt → 입력창에 > Preferences: Open Workspace Settings (json) 선택 → setting.json에 **주석 제거 후** 옵션 추가


```json lines
{
  //ESLint 작업할 디렉토리 자동 감지
  "eslint.workingDirectories": [{ "mode": "auto" }],
  //저장 시 자동으로 코드 포맷팅 실행
  "editor.formatOnSave": true, 
  //VS Code 기본 포맷터를 prettier 지정
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  //언어별 포맷터 설정
  "[html]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[javascript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[javascriptreact]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[json]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[typescript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[typescriptreact]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  //저장 시 ESLint 코드 수정
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
