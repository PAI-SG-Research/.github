# PAI-SG Research | Physical AI Spider Grid Research Working Group

**Researching, testing, and validating intelligence for systems that perceive, reason, and act in the physical world.**

[한국어 안내](#한국어--pai-sg-research) | [PAI-SG Foundation](https://github.com/PAI-SG-Foundation) | [Statera Research](https://github.com/Statera-Research)

## About PAI-SG Research

PAI-SG Research is the research working group of the **Physical AI Spider Grid (PASG)** initiative. Its mission is to turn questions about physical intelligence into testable hypotheses, reproducible experiments, measurable evidence, and research outputs that can inform implementations and shared technical specifications.

Physical AI brings perception, state estimation, temporal understanding, decision-making, and action into a common operational setting. Research in these areas must account for the physical constraints of sensors, computation, timing, motion, safety, and environmental uncertainty. PAI-SG Research explores these connections while keeping a clear distinction between an experimental result and a production-ready capability.

This organization serves as a public-facing research entry point. Public descriptions, research summaries, and openly approved artifacts may be shared here; internal engineering designs, raw evidence, supplier or cost information, and unpublished work remain outside the public layer unless expressly authorized.

## Research Directions

### Perception and Physical Scene Understanding

Research topics include image and video classification, object detection, semantic, instance and panoptic segmentation, multi-object tracking, pose estimation, depth and 3D perception, and multimodal sensor fusion. The emphasis is not merely on benchmark scores but also on robustness, latency, calibration, temporal consistency, and suitability for embodied operation.

### Temporal Intelligence and World Representation

Physical systems need to represent changes over time. Research may examine video transformers, motion representations, spatiotemporal features, object permanence, scene graphs, physical state estimation, world models, and uncertainty-aware prediction. PASG knowledge-graph and physical-state concepts provide a shared context for relating observations to persistent entities and events.

### Embodied Decision-Making and Learning

Relevant research includes robot learning, imitation learning, reinforcement learning, planning under uncertainty, action-conditioned prediction, navigation, manipulation, and coordination among physical agents. These topics are studied with attention to observable evidence, bounded operating conditions, and practical interfaces to robotic systems.

### Evaluation, Data Integrity, and Generalization

Research should document datasets, splits, baselines, evaluation metrics, failure cases, and reproducibility constraints. Synthetic data and mathematically controlled test cases can help investigate algorithmic integrity and generalization, but they complement rather than replace validation against real-world physical conditions. Claims should be limited to the evidence actually obtained.

### Edge-to-Collective Intelligence

PASG spans physical devices and broader knowledge systems. Research may investigate efficient on-device inference, model compression, distributed learning, privacy-preserving exchange, and the movement of verified results between edge deployments, on-premise systems, and cloud services. Any such design is subject to applicable safety, security, and governance requirements.

## Research Workflow and Evidence

A research contribution should make it possible to understand **what was tested, why it was tested, and what the result does and does not establish**. A useful record typically identifies the research question, hypothesis, method, dataset or test environment, model and code version, evaluation procedure, results, limitations, and references.

Research outputs may include literature reviews, experimental notebooks, baseline implementations, benchmark protocols, datasets or dataset descriptors, model evaluations, reproducibility reports, and proposals for new shared specifications. Publication and reuse depend on licensing, permissions, and the distinction between public and internal source material.

The intended progression is:

**Research question → hypothesis → experiment → evidence → review → reproducible implementation → candidate standard**

This is a conceptual workflow, not a claim that every stage is already implemented or that research results are automatically adopted as standards.

## The Six PAI-SG Working Groups

The Physical AI Spider Grid initiative is organized around six complementary areas. Each group has its own focus and public GitHub organization.

| Working Group | Responsibility | Organization |
| --- | --- | --- |
| **Foundation** | Mission, principles, governance, and stewardship | [PAI-SG-Foundation](https://github.com/PAI-SG-Foundation) |
| **Library** | Organized technical knowledge, references, and publications | [PAI-SG-Library](https://github.com/PAI-SG-Library) |
| **Workshop** | Reproducible implementations, experiments, and practical integration | [PAI-SG-Workshop](https://github.com/PAI-SG-Workshop) |
| **Guild** | Contributor collaboration, domain roles, and evidence-based contributions | [PAI-SG-Guild](https://github.com/PAI-SG-Guild) |
| **Research** | Research hypotheses, experimental validation, and new methods | [PAI-SG-Research](https://github.com/PAI-SG-Research) |
| **Standards** | Shared schemas, interfaces, semantics, and interoperability | [PAI-SG-Standards](https://github.com/PAI-SG-Standards) |

Research informs the Library with reviewed knowledge, works with the Workshop on executable baselines, collaborates through the Guild, and proposes evidence-backed improvements for Standards under the principles established by Foundation.

## Relationship to the Statera Working Groups

The Statera organizations provide the related source-oriented knowledge, research, implementation, collaboration, and standards structure. PAI-SG presents the Physical AI Spider Grid application-facing view. The two should remain linked without treating public-facing summaries as substitutes for controlled source records or exposing non-public material.

| Statera Organization | Link |
| --- | --- |
| Statera Foundation | [Statera-Foundation](https://github.com/Statera-Foundation) |
| Statera Library | [Statera-Library](https://github.com/Statera-Library) |
| Statera Workshop | [Statera-Workshop](https://github.com/Statera-Workshop) |
| Statera Guild | [Statera-Guild](https://github.com/Statera-Guild) |
| **Statera Research** | **[Statera-Research](https://github.com/Statera-Research)** |
| Statera Standards | [Statera-Standards](https://github.com/Statera-Standards) |

Research artifacts should identify their provenance, revision, scope of validation, and applicable access restrictions. Synchronization or publication should be explicit and reviewable rather than assumed.

## Participation and Research Collaboration

Researchers, engineers, educators, and domain specialists may contribute research questions, benchmark proposals, reproducibility studies, implementation findings, and technical reviews through publicly available collaboration channels when established. Participation processes and project-specific contribution rules should be checked in the relevant repositories. A public organization profile does not itself imply that a formal membership, reward, or review program is already operating.

## Contact

**Richard Minsoo Go**  
Head of AI, Hills Robotics  
Statera Working Group

**Personal / Research Contact:**  
[gominsoo888@gmail.com](mailto:gominsoo888@gmail.com)

**Hills Robotics / Business Contact:**  
[minsoo.go@hillslogis.com](mailto:minsoo.go@hillslogis.com)

---

# 한국어 | PAI-SG Research

**물리 세계를 인지하고, 추론하고, 행동하는 지능을 연구·실험·검증하는 Physical AI Spider Grid 연구 워킹그룹입니다.**

## PAI-SG Research 소개

PAI-SG Research는 **Physical AI Spider Grid(PASG)**의 연구 워킹그룹(Research Working Group)입니다. 물리 지능(Physical Intelligence)에 관한 질문을 검증 가능한 연구 가설, 재현 가능한 실험, 측정 가능한 증거, 그리고 구현 및 공통 기술 규격에 활용할 수 있는 연구 결과로 발전시키는 것을 목적으로 합니다.

피지컬 AI(Physical AI)는 인지(Perception), 상태 추정(State Estimation), 시간적 이해(Temporal Understanding), 의사결정(Decision-Making), 행동(Action)을 실제 운영 환경에서 연결합니다. 따라서 센서 특성, 계산 자원, 시간 제약, 동작, 안전, 환경의 불확실성을 함께 고려해야 합니다. PAI-SG Research는 이러한 연결을 연구하면서 **실험 결과와 실제 운용이 검증된 기술을 명확하게 구분**합니다.

이 Organization은 공개 연구 활동의 진입점입니다. 공개가 승인된 연구 개요와 결과물은 공유할 수 있지만, 내부 설계, 원시 검증 자료, 공급업체 및 비용 정보, 미공개 연구 내용은 별도의 승인 없이 공개하지 않습니다.

## 주요 연구 영역

### 인지 및 물리 장면 이해(Perception and Physical Scene Understanding)

이미지·영상 분류(Classification), 객체 감지(Object Detection), 의미·인스턴스·파놉틱 분할(Segmentation), 다중 객체 추적(Multi-Object Tracking), 자세 추정(Pose Estimation), 깊이 및 3차원 인지(3D Perception), 다중 센서 융합(Sensor Fusion) 등을 연구합니다. 단순한 정확도뿐 아니라 강건성, 지연시간, 보정, 시간적 일관성, 실제 로봇 적용 가능성을 함께 평가합니다.

### 시간 지능 및 월드 표현(Temporal Intelligence and World Representation)

물리 시스템은 시간에 따라 변하는 환경을 표현해야 합니다. Video Transformer, 동작 표현(Motion Representation), 시공간 특징(Spatiotemporal Feature), 객체 지속성(Object Permanence), 장면 그래프(Scene Graph), 물리 상태 추정(Physical State Estimation), 월드 모델(World Model), 불확실성을 고려한 예측 등을 연구 대상으로 삼습니다. PASG 지식 그래프와 물리 상태 개념은 관측, 객체, 사건을 연결하는 공통 문맥을 제공합니다.

### 체화된 의사결정과 학습(Embodied Decision-Making and Learning)

로봇 학습(Robot Learning), 모방 학습(Imitation Learning), 강화 학습(Reinforcement Learning), 불확실성 하의 계획(Planning under Uncertainty), 행동 조건부 예측(Action-Conditioned Prediction), 자율주행·이동(Navigation), 조작(Manipulation), 다중 에이전트 협업 등을 다룹니다. 실제 로봇과 연결되는 인터페이스 및 안전한 운용 조건을 함께 고려합니다.

### 평가·데이터 무결성·일반화(Evaluation, Data Integrity and Generalization)

연구에서는 데이터셋, 학습·검증 분할, 기준 모델(Baseline), 평가 지표, 실패 사례, 재현 조건을 기록하는 것을 중요하게 봅니다. 합성 데이터(Synthetic Data)와 수학적으로 통제된 시험 사례는 알고리즘 무결성과 일반화 특성 검증에 도움이 될 수 있지만, 실제 물리 환경 검증을 대체하지는 않습니다. 연구의 주장은 확보된 증거 범위 안에서 제시합니다.

### 엣지 및 집단 지능(Edge-to-Collective Intelligence)

PASG는 개별 물리 장치와 광범위한 지식 시스템을 연결하는 방향을 지향합니다. 엣지 추론(Edge Inference), 모델 경량화(Model Compression), 분산 학습(Distributed Learning), 개인정보를 고려한 정보 교환, 엣지·온프레미스·클라우드 사이의 검증 결과 공유를 연구할 수 있습니다. 모든 설계는 해당 안전·보안·거버넌스 요구사항을 충족해야 합니다.

## 연구 절차와 증거 관리

연구 기여는 **무엇을, 왜, 어떻게 시험했으며 그 결과가 무엇을 입증하고 무엇을 입증하지 못하는지** 이해할 수 있어야 합니다. 연구 기록에는 연구 질문, 가설, 방법, 데이터셋 또는 시험 환경, 모델 및 코드 버전, 평가 절차, 결과, 한계, 참고문헌 등을 포함하는 것이 바람직합니다.

연구 산출물에는 문헌 조사, 실험 노트북, 기준 구현, 벤치마크 절차, 데이터셋 설명, 모델 평가, 재현성 보고서, 공통 규격 제안 등이 포함될 수 있습니다. 공개와 재사용은 라이선스, 접근 권한, 공개 자료와 내부 원본 자료의 구분에 따릅니다.

**연구 질문 → 가설 → 실험 → 증거 → 검토 → 재현 가능한 구현 → 표준 후보**

이는 지향하는 연구 흐름이며, 모든 단계가 이미 운영 중이거나 연구 결과가 자동으로 표준으로 채택된다는 의미는 아닙니다.

## PAI-SG의 6개 Working Group

| 워킹그룹 | 주요 역할 | GitHub |
| --- | --- | --- |
| **Foundation** | 목적, 원칙, 거버넌스 및 운영 방향 | [PAI-SG-Foundation](https://github.com/PAI-SG-Foundation) |
| **Library** | 기술 지식, 참고자료, 출판물의 체계화 | [PAI-SG-Library](https://github.com/PAI-SG-Library) |
| **Workshop** | 재현 가능한 구현, 실험 및 실제 시스템 연동 | [PAI-SG-Workshop](https://github.com/PAI-SG-Workshop) |
| **Guild** | 기여자 협업, 전문 분야별 역할 및 증거 기반 기여 | [PAI-SG-Guild](https://github.com/PAI-SG-Guild) |
| **Research** | 연구 가설, 실험적 검증 및 신규 기술 연구 | [PAI-SG-Research](https://github.com/PAI-SG-Research) |
| **Standards** | 공통 스키마, 인터페이스, 의미 체계 및 상호운용성 | [PAI-SG-Standards](https://github.com/PAI-SG-Standards) |

Research는 검토된 연구 지식을 Library와 연결하고, Workshop과 재현 가능한 기준 구현을 협력하며, Guild를 통해 기여를 조율하고, Foundation의 원칙 아래 Standards에 증거 기반 기술 제안을 전달합니다.

## Statera Working Group과의 관계

Statera는 지식, 연구, 구현, 협업 및 표준의 원본 지향 체계를 제공하며, PAI-SG는 이를 Physical AI Spider Grid의 적용 관점에서 소개합니다. 공개 소개 자료를 통제된 원본 기록과 혼동하지 않고, 비공개 자료를 임의로 복제하지 않는 것을 원칙으로 합니다.

| 대응 조직 | GitHub |
| --- | --- |
| Statera Foundation | [Statera-Foundation](https://github.com/Statera-Foundation) |
| Statera Library | [Statera-Library](https://github.com/Statera-Library) |
| Statera Workshop | [Statera-Workshop](https://github.com/Statera-Workshop) |
| Statera Guild | [Statera-Guild](https://github.com/Statera-Guild) |
| **Statera Research** | **[Statera-Research](https://github.com/Statera-Research)** |
| Statera Standards | [Statera-Standards](https://github.com/Statera-Standards) |

연구 결과물에는 출처(Provenance), 버전(Revision), 검증 범위(Validation Scope), 접근 제한(Access Restriction)을 명확히 기록하는 것이 바람직합니다. 자료 동기화 및 공개는 별도의 검토와 승인에 따라 수행합니다.

## 연구 참여와 협업

연구자, 엔지니어, 교육자 및 분야별 전문가는 공개 협업 채널이 마련된 범위에서 연구 질문, 벤치마크 제안, 재현성 검증, 구현 결과, 기술 검토에 참여할 수 있습니다. 구체적인 참여 방법은 각 Repository의 기여 지침을 확인해야 합니다. 이 소개 페이지 자체가 공식 회원 제도나 보상·심사 프로그램의 운영을 의미하지는 않습니다.

## 연락처(Contact)

**Richard Minsoo Go**  
Head of AI, Hills Robotics  
Statera Working Group

**개인 / 연구 문의(Personal / Research Contact):**  
[gominsoo888@gmail.com](mailto:gominsoo888@gmail.com)

**힐스로보틱스 / 사업 문의(Hills Robotics / Business Contact):**  
[minsoo.go@hillslogis.com](mailto:minsoo.go@hillslogis.com)
