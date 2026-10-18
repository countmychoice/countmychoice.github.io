# 터치프리 개인정보처리방침 — GitHub Pages 올리기

`index.html` 한 파일이면 됩니다. 외부 파일 의존성은 Google Fonts뿐이고 나머지는 전부 파일 안에 들어 있습니다.

소요 시간 약 10분, 비용 없음.

---

## 1. GitHub 계정

`countmychoice@gmail.com`으로 새 계정을 만드세요. 기존 계정을 쓰면 다른 저장소·프로필이 같이 노출됩니다.

**가입 직후 이것부터 하세요.** Settings → Emails에서 두 가지를 켭니다.

- ☑ **Keep my email addresses private**
- ☑ **Block command line pushes that expose my email**

커밋에 이메일 주소가 박혀 공개되는 것을 막아 줍니다. 웹에서 파일을 올릴 때도 이 설정이 적용됩니다.

---

## 2. 저장소 만들기

New repository → 아래 중 하나를 고릅니다.

| 저장소 이름 | 완성되는 주소 |
|---|---|
| `touchfree` | `https://<아이디>.github.io/touchfree/` |
| `<아이디>.github.io` | `https://<아이디>.github.io/` |

- **Public**으로 만들어야 합니다 (Private은 Pages가 동작하지 않습니다)
- README 추가 체크는 해제해도 됩니다

> 저장소가 Public이라는 건 **파일 내용**이 공개된다는 뜻입니다. 이 파일에는 공개해도 되는 내용만 들어 있습니다.

---

## 3. 파일 올리기

저장소 화면에서 **Add file → Upload files** → `index.html`을 끌어다 놓고 **Commit changes**.

---

## 4. Pages 켜기

Settings → Pages

- **Source**: Deploy from a branch
- **Branch**: `main` / 폴더 `/ (root)`
- **Save**

1~2분 뒤 같은 화면 위쪽에 주소가 뜹니다. 첫 배포는 조금 더 걸릴 수 있습니다.

---

## 5. 확인

**시크릿 창에 주소를 붙여넣어 로그인 없이 열리는지 확인하세요.** 이게 Google 심사가 보는 화면입니다.

함께 볼 것:

- [ ] 한국어 ↔ English 전환이 동작하는가
- [ ] 폰트가 제대로 적용되는가 (제목이 굵은 고딕체)
- [ ] 휴대폰에서 가로 스크롤이 생기지 않는가
- [ ] §11 문의처에 `countmychoice@gmail.com`이 보이는가

---

## 6. Play Console에 넣기

Play Console → **앱 콘텐츠** → **개인정보처리방침** → 위 주소 입력.

같은 주소를 스토어 등록정보에도 넣어 두면 이용자가 설치 전에 확인할 수 있습니다.

---

## 나중에 수정할 때

저장소에서 `index.html`을 열고 연필 아이콘 → 수정 → Commit. 1분 안에 반영됩니다. 주소는 그대로입니다.

방침을 고칠 때는 두 군데를 같이 바꾸세요.

1. 상단 `시행일` / `Effective`
2. 맨 아래 footer의 날짜 문장

제10조에 **적용 전에 고지**하겠다고 명시해 뒀으므로, 인터넷 권한 추가·광고 도입·대상 앱 추가는 **앱 업데이트 전에** 이 페이지를 먼저 고쳐야 합니다.

---

## 파일 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 완성된 페이지 (한국어 + 영어, 다크 모드 지원, 31KB) |

폰트는 Google Fonts에서 Gothic A1 / IBM Plex Sans KR / IBM Plex Mono를 불러옵니다. 네트워크가 막혀도 시스템 고딕으로 대체되어 읽는 데 지장은 없습니다.
