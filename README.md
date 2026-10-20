# 2팀 토큰 저장소 (테스트용)

[Token Bridge](https://github.com/chaen1209/token-bridge) 플러그인을 연습하려고 만든 저장소예요. 여기 있는 토큰은 연습용이고, 실제 서비스에 쓰이지 않아요.

1팀 디자이너가 **공용토큰** Figma 파일의 토큰을 1팀 저장소와 이 저장소에 함께 푸시하는 상황을 연습해요.

## 구성

- 토큰 파일: `packages/tokens/tokens.json` (Tokens Studio 형식, 파일 하나)
- 브랜치
  - `main`: 기본 브랜치예요. PR로만 합칠 수 있어요 (승인 0명).
  - `tokens/chaentest`: 공용토큰을 받는 브랜치예요. 플러그인의 "다른 저장소 추가"로 올릴 곳에 넣어요.
- 짝 저장소: [team1-tokens-test](https://github.com/chaen1209/team1-tokens-test) (1팀 저장소, 플러그인을 연결하는 곳)

## 연습 상황

| 상황 | 상태 | 표시(태그) |
| --- | --- | --- |
| 1 | 저장소를 막 만든 상태예요. 토큰 파일이 없어요. | `state-1-empty` |
| 2 | 공용 토큰과 2팀만 쓰는 토큰이 이미 들어 있는 상태예요. | `state-2-filled` (준비 중) |

상황 2에서는 2팀만 쓰는 토큰이 있어요. 공용토큰을 푸시해도 이 토큰들은 그대로 남아야 해요.

상황을 바꾸면 `main`과 `tokens/chaentest`를 그 상태로 되돌려요.
