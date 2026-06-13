# 🎨 컬러 팔레트 생성기
**AI 오르리 · Color Studio**

색상 하나로 완성하는 조화로운 팔레트 — 두 색의 궁합을 즉시 확인하는 정적 웹 도구

---

## 주요 기능

- **색 궁합 팔레트** — 내가 원하는 색 A + 색 B를 입력하면 어울리는 팔레트 자동 생성
- **한국어 색상명 입력** — 번트시엔나, 밝은 코랄, 광택있는 골드 등 자연어 지원
- **이미지 업로드** — 사진·미드저니 스크린샷에서 주요 색 5개 자동 추출
- **120개 예시 팔레트** — 따뜻한·차가운·자연·모던·레트로·파스텔·금색·은색·형광
- **JSON / CSV 다운로드** + 즐겨찾기 (localStorage)
- **Spline 3D 히어로** — 인터랙티브 3D 씬

## 기술 스택

- 순수 HTML / CSS / JavaScript (빌드 도구 없음)
- Spline Viewer CDN (`@splinetool/viewer`)
- localStorage 기반 데이터 저장

## 로컬 실행

```bash
# Python 3
python -m http.server 3456
# 브라우저에서 http://localhost:3456 열기
```

또는 `index.html` 파일을 브라우저에 직접 드래그

## 배포

Vercel — `index.html` 단일 파일 정적 배포

---

**제작**: 오르리  
**연락**: 010-4712-5597 · is9916@naver.com  
**인스타**: [@duri_um](https://www.instagram.com/duri_um/)  
**카카오**: [채널 바로가기](http://pf.kakao.com/_eDxmrn)
