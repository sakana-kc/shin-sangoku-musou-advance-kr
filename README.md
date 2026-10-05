# 진·삼국무쌍 어드밴스 한글 패치

GBA 『真・三國無双 Advance』(일본판)를 한국어로 즐길 수 있게 하는 비공식 팬 한글 패치입니다.

> **v0.9 베타** · 대부분의 화면을 확인했지만 엔딩 등 일부는 직접 플레이로 확인하지 못했습니다.

## 다운로드

**[Releases 페이지](https://github.com/sakana-kc/shin-sangoku-musou-advance-kr/releases)** 에서 최신 zip을 받으세요. 
이 저장소에는 패치(.bps)만 있으며 **게임 롬은 포함되어 있지 않습니다.** 롬을 공유하거나 요청하지 마세요.

## 필요한 원본

| 항목 | 값 |
|---|---|
| 게임 | 真・三國無双 Advance (일본판, B36J) |
| 크기 | 16,777,216 바이트 |
| CRC32 | `FE1BE6C1` |
| MD5 | `b4da8d96a5701f91ef8934ee84b8358f` |
| SHA-1 | `677cd51c1ecdde73a6f40ec2cd30d35c77db459a` |
| SHA-256 | `b7be0f80598a37f19ca283f3e4f2525e4bd183c24a455a83af0e6264034e9647` |

RomPatcher.js에 롬을 넣으면 CRC32·MD5·SHA-1이 표시되니 위 표와 비교해 보세요. 미국판(B36E)이나 값이 다른 롬에는 이 패치가 맞지 않습니다.

## 적용 방법

1. [RomPatcher.js](https://www.marcrobledo.com/RomPatcher.js/) 를 엽니다 (Floating IPS도 가능).
2. "ROM file"에 일본판 롬, "Patch file"에 `ShinSangokuMusouAdvance_KR_v0.9beta.bps` 를 넣고 적용합니다.
3. 만들어진 파일의 값이 아래 '패치 후 롬' 표와 같으면 정상입니다.

## 패치 후 롬 (v0.9 베타)

| 항목 | 값 |
|---|---|
| 크기 | 16,777,216 바이트 |
| CRC32 | `7C8AA693` |
| MD5 | `f758abbb0b3f9a6998ca99d1c7d3b408` |
| SHA-1 | `9361c2a3915e4f7c80f926862d29da8c4be868fb` |
| SHA-256 | `eb3fbf6c85f2f157b8abd495cef4e834eb7ec3f2c16bd5f420cb2aa84d460a77` |

패치 파일 `ShinSangokuMusouAdvance_KR_v0.9beta.bps` SHA-256: `ff3994c339c65da6e0d7d0896f658643446bdfca395a8adc9f0510be15999e1c`

## 한글화 범위

- 대사, 용어 사전, 줄거리, 무장 소개 등 게임 내 문장 전체
- 메뉴, 버튼 안내, 확인창, 챌린지 모드
- 스테이지 제목, 세력 지도, 능력치 오각형, 턴 배너, 승리·패배 글자, 조작설명 그림 속 글자

타이틀의 한자 엠블럼(真三國無双)은 원작 분위기를 위해 그대로 두었습니다.

## 오류 제보

글자 잘림, 번역 오류, 멈춤 등을 발견하면 [Issues](../../issues) 에 스크린샷과 어느 장면인지 함께 알려 주세요.

## 사용한 글꼴

모두 SIL Open Font License 1.1 (zip 안 `licenses` 폴더 참고): 갈무리(Galmuri), 도현체(Do Hyeon), 송명(Song Myung).

---

원작: © 2005 KOEI. 이 패치는 비공식 팬 번역이며 원저작사와 관계가 없습니다.
