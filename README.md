# toon-craft

일본 만화, 한국 웹툰, 영화의 연출 문법과 스토리 작법을 리서치해서 만든 Claude Code 스킬이에요. 인스타툰·웹툰·만화의 시놉시스, 회차 구성, 글콘티, 컷 연출, 블로킹 콘티를 짜고 검토해요.

## 설치
```bash
git clone https://github.com/ywf2661/toon-craft.git ~/.claude/skills/toon-craft
```
Claude Code를 다시 열면 콘티, 연출, 후킹, 반전, 복선 같은 이야기가 나올 때 자동으로 켜져요. `/toon-craft`로 직접 부를 수도 있어요.

작품마다 세계 규칙이나 작가 취향이 다르니, 작품 노트(작품 이름의 스킬이나 프로젝트의 `CLAUDE.md`)를 따로 두고 함께 쓰는 걸 권해요. 이 스킬은 작품 노트가 있으면 먼저 읽어요.

## 구성
| 파일 | 내용 |
|---|---|
| `SKILL.md` | 작업 순서, 핵심 원칙 15개, 출력 형식, 증상 → 원인 → 처방 표 |
| `references/direction.md` | 매체별 호흡, 샷과 앵글, 間, 넘김 설계(めくり), 연출 패턴, 180도 규칙, 영화 편집 기법 |
| `references/story.md` | 기승전결, Save the Cat, 인과 구조, 복선과 반전, SF 설정 규칙, 캐릭터 동기, 절단신공 |
| `references/checklist.md` | 자기검토 체크리스트와 작가 취향 기록 |
| `references/safety.md` | 자살·자해 묘사 가이드 (WHO 2019 기반) |
| `references/sources.md` | 출처 목록 |
