[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/broadeep/ha-esp)

# Ha-esp 485 (esp-RS485 to HA)

RS485 기반 월패드(홈넷) 신호를 esp 또는 M5stack (atom lite) + tail 485 를 통해서 홈어시스턴트 스마트홈 플랫폼에서 일괄적으로 제어/모니터링할 수 있도록 연결해 주는 통합 브릿지 솔루션입니다.

## 문서 바로가기

https://ha-esp-docs.vercel.app

## 주요 기능 및 지원 모드

- **esp를 통한 기기 직연동 모드 (EspHome)**: 기기 상태를 Home Assistant의 espHome을 통해 자동 등록합니다.
- **실시간 패킷 모니터링**: espHome 웹을 통해 RS485 통신 상태를 모니터링하고 분석에 활용합니다.

## 빠른 요약

- **권장 설치 방법**: Home Assistant Add-on (`espHome Device Builder`)
- **첫 실행 검증**: espHome → M5Stack → 로그에서 패킷 전송 확인

## 개발 관련

- 워크스페이스 빌드: `pnpm build`
- 린트 및 포맷: `pnpm lint`, `pnpm format`
- 테스트: `pnpm test`

## 지원 채널

- [GitHub Issues](https://github.com/broadeep72-cloud/HA-esp/issues)
- [Discord](https://discord.gg/)

## 라이선스

MIT
