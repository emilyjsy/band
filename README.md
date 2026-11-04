# 1/19 공연장 대관 정리

사이트 파일은 `index.html` 하나와 사진을 넣는 `images` 폴더로 되어 있어.

## 깃허브에 올리는 방법 (GitHub Pages)

1. github.com에서 **New repository**를 눌러 새 저장소를 만들어. 이름은 예를 들어 `venue-1-19`로 하고, 공개 범위는 **Public**으로 해. 무료 계정에서는 Public이어야 Pages를 쓸 수 있어.
2. 저장소 화면에서 **Add file → Upload files**를 눌러. 압축을 푼 폴더 안의 `index.html`, `README.md`, `images` 폴더를 한꺼번에 끌어다 놓고 **Commit changes**를 눌러.
3. **Settings → Pages**로 가서 Source를 **Deploy from a branch**로, Branch를 `main` / `(root)`로 고른 다음 **Save**를 눌러.
4. 1~2분 기다리면 `https://아이디.github.io/venue-1-19/` 주소가 생겨.

## 내용 고치는 법

- 가격, 상태, 비고는 `index.html` 안의 `VENUES` 목록만 고치면 돼. 상태 값은 `ok`(가능), `wait`(연락 중), `no`(불가), `ex`(제외) 중 하나로 써.
- 사진을 넣으려면 `images` 폴더에 파일을 올리고, 해당 공연장의 `photo:""` 안에 파일 이름을 적으면 돼.
