# arachaaa.github.io

`arachaaa` 의 **공개 페이지**다. GitHub Pages 로 서비스된다.

> Small tools, made well.

## 왜 저장소가 따로 있나

앱 소스 저장소(`kongduboo/pemvio` 등)는 **PRIVATE 을 유지**하는데,
GitHub Pages 는 무료 플랜에서 **public 저장소에만** 붙는다.
그래서 공개해야 하는 문서만 이 저장소로 분리했다.

**앱 소스는 여기에 두지 않는다.**

## 구조

앱마다 하위 경로를 하나씩 쓴다 — `com.arachaaa.pemvio` · `com.arachaaa.product2` 처럼
maker 하나에 앱이 여러 개 붙는 구조를 그대로 따른다.

```text
pemvio/privacy/index.html    → https://arachaaa.github.io/pemvio/privacy/
pemvio/support/index.html    → https://arachaaa.github.io/pemvio/support/
```

| 페이지 | 쓰이는 곳 |
|---|---|
| `pemvio/privacy/` | App Store Connect 의 **Privacy Policy URL** · 앱 스토어 페이지에 공개 |
| `pemvio/support/` | App Store Connect 의 **Support URL**(필수) · 앱 스토어 페이지의 「앱 지원」 링크 |

## 고칠 때

방침 원문은 **이 저장소에만 있다.** 앱 저장소에는 URL 만 적혀 있다
(같은 글을 두 곳에 두면 한쪽이 낡는다 — `kongduboo/pemvio` 의 `docs/DECISIONS.md` D-016).

내용을 바꾸면 페이지의 **최종 수정일도 함께** 고친다.

## 연락처

arachaaa.support@gmail.com
