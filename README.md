# minor7295.github.io

GitHub Pages를 사용한 이력서 사이트입니다.

## 설정

이 프로젝트는 Jekyll과 resume-theme를 사용합니다.

## GitHub Pages 배포

1. 이 저장소를 GitHub에 푸시합니다.
2. GitHub 저장소 설정에서:
   - Settings > Pages로 이동
   - Source를 **"Branch"**로 설정
   - Branch를 `main` 또는 `master`로 선택
3. `main` 또는 `master` 브랜치에 푸시하면 GitHub가 자동으로 Jekyll을 빌드하고 배포합니다.

사이트는 다음 주소에서 확인할 수 있습니다: https://minor7295.github.io

> **참고**: 현재 설정은 "Branch" 방식에 최적화되어 있습니다. GitHub Actions 워크플로우 파일(`.github/workflows/jekyll.yml`)이 있지만, "Branch" 방식을 사용하면 이 파일은 무시됩니다.

## 로컬에서 실행하기

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 http://localhost:4000 으로 접속하세요.