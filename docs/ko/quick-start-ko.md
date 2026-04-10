# 빠른 시작 — Sal-Meter Kernel Program

> 이 문서는 한국어 사용자가 **5분 안에 저장소의 성격, 현재 상태, 읽는 순서**를 파악할 수 있도록 만든 빠른 안내 페이지입니다.  
> 정본 권위는 GitHub가 아니라 **DOI 등록 문서 (Zenodo / OSF)** 에 있습니다.

---

## 한 줄 요약

이 저장소는 “이미 열린 공모전 페이지”가 아니라,  
**Sal-Meter 커널이 진짜인지 먼저 증명하려는 연구 관문**입니다.

---

## 이 저장소는 무엇인가

이 저장소는 **Sal-Meter Kernel Program**의 공개 운영 인덱스입니다.

즉, 이곳의 역할은 다음과 같습니다.

- 프로젝트의 현재 상태를 설명
- 핵심 helper 문서로 빠르게 연결
- FAQ와 상태 문서를 통해 오해를 차단
- broader opening 이전 단계에서 구조와 방향을 정리
- GitHub 차원의 운영·안내·조정 기능 수행

이 저장소는 **정본 권위 문서 자체**가 아닙니다.  
정본 권위는 DOI 문서에만 있습니다.

---

## 이 저장소가 아닌 것

이 저장소는 다음이 아닙니다.

- 공개 competition이 이미 열린 공식 참가 페이지
- 의료기기 소개 페이지
- 인증 / compliance 승인 페이지
- 상용화 안내 페이지
- SDK 배포 페이지
- “이미 기술이 증명되었다”는 선언문

즉, 이 저장소는 **홍보용 결과물**이 아니라  
**검증 전 단계의 구조화된 연구 인덱스**입니다.

---

## 현재 상태

현재 프로젝트는 다음 상태로 이해하시면 됩니다.

- **연구 단계 (research-stage)**
- **비진단적 (non-diagnostic)**
- **비치료적 (non-therapeutic)**
- **비임상 의미 (non-clinical in meaning)**
- **broad public competition은 아직 열리지 않음**
- **GitHub는 operational layer**
- **DOI 문서는 authoritative layer**

---

## 지금 진행 방향

프로젝트는 지금 **competition-first**가 아니라 **kernel-first** 방향으로 진행됩니다.

즉,

세상에 넓게 열기 전에  
먼저 내부에서 커널이 실제로 존재하는지, 반복 가능한지, 의미가 있는지를 확인하는 구조입니다.

핵심 흐름은 아래와 같습니다.

1. **External Layer-0**
   - 사전 feasibility 지원 트랙
   - iodine redox + thiol/disulfide 인터페이스의 안정적 신호 창 탐색

2. **Internal Phase 0**
   - G축 상태 분리 가능성 확인
   - baseline, GGI, SOP 고정

3. **Internal Phase 1**
   - I채널 재현성 고정
   - I₃⁻ 타깃 채널 관리 규율 정리

4. **Internal Phase 2a**
   - Twin Mini-Cell 독립성 / 누수 시험

5. **Internal Phase 2b**
   - 사람 파일럿 반복 재현성 검토

6. **Lock 1**
   - 인터페이스가 실제로 존재하는가

7. **Lock 2**
   - 그 인터페이스가 broader opening을 검토할 만큼 의미가 있는가

8. **Broader Opening**
   - 위 조건이 충분히 충족된 후에만 검토

한 줄로 줄이면:

**먼저 커널을 증명하고, 그 다음에만 필드를 연다.**

---

## 지금 외부인이 할 수 있는 일

현재 시점에서 외부인이 할 수 있는 가장 현실적인 일은 다음과 같습니다.

- 저장소 구조 이해
- README 읽기
- FAQ 읽기
- helper 문서로 빠르게 진입
- canonical DOI 문서 확인
- 본인이 기여 가능한 **bounded question**이 있는지 판단
- future broader opening을 대비한 사전 관찰

즉, 지금은  
“당장 참가 신청”보다  
**무엇이 실제로 검증 가능한가를 먼저 파악하는 단계**에 더 가깝습니다.

---

## 먼저 읽는 순서

한국어 사용자가 가장 빠르게 구조를 파악하려면 아래 순서를 권합니다.

### 1단계 — 저장소 성격 파악
1. [`../../README.md`](../../README.md)
2. [`status-ko.md`](./status-ko.md)
3. [`../faq.md`](../faq.md)

### 2단계 — 빠른 진입 문서
4. [`../PI_Quick_Decision_Pack.md`](../PI_Quick_Decision_Pack.md)

### 3단계 — 시스템과 기술 흐름 이해
5. `System Overview`
6. `Technical Snapshot`
7. `Phase / roadmap related docs`

### 4단계 — 최종 권위 경계 확인
8. DOI 등록 canonical documents

질문이 커질수록,  
GitHub 문서보다 DOI 문서로 먼저 내려가야 합니다.

---

## 이 저장소를 보면 좋은 사람

특히 아래와 같은 분들에게 이 저장소가 더 유의미합니다.

- 전기화학 연구자
- 압타머 / 분자 인터페이스 설계자
- 바이오센서 엔지니어
- 신호처리 / 통계 / ML 연구자
- 검증 / 재현성 설계 담당자
- HCI / AI 거버넌스 연구자
- “이것이 반복 가능한가?”를 먼저 묻는 PI급 리더

질문이  
“멋져 보이는가?”가 아니라  
**“검증을 견딜 수 있는가?”** 라면  
이 저장소는 올바른 출발점일 가능성이 높습니다.

---

## 왜 저장소 톤이 엄격한가

이 프로젝트는 일부러 엄격하게 운영됩니다.

그 이유는 다음과 같은 실패를 막기 위해서입니다.

- 개념 드리프트
- 약한 엔지니어링 위의 과장된 서사
- premature commercialization
- naming confusion
- helper 문서와 canonical authority의 혼동
- 측정 이전에 의미를 과장하는 오류

이 엄격함은 프로젝트를 닫기 위한 것이 아니라,  
**커널이 살아남기 위한 장치**입니다.

---

## 영어와 한국어의 역할

이 저장소는 **영문 메인 / 한글 안내 레이어** 구조를 따릅니다.

원칙은 다음과 같습니다.

- 영어는 국제 과학 접근성을 위한 메인 언어
- 한국어는 빠른 이해를 위한 지원 레이어
- GitHub prose는 operational layer
- DOI 문서는 authoritative layer

즉,

- 영문 = 공용 진입면
- 한글 = 안내층
- 정본 = DOI

한국어 문서는 도움이 되지만,  
정본 권위를 따로 형성하지 않습니다.

---

## 지금 기억해야 할 핵심 문장

이 저장소는 승리를 선언하지 않습니다.

이 저장소는 **시험을 선언합니다**.

인터페이스가 이미 증명되었다고 말하지 않습니다.  
대신, **증명의 부담을 구조화했다**고 말합니다.

그것이 진짜 연구의 시작입니다.

---

## 관련 한국어 문서

- [`status-ko.md`](./status-ko.md)
- `faq-ko.md`
- 이 페이지 `quick-start-ko.md`

---

## Canonical Identity

**Origin Architect:** Jinho Lee, MD  
**ORCID:** https://orcid.org/0009-0005-3809-4588

**Affiliation:** Salpida Foundation / Salpida Institute of Consciousness Science (SICS)

**Primary public hub:** https://salpida.foundation

**Repository:** https://github.com/salpida-foundation/sal-meter-kernel-program

**Canonical index layer:** https://github.com/salpida-foundation/salpida-canonical
