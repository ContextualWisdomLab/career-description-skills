# Career Description Skills

공개 채용 공고와 공식 작성 지침을 참고해 한국어 팀장급 경력기술서를 작성·검토하는 스킬이다. IT·개발·데이터·AI·AX 역할을 우선 다루며, 실제 지원 공고와 제출 양식을 기준으로 적용한다.

## 포함된 스킬

**[write-career-description](skills/write-career-description/SKILL.md)**는 지원 요건에 맞는 프로젝트를 고르고, 책임·판단·행동·성과를 확인된 경력으로 설명한다. 관리자 경력뿐 아니라 기술 리드나 팀장 승진 지원자의 경험도 실제 권한 범위 안에서 작성한다.

```text
$write-career-description 스킬로 이 채용 공고와 경력 자료를 대조해
팀장급 경력기술서를 작성해 줘. 회사 지정 양식을 지키고,
프로젝트별 본인 역할·의사결정·팀 성과가 드러나게 써 줘.
```

## 구성

| 파일 | 용도 |
| --- | --- |
| [스킬 본문](skills/write-career-description/SKILL.md) | 자료 선택과 작성 순서 |
| [채용 조사](skills/write-career-description/references/hiring-research.md) | 공고 6건·공식 작성 지침·출처 수준·확인일·적용 한계 |
| [근거와 수치 처리](skills/write-career-description/references/evidence-and-metrics.md) | 경력 중복, 리딩 권한, 지표·산식·팀 기여 |
| [제출 검수](skills/write-career-description/references/submission-review.md) | 한국어, 지정 양식, DOCX/PDF, 텍스트 추출 |
| [경력 근거표](skills/write-career-description/assets/evidence-ledger.md) | 요건과 경험을 연결하는 작업 양식 |
| [문서 구성](skills/write-career-description/assets/career-description-outline.md) | 자유 양식 작성 시 참고할 구조 |
| [평가 사례](evaluations/cases.md) · [평가 결과](evaluations/results.md) | 합성 경력으로 확인한 동작과 한계 |
| [요구사항과 설계](docs/design.md) | 범위·설계 선택·완료 기준 |

## 사용

Agent Skills를 지원하는 환경의 개인 스킬 경로에 `skills/write-career-description` 폴더 전체를 설치한다. `SKILL.md`와 참조자료를 함께 유지한다. 설치 경로와 활성화 방식은 사용하는 클라이언트의 지침을 따른다. ChatGPT 개인 스킬은 해당 환경의 skill-creator 절차로 설치한다.

입력은 목표 공고, 경력 자료, 제출 양식이 기본이다. 공고가 없으면 목표 역할을 기준으로 범용 초안을 만들 수 있다. 문서 파일을 요청할 때는 해당 환경의 DOCX/PDF 생성 도구를 함께 사용한다.

한국어 편집은 [ContextualWisdomLab/korean-writing-skills](https://github.com/ContextualWisdomLab/korean-writing-skills)의 korean-editing과 함께 사용할 수 있다. 설치되어 있지 않아도 이 스킬의 기본 편집·검수 절차를 적용할 수 있다. 다른 스킬이나 코드를 자동 다운로드·실행하지 않는다.

## 근거 범위

조사 기준일은 **2026-11-08, Asia/Seoul**이다. 공개 채용 공고는 요구사항을 보여 주는 사례다. 실제 합격자의 경력기술서, 채용 성공률 또는 특정 형식의 효과를 입증하는 자료로 취급하지 않는다. 상세 열람 범위와 날짜는 채용 조사 파일에 기록했다.

기간 중복 제거, 역할 구분, 내부 근거표, 문서 구성은 이 저장소의 편집·검증 설계다. 이를 모든 회사의 의무 기준으로 확대하지 않는다. 고정 쪽수·ATS 점수·합격률을 보장하지 않는다.

## 후보자 자료

예시와 평가 입력은 모두 합성 자료다. 실제 이력서, 연락처, 보상, 비공개 프로젝트·고객 자료를 이 저장소에 추가하지 않는다. 문서 작성은 지원서 전송이나 포트폴리오 공개를 포함하지 않는다.
