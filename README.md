# PDF 편집기 — 다운로드

**PDF 편집기** — 가족용 PDF 열람·편집 프로그램 · 문의: jdent0228@gmail.com

PDF 열람/편집 프로그램 설치 파일 배포 페이지입니다. 모든 처리가 내 컴퓨터 안에서만 일어나며, **PDF 파일은 어떤 서버로도 전송되지 않습니다.**

## 다운로드

👉 **[최신 버전 다운로드](https://github.com/jdent0228/pdfedit-releases/releases/latest)**

| 운영체제 | 파일 |
|---|---|
| macOS (Apple Silicon) | `PDF Edit by Dr.J-x.y.z-arm64.dmg` |
| Windows (64비트) | `PDF Edit by Dr.J Setup x.y.z.exe` |

## 설치 방법

**macOS**: dmg를 열고 앱을 응용 프로그램 폴더로 드래그. Apple 개발자 서명이 없는 앱이라 **처음 실행할 때 "손상되었기 때문에 열 수 없습니다" 경고**가 뜹니다 — 실제 손상이 아니라 macOS의 미서명 앱 차단입니다. **터미널을 열고 아래 한 줄을 붙여넣어 실행**하면 해결됩니다 (최초 1회만, 이후 자동 업데이트는 이 절차가 필요 없습니다):

```
xattr -cr "/Applications/PDF Edit by Dr.J.app"
```

**Windows**: Setup.exe 실행(클릭 한 번으로 설치). "Windows의 PC 보호" 창이 뜨면 **추가 정보 → 실행**.

## 기본 PDF 뷰어로 지정

- **macOS**: 아무 PDF 파일 우클릭 → 정보 가져오기 → "다음으로 열기"에서 이 앱 선택 → **모두 변경**
- **Windows**: 설정 → 앱 → 기본 앱 → `.pdf` → 이 앱 선택

## 주요 기능

검색 · 형광펜/밑줄/취소선 · 자유 필기 펜 · 도형 · 텍스트 추가/편집 · 서명 · 페이지 정리(썸네일 드래그/회전/병합/추출/분할) · 목차/북마크 · **문자인식 OCR(한국어+영어, 오프라인)** · 인쇄 · 다중 탭

