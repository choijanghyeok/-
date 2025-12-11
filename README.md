# ICanStory Website Deployment Guide

이 프로젝트는 React와 Tailwind CSS(CDN 방식)로 제작된 정적 웹사이트입니다. Vercel에 쉽게 배포할 수 있습니다.

## Vercel 배포 방법

### 방법 1: Vercel CLI 사용 (권장)
컴퓨터에 Node.js가 설치되어 있다면 다음 명령어로 바로 배포할 수 있습니다.

1. 터미널에서 프로젝트 폴더로 이동
2. Vercel 로그인 및 배포:
   ```bash
   npx vercel login
   npx vercel
   ```
3. 질문이 나오면 모두 기본값(Enter)으로 진행하면 됩니다.

### 방법 2: GitHub 연동
1. 이 폴더의 파일들을 GitHub 저장소에 푸시합니다.
2. Vercel 대시보드(vercel.com)에서 'Add New Project'를 클릭합니다.
3. GitHub 저장소를 선택하고 'Import'를 클릭합니다.
4. 별도의 설정 없이 'Deploy'를 누르면 완료됩니다.

### 방법 3: 수동 업로드 (Drag & Drop)
1. Vercel 대시보드(vercel.com)에 접속합니다.
2. 'Add New Project'를 클릭합니다.
3. 이 프로젝트 폴더(`아이캔`) 전체를 브라우저 창으로 드래그 앤 드롭합니다.
4. 즉시 배포가 시작됩니다.

## 파일 구조
- `index.html`: 웹사이트의 모든 코드가 포함된 메인 파일
- `vercel.json`: Vercel 배포를 위한 설정 파일

## 문의
배포 중 문제가 발생하면 연락주세요.
