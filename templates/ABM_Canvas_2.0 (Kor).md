# ABM Specification Canvas 2.0 (ABM 명세 캔버스 2.0)

---

### 1. Research Question & Purpose (연구 질문 및 목적)
* **설명:** 시뮬레이션을 통해 해결하고자 하는 주된 질문은 무엇입니까? 배경 맥락은 무엇입니까?
* **입력:** > 

---

### 2. Agents & Attributes (에이전트 및 속성)
* **설명:** 등장하는 에이전트의 종류(Breeds)와 각 에이전트가 가지는 고유 변수(Attributes)를 나열하세요. (예: `wolves` have `energy`, `sheep` have `speed`)
* **입력:** > 

---

### 3. Environment & Constraints (환경 및 제약조건)
* **설명:** 월드의 형태(토러스/상자), 그리드 크기(Patch size), 패치(Patch)가 가지는 변수 등을 정의하세요.
* **입력:** > 

---

### 4. Process Overview & Scheduling (실행 순서)
* **설명:** **[매우 중요]** `to go` 프로시저에서 실행되는 정확한 순서를 적어주세요. (예: 1. 이동 -> 2. 섭취 -> 3. 번식 -> 4. 죽음)
* **입력:** > 

---

### 5. Behavioral Rules (행동 규칙)
* **설명:** 개별 에이전트는 어떻게 움직입니까? 어떤 조건에서 의사결정을 내립니까? (이동 로직, 상태 변화 등)
* **입력:** > 

---

### 6. Interaction Rules (상호작용 규칙)
* **설명:** 에이전트가 서로 만났을 때(또는 특정 반경 내에 있을 때) 어떤 일이 발생합니까? (예: 전투, 거래, 감염, 짝짓기)
* **입력:** > 

---

### 7. Initialization (초기화 - Setup)
* **설명:** `to setup` 버튼을 눌렀을 때의 초기 상태입니다. 에이전트는 몇 마리이며, 어디에, 어떤 상태로 배치됩니까?
* **입력:** > 

---

### 8. Parameters (파라미터 - Sliders/Switches)
* **설명:** 인터페이스에서 사용자가 조절할 수 있는 전역 변수와 기본 범위(Range)를 정의하세요. (예: `infection-rate` 0 ~ 100%)
* **입력:** > 

---

### 9. Evaluation Metrics (평가 지표 - Plots/Monitors)
* **설명:** 시뮬레이션 결과로 무엇을 측정합니까? 그래프나 모니터로 보고 싶은 데이터는 무엇입니까?
* **입력:** > 

---

### 10. Experiment Design (실험 설계)
* **설명:** 모델 검증 및 데이터 수집을 위한 시나리오입니다.

**A. Manual Presets (버튼)**
* **설명:** 빠른 테스트를 위한 설정 버튼입니다. (예: "Setup Simple", "Setup High Density")
* **입력:** > 

**B. Automated Experiment (BehaviorSpace)**
* **설명:** XML 생성을 위한 BehaviorSpace 설계입니다. 어떤 변수를 어떤 범위로 변화시키며(Sweep), 결과적으로 무엇을 측정할 것입니까?
* **입력:** >