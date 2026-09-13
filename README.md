# 데일리잉글리쉬 — 한 문장 더 버튼

[데일리영어](https://github.com/reepower84-png/daily-english)에서 **문장을 한 개 더 받는 한 장짜리 페이지**입니다.

매일 아침 7시에 생활영어 한 문장이 디스코드로 저절로 옵니다.
그 알림에 달린 링크로 들어와 버튼을 누르면, 누른 만큼 한 문장씩 더 옵니다.

- **한 번 누를 때마다 한 문장.** 더 배우고 싶으면 또 누르면 됩니다.
- **상황을 고를 수 있습니다.** 자동 / 인사·안부 / 식당·카페 / 길·교통 … 열여덟 가지.
  자동이면 상황을 한 바퀴씩 번갈아 돌아갑니다.

- 주소: <https://reepower84-png.github.io/daily-english-app/>
- 이 저장소는 공개지만 **비밀은 하나도 없습니다.** 문장 서가·진도·웹후크는 모두
  비공개 저장소 `daily-english` 에 있고, 이 페이지는 브라우저에 저장된 개인 토큰으로
  그 저장소의 발송 워크플로를 실행시킬 뿐입니다.
- 토큰은 이 기기의 `localStorage` 에만 있습니다. 서버로 보내지 않습니다.

## 처음 설정

1. 페이지를 열면 토큰을 물어봅니다.
2. [Fine-grained PAT 발급](https://github.com/settings/personal-access-tokens/new)
   - Repository access: **Only select repositories** → `daily-english`
   - Permissions: **Actions** = Read and write, **Contents** = Read-only
3. 붙여넣고 저장하면 끝. 이후로는 링크만 열면 됩니다.
4. (선택) 브라우저 메뉴 → '홈 화면에 추가' 하면 앱처럼 쓸 수 있습니다.
