# AI Agent 특강 아카이브

2026년 9월 22일 미래융합연구원 특강의 강의노트와 녹음을 공유하는 정적 웹사이트입니다.

## 폴더 구조

```text
github-pages-ai-agent/
├─ index.html
├─ styles.css
├─ .nojekyll
└─ assets/
   ├─ audio/
   │  └─ ai-agent-lecture-recording.mp3
   ├─ docs/
   │  └─ ai-agent-lecture-notes.pdf
   └─ images/
      └─ lecture-poster.png
```

## GitHub Pages 배포

1. GitHub에서 새 공개 저장소를 만듭니다. 저장소 이름 예시: `ai-agent-lecture`.
2. 이 폴더 안의 파일과 `assets` 폴더를 저장소 최상위에 모두 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**에서 Source를 **Deploy from a branch**로 선택합니다.
5. Branch는 **main**, 폴더는 **/(root)**를 선택하고 **Save**를 누릅니다.
6. 잠시 후 같은 화면에 표시되는 주소로 접속합니다.

주소 형식은 보통 다음과 같습니다.

```text
https://GITHUB-ID.github.io/ai-agent-lecture/
```

## 참고

- 녹음은 GitHub 웹 업로드 한도에 맞도록 약 22MB의 MP3로 최적화했습니다.
- 파일명은 GitHub Pages 주소 호환성을 위해 영문 소문자와 하이픈으로 통일했습니다.
- `index.html`과 `assets` 폴더의 상대경로 구조를 바꾸지 않아야 링크가 정상 작동합니다.
- 사이트를 공개하면 PDF와 녹음도 공개 인터넷에서 접근할 수 있습니다. 공유 권한을 확인한 뒤 배포하세요.
