# 최정요 휴대폰

tvN 드라마 '포핸즈'의 최정요 캐릭터 휴대폰을 열어볼 수 있는 웹페이지입니다.
파일 하나(`index.html`)에 화면·사진·소리가 모두 들어 있어서, 다른 설정 없이 그대로 배포됩니다.

- 잠금 해제 비밀번호 / 힌트 / 알림 문구 / 디데이 등은 `index.html` 위쪽의 `D` 데이터 블록에서 바꿀 수 있습니다.
- 사진·영상·소리는 같은 파일 안에 base64로 들어 있습니다. (파일 크기 약 9MB)

## GitHub Pages로 배포하기

1. GitHub에서 새 저장소(Repository)를 만듭니다. (무료 계정은 **Public**이어야 Pages를 쓸 수 있습니다.)
2. 저장소 화면에서 **Add file → Upload files**로 `index.html`과 `README.md`를 올리고 **Commit changes**를 누릅니다.
3. **Settings → Pages**로 들어가 **Source: Deploy from a branch**, **Branch: main / (root)** 를 고르고 **Save**를 누릅니다.
4. 1~2분 뒤 같은 화면 위쪽에 주소가 나타납니다. 보통 `https://<계정이름>.github.io/<저장소이름>/` 입니다.

## 내용을 바꿀 때

`index.html`을 수정해서 같은 저장소에 다시 올리면(Add file → Upload files, 같은 이름으로 덮어쓰기) 1~2분 뒤 반영됩니다.
