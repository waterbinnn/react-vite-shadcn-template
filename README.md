# React + Vite + TypeScript 템플릿

React, Vite, TypeScript를 사용하여 프로젝트를 빠르게 시작할 수 있는 템플릿입니다.  
TailwindCSS와 ShadCN/UI를 활용하여 효율적인 스타일링과 컴포넌트 구성을 제공합니다.

---

## 시작하기

### 사전 준비

- [Node.js](https://nodejs.org/) (version 18+ or 20+) 설치가 필요

### 설치 및 설정

1. **저장소 클론**

   ```bash
   git clone https://github.com/waterbinnn/react-vite-shadcn-template.git
   cd react-vite-shadcn-template
   ```

2. **의존성 설치**
   ```bash
   yarn install
   ```

---

## Development

```bash
yarn dev
```

## Build

```bash
yarn build
```

빌드 결과물은 `dist` 디렉토리에 생성됩니다.

## 🗂️ 프로젝트 구조

- `public/`: Contains static files
- `src/`: React 애플리케이션 소스 코드
- `components.json`: ShadCN/UI를 위한 설정 파일. 프로젝트에서 사용할 컴포넌트의 스타일과 구성을 정의하며, ShadCN/UI를 커스터마이징하거나 새로운 컴포넌트를 추가할 때 수정할 수 있습니다.
- `eslint.config.js` :
- `vite.config.ts`: Vite 설정 파일
- `tsconfig.json`: TypeScript 설정 파일
- `package.json`: 프로젝트 의존성과 스크립트 정의
- `commitlint.config.js`: Commitlint 설정 파일. 커밋 메시지 규칙 정의
- `eslint.config.js`: ESLint 설정 파일. 코드 품질을 유지하기 위한 린트 규칙 정의

## 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.
