# NX - NX & ASLR

이 프로젝트는 바이너리 분석을 통해 발견한 **NX 우회 후 버퍼 오버플로우(Buffer Overflow)** 취약점을 기반으로 한 익스플로잇 연습 예제입니다.

---


## 파일 구성

- `nx.c`  → 취약한 C 소스코드 (바이너리 분석 대상)                     
- `nx.s`  → 해당 바이너리의 어셈블리 코드   
- `nx.md` → 바이너리 분석 및 리버싱 기반 C 코드 추정, 취약점 분석, 익스플로잇 작성

---

## 참고

- 해당 바이너리는 공개 실습 플랫폼에서 제공된 예제를 기반으로 리버싱 및 분석한 것입니다.
- 문제명 및 flag 등은 포함하지 않았으며, 순수 기술 학습 목적으로 작성되었습니다.