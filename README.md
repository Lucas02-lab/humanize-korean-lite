# humanize-korean-lite

의미와 수치를 보존하면서 한국어 문장을 자연스럽게 다듬습니다.

## 사용 예

> 다음 문장을 기관에 보내기 좋은 간결한 한국어로 다듬어줘.

## Codex 설치

이 저장소 전체가 하나의 스킬 폴더입니다. 터미널에서 아래 명령을 실행합니다. 같은 이름의 폴더가 이미 있으면 덮어쓰지 않습니다.

```sh
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
git clone https://github.com/Lucas02-lab/humanize-korean-lite.git "${CODEX_HOME:-$HOME/.codex}/skills/humanize-korean-lite"
```

새 Codex 세션에서 `$humanize-korean-lite`을 지정하거나 위 예시처럼 요청합니다. 다른 에이전트의 설치 경로는 해당 제품의 안내를 확인하세요.

## 출처와 시험

[스킬 지침](SKILL.md) · [원본과 변경 내역](ORIGIN.md) · [시험 기록](tests/)

시험 기록의 실행 범위와 미검증 항목을 확인하세요. 재배포와 이용 시 이 폴더의 원본 라이선스를 따릅니다.
