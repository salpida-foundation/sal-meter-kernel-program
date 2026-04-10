# 상태 안내 — Sal-Meter Kernel Program

> 이 문서는 현재 저장소의 상태를 한국어로 빠르게 설명하기 위한 안내 페이지입니다.  
> 정본 권위는 GitHub가 아니라 **DOI 등록 문서 (Zenodo / OSF)** 에 있습니다.

---

## 현재 상태

Sal-Meter 프로젝트는 현재 **broad public competition이 열린 상태가 아닙니다**.

지금 이 저장소는 **Sal-Meter Kernel Program**의 공개 준비 및 운영 인덱스이며,  
핵심 목적은 외부 확장보다 먼저 **커널이 실제로 존재하는지, 반복 가능한지, 의미가 있는지**를 구조적으로 검증하는 데 있습니다.

현재 단계는 다음과 같이 이해하시면 됩니다.

- **연구 단계 (research-stage)**
- **비진단적 (non-diagnostic)**
- **비치료적 (non-therapeutic)**
- **비임상 의미 (non-clinical in meaning)**
- **정본 권위는 DOI 문서에만 존재**
- **GitHub는 운영·안내·조정 레이어**

---

## 지금 무엇이 진행 중인가

현재 프로젝트는 **competition-first**가 아니라 **kernel-first** 순서로 진행됩니다.

즉, 먼저 세상에 넓게 여는 것이 아니라,  
먼저 내부에서 **측정 커널의 존재와 안정성**을 증명한 뒤에야 broader opening을 검토하는 구조입니다.

핵심 흐름은 아래와 같습니다.

1. **External Layer-0**
   - 별도 pre-phase feasibility 지원 트랙
   - iodine redox + thiol/disulfide 인터페이스가 실제로 안정적 신호 창을 만들 수 있는지 탐색

2. **Internal Phase 0**
   - G축 상태 분리 가능성 확인
   - baseline, GGI, SOP 고정

3. **Internal Phase 1**
   - I채널 재현성 고정
   - I₃⁻ 타깃 채널의 반복 가능성과 취급 규율 정리

4. **Internal Phase 2a**
   - Twin Mini-Cell 독립성 / 누수 시험
   - 채널 간 공존 가능성 확인

5. **Internal Phase 2b**
   - 사람 파일럿 반복 재현성 검토
   - G + I 동시 세션의 반복 가능한 커널 구조 확인

6. **Lock 1 — Interface Exists**
   - 인터페이스가 실제로 존재하는가

7. **Lock 2 — Interface Matters**
   - 그 인터페이스가 단지 측정 가능할 뿐 아니라, broader opening을 검토할 만큼 의미가 있는가

8. **Broader Opening**
   - 위 조건이 충분히 충족된 후에만 검토
   - 그 전까지는 조심스럽고 제한된 단계 유지

한 줄로 요약하면 이렇습니다.

**먼저 커널을 증명하고, 그 다음에만 필드를 연다.**

---

## 현재 저장소 업데이트가 뜻하는 것

이 저장소의 업데이트는 보수적으로 읽어야 합니다.

### 저장소 업데이트가 뜻할 수 있는 것

- 문서 정리 및 표현 개선
- helper material 최신화
- governance 경계 보강
- phase 방향 명확화
- bounded technical preparation
- FAQ, status, quick-start 같은 운영 문서 추가
- broader opening 이전의 준비 강화

### 저장소 업데이트가 자동으로 뜻하지 않는 것

- 공개 공모전 시작
- compliance 인정
- certification
- broader external build authorization
- SDK 공개
- 상용화 준비 완료
- 임상 / 의료기기 readiness
- 공식 mark 사용 권한 부여

즉, 저장소가 활발히 움직인다고 해서  
곧바로 “이제 열렸다”거나 “이제 써도 된다”는 뜻은 아닙니다.

---

## 현재 외부인이 할 수 있는 일

현재 시점에서 외부인이 할 수 있는 가장 현실적인 일은 다음과 같습니다.

- README와 FAQ를 통해 구조를 이해하기
- helper 문서를 통해 빠르게 진입하기
- DOI canonical 문서를 통해 authority boundary를 확인하기
- 자신이 기여 가능한 **bounded question**이 있는지 판단하기
- 너무 빨리 “참여 가능 여부”부터 묻기보다, **무엇이 실제로 검증 가능한가**를 먼저 보는 것

즉, 지금은 대규모 참여보다  
**구조를 이해하고, 기술적 질문을 좁히는 단계**에 가깝습니다.

---

## 지금 참여해도 되는가

질문의 핵심에 따라 답이 다릅니다.

### 지금 가능한 것

- 구조 이해
- helper 문서 검토
- canonical 문서 확인
- lab / engineering fit 판단
- bounded technical question 도출
- future broader opening을 대비한 사전 관찰

### 아직 이르다고 봐야 하는 것

- 공개 competition이 이미 열린 것처럼 행동하는 것
- Sal-Meter 명칭을 임의 사용
- compliance / certification을 기정사실화하는 것
- 의료기기 / 임상 의미를 덧씌우는 것
- 상용화 전제의 홍보 문구 작성
- “이미 증명된 기술”처럼 외부 설명하는 것

---

## 이 저장소를 보는 것이 의미 있는 사람

이 저장소는 모든 사람을 위한 곳은 아닙니다.

특히 아래와 같은 분들에게 더 의미가 있습니다.

- 전기화학 연구자
- 압타머 / 분자 인터페이스 설계자
- 바이오센서 엔지니어
- 신호처리 / 통계 / ML 연구자
- 재현성 / 검증 설계 담당자
- HCI / AI 거버넌스 연구자
- “이것이 반복 가능한가?”를 먼저 묻는 PI급 리더

질문이  
“이게 멋져 보이는가?”가 아니라  
**“이게 반복 측정과 검증을 견딜 수 있는가?”** 라면  
이 저장소는 올바른 문일 가능성이 높습니다.

---

## 왜 이렇게 엄격하게 운영하는가

이 프로젝트는 처음부터 넓게 여는 방식보다,  
먼저 구조를 고정하는 방식을 택하고 있습니다.

그 이유는 분명합니다.

너무 빨리 열리는 프로젝트는 종종 다음과 같은 문제를 부릅니다.

- 개념 드리프트
- 약한 엔지니어링 위에 과한 서사
- premature commercialization
- naming confusion
- helper 문서와 canonical authority의 혼동
- 측정 이전에 의미를 과장하는 오류

이 저장소의 엄격함은 폐쇄를 위한 엄격함이 아니라,  
**커널이 살아남기 위한 엄격함**입니다.

---

## 영어와 한국어의 역할

이 저장소는 **영문 메인 / 한글 안내 레이어** 구조를 따릅니다.

원칙은 다음과 같습니다.

- 영어는 국제 과학 접근성을 위한 메인 언어
- 한국어는 환영과 빠른 이해를 위한 지원 레이어
- GitHub prose는 operational layer
- DOI 문서는 authoritative layer

즉,

- 영문 = 공용 진입면
- 한글 = 안내층
- 정본 = DOI

한글 문서는 도움이 되지만,  
정본 권위를 따로 형성하지 않습니다.

---

## 먼저 읽으면 좋은 문서

빠르게 전체 구조를 보려면 다음 순서를 권합니다.

1. **README**
2. **FAQ (`docs/faq.md`)**
3. **PI Quick Decision Pack**
4. **System Overview**
5. **Technical Snapshot**
6. **Canonical DOI documents**

질문이 커질수록,  
GitHub보다 먼저 DOI 문서로 내려가야 합니다.

---

## 현재 상태를 한 줄로 요약하면

이 저장소는 “이미 열린 대회장”이 아닙니다.

이 저장소는  
**열기 전에 커널이 진짜인지 먼저 증명하려는 연구 관문**입니다.

---

## 지금 기억해야 할 가장 중요한 문장

이 저장소는 승리를 선언하지 않습니다.

이 저장소는 **시험을 선언합니다**.

인터페이스가 이미 증명되었다고 말하지 않습니다.  
대신, **증명의 부담을 구조화했다**고 말합니다.

그것이 진짜 연구의 시작입니다.

---

## Canonical Identity

**Origin Architect:** Jinho Lee, MD  
**ORCID:** https://orcid.org/0009-0005-3809-4588

**Affiliation:** Salpida Foundation / Salpida Institute of Consciousness Science (SICS)

**Primary public hub:** https://salpida.foundation

**Repository:** https://github.com/salpida-foundation/sal-meter-kernel-program

**Canonical index layer:** https://github.com/salpida-foundation/salpida-canonical
