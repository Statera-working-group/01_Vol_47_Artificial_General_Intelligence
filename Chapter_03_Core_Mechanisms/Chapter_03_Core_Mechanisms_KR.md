**Volume 47. Artificial General Intelligence**

# Chapter 03. Core Mechanisms

## 03.00. Perception System

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

지각(perception)은 지능형 에이전트(intelligent agent)가 원시 감각 신호(raw sensory signal)를 외부 세계와 자신의 내부 상태에 대한 구조화된 표현(structured representation)으로 변환하는 과정이다. AGI에서 지각은 이미지 속 개별 객체를 인식하는 것에만 제한될 수 없다. 추론(reasoning), 예측(prediction), 메모리(memory), 계획(planning), 행동(action)을 지원할 수 있도록 이질적인 관측을 의미 있는 개체(entity), 사건(event), 관계(relation), 공간 구조(spatial structure), 시간적 패턴(temporal pattern)으로 지속적으로 조직해야 한다.

멀티모달 지각(multimodal perception)은 여러 감각 양식(sensory modality)의 정보를 통합함으로써 이러한 과정을 확장한다. 시각(vision)은 외형, 기하 구조(geometry), 움직임, 공간적 맥락(spatial context)을 제공하고, 오디오(audio)는 보이지 않는 사건이나 음원의 존재를 알려줄 수 있다. 언어(language)는 의미적 설명과 지시를 제공하며, 촉각(touch)은 접촉, 질감, 힘, 재질에 관한 정보를 제공한다. 물리적 에이전트(physical agent)는 추가적으로 LiDAR, 레이더(radar), 깊이 카메라(depth camera), 고유수용감각(proprioception), 관성 센서(inertial sensor), 위치 측정 시스템(positioning system)을 활용할 수 있다.

서로 다른 모달리티(modality)는 동일한 환경에 대해 상호 보완적인 관점(complementary view)을 제공한다. 카메라는 접근하는 차량을 식별할 수 있고, 레이더는 거리와 상대 속도를 추정하며, 오디오는 현재 시야(field of view) 밖에 있는 긴급 차량의 사이렌을 감지할 수 있다. 이러한 관측 중 어느 하나만으로는 환경을 완전하게 설명하지 못할 수 있다. 멀티모달 지능(multimodal intelligence)은 상호 보완적인 증거를 하나의 일관된 해석으로 결합하여 개별 감각 채널보다 더 풍부하고 강건한 정보를 생성할 때 나타난다.

멀티모달 지각은 감각 스트림(sensory stream)의 구조가 서로 크게 다르기 때문에 어렵다. 이미지는 공간적으로 구성되고, 오디오 신호는 시간에 따라 빠르게 변화하며, 언어는 이산적인 기호 시퀀스(symbolic sequence)로 구성되고, 고유수용감각 측정값은 에이전트 자신의 상태를 설명한다. 센서마다 주파수, 해상도, 좌표계(coordinate system), 지연시간(latency)도 다를 수 있다. 따라서 범용 지각 아키텍처(general perception architecture)는 이질적인 입력을 의미 있게 비교하고 정렬하며 통합할 수 있는 표현으로 변환해야 한다.

표현학습(representation learning)은 원시적인 모달리티별 신호를 유용한 내부 특징(internal feature)으로 변환하는 메커니즘을 제공한다. 서로 다른 인코더(encoder)는 이미지, 오디오, 언어, 깊이 정보 등의 관측을 관련 구조를 포착하는 잠재 표현(latent representation)으로 변환할 수 있다. 이러한 표현은 모달리티별 정보를 유지하면서 동시에 공유되는 개념(shared concept)을 드러낼 수 있다. 성공적인 멀티모달 학습은 어떤 정보를 모달리티별로 유지하고 어떤 정보를 감각 영역 사이에서 정렬해야 하는지를 결정해야 한다.

정렬(alignment)은 서로 다른 모달리티를 통해 들어오는 정보 사이의 대응관계(correspondence)를 설정한다. 음성으로 표현된 단어는 시각적 장면의 객체와 대응할 수 있고, 촉각 사건은 눈으로 확인되는 접촉과 동시에 발생할 수 있으며, LiDAR 클러스터(cluster)는 동일한 물리적 객체를 나타내는 이미지 영역과 대응할 수 있다. 정렬은 공간적, 시간적, 의미적 또는 이러한 차원들의 조합으로 이루어질 수 있다. 서로 다른 센서의 정보를 의미 있게 융합하려면 먼저 신뢰할 수 있는 대응관계가 확립되어야 한다.

시간 동기화(temporal synchronization)는 체화 지능(embodied intelligence)에서 특히 중요하다. 센서는 서로 다른 샘플링 속도(sampling rate)로 작동하고 서로 다른 처리 지연(processing delay)을 가질 수 있다. 서로 다른 순간을 나타내는 관측을 동시에 발생한 것처럼 융합하면 생성된 세계 표현(world representation)이 기하학적 또는 동역학적으로 불일치할 수 있다. 따라서 시간 동기화, 타임스탬프 관리(timestamp management), 운동 보상(motion compensation), 시간적 연관(temporal association)은 빠르게 변화하는 환경에서 멀티모달 지각을 구현하기 위한 중요한 기반이다.

공간 보정(spatial calibration)은 또 다른 필수적인 정렬 방법이다. 서로 다른 물리적 위치에 장착된 센서는 각각 다른 좌표 프레임(coordinate frame)에서 환경을 관측한다. 따라서 측정값을 공통된 기하학적 표현으로 변환하려면 센서 사이의 상대 변환(relative transformation)을 알고 있거나 추정할 수 있어야 한다. 카메라 보정(camera calibration), LiDAR-카메라 보정, 레이더 정렬, 센서·로봇·세계 좌표계 사이의 변환은 물리적으로 분리된 센서들의 관측이 동일한 위치를 일관되게 표현할 수 있도록 한다.

융합(fusion)은 정렬된 멀티모달 정보를 어떻게 결합할 것인지를 결정한다. 초기 융합(early fusion)은 비교적 낮은 수준의 특징을 통합하여 처리 초기부터 모달리티 사이의 상호작용을 학습한다. 후기 융합(late fusion)은 모달리티별 시스템이 독립적으로 생성한 높은 수준의 예측이나 결정을 결합한다. 중간 융합(intermediate fusion)은 이 두 방식의 중간 단계에서 선택된 처리 계층의 잠재 특징을 교환한다. 적절한 전략은 센서 특성, 과제 요구사항, 계산 자원, 강건성 요구조건에 따라 달라진다.

어텐션 메커니즘(attention mechanism)은 멀티모달 융합을 위한 유연한 방법을 제공한다. 교차 어텐션(cross-attention)을 이용하면 시각 특징이 관련 언어 정보를 선택하거나, 언어 토큰(language token)이 이미지 영역에 주의를 기울이거나, 하나의 센서 스트림이 다른 센서에서 유용한 특징을 검색할 수 있다. 모든 정보를 동일하게 결합하는 대신 어텐션은 상황에 따라 관측의 중요도를 다르게 할당한다. 센서 수와 멀티모달 데이터의 양이 증가할수록 이러한 선택적 정보 처리는 더욱 중요해진다.

공유 잠재 공간(shared latent space)은 서로 관련된 관측을 가까운 내부 표현으로 매핑하여 교차 모달 이해(cross-modal understanding)를 지원할 수 있다. 객체 이미지, 해당 객체의 텍스트 설명, 그리고 관련된 소리는 서로 다른 모달리티에서 생성되더라도 공통된 의미 구조(semantic structure)를 공유할 수 있다. 이러한 표현은 교차 모달 검색(cross-modal retrieval), 그라운딩(grounding), 전이(transfer), 추론을 가능하게 한다. 그러나 각 모달리티에는 고유한 정보가 존재하므로 표현의 유사성을 얻기 위해 모든 정보를 완전히 정렬하는 것이 항상 바람직한 것은 아니다.

그라운딩은 추상적 표현(abstract representation)을 지각 경험(perceptual experience)에 연결한다. "문 옆에 있는 빨간색 컨테이너"와 같은 언어 표현은 관련된 개념을 현재 환경의 실제 개체 및 관계와 연결할 수 있을 때 체화 에이전트에게 유용해진다. 따라서 멀티모달 그라운딩(multimodal grounding)은 단어, 시각 영역, 공간적 관계, 행동, 감각적 결과를 연결한다. AGI에서 그라운딩은 기호적 또는 언어적 지식을 의사결정이 실제로 수행되어야 하는 지속적으로 변화하는 물리적 세계와 연결하는 데 도움을 준다.

객체 중심 지각(object-centric perception)은 감각 입력을 구분되지 않은 하나의 스트림으로 처리하는 대신 지속적으로 존재하는 개체를 중심으로 관측을 조직한다. 하나의 객체는 시간의 흐름에 따라 시각적 외형, 기하 구조, 움직임, 의미적 정체성(semantic identity), 촉각적 속성, 상호작용 이력(interaction history)을 축적할 수 있다. 이러한 표현은 객체 영속성(object permanence)을 지원하고 객체가 일시적으로 가려지더라도 이에 대한 추론을 가능하게 한다. 따라서 객체 중심 멀티모달 모델은 메모리, 인과 추론(causal reasoning), 조작(manipulation), 계획을 위한 유용한 구성요소를 제공할 수 있다.

장면 수준 지각(scene-level perception)은 개별 객체를 넘어 객체 사이의 관계와 환경적 맥락(environmental context)을 표현한다. 지능형 에이전트는 하나의 객체가 다른 객체 내부에 있거나, 사람이 출입구에 접근하고 있거나, 장애물이 계획된 경로를 막고 있다는 사실을 이해해야 할 수 있다. 장면 그래프(scene graph), 공간 지도(spatial map), 의미 지도(semantic map), 구조화된 잠재 표현(structured latent representation)은 이러한 관계를 인코딩할 수 있다. 멀티모달 증거는 기하학적, 의미적, 동적, 맥락적 정보를 결합하여 이러한 구조를 더욱 풍부하게 만들 수 있다.

시간적 지각(temporal perception)은 서로 분리된 관측을 사건과 과정으로 변환한다. 지능은 무엇이 존재하는지를 이해하는 것뿐만 아니라 무엇이 일어나고 있으며 상황이 어떻게 변화하고 있는지도 이해해야 한다. 추적(tracking), 운동 추정(motion estimation), 사건 인식(event recognition), 시간적 분할(temporal segmentation), 시퀀스 모델링(sequence modeling)은 시간에 따라 관측을 연결하는 데 도움을 준다. 멀티모달 시스템은 시각적 움직임, 소리, 언어, 고유수용감각 피드백을 결합하여 하나의 순간적인 관측만으로는 모호한 사건을 추론할 수 있다.

멀티모달 지각은 부분 관측 가능성(partial observability) 아래에서 상태 추정(state estimation)도 지원한다. 어떠한 센서도 세계의 모든 관련 속성을 지속적으로 관측할 수 없으며, 객체는 장애물 뒤에 가려지거나 시야 밖으로 이동할 수 있다. 따라서 에이전트는 현재 관측을 메모리 및 예측과 결합하여 숨겨진 상태(hidden state)를 추정해야 한다. 순환 모델(recurrent model), 필터링 방법(filtering method), 믿음 표현(belief representation), 월드 모델(world model)은 현재 직접 관측할 수 없는 환경 요소에 대한 가설을 유지할 수 있다.

서로 다른 모달리티는 잡음이 있거나 모호하거나 서로 모순될 수 있으므로 불확실성(uncertainty)은 필수적으로 고려되어야 한다. 지각 시스템은 모든 측정값을 동일하게 신뢰해서는 안 된다. 센서 불확실성(sensor uncertainty), 환경 조건, 모델 신뢰도(model confidence), 모달리티 사이의 불일치(disagreement)는 증거에 부여되는 가중치에 영향을 줄 수 있다. 확률적 융합(probabilistic fusion)과 불확실성 인식 표현(uncertainty-aware representation)을 이용하면 증거가 부족할 때 잠재적으로 잘못된 하나의 해석을 성급하게 선택하는 대신 여러 가설을 유지할 수 있다.

센서 중복성(sensor redundancy)은 여러 모달리티가 중첩되는 정보를 제공할 때 강건성(robustness)을 향상시킨다. 시각은 어둠이나 안개에서 성능이 저하될 수 있지만 레이더나 LiDAR는 계속 유용한 기하학적 측정값을 제공할 수 있다. 오디오는 시각 정보가 가려졌을 때 단서를 제공할 수 있고, 외부 센싱이 불안정해져도 고유수용감각은 계속 사용할 수 있다. 높은 능력을 가진 멀티모달 아키텍처는 모든 모달리티가 항상 동일하게 유용하다고 가정하는 대신 상황에 따라 중복 정보를 동적으로 활용해야 한다.

누락된 모달리티(missing modality)는 중요한 일반화 문제(generalization challenge)를 만든다. 고정된 센서 조합으로 학습한 시스템은 하나의 스트림이 사용할 수 없게 되거나 손상되거나 지연되거나 교체될 경우 실패할 수 있다. 따라서 강건한 멀티모달 지각은 모달리티 드롭아웃(modality dropout), 중복 표현(redundant representation), 조건부 계산(conditional computation), 가변적인 센서 부분집합(sensor subset)으로도 작동할 수 있는 모델로부터 이점을 얻는다. AGI는 예상했던 입력 하나가 사라졌다는 이유만으로 전체 기능이 붕괴하는 대신 점진적으로 성능이 저하되어야 한다.

능동 지각(active perception)은 지각 과정에 행동을 추가한다. 지능형 에이전트는 관측을 수동적으로 받아들이는 존재일 필요가 없다. 카메라를 움직이거나, 시점을 변경하거나, 객체에 접근하거나, 표면을 만지거나, 질문을 하거나, 자신의 위치를 변경하여 불확실성을 감소시킬 수 있다. 따라서 지각과 행동은 피드백 루프(feedback loop)를 형성하며, 에이전트는 환경을 이해하고 현재 목표를 달성하는 데 예상되는 가치에 따라 어떤 관측을 획득할 것인지를 선택할 수 있다.

멀티모달 지각은 감각 관측이 현실 자체에 대한 완전한 설명이 아니라 기반 상태(underlying state)에 대한 증거라는 점에서 월드 모델링(world modeling)과 밀접하게 연결된다. 월드 모델은 여러 모달리티와 시간에 걸친 정보를 지속적인 잠재 상태(persistent latent state)로 통합하고, 해당 상태가 어떻게 변화할지를 예측하며, 미래 관측에 대한 기대를 생성할 수 있다. 이후 예측 오차(prediction error)는 예상하지 못한 사건, 센서 고장, 환경 변화 또는 기존 내부 모델(internal model)의 한계를 나타낼 수 있다.

대규모 멀티모달 모델(large multimodal model)은 이미지, 언어, 오디오, 비디오 등의 대규모 데이터 사이의 대응관계를 학습함으로써 지각 능력을 확장한다. 이러한 모델은 광범위한 의미 표현(semantic representation)을 제공하고 모달리티 사이에서 지식을 전이하여 언어 지식이 시각적 해석을 지원하거나 시각적 경험이 언어를 현실에 그라운딩하도록 할 수 있다. 그러나 광범위한 의미적 능력만으로 정확한 물리적 지각이 보장되는 것은 아니며, 특히 정밀한 기하 구조, 시간 동기화, 불확실성, 실제 세계와의 상호작용이 요구될 때는 추가적인 메커니즘이 필요하다.

체화 AGI(embodied AGI)는 멀티모달 지각에 특히 까다로운 요구사항을 부과한다. 시스템은 지연시간, 에너지, 메모리, 계산량에 대한 엄격한 제약 아래에서 높은 대역폭의 감각 스트림(high-bandwidth sensory stream)을 행동 가능한 표현(actionable representation)으로 변환해야 한다. 지각은 제어(control)를 수행할 만큼 충분히 빠르면서도 상위 수준의 추론에 필요한 의미적·기하학적 정보를 보존해야 한다. 계층적 처리(hierarchical processing)는 빠른 국소적 반응과 상대적으로 느리지만 풍부한 해석 및 숙고(deliberation)를 분리함으로써 이러한 요구를 충족하는 데 도움을 줄 수 있다.

궁극적으로 멀티모달 지각(multimodal perception)은 지능형 에이전트와 이해해야 할 세계 사이의 인터페이스(interface)를 제공한다. 그 목적은 단순히 여러 센서를 결합하는 것이 아니라 이질적인 증거로부터 일관되고 지속적이며 불확실성을 인식하는 표현을 구축하는 데 있다. 정렬, 융합, 그라운딩, 시간적 추론, 객체 구조, 메모리, 능동 센싱(active sensing), 월드 모델을 통합함으로써 AGI는 단편적인 관측을 예측, 추론, 계획, 지능적 행동을 위한 통합된 지각적 기반(unified perceptual foundation)으로 변환할 수 있다.

## 03.01. Memory Systems

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

메모리 시스템(memory system)은 지능형 에이전트(intelligent agent)가 정보가 지각된 순간을 넘어 유용한 정보를 보존해야 한다는 점에서 일반지능(general intelligence)의 근본적인 요소이다. 메모리가 없다면 모든 관측은 처리된 직후 사라지고 각각의 상황은 사실상 처음부터 다시 시작해야 한다. 따라서 AGI의 메모리 아키텍처(memory architecture)는 여러 시간 규모(timescale)에 걸쳐 경험을 유지하고, 필요할 때 관련 지식을 검색하며, 저장된 정보를 갱신하고, 예측(prediction), 추론(reasoning), 계획(planning), 행동(action)에 더 이상 기여하지 않는 정보를 선택적으로 잊을 수 있어야 한다.

단기 메모리(short-term memory)는 즉각적인 인지(cognition)와 진행 중인 상호작용에 필요한 정보를 유지한다. 여기에는 최근 관측, 현재 목표, 중간 추론 상태(intermediate reasoning state), 활성화된 지시사항, 객체 위치, 아직 해결되지 않은 사건 등이 포함될 수 있다. 모든 입력 신호를 유지하면 과도한 계산 자원을 소비하고 불필요한 정보가 축적되므로 단기 메모리의 용량은 제한적이어야 한다. 따라서 단기 메모리는 현재 유용한 정보를 접근 가능한 상태로 유지하면서 관련성이 낮은 세부정보를 빠르게 소멸시키거나 교체하는 동적 작업공간(dynamic workspace)의 역할을 한다.

작업 메모리(working memory)는 단기 메모리의 능동적인 계산 구성요소(active computational component)로 이해할 수 있다. 단순히 최근 정보를 저장하는 것이 아니라 추론과 의사결정 과정에서 현재 조작되고 있는 표현(representation)을 유지한다. 예를 들어 내비게이션 문제를 해결하는 에이전트는 목적지, 주변 장애물, 후보 경로(candidate route), 최근 이동 이력을 일시적으로 보존할 수 있다. 작업 메모리는 과제와 관련된 상태를 여러 계산 단계에 걸쳐 유지함으로써 지각(perception)과 추론을 연결한다.

단기 메모리의 내용은 어텐션(attention)과 관련성(relevance)에 의해 제어되어야 한다. 높은 우선순위를 가진 관측, 예상하지 못한 사건, 현재 목표, 활성화된 계획에 필요한 정보는 반복적이거나 예측 가능한 신호보다 더 오랫동안 유지되어야 한다. 이러한 선택적 메커니즘(selective mechanism)은 메모리 작업공간이 중복된 감각 정보로 포화되는 것을 방지한다. 체화 AGI(embodied AGI)에서는 카메라, LiDAR, 오디오, 고유수용감각(proprioception) 등의 연속적인 센서가 직접 저장할 수 있는 양보다 훨씬 많은 정보를 생성하므로 이러한 우선순위화가 특히 중요하다.

장기 메모리(long-term memory)는 즉각적인 상호작용을 넘어 정보를 보존하며 장기간의 경험을 통해 지식이 축적될 수 있도록 한다. 여기에는 의미 지식(semantic knowledge), 학습된 기술(skill), 환경 모델(environmental model), 이전의 에피소드(episode), 사용자별 맥락(user-specific context), 성공한 계획, 실패 경험, 추상적 개념(abstract concept) 등이 포함될 수 있다. 단기 메모리와 달리 장기 메모리는 몇 시간, 며칠 또는 훨씬 이후에 발생할 수 있는 미래 상황을 지원하도록 설계되며, 지능형 에이전트가 동일한 지식을 반복해서 다시 발견하지 않고 과거 경험을 활용할 수 있도록 한다.

에피소드 메모리(episodic memory)는 시간과 맥락 속에서 발생한 특정 경험을 표현한다. 하나의 에피소드는 에이전트가 어디에 있었는지, 무엇을 관측했는지, 어떤 행동을 수행했는지, 그리고 이후 어떤 결과가 발생했는지를 설명할 수 있다. 이러한 메모리는 이전 사건에 관한 질문을 지원하고 미래 추론을 위한 사례를 제공한다. 자율 로봇(autonomous robot)에서는 어려운 지형과의 조우, 내비게이션 실패, 비정상적인 객체, 성공적인 복구 행동(recovery action) 등을 보존하여 이후 유사한 상황에서 행동을 결정하는 데 활용할 수 있다.

의미 메모리(semantic memory)는 하나의 특정 에피소드에 종속되지 않는 일반화된 지식(generalized knowledge)을 표현한다. 반복된 경험을 통해 지속적으로 나타나는 사실, 개념, 관계, 규칙성을 발견하면 처음 학습된 구체적인 상황과 독립적인 지식으로 만들 수 있다. 문이 공간과 공간을 연결한다는 사실, 배터리가 작동 중에 충전량을 잃는다는 사실, 특정 객체가 특정 기능을 지원한다는 지식 등을 의미적으로 표현할 수 있다. 이를 통해 경험은 서로 분리된 기록에서 재사용 가능한 지식(reusable knowledge)으로 변환된다.

절차 메모리(procedural memory)는 행동과 기술을 어떻게 수행하는지에 관한 지식을 저장한다. 모든 제어 단계를 상세한 언어적 설명으로 기억하는 대신 에이전트는 적절한 상황에서 실행할 수 있는 정책(policy), 행동 시퀀스(action sequence), 운동 프리미티브(motor primitive), 계획 절차(planning procedure), 학습된 제어기(learned controller)를 보존할 수 있다. 절차 메모리는 높은 능력의 행동이 세계에 관한 사실을 아는 것뿐만 아니라 세계와 효율적으로 상호작용하는 방법을 유지하는 데에도 의존한다는 점에서 체화 지능(embodied intelligence)에 특히 중요하다.

메모리 통합(memory consolidation)은 단기 메모리와 장기 메모리를 연결한다. 모든 일시적인 관측을 영구적으로 저장할 필요는 없으므로 시스템은 어떤 경험이 장기적인 가치를 가지는지를 판단해야 한다. 새로운 사건, 반복적으로 나타나는 패턴, 중요한 결과, 실패, 높은 보상을 제공한 경험, 현재 목표와 강하게 연결된 정보는 더 높은 통합 우선순위(consolidation priority)를 받을 수 있다. 통합 과정은 상세한 에피소드를 압축된 의미 지식으로 변환하여 저장 공간을 줄이면서 재사용 가능한 구조를 보존할 수도 있다.

망각(forgetting)은 단순히 메모리의 결함이 아니라 중요한 계산 메커니즘(computational mechanism)이다. 모든 정보를 무제한으로 유지하면 저장 비용이 증가하고 관련성이 낮은 경험이 축적되면서 검색이 점점 어려워질 수 있다. 따라서 메모리 시스템에는 감쇠(decay), 삭제(deletion), 압축(compression), 요약(summarization), 교체(replacement)를 위한 정책이 필요하다. 반복적이거나 오래되었거나 신뢰성이 낮거나 관련성이 약한 정보는 제거하거나 축소할 수 있으며, 드물지만 중요한 경험은 훨씬 오랫동안 보존할 수 있다.

검색(retrieval)은 저장된 정보 중 어떤 정보가 현재 인지 과정에서 다시 사용될 것인지를 결정한다. 유용한 메모리 시스템은 새로운 상황을 만날 때마다 저장된 모든 기록을 완전하게 탐색할 수 없다. 대신 의미적 유사성(semantic similarity), 시간적 맥락(temporal context), 공간적 맥락(spatial context), 개체(entity), 목표, 인과관계(causal relationship), 학습된 관련성 함수(learned relevance function)를 사용할 수 있다. 목표는 현재 입력과 단순히 비슷한 메모리를 찾는 것이 아니라 현재의 의사결정이나 추론을 실제로 향상시킬 수 있는 정보를 검색하는 것이다.

현대 AI 시스템은 장기 메모리를 구현하기 위해 벡터 표현(vector representation)과 유사도 검색(similarity search)을 자주 사용한다. 텍스트, 이미지, 사건 또는 구조화된 기록을 임베딩(embedding)으로 인코딩하여 벡터 데이터베이스(vector database)나 관련 검색 구조에 저장할 수 있다. 현재 질의(query) 역시 동일한 표현 공간으로 인코딩하여 가까운 메모리를 효율적으로 식별할 수 있다. 이러한 메커니즘은 검색 증강 생성(retrieval-augmented generation)과 에이전트 메모리(agent memory)를 위한 실용적인 기반을 제공하지만 의미적 유사성만으로 해당 정보의 유용성이 보장되는 것은 아니다.

구조화된 메모리(structured memory)는 개체, 관계, 타임스탬프(timestamp), 위치, 신뢰도(confidence), 인과적 연결(causal link)을 명시적으로 저장함으로써 벡터 검색을 보완할 수 있다. 지식 그래프(knowledge graph), 관계형 데이터베이스(relational database), 이벤트 저장소(event store), 기호적 기록(symbolic record)은 임베딩만으로 신뢰성 있게 복구하기 어려운 정보를 보존할 수 있다. 따라서 하이브리드 메모리 시스템(hybrid memory system)은 의미적 검색과 구조화된 필터링(structured filtering)을 결합하여 의미를 기준으로 검색하면서 시간적, 공간적, 논리적 또는 과제별 제약조건도 적용할 수 있다.

실용적인 메모리 시스템은 인코딩(encoding), 저장(storage), 검색, 갱신(update), 망각을 연결하는 파이프라인(pipeline)으로 구현할 수 있다. 들어오는 관측은 먼저 압축된 표현으로 변환되고 시간, 출처, 중요도(importance), 신뢰도, 모달리티(modality) 등의 메타데이터(metadata)가 부여된다. 저장 정책(storage policy)은 해당 정보가 단기 메모리에 유지될지, 에피소드 장기 저장소로 이동할지, 의미 지식에 기여할지를 결정한다. 이후 검색 과정은 관련 기록을 선택하여 에이전트의 활성 추론 맥락(active reasoning context)에 제공한다.

이러한 시스템의 코드 아키텍처(code architecture)는 모듈식 인터페이스(modular interface)를 활용할 때 효과적이다. 단기 메모리 모듈은 제한된 버퍼(bounded buffer)나 우선순위가 지정된 작업 집합(working set)을 관리하고, 장기 메모리 모듈은 영구 저장소(persistent storage)를 관리할 수 있다. 인코더(encoder)는 관측을 임베딩이나 구조화된 표현으로 변환하고, 검색기(retriever)는 후보 메모리의 순위를 결정하며, 메모리 관리자(memory manager)는 삽입, 통합, 갱신, 삭제를 제어한다. 이러한 책임을 분리하면 전체 에이전트를 다시 설계하지 않고도 저장 기술이나 검색 알고리즘을 변경할 수 있다.

메모리 기록(memory record)은 원시 콘텐츠(raw content) 이상의 정보를 포함해야 한다. 유용한 필드에는 식별자(identifier), 타임스탬프, 출처 모달리티(source modality), 의미 임베딩(semantic embedding), 중요도 점수(importance score), 신뢰도 추정치(confidence estimate), 과제 식별자(task identifier), 참조된 개체, 다른 메모리와의 관계 등이 포함될 수 있다. 에피소드 기록에는 추가적으로 관측, 행동, 보상(reward), 결과 상태(resulting state)를 포함할 수 있다. 이러한 메타데이터를 이용하면 검색 정책이 하나의 유사도 점수에만 의존하지 않고 의미적 관련성과 최신성(recency), 신뢰성, 중요도, 맥락적 적합성(contextual compatibility)을 결합할 수 있다.

저장된 지식은 시간이 지나면서 잘못될 수 있기 때문에 메모리 갱신(memory updating)이 필요하다. 환경이 변화하거나 이전 관측이 수정될 수 있으며 새로운 증거가 기존의 믿음과 충돌할 수도 있다. 따라서 강건한 메모리 시스템은 변경되지 않는 역사적 에피소드(immutable historical episode)와 수정 가능한 지식 주장(mutable knowledge claim)을 구분해야 한다. 에피소드에는 특정 시점에 관측한 내용을 보존하고, 의미 메모리에는 현재의 믿음을 신뢰도 및 출처 정보(provenance)와 함께 유지할 수 있다. 이를 통해 새로운 증거가 역사적 기록을 다시 작성하지 않으면서 현재의 지식을 수정할 수 있다.

메모리가 증가할수록 모순 처리(contradiction handling)는 더욱 중요해진다. 두 메모리가 서로 다른 상태를 설명하는 이유는 세계가 변화했기 때문일 수도 있고, 센서가 불확실했기 때문일 수도 있으며, 하나의 기록이 잘못되었기 때문일 수도 있다. 시스템은 충돌하는 정보를 자동으로 하나의 진술로 병합해서는 안 된다. 시간적 순서, 출처 신뢰도(source reliability), 신뢰도, 맥락적 차이를 활용하면 해당 메모리가 실제 모순인지, 환경 변화인지, 또는 별개의 상황을 나타내므로 독립적으로 유지해야 하는지를 판단하는 데 도움이 된다.

메모리와 월드 모델(world model)은 밀접하게 연결되어 있다. 메모리는 이전 상태와 상태 전이(state transition)에 관한 증거를 제공하고, 월드 모델은 이러한 경험에서 재사용 가능한 구조를 추출하여 미래 상태를 예측한다. 에피소드 메모리는 현재 모델에 도전하는 비정상적인 상태 전이를 보존할 수 있고, 의미 메모리는 여러 에피소드에서 학습한 규칙성을 유지할 수 있다. 반대로 예측 오차(prediction error)는 어떤 새로운 경험을 저장해야 하는지를 결정하는 데 활용될 수 있으며, 이를 통해 기억, 학습, 예측 사이에 피드백 루프(feedback loop)가 형성된다.

메모리는 새로운 지식을 영구적인 파라미터 갱신(parameter update)에만 의존하지 않고 통합할 수 있도록 함으로써 지속학습(continual learning)도 지원한다. 에이전트는 모델을 다시 학습하기에 충분한 데이터가 존재하지 않더라도 새로운 경험을 즉시 저장하고 필요할 때 검색할 수 있다. 시간이 지나면서 반복적으로 유용하게 사용되는 메모리는 모델 파라미터나 상위 수준의 의미 구조(semantic structure)로 통합될 수 있다. 이를 통해 즉각적인 저장에서 점진적인 표현 및 정책 적응(policy adaptation)에 이르는 여러 학습 시간 규모가 형성된다.

AGI에서 메모리 검색은 궁극적으로 의사결정 인식(decision-aware) 방식이어야 한다. 가장 유사한 메모리가 반드시 가장 유용한 메모리는 아니다. 현재 상황에 동일한 위험 요소가 존재한다면 수년 전에 발생한 특이한 실패 경험이 최근의 수백 개 일상적인 경험보다 더 중요할 수 있다. 따라서 고급 메모리 시스템은 표면적인 유사성만으로 메모리의 순위를 정하는 대신 예측, 계획, 불확실성 감소(uncertainty reduction), 안전(safety), 목표 달성에 검색된 정보가 제공할 것으로 예상되는 가치(expected value)를 평가해야 한다.

완전한 메모리 아키텍처는 결과적으로 지각하고, 인코딩하고, 유지하고, 검색하고, 추론하고, 행동하고, 평가하고, 통합하고, 망각하는 지속적인 순환 구조를 형성한다. 단기 메모리는 활성화된 인지 상태(active cognitive state)를 유지하고, 장기 메모리는 축적된 경험과 지식을 보존하며, 메모리 관리 시스템(memory management system)은 정보가 이들 사이에서 어떻게 이동하는지를 결정한다. 이러한 메커니즘을 통해 지능형 에이전트는 현재 상황을 자신의 과거 경험과 연결하면서 동시에 미래의 학습을 위한 자원을 유지할 수 있다.

궁극적으로 메모리(memory)는 지능을 서로 단절된 반응의 연속에서 지속적인 적응 과정(persistent adaptive process)으로 변화시킨다. 단기 메모리는 즉각적인 계산 과정에서 연속성을 제공하고, 장기 메모리는 에피소드, 지식, 기술을 축적하며, 구현된 메모리 시스템은 저장, 검색, 통합, 갱신, 망각을 조정한다. 따라서 AGI에서 효과적인 메모리는 단순히 과거를 저장하는 데이터베이스가 아니라 경험의 어떤 부분이 미래의 이해, 추론, 행동에 계속 영향을 미칠 수 있도록 유지될 것인지를 결정하는 능동적인 메커니즘(active mechanism)이다.

## 03.02. Reasoning Engine

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

추론 엔진(reasoning engine)은 지능형 시스템(intelligent system)이 이용 가능한 지식(knowledge), 관측(observation), 목표(goal), 중간 표현(intermediate representation)을 결론, 설명, 계획 또는 의사결정으로 변환하는 구성요소이다. AGI에서 추론은 하나의 고정된 메커니즘에만 의존할 수 없다. 서로 다른 문제는 서로 다른 형태의 추론을 요구하기 때문이다. 일부 과제는 명시적인 논리적 일관성(logical consistency)을 요구하고, 다른 과제는 통계적 패턴 인식(statistical pattern recognition)에 의존하며, 많은 실제 문제에서는 구조화된 규칙과 학습된 표현이 함께 작동해야 한다.

기호적 추론(symbolic reasoning)은 명시적인 기호(symbol), 관계(relation), 규칙(rule), 술어(predicate), 그래프(graph), 논리 표현(logical expression)을 사용하여 지식을 표현한다. 이를 통해 연역(deduction), 정리 증명(theorem proving), 계획(planning), 제약조건 충족(constraint satisfaction), 규칙 기반 의사결정(rule-based decision making)을 지원할 수 있다. 관계가 명시적으로 표현되므로 기호적 시스템은 해석 가능한 추론 경로(reasoning trace)를 제공하고 강제 제약조건(hard constraint)을 적용할 수 있다. 따라서 정확성, 일관성, 추적 가능성(traceability), 도메인 규칙(domain rule)이 중요한 경우에 유용하다.

기호적 지식 표현(symbolic knowledge representation)은 (On(A,B)), (Blocked(Path_1)), (BatteryLow(Robot))과 같은 사실과 기존 사실에서 새로운 결론을 도출하는 규칙을 표현할 수 있다. 예를 들어 차단된 경로는 내비게이션에서 선택할 수 없다는 규칙이 있다면 기호적 추론기(symbolic reasoner)는 해당 경로를 명시적으로 제거할 수 있다. 따라서 추론 과정은 통계적 유사성에만 의존하는 것이 아니라 정의된 추론 절차에 따라 구조화된 명제(structured statement)를 조작하는 방식으로 이루어진다.

연역적 추론(deductive reasoning)은 기호적 시스템의 가장 강력한 능력 가운데 하나이다. 수용된 전제(premise)와 유효한 규칙이 주어지면 시스템은 그로부터 논리적으로 따라오는 결론을 도출한다. 이러한 특성은 계획, 형식 검증(formal verification), 구성(configuration), 진단(diagnosis), 안전 논리(safety logic)에 유용하다. 그러나 연역은 이용 가능한 지식 베이스(knowledge base)의 품질과 완전성에 크게 의존하며, 실제 환경에는 수작업으로 인코딩하기 어려운 불확실성, 불완전한 정보, 모호한 관측, 예외가 자주 존재한다.

기호적 추론은 지식 획득(knowledge acquisition)과 확장성(scalability) 문제도 가지고 있다. 대규모 규칙 베이스(rule base)는 구축, 유지관리, 검색이 어려워질 수 있으며, 환경의 작은 변화에도 수작업으로 설계한 표현을 상당히 수정해야 할 수 있다. 또한 픽셀, 오디오 파형(audio waveform), 고차원 관측(high-dimensional observation)은 자연스럽게 정리된 기호의 형태로 제공되지 않기 때문에 기호적 시스템은 원시 감각 입력(raw sensory input)을 직접 처리하는 데 어려움을 겪는다. 따라서 연속적인 데이터를 구조화된 개체(entity)와 관계로 변환하는 지각(perception) 또는 그라운딩 계층(grounding layer)이 필요한 경우가 많다.

신경망 추론(neural reasoning)은 반대 방향에서 문제에 접근한다. 신경망(neural network)은 데이터에서 직접 표현과 변환을 학습하여 모든 규칙을 명시적으로 지정하지 않고도 통계적 규칙성을 발견할 수 있다. 심층 신경망(deep network)은 복잡한 관측을 관계를 모델링하기 쉬운 잠재 공간(latent space)으로 매핑할 수 있다. 이를 통해 신경망 추론은 지각, 언어, 패턴 인식, 근사(approximation), 대규모의 잡음이 포함된 데이터에 대한 일반화(generalization)에서 강력한 능력을 제공한다.

대규모 언어 모델(large language model)은 학습된 표현을 이용하여 다단계 추론(multi-step inference), 유추(analogy), 설명, 코드 생성(code generation), 계획과 유사한 행동을 지원하는 강력한 신경망 추론의 한 형태를 보여준다. 이러한 능력은 수작업으로 인코딩된 논리적 지식 베이스가 아니라 대규모 말뭉치(corpus)의 학습으로부터 나타난다. 따라서 신경망 모델은 특히 관련 지식이 수많은 사례와 맥락에 분산되어 있는 경우 기존 규칙 기반 시스템보다 개방적이고 모호한 문제를 더욱 유연하게 처리할 수 있다.

그러나 신경망 추론이 자동으로 논리적 일관성을 보장하는 것은 아니다. 모델은 명시적인 제약조건이나 이전에 진술된 사실과 충돌하면서도 그럴듯한 결론을 생성할 수 있다. 내부 표현은 직접적으로 해석 가능한 형태가 아니라 분산 표현(distributed representation)이므로 특정 결론이 정확히 왜 생성되었는지를 파악하기 어려울 수 있다. 또한 신경망 시스템은 분포 변화(distribution shift), 프롬프트 변화(prompt variation), 맥락 부족, 충분히 학습되지 않은 사례에 민감할 수 있으며, 이는 높은 신뢰성이 요구되는 추론에서 문제가 될 수 있다.

또 다른 한계는 신경망 모델이 불확실성(uncertainty)과 지식을 암묵적으로 표현하는 경우가 많다는 것이다. 학습된 파라미터에 특정 패턴이 존재한다고 해서 모델이 특정 결론에 대해 강한 증거, 약한 증거 또는 상충하는 증거를 가지고 있는지를 반드시 알 수 있는 것은 아니다. 보정된 신뢰도(calibrated confidence), 검색(retrieval), 확률적 모델링(probabilistic modeling), 자기 일관성(self-consistency), 모델 앙상블(model ensemble) 등의 기법은 신뢰성을 향상시킬 수 있지만, 신경망 추론은 여전히 제약조건을 감시하고 중요한 출력을 검증하는 외부 메커니즘으로부터 도움을 받을 수 있다.

따라서 기호적 추론과 신경망 추론은 상호 보완적인 강점을 제공한다. 기호적 시스템은 명시적인 구조, 조합적 규칙(compositional rule), 해석 가능성(interpretability), 제약조건 처리를 제공하고, 신경망 시스템은 유연한 지각, 표현학습(representation learning), 근사, 패턴 기반 일반화(pattern-based generalization)를 제공한다. 하이브리드 추론 엔진(hybrid reasoning engine)은 이러한 능력을 결합하여 학습된 모델이 복잡한 관측을 처리하는 동시에 기호적 구성요소가 구조를 강제하고 명시적인 지식을 조작하며 중요한 결론을 검증하도록 한다.

단순한 하이브리드 파이프라인(hybrid pipeline)은 신경망 기반 지각과 표현학습에서 시작할 수 있다. 이미지, 언어 지시(language instruction), 멀티모달 관측(multimodal observation)을 개체, 속성(attribute), 관계, 신뢰도 값(confidence value)으로 변환한다. 이렇게 생성된 구조화된 출력은 규칙, 제약조건 또는 계획 연산자(planning operator)를 적용하는 기호적 추론 계층으로 전달된다. 이후 생성된 결론을 다시 신경망 모델로 전달하여 언어 생성, 행동 선택(action selection), 맥락 의존적 해석(context-sensitive interpretation)에 활용할 수 있다.

또 다른 하이브리드 설계에서는 신경망 모델이 가설(hypothesis)을 제안하고 기호적 구성요소가 이를 검사한다. 언어 모델은 후보 계획(candidate plan), 수학적 단계, 가능한 설명을 생성하고 검증기(verifier)는 논리적, 물리적 또는 안전 제약조건을 위반하는 후보를 제거할 수 있다. 이러한 아키텍처는 창의적인 탐색(creative search)과 구조화된 검증(structured validation)을 분리한다. 가설 공간이 순수한 기호적 열거(symbolic enumeration)만으로 처리하기에는 지나치게 크지만 제약 없는 신경망 생성만으로는 충분한 신뢰성을 확보하기 어려운 경우에 특히 유용하다.

반대의 관계도 가능하다. 기호적 계획기(symbolic planner)가 상위 수준의 목표나 행동 시퀀스를 생성하고, 신경망 정책(neural policy)이 불확실한 물리적 환경에서 각각의 기호적 단계를 실행할 수 있다. 예를 들어 계획기는 객체로 이동하고 객체를 파지(grasp)한 다음 목적지에 배치하도록 결정할 수 있으며, 신경망 제어기는 지각, 파지 자세 추정(grasp pose estimation), 모터 제어(motor control)를 담당할 수 있다. 따라서 하이브리드 추론은 서로 다른 추상화 수준(abstraction level)에 서로 다른 계산 메커니즘을 적용할 수 있도록 한다.

뉴로-심볼릭 표현(neuro-symbolic representation)은 기호와 미분 가능한 신경망 표현(differentiable neural representation)이 하나의 학습 시스템 내부에서 상호작용하도록 함으로써 이러한 메커니즘을 더욱 깊게 통합하려고 한다. 논리적 관계는 신경망 출력을 제약할 수 있고, 신경망 임베딩(neural embedding)은 기호적 개체 사이의 부드러운 유사성(soft similarity)을 제공할 수 있다. 미분 가능 논리(differentiable logic), 그래프 신경망(graph neural network), 신경망 정리 증명(neural theorem proving), 구조화된 잠재 모델(structured latent model)은 연속적 학습과 명시적 관계 구조를 연결하는 다양한 접근법을 보여준다.

AGI에서 하이브리드 추론은 불확실한 지각과 명시적인 목표를 함께 처리해야 하기 때문에 특히 중요하다. 로봇은 잡음이 포함된 센서 데이터로부터 어떤 객체가 도구일 가능성이 높다고 추론하고, 해당 도구에 관한 의미 지식(semantic knowledge)을 검색하고, 과제 제약조건(task constraint)을 적용한 다음 안전한 행동 시퀀스를 계획해야 할 수 있다. 모든 단계에 이상적인 하나의 표현 방식은 존재하지 않는다. 연속적인 신경망 특징은 지각에 유용하고, 기호적 구조는 이산적인 목표, 관계, 제약조건을 표현하는 데 더 적합할 수 있다.

메모리(memory)는 추론 엔진을 더욱 강화한다. 단기 메모리(short-term memory)는 활성 전제(active premise), 중간 결론, 해결되지 않은 하위 목표(subgoal)를 유지하고, 장기 메모리(long-term memory)는 관련 사실, 이전 해결책, 절차, 에피소드(episode)를 제공한다. 추론 엔진은 추론을 수행하기 전에 지식을 검색하고 이후 유용한 결론을 다시 저장할 수 있다. 이를 통해 추론이 메모리를 사용하면서 동시에 미래의 추론을 개선할 수 있는 새로운 정보를 생성하는 순환 구조가 만들어진다.

월드 모델(world model)은 또 다른 중요한 입력을 제공한다. 가능한 행동을 추론하려면 환경이 어떻게 변화할 수 있는지를 예측해야 한다. 신경망 월드 모델(neural world model)은 미래의 잠재 상태(latent state)를 추정할 수 있고, 기호적 모델(symbolic model)은 명시적인 인과적 또는 관계적 제약조건을 표현할 수 있다. 하이브리드 추론기는 신경망 시뮬레이션(neural simulation)을 이용하여 가능한 미래 궤적(future trajectory)을 생성하고 기호적 평가를 이용하여 해당 궤적이 목표, 안전 요구사항, 자원 제한(resource limit), 논리적 조건을 만족하는지를 판단할 수 있다.

불확실성은 모든 추론 방식에서 유지되어야 한다. 기호적 사실은 불완전한 센서에서 생성되었기 때문에 불확실할 수 있으며, 신경망 예측 역시 제한된 신뢰도를 가질 수 있다. 하이브리드 시스템은 기호에 확률이나 신뢰도 값을 연결하고 이를 추론 과정에서 전파할 수 있다. 확률 논리(probabilistic logic), 베이지안 네트워크(Bayesian network), 팩터 그래프(factor graph), 불확실성 인식 신경망 모델(uncertainty-aware neural model)은 모든 명제를 단순히 참 또는 거짓으로 가정하지 않고 이산적 구조와 불확실한 증거를 결합하는 메커니즘을 제공한다.

코드(code)를 포함하는 실용적인 추론 엔진은 모듈식 인터페이스(modular interface)를 중심으로 구성할 수 있다. 신경망 모듈은 원시 관측이나 임베딩된 관측을 입력받아 후보 개념이나 가설을 반환한다. 기호적 모듈은 구조화된 사실을 유지하고 규칙을 적용한다. 하이브리드 조정기(hybrid coordinator)는 각 구성요소를 언제 호출할 것인지 결정하고, 이들 사이의 표현을 변환하며, 신뢰도를 추적하고, 충돌을 해결한다. 추가적으로 검증기를 사용하여 결론이 계획기나 행동 시스템에 전달되기 전에 명시적인 제약조건과 비교하여 출력을 검사할 수 있다.

코드에서 기호적 추론은 \`if obstacle_detected and distance \< threshold: stop = True\`와 같은 규칙으로 표현할 수 있으며, 신경망 추론은 객체 정체성(object identity), 자유 공간 확률(free-space probability), 예측 궤적(predicted trajectory)과 같은 값을 생성할 수 있다. 이후 하이브리드 제어기(hybrid controller)는 신뢰도가 적절한 임계값을 초과하면 신경망 출력을 기호적 술어(symbolic predicate)로 변환하고 관련 규칙을 평가하며, 증거가 충분하지 않은 경우 추가적인 지각을 요청할 수 있다. 핵심적인 아키텍처 원리는 학습된 추정(learned estimation)과 명시적인 의사결정 제약조건(explicit decision constraint)을 분리하는 것이다.

조정기는 신경망 예측을 항상 강제적으로 고정된 기호로 변환해서는 안 된다. 너무 이른 이산화(premature discretization)는 유용한 불확실성 정보를 제거할 수 있다. 대신 하이브리드 시스템은 충분한 증거가 확보될 때까지 소프트 술어(soft predicate), 신뢰도 분포(confidence distribution), 여러 경쟁 가설(competing hypothesis)을 유지할 수 있다. 이를 통해 기호적 추론이 불확실한 입력을 처리하면서도 신경망 표현의 유연성을 보존할 수 있다. 시스템이 어떤 결론이 확정적이고 어떤 결론이 잠정적인지를 구분할 수 있을 때 더욱 신뢰할 수 있는 의사결정을 생성할 수 있다.

추론 깊이(reasoning depth) 역시 과제의 난이도에 따라 조정되어야 한다. 익숙하고 위험도가 낮은 상황은 빠른 신경망 추론이나 캐시된 기호적 절차(cached symbolic procedure)를 이용하여 처리할 수 있지만, 새롭거나 안전이 중요한 상황에서는 더 깊은 탐색(search), 명시적 검증, 검색, 시뮬레이션, 여러 차례의 추론 과정을 활성화할 수 있다. 자원 인식 추론(resource-aware reasoning)은 AGI가 모든 문제에 최대 계산량을 사용하는 것을 방지하고 추론 엔진을 적응형 계산(adaptive computation)과 제한된 합리성(bounded rationality)을 위한 더 넓은 메커니즘과 연결한다.

궁극적으로 기호적 추론(symbolic reasoning), 신경망 추론(neural reasoning), 하이브리드 추론(hybrid reasoning)은 서로 배타적인 대안이 아니라 상호 보완적인 메커니즘으로 이해해야 한다. 기호적 추론은 명시적인 구조와 검증 가능성(verifiability)을 제공하고, 신경망 추론은 학습된 표현과 유연한 일반화를 제공하며, 하이브리드 추론은 이 두 방식을 하나의 공통된 의사결정 과정 안에서 조정한다. AGI에서 가장 강력한 추론 엔진은 학습된 패턴 인식을 명시적인 지식, 메모리, 불확실성, 월드 모델, 계획, 검증과 결합함으로써 지능이 유연성을 유지하면서도 체계적이고 규율된 방식으로 작동하도록 하는 형태가 될 가능성이 높다.

## 03.03. Planning System

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

계획(planning)은 지능형 에이전트(intelligent agent)가 목표(goal)를 현재 상태에서 원하는 미래 상태로 이동할 수 있는 체계적인 행동 시퀀스(action sequence)로 변환하는 과정이다. 계획 시스템(planning system)은 즉각적인 반응을 넘어 행동하기 전에 가능한 결과를 고려해야 한다. AGI에서 계획은 지각(perception), 메모리(memory), 추론(reasoning), 월드 모델(world model), 행동(action)을 연결하며, 에이전트가 현재의 관측에만 반응하는 것이 아니라 미래의 결과에 따라 행동을 선택할 수 있도록 한다.

계획기(planner)는 상태(state), 행동(action), 목표, 제약조건(constraint), 예상 상태 전이(expected transition)의 표현을 기반으로 작동한다. 현재 상태는 에이전트가 환경에 대해 가지고 있는 믿음(belief)을 나타내며, 목표는 최종적으로 참이 되어야 하는 조건을 정의한다. 행동은 가능한 개입(intervention)과 그 효과를 나타낸다. 계획은 이러한 행동의 조합을 탐색하여 물리적, 논리적, 시간적, 안전, 자원 제약조건을 만족하면서 목표를 달성하는 궤적(trajectory)을 찾는다.

고전적 계획(classical planning)은 행동을 명시적인 전제조건(precondition)과 효과(effect)를 통해 표현한다. 행동은 전제조건이 충족될 때만 실행될 수 있으며, 행동이 실행되면 정의된 효과에 따라 상태가 변화한다. 예를 들어 로봇은 객체 가까이에 있고 그리퍼(gripper)를 사용할 수 있을 때만 객체를 파지(grasp)할 수 있다. 이러한 구조화된 표현(structured representation)은 각각의 단계가 왜 적용될 수 있고 어떤 상태 변화를 발생시키는지를 확인할 수 있기 때문에 계획을 해석 가능하게 만든다.

상태 공간 계획(state-space planning)은 세계의 가능한 상태 구성을 직접 탐색한다. 순방향 탐색(forward search)은 현재 상태에서 시작하여 목표 상태에 도달할 때까지 가능한 행동을 반복적으로 적용한다. 역방향 탐색(backward search)은 목표 조건에서 시작하여 어떤 행동이 해당 조건을 만들어낼 수 있는지를 결정하고 필요한 선행 상태(predecessor state)를 재귀적으로 식별한다. 두 방식의 효율성은 상태 공간의 크기와 탐색을 안내하는 메커니즘의 품질에 크게 의존한다.

탐색 알고리즘(search algorithm)은 많은 계획기의 계산적 기반을 제공한다. 너비 우선 탐색(breadth-first search)은 짧은 경로를 발견할 수 있지만 분기(branching)가 많으면 계산 비용이 크게 증가하고, 깊이 우선 탐색(depth-first search)은 메모리 요구량을 줄이지만 좋지 않은 분기를 오랫동안 탐색할 수 있다. 다익스트라 알고리즘(Dijkstra\'s algorithm)과 A\* 같은 알고리즘은 경로 비용(path cost)과 휴리스틱(heuristic)을 도입하여 가능성이 높은 상태를 우선적으로 탐색할 수 있도록 한다. 유용한 휴리스틱은 후보 상태가 원하는 목표 달성으로부터 얼마나 떨어져 있는지를 추정한다.

행동의 결과가 불확실하면 계획은 훨씬 어려워진다. 로봇이 객체를 파지하려고 시도했지만 실패할 수 있고, 내비게이션 경로가 차단될 수 있으며, 다른 에이전트가 예상하지 못한 행동을 할 수도 있다. 따라서 확률적 계획(probabilistic planning)은 상태 전이를 결정론적 변환(deterministic transformation)이 아니라 가능한 미래 상태에 대한 확률분포(distribution)로 표현한다. 계획기는 예상 결과, 위험(risk), 불확실성(uncertainty), 예측이 틀렸을 때의 복구 가능성을 기준으로 행동을 비교해야 한다.

마르코프 의사결정 과정(Markov Decision Process, MDP)은 확률적 상태 전이 아래에서 순차적 의사결정(sequential decision making)을 수행하기 위한 형식적 프레임워크를 제공한다. 상태는 관련 정보를 요약하고, 행동은 상태 전이 확률에 영향을 미치며, 보상(reward)은 결과에 대한 선호를 나타낸다. 정책(policy)은 각각의 상태에서 어떤 행동을 선택해야 하는지를 정의한다. 따라서 MDP에서 계획은 목표에 도달하는 하나의 고정된 행동 시퀀스를 찾는 것이 아니라 기대 누적 보상(expected cumulative reward)을 최대화하는 정책을 찾는 과정이다.

부분 관측 가능성(partial observability)은 에이전트가 환경의 실제 상태를 정확하게 알 수 없기 때문에 또 다른 복잡성을 추가한다. 부분 관측 마르코프 의사결정 과정(Partially Observable Markov Decision Process, POMDP)에서는 가능한 상태에 대한 확률분포를 나타내는 믿음 상태(belief state)를 기반으로 계획한다. 따라서 행동은 물리적 가치뿐만 아니라 정보적 가치(informational value)를 가질 수 있다. 불확실성이 신뢰할 수 있는 의사결정을 내리기에는 너무 높다면 에이전트는 행동을 확정하기 전에 의도적으로 추가 관측을 수집할 수 있다.

계층적 계획(hierarchical planning)은 큰 목표를 작은 하위 목표(subgoal)로 분해하여 복잡성을 줄인다. 모든 저수준 행동을 직접 탐색하는 대신 계획기는 먼저 이동(navigate), 검사(inspect), 파지, 운반(transport), 배치(place)와 같은 추상적인 시퀀스를 구성할 수 있다. 이후 각각의 추상적 연산을 보다 상세한 절차로 확장한다. 계층적 작업 네트워크(Hierarchical Task Network, HTN)는 상위 수준의 과제를 점차 구체적인 하위 과제로 분해하는 방법(method)을 표현함으로써 이러한 개념을 형식화한다.

계층적 계획은 실제 목표가 매우 다양한 시간적·추상적 규모를 가질 수 있다는 점에서 AGI에 특히 중요하다. 상위 수준 계획기(high-level planner)는 수분 또는 수시간 동안 지속되는 목표를 추론할 수 있고, 하위 수준 계획기는 수초 단위의 궤적을 결정하며, 제어기(controller)는 훨씬 높은 주파수로 명령을 생성한다. 이러한 수준을 분리하면 전략적 추론(strategic reasoning)이 모든 모터의 세부 동작에 압도되는 것을 방지하면서 추상적인 목표를 물리적 행동으로 변환할 수 있다.

시간 계획(temporal planning)은 행동 지속시간(action duration), 순서(ordering), 동시성(concurrency), 마감시간(deadline)을 명시적으로 표현한다. 실제의 많은 행동은 순간적으로 발생하지 않으며 자원 요구사항이 충돌하지 않는다면 여러 활동을 동시에 실행할 수도 있다. 계획기는 데이터를 처리하면서 배터리를 충전하거나 여러 로봇이 서로 다른 하위 과제를 수행하도록 조정해야 할 수 있다. 따라서 시간적 제약조건(temporal constraint)은 무엇이 발생해야 하는지를 결정하는 것에서 더 나아가 언제 어떤 순서로 발생해야 하는지를 결정하도록 계획의 범위를 확장한다.

자원 인식 계획(resource-aware planning)은 에너지, 계산 자원(computation), 메모리, 시간, 통신 대역폭(communication bandwidth), 페이로드 용량(payload capacity), 사용 가능한 도구와 같은 제한된 자원을 고려한다. 이론적으로 유효한 계획이라도 로봇이 보유한 배터리보다 많은 에너지를 소비하거나 사용할 수 없는 계산 자원을 요구한다면 실행할 수 없다. 따라서 AGI 계획기는 목표 달성과 함께 실행 가능성(feasibility)을 평가하여 선택된 계획이 실제 에이전트와 환경의 제한조건 아래에서 실행 가능하도록 해야 한다.

제약조건 기반 계획(constraint-based planning)은 실행 과정 전체에서 만족되어야 하는 요구사항을 포함한다. 안전 구역(safety zone), 충돌 회피(collision avoidance), 접근 권한(access permission), 운영 규칙(operational rule), 선후 관계(precedence relationship), 물리적 한계는 허용 가능한 계획의 공간을 제한할 수 있다. 제약 충족(constraint satisfaction) 및 최적화(optimization) 기법은 실행 전에 유효하지 않은 대안을 제거할 수 있다. 강제 제약조건(hard constraint)은 절대로 위반할 수 없는 조건을 나타내고, 완화 제약조건(soft constraint)은 모든 선호를 동시에 만족하는 해법이 없을 때 절충을 허용한다.

월드 모델(world model)은 계획이 아직 발생하지 않은 미래에 대해 추론하는 과정이라는 점에서 고급 계획(advanced planning)의 핵심적인 요소이다. 월드 모델은 후보 행동(candidate action)에 따라 상태가 어떻게 변화할 수 있는지를 예측한다. 계획기는 이러한 예측을 이용하여 대안적인 궤적을 시뮬레이션하고 결과를 추정한 다음 실제 환경과 상호작용하기 전에 서로 비교할 수 있다. 따라서 계획의 품질은 기반 상태 전이 모델(transition model)의 정확성과 일반화 능력(generalization capability)에 크게 의존한다.

모델 기반 계획(model-based planning)은 학습되었거나 사전에 정의된 동역학 모델(dynamics model)을 반복적으로 사용하여 후보 행동을 평가한다. 모델 예측 제어(Model Predictive Control, MPC)와 같은 기법은 제한된 미래 시간 범위(future horizon)에 대해 계획하고, 선택된 계획의 첫 번째 부분만 실행한 다음 결과 상태를 관측하고 다시 계획한다. 이러한 이동 시간 범위 전략(receding-horizon strategy)은 긴 개방 루프 행동 시퀀스(open-loop action sequence)에 의존하지 않고 새로운 관측을 사용하여 의사결정을 지속적으로 갱신하므로 예측 오차에 강건하다.

계획은 신경망 모델(neural model)을 이용하여 후보 해법을 생성할 수도 있다. 학습된 계획기(learned planner)는 이전 사례를 기반으로 가능성이 높은 행동, 하위 목표, 궤적 또는 완전한 계획을 예측할 수 있다. 신경망 계획(neural planning)은 관련 과제에서 학습된 패턴을 활용하여 비용이 높은 탐색을 줄일 수 있다. 그러나 생성된 계획은 명시적인 제약조건을 위반하거나 일관되지 않은 단계를 포함할 수 있으므로 행동을 실행하기 전에 기호적 검증(symbolic verification), 시뮬레이션 또는 최적화를 적용하는 것이 유용하다.

하이브리드 계획(hybrid planning)은 학습된 제안 메커니즘(learned proposal mechanism)을 명시적 탐색 및 검증과 결합한다. 신경망 모델은 탐색 공간에서 가능성이 높은 영역을 식별하거나 후보 하위 목표를 생성하고, 휴리스틱 값을 추정하거나, 가능한 결과를 예측할 수 있다. 이후 기호적 또는 최적화 기반 계획기가 전제조건, 자원 제한, 시간적 관계, 안전 제약조건을 강제할 수 있다. 이러한 결합은 학습 기반 계획의 유연성을 제공하면서 필요한 영역에서는 구조화된 보장(structured guarantee)을 유지한다.

메모리(memory)는 이전 계획, 결과, 실패, 환경 지식, 재사용 가능한 절차를 제공하여 계획을 지원한다. 이전에 유사한 문제가 발생했다면 계획기는 처음부터 탐색을 시작하는 대신 과거에 성공한 해법을 검색할 수 있다. 사례 기반 계획(case-based planning)은 저장된 계획을 새로운 상황에 맞게 수정할 수 있고, 에피소드 메모리(episodic memory)는 피해야 할 실패 패턴을 알려줄 수 있다. 따라서 반복적인 상호작용을 통해 경험이 축적될수록 계획 능력도 향상될 수 있다.

계획과 추론(reasoning)은 밀접하게 연결되어 있지만 서로 다른 역할을 수행한다. 추론은 이용 가능한 정보로부터 결론을 도출하고, 계획은 환경을 원하는 조건으로 변화시킬 수 있는 개입을 탐색한다. 추론은 특정 복도가 차단되어 있다는 결론을 내릴 수 있고, 계획은 어떤 대체 경로를 선택해야 하는지를 결정한다. 통합된 AGI 아키텍처에서 추론 엔진(reasoning engine)이 생성한 결론은 계획기가 사용하는 제약조건, 사실, 예측 또는 가설이 된다.

실용적인 계획기(Planner) 구현은 \`plan(state, goal, constraints)\`와 같은 모듈식 인터페이스(modular interface)를 제공하고 정렬되거나 계층적인 행동 집합을 반환하도록 구성할 수 있다. 내부적으로 계획기는 상태 표현(state representation), 행동 모델(action model), 후속 상태 생성기(successor generator), 휴리스틱 평가기(heuristic evaluator), 탐색 프런티어(search frontier), 제약조건 검사기(constraint checker), 목표 검사(goal test)를 포함할 수 있다. 이러한 구성요소를 분리하면 주변 에이전트 아키텍처를 다시 설계하지 않고도 A\*, 과제 분해(task decomposition), 궤적 최적화(trajectory optimization), 학습된 탐색 정책(learned search policy) 등을 교체할 수 있다.

단순화된 탐색 구현(search implementation)은 현재 상태, 누적 비용(accumulated cost), 휴리스틱 추정값, 행동 이력(action history)을 포함하는 노드(node)를 유지할 수 있다. 계획기는 우선순위 큐(priority queue)에서 가장 가능성이 높은 노드를 꺼내 해당 상태가 목표를 만족하는지 검사하고, 유효한 후속 상태를 생성하고, 비용을 계산한 다음 가능성이 높은 대안을 다시 큐에 삽입한다. 이러한 반복 과정은 유효한 계획을 발견하거나 계산 한계에 도달하거나 현재 목표를 달성할 수 없다고 판단할 때까지 계속된다.

실제 계획 시스템은 생성된 계획이 예측한 그대로 실행될 것이라고 가정해서는 안 된다. 실행 모니터링(execution monitoring)은 행동이 발생한 이후 예상된 상태 전이와 실제 관측을 비교한다. 관측된 상태가 허용 가능한 범위를 넘어 예상과 달라지면 시스템은 남은 계획을 수정하거나 재계획(replanning)을 실행할 수 있다. 이를 통해 계획을 행동 전에 한 번만 수행하는 계산으로 취급하는 대신 계획하고, 실행하고, 관측하고, 비교하고, 다시 계획하는 폐루프 계획(closed-loop planning)이 형성된다.

재계획은 동적 환경(dynamic environment)에서 특히 중요하다. 사람, 차량, 로봇, 장애물, 통신 조건, 사용 가능한 자원은 계획이 실행되는 동안 변화할 수 있다. 매번 전체 계획을 다시 생성하는 것은 계산 비용이 높을 수 있으므로 증분 계획(incremental planning)은 여전히 유효한 부분을 보존하면서 영향을 받은 구간만 수정할 수 있다. 계획기는 중요하지 않은 환경 변화에 불필요하게 반응하지 않으면서 필요한 경우 신속하게 계획을 변경하도록 응답성과 계산 비용 사이의 균형을 유지해야 한다.

다중 에이전트 계획(multi-agent planning)은 여러 에이전트가 상호작용하는 상황으로 이러한 원리를 확장한다. 계획은 협력(cooperation), 경쟁(competition), 공유 자원(shared resource), 통신 제한, 다른 에이전트의 행동을 고려해야 한다. 과제는 능력, 위치, 에너지, 작업량(workload)에 따라 할당할 수 있으며, 궤적은 서로 충돌하지 않도록 조정되어야 한다. 따라서 다중 로봇 시스템(multi-robot system)의 계획은 개별 에이전트의 행동 선택뿐만 아니라 공유되거나 양립 가능한 목표를 향한 집단 행동(collective behavior)의 조정도 포함한다.

계획 품질(planning quality)은 최종 목표를 달성했는지만으로 평가해서는 안 된다. 유용한 평가 척도에는 실행 비용(execution cost), 시간, 에너지 소비, 위험, 강건성(robustness), 계산 비용(computational effort), 복구 능력(recovery capability), 불확실성에 대한 민감도가 포함된다. 서로 다른 목표에는 서로 다른 최적화 기준이 필요할 수 있다. 따라서 AGI 계획기는 다목적 의사결정(multi-objective decision making)을 지원하고 하나의 보편적인 지표만을 최적화하는 대신 상황에 따라 적절한 절충 관계(trade-off)를 선택할 수 있어야 한다.

궁극적으로 계획 시스템(planning system)은 세계에 관한 지능을 목적 지향적인 미래 행동(purposeful future-directed behavior)으로 변환한다. 계획기(Planner)는 목표와 현재의 믿음을 입력받고, 관련 지식을 검색하며, 가능한 상태 전이를 예측하고, 후보 행동을 탐색하거나 생성하고, 제약조건을 검사하고, 계획을 선택하며, 실행을 모니터링하고, 필요할 경우 재계획한다. 탐색, 계층 구조, 불확실성, 월드 모델, 메모리, 추론, 학습, 피드백(feedback)을 통합함으로써 계획은 AGI가 현재 무엇이 일어나고 있는지를 이해하는 단계를 넘어 다음에 무엇이 일어날지를 의도적으로 만들어갈 수 있도록 한다.

## 03.04. Learning System

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

범용 인공지능(Artificial General Intelligence)의 학습 시스템(Learning System)은 하나의 고정된 데이터셋(dataset)에 대해 모델을 최적화하는 것 이상의 역할을 수행해야 한다. 학습 시스템은 경험(experience)을 지속적으로 재사용 가능한 지식(knowledge)으로 변환하고, 변화하는 환경(environment)에 적응하며, 미래의 지각(perception), 추론(reasoning), 계획(planning), 행동(action)을 개선해야 한다. 따라서 AGI 핵심 아키텍처(core architecture)에서 학습은 독립된 훈련 단계가 아니라 기억(memory), 월드 모델(world model), 추론, 계획, 제어(control)를 연결하는 범시스템적 메커니즘(cross-cutting mechanism)으로 작동한다.

지도 학습(Supervised Learning)은 원하는 출력이 알려진 사례로부터 입력과 출력 사이의 대응 관계(mapping)를 획득하는 가장 직접적인 메커니즘을 제공한다. 관측(observation)이 레이블(label), 목표값(target), 시범(demonstration), 구조화된 정답과 함께 제공되면 시스템은 유사한 입력에 적절한 예측을 생성하도록 내부 매개변수(parameter)를 조정한다. 분류(classification), 회귀(regression), 객체 인식(object recognition), 언어 이해(language understanding), 전문가 시범을 통한 모방(imitation), 다양한 작업 특화 적응(task-specific adaptation)이 이 패러다임으로 표현될 수 있다.

그러나 AGI에서 지도 학습은 지배적인 학습 메커니즘이라기보다 더 광범위한 학습 아키텍처(Learning Architecture)의 한 구성 요소로 이해해야 한다. 사람이 생성한 레이블은 비용이 많이 들고 불완전하며, 범용 에이전트(general agent)가 접할 수 있는 상황 중 극히 일부만을 포함할 수밖에 없다. 레이블이 있는 사례에만 의존하여 학습된 시스템은 훈련 데이터가 나타내는 분포(distribution) 안에서는 높은 능력을 보일 수 있지만 목표, 환경, 개념 또는 기술 조합이 변경되면 취약할 수 있다.

따라서 지도 학습의 중요한 기여는 명시적인 의미 구조(semantic structure)와 행동 구조(behavioral structure)를 시스템에 주입하는 것이다. 레이블은 범주(category)를 정의하고, 시범은 바람직한 행동을 전달하며, 선호 데이터(preference data)는 더 나은 응답과 그렇지 않은 응답을 구별할 수 있게 한다. 또한 세심하게 선별된 사례는 추상적인 능력을 사람이 정의한 목표(objective)에 연결하고, 대규모 비레이블 경험(unlabeled experience)에서 이미 획득한 표현(representation)을 정밀한 해석이나 제어가 필요한 작업에 특화할 수 있다.

강화 학습(Reinforcement Learning)은 근본적으로 다른 학습 문제를 다룬다. 모든 관측에 대해 올바른 출력을 직접 제공받는 대신 에이전트(agent)는 환경과 상호작용하고, 행동을 선택하고, 그 결과를 관측하며, 결과가 얼마나 바람직한지를 나타내는 신호를 받는다. 하나의 행동이 이후 의사결정이 이루어지는 상태(state)를 변화시키며, 보상(reward)은 그것을 발생시킨 의사결정보다 훨씬 나중에 주어질 수도 있기 때문에 학습은 순차적(sequential) 특성을 갖는다.

이러한 형식은 강화 학습을 특히 자율 에이전트(autonomous agent)에 적합하게 만든다. AGI 시스템은 관측이 무엇을 의미하는지만 판단하는 것이 아니라 다음에 무엇을 해야 하는지도 결정해야 한다. 여러 대안을 평가하고, 즉각적인 결과와 지연된 결과 사이의 균형을 맞추며, 불확실한 가능성을 탐색하고, 장기적인 기대 효용(expected long-term utility)을 최대화하는 정책(policy)을 구성해야 한다. 이러한 요구사항은 강화 학습을 계획, 의사결정(decision making), 월드 모델링(world modeling), 기억, 행동 및 제어 메커니즘과 직접 연결한다.

가치 기반 접근법(value-based approach)은 상태나 행동과 관련된 미래 기대 수익(expected future return)을 추정하며, 정책 기반 접근법(policy-based approach)은 행동을 선택하는 정책 자체를 직접 최적화한다. 액터-크리틱(actor-critic) 시스템은 정책과 평가 메커니즘을 함께 학습함으로써 두 관점을 결합한다. 모델 기반 강화 학습(model-based reinforcement learning)은 여기에 환경 동역학(environment dynamics)의 모델을 학습하거나 활용하여 실제 행동을 실행하기 전에 가능한 미래를 시뮬레이션(simulation)할 수 있는 능력을 추가한다.

따라서 범용 지능(general intelligence)에서는 학습과 계획의 구분이 점차 모호해진다. 학습된 월드 모델은 상태가 어떻게 변화하는지 예측할 수 있고, 계획 시스템(planner)은 예측된 궤적(trajectory)을 탐색할 수 있으며, 강화 신호(reinforcement signal)는 어떤 궤적이 바람직한지를 결정할 수 있다. 상호작용 과정에서 생성된 경험은 다시 월드 모델과 정책을 개선하면서 예측, 행동, 평가, 기억, 후속 학습이 서로 지속적으로 영향을 미치는 폐루프(closed loop)를 형성한다.

자기지도 학습(Self-Supervised Learning)은 지능형 시스템이 이용할 수 있는 대부분의 정보가 외부에서 제공되는 레이블 없이 도착한다는 점에서 세 번째 핵심 기반을 제공한다. 사람이 정답 목표를 직접 지정하는 대신 학습 과정 자체가 데이터 구조로부터 훈련 신호(training signal)를 만들어낸다. 관측의 일부를 숨기고 나머지로부터 예측하거나, 이전 상태에서 미래 상태를 예측하거나, 동일한 객체나 사건을 나타내는 서로 다른 관측이 관련된 표현을 생성하도록 학습할 수 있다.

마스킹 모델링(masked modeling)은 이러한 원리를 명확하게 보여준다. 텍스트, 이미지, 센서 스트림(sensor stream) 또는 기타 구조화된 관측의 일부를 제거하거나 손상시킨 뒤 모델이 누락된 정보를 복원하거나 예측하도록 학습한다. 이를 성공적으로 수행하려면 시스템은 관측 가능한 요소 사이의 통계적 관계(statistical relationship)를 파악해야 한다. 충분한 규모로 학습되면 이러한 단순한 목표에서도 의미적, 문맥적, 공간적, 시간적, 관계적 정보를 포함하는 표현이 형성될 수 있으며, 이후 다양한 작업에서 이를 재사용할 수 있다.

대조 학습(contrastive learning)과 표현 기반 방법(representation-based method)은 다른 방향에서 동일한 목적에 접근한다. 모든 원시 입력값(raw input value)을 직접 예측하는 대신 관련된 관측은 가까워지고 무관하거나 양립할 수 없는 관측은 구별되는 임베딩 공간(embedding space)을 학습한다. 이러한 학습은 이미지, 언어, 오디오(audio), 고유수용감각(proprioception), 라이다(LiDAR), 행동 및 기타 감각 스트림을 공통 객체, 사건, 상태, 개념과 연결해야 하는 멀티모달 AGI(multimodal AGI)에 특히 중요하다.

시간적 자기지도 학습(temporal self-supervision)은 체화 지능(embodied intelligence)에서 특히 중요하다. 연속적인 관측은 임의의 표본이 아니라 물리적 동역학(physical dynamics)과 에이전트 자신의 행동을 통해 서로 연결된다. 다음 관측, 잠재 상태(latent state), 움직임(motion), 행동의 결과 또는 더 긴 미래 궤적을 예측하도록 학습하면 시스템은 환경에 존재하는 규칙성을 발견할 수 있다. 이렇게 학습된 동역학은 예측과 계획에 사용되는 내부 월드 모델(internal world model)의 기반이 될 수 있다.

SelfSupervised [w/Code]로 표시된 실제 구현은 단순히 또 하나의 분류기(classifier)를 만드는 과정이라기보다 표현 학습 파이프라인(representation-learning pipeline)으로 이해할 수 있다. 원시 관측은 인코더(encoder)를 통해 잠재 표현(latent representation)으로 변환되고, 데이터 자체에서 생성된 목표와 예측 또는 표현을 비교하는 자기생성 목적함수(self-generated objective)가 적용된다. 경사 기반 최적화(gradient-based optimization)는 인코더를 갱신하며, 생성된 표현은 이후 지도 미세조정(supervised fine-tuning), 강화 학습, 검색(retrieval), 예측 또는 계획에 활용될 수 있다.

이 세 가지 학습 패러다임(learning paradigm)은 서로 협력할 때 가장 강력하다. 자기지도 학습은 방대한 비레이블 경험을 흡수하여 범용적인 표현을 구축할 수 있고, 지도 학습은 이러한 표현에 명시적인 의미, 작업 목표, 인간의 시범을 연결할 수 있다. 이후 강화 학습은 상호작용과 그 결과를 통해 실제 행동을 정교화할 수 있다. 따라서 동일한 기반 모델(underlying model)이 하나의 학습 방식에 영구적으로 속하는 것이 아니라 여러 학습 체계를 순차적 또는 복합적으로 거칠 수 있다.

범용 에이전트는 자신의 행동을 통해 새로운 학습 데이터를 생성할 수도 있다. 환경과의 상호작용은 관측, 행동, 상태 전이(state transition), 성공, 실패, 지연된 결과를 포함하는 궤적 데이터를 만든다. 이러한 궤적은 강화 학습 신호와 자기지도 예측 목표를 동시에 제공할 수 있다. 성공적인 경험은 이후 지도 학습이나 모방 학습(imitation learning)의 시범 데이터가 될 수 있으며, 실패는 추가적인 탐색, 시뮬레이션 또는 인간의 지도가 필요한 불확실한 상태를 식별하는 데 활용될 수 있다.

기억(memory)은 학습을 단순한 매개변수 최적화(parameter optimization)에서 누적 지능(cumulative intelligence)으로 변화시킨다. 일화 기억(episodic memory)은 특정 경험을 유지하고, 의미 기억(semantic memory)은 일반화된 지식을 보존하며, 학습된 모델 매개변수는 수많은 경험에서 발견된 통계적 규칙성을 인코딩할 수 있다. 이러한 메커니즘이 상호작용하면 에이전트는 모든 유용한 사실을 즉시 신경망 가중치(neural weights)에 압축할 필요 없이 과거 경험을 검색하고 현재 상황과 비교하여 무엇을 추가 학습을 통해 통합해야 하는지 판단할 수 있다.

성숙한 AGI 학습 시스템은 안정성(stability)과 가소성(plasticity) 사이의 균형도 관리해야 한다. 지나친 가소성은 새롭게 획득한 지식이 기존의 유용한 능력을 덮어쓰게 만들며, 지나친 안정성은 의미 있는 적응을 방해한다. 리플레이(replay), 정규화(regularization), 모듈형 표현(modular representation), 선택적 매개변수 갱신(selective parameter update), 외부 기억(external memory), 지속 학습(continual learning), 주기적으로 갱신되는 훈련 데이터 혼합(training mixture)은 기존 능력을 보존하면서 새로운 환경, 개념, 기술을 통합하는 데 도움을 줄 수 있다.

학습은 궁극적으로 상위 수준의 목표(higher-level objective)에 의해 통제되어야 한다. 경험을 통해 스스로 개선할 수 있는 자율 시스템은 어떤 경험을 신뢰할 수 있는지, 어떤 오류를 수정해야 하는지, 언제 탐색이 정당화되는지, 학습된 행동이 안전 제약(safety constraint)과 의도된 목표에 계속 부합하는지를 판단해야 한다. 따라서 평가(evaluation), 불확실성 추정(uncertainty estimation), 인간 감독(human oversight), 메타인지 모니터링(meta-cognitive monitoring)은 훈련 이후에만 수행되는 외부 활동이 아니라 학습 과정 자체의 구성 요소가 된다.

결과적으로 이러한 아키텍처는 지도 학습(Supervised Learning), 강화 학습(RL), 자기지도 학습(Self-Supervised Learning)이 서로 독립적으로 작동하는 단순한 결합이 아니다. 자기지도 학습은 표현과 예측 구조를 구축하고, 지도 학습은 명시적인 지식과 원하는 행동을 주입하며, 강화 학습은 지식을 실제 결과를 수반하는 행동과 연결한다. 기억은 경험을 보존하고, 월드 모델은 결과를 예측하며, 추론은 대안을 평가하고, 계획은 시간에 걸친 행동을 조직한다.

AGI 관점에서 이 학습 시스템의 가장 근본적인 목적은 하나의 벤치마크(benchmark)를 위한 최적화가 아니라 여러 작업과 환경에 걸친 지속적인 적응(continual adaptation)이다. 범용 지능 에이전트는 처음 접하는 관측을 만나더라도 기존에 학습한 표현을 활용하고, 어떤 지식을 전이(transfer)할 수 있는지 판단하며, 부족한 정보를 획득하고, 행동을 시험하고, 결과로부터 학습하며, 새롭게 얻은 경험을 미래 행동에 통합할 수 있어야 한다. 이러한 능력을 통해 학습은 단순한 훈련 절차(training procedure)를 넘어 지능을 지속적으로 형성하고 발전시키는 핵심 메커니즘이 된다.

## 03.05. Action and Control

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

행동 및 제어(Action and Control)는 지능형 에이전트(intelligent agent)가 내부의 의사결정을 외부 세계의 변화로 전환하는 실행 계층(execution layer)을 구성한다. 지각(perception)은 현재 상황을 추정하고, 추론(reasoning)은 그 의미를 해석하며, 계획(planning)은 바람직한 미래 상태를 결정하지만, 시스템이 행동을 선택하고 실행할 수 없다면 이러한 능력만으로는 실질적인 지능을 구현할 수 없다. 따라서 AGI 아키텍처에서 행동은 내부 인지(internal cognition)와 환경적 결과(environmental consequence)를 연결하는 루프를 완성한다.

행동 시스템(action system)은 상위 수준의 인지 모듈(cognitive module)에서 목표(goal), 계획, 정책(policy), 제약조건(constraint), 현재 상태 추정(state estimation)을 전달받아 이를 실행 가능한 명령(executable command)으로 변환한다. 이러한 명령은 물리적 움직임, 소프트웨어 연산, 통신, 도구 사용(tool use), 정보 검색 또는 다른 시스템의 상태 변경을 의미할 수 있다. 구체적인 인터페이스(interface)는 에이전트의 체화 형태(embodiment)에 따라 달라지지만, 추상적인 의도(intention)를 제어 가능한 행동으로 변환한다는 기본 기능은 동일하다.

제어(control)는 상위 수준 계획보다 짧고 연속적인 시간 척도(timescale)에서 작동한다. 계획 시스템은 로봇이 목적지로 이동하거나, 객체를 파지하거나, 특정 영역을 검사해야 한다고 결정할 수 있지만, 제어기는 의도한 행동이 실제로 구현되도록 속도, 위치, 힘, 자세, 액추에이터 출력(actuator output)을 지속적으로 조절해야 한다. 이러한 분리는 장기적인 추론과 동적 환경에서 필요한 빠른 피드백 보정(feedback correction)이 함께 작동하도록 한다.

효과적인 AGI 제어 아키텍처(control architecture)는 계층적(hierarchical)으로 구성될 수 있다. 가장 높은 수준에서 에이전트는 목표와 전략(strategy)을 선택하고, 중간 계층은 이러한 목표를 기술(skill), 궤적(trajectory), 하위 행동(sub-action)으로 변환하며, 낮은 계층은 정밀한 제어 신호(control signal)를 생성한다. 이러한 분해는 계산 복잡도(computational complexity)를 줄이고 안정화를 위한 밀리초 단위 제어에서 수초 또는 수분 단위의 숙고형 계획까지 서로 다른 시간 해상도에서 적절한 메커니즘이 작동하도록 한다.

피드백(feedback)은 신뢰할 수 있는 제어의 핵심 요소이다. 개방 루프 실행(open-loop execution)은 환경이 예측한 대로 정확하게 움직인다고 가정하지만, 폐루프 제어(closed-loop control)는 기대 상태와 실제 관측 상태를 반복적으로 비교하고 편차를 보정한다. 불확실한 환경에서 작동하는 지능형 에이전트에게 폐루프 제어는 필수적이다. 외란(disturbance), 모델링 오차, 센서 잡음(sensor noise), 이동 객체, 예상하지 못한 사건이 사전에 결정된 행동 순서를 지속적으로 무효화할 수 있기 때문이다.

상태 추정(state estimation)은 지각과 제어를 연결한다. 제어기는 실제 환경 상태(true environmental state)에 직접 접근하는 경우가 드물며, 센서, 기억(memory), 예측 모델(predictive model)에서 얻어진 추정값을 바탕으로 행동한다. 이러한 추정에는 위치, 속도, 객체 관계, 작업 진행 상태, 불확실성(uncertainty), 숨겨진 문맥 변수(contextual variable)가 포함될 수 있다. 따라서 행동의 품질은 제어기 자체뿐 아니라 시스템이 제어 대상의 상태를 얼마나 정확하게 표현하는지에도 의존한다.

고전 제어(classical control) 기법은 고도화된 AGI 시스템에서도 여전히 중요하다. 비례-적분-미분 제어(Proportional-Integral-Derivative Control), 상태공간 제어(state-space control), 최적 제어(optimal control), 모델 예측 제어(Model Predictive Control), 궤적 추종(trajectory tracking)은 잘 정의된 동적 시스템(dynamical system)을 조절하기 위한 수학적으로 구조화된 방법을 제공한다. 이러한 기법은 시스템 동역학을 충분히 알고 있고, 안전 여유가 중요하며, 예측 가능한 실시간 동작(real-time behavior)이 요구되는 경우 특히 유용하다.

모델 예측 제어(Model Predictive Control)는 유한한 예측 구간(prediction horizon)에서 미래의 시스템 동작을 반복적으로 예측하고, 제약조건을 만족하면서 목적함수(objective)를 최적화하는 행동을 선택하기 때문에 지능형 시스템과 특히 밀접하다. 계획된 행동의 일부만 실행한 후 새로운 상태를 관측하고 다시 최적화 문제를 해결한다. 이러한 이동 지평 전략(receding-horizon strategy)은 예측, 계획, 피드백 제어를 자연스럽게 연결한다.

학습 기반 제어(learned control)는 시스템 동역학을 분석적으로 모델링하기 어려운 경우 이러한 접근법을 확장한다. 신경망 정책(neural policy)은 감각 상태 또는 잠재 상태(latent state)를 직접 행동으로 변환할 수 있으며, 학습된 동역학 모델(learned dynamics model)은 계획과 예측 제어를 지원할 수 있다. 강화 학습(Reinforcement Learning)은 상호작용으로부터 정책을 최적화하고, 모방 학습(imitation learning)은 전문가 시범(expert demonstration)에서 행동을 습득할 수 있다. 이러한 방법은 제어 가능한 작업의 범위를 확장하지만 불확실성, 분포 변화(distribution shift), 검증(verification)이라는 새로운 문제도 발생시킨다.

AGI에서는 순수한 반응형 제어(reactive control)만으로 충분하지 않다. 많은 행동은 문맥(context), 목표, 미래의 결과를 고려하여 선택되어야 한다. 동일한 즉각적 관측이라도 이전 사건, 현재 목표, 사용 가능한 자원, 안전 제약(safety constraint), 예측된 미래 상태에 따라 서로 다른 행동이 필요할 수 있다. 따라서 행동 선택(action selection)은 현재의 감각 입력만이 아니라 기억, 추론, 월드 모델(world model)에 의존한다.

월드 모델은 행동을 실제로 실행하기 전에 어떤 일이 발생할 수 있는지를 추정할 수 있게 한다는 점에서 중요한 역할을 한다. 후보 행동(candidate action)을 내부적으로 시뮬레이션하여 예상되는 상태 전이(state transition)와 가능한 결과를 생성할 수 있다. 계획 시스템은 이러한 미래를 비교하고 제어 시스템은 선택된 궤적을 실행한다. 이후 실제 관측에서 발생하는 예측 오차(prediction error)는 월드 모델과 향후 제어 의사결정을 모두 개선하는 데 사용될 수 있다.

행동 선택에서는 불확실성도 고려해야 한다. 상태 추정이나 모델 예측의 신뢰도가 낮은 상황에서 공격적인 행동을 수행하면 허용할 수 없는 위험이 발생할 수 있다. 따라서 지능형 제어기(intelligent controller)는 신뢰도(confidence)에 따라 행동을 조정하여 속도를 낮추거나, 추가 정보를 수집하거나, 보다 안전한 대안을 선택하거나, 외부 지원을 요청할 수 있어야 한다. 불확실성 인식 행동(uncertainty-aware action)은 지식의 한계와 안전한 자율 행동 사이를 연결하는 중요한 메커니즘이다.

안전 제약(safety constraint)은 계획 이후에 추가되는 별도의 기능이 아니라 행동 계층 전체에서 작동해야 한다. 상위 수준의 목표에서는 금지된 결과(forbidden outcome)를 정의할 수 있고, 중간 계층에서는 허용 가능한 궤적을 제한할 수 있으며, 하위 수준 제어기는 속도, 토크(torque), 가속도, 안전거리, 운용 경계와 같은 물리적 한계를 강제할 수 있다. 여러 계층에서 제약조건을 적용하면 하나의 의사결정 메커니즘에 대한 의존도를 낮출 수 있다.

제어 시스템은 원하는 행동(desired behavior)과 실행 가능한 행동(feasible behavior)을 구분해야 한다. 계획 시스템은 물리적 한계, 환경 장애물, 부족한 에너지, 사용할 수 없는 도구 또는 서로 충돌하는 제약조건 때문에 달성할 수 없는 상태를 요구할 수 있다. 따라서 행동 계층은 제안된 행동이 실제로 실행 가능한지를 판단하는 실행 가능성 검사(feasibility check)를 수행하고, 필요하면 실패 정보를 계획 시스템으로 반환하여 계획을 수정하도록 해야 한다.

기술 추상화(skill abstraction)는 개별 제어 명령과 복잡한 지능적 행동 사이의 연결 계층을 제공한다. AGI 시스템은 수천 개의 액추에이터 갱신(actuator update)을 직접 추론하는 대신 이동(navigate), 파지(grasp), 열기(open), 검사(inspect), 통신(communicate), 검색(search), 조작(manipulate)과 같은 재사용 가능한 능력을 표현할 수 있다. 각각의 기술은 내부적으로 지각, 지역 계획(local planning), 피드백 제어를 포함할 수 있어 추론 시스템이 재사용 가능한 행동 기본 요소(behavioral primitive)를 조합하여 복잡한 작업을 수행하도록 한다.

기술 실행(skill execution)에는 종료 조건(termination condition)과 모니터링(monitoring)도 필요하다. 시스템은 행동이 성공했는지, 실패했는지, 위험한 상태가 되었는지 또는 환경 변화로 인해 중단해야 하는지를 판단해야 한다. 따라서 실행과 동시에 모니터링이 수행되며 예상 진행 상태와 실제 관측을 비교한다. 편차가 커지면 에이전트는 행동을 재시도하거나, 전략을 변경하거나, 재계획(replanning)을 수행하거나, 더 높은 인지 계층으로 제어권을 전달할 수 있다.

장기 행동(long-horizon action)은 수많은 단기 제어 에피소드(short-horizon control episode) 사이의 조정을 필요로 한다. 복잡한 목표는 이전 행동의 결과에 의존하는 수백 또는 수천 개의 중간 의사결정으로 구성될 수 있다. 계층적 계획(hierarchical planning), 지속적 기억(persistent memory), 진행 상태 추적(progress tracking), 동적 재계획(dynamic replanning)은 조건이 변화하더라도 전체 목표를 유지하면서 지역 행동을 적응적으로 수정할 수 있게 한다.

체화 AGI(embodied AGI)에서 행동은 탐색(exploration)과도 밀접하게 연결된다. 움직임은 에이전트가 무엇을 지각할 수 있는지를 변화시키므로 행동은 단순한 출력이 아니라 정보를 획득하는 수단이기도 하다. 에이전트는 불확실성을 줄이기 위해 센서 위치를 변경하거나, 객체에 접근하거나, 객체를 조작하거나, 다른 영역으로 이동할 수 있다. 이러한 능동 지각(active perception)은 행동이 정보적 가치(informational value)를 고려하여 선택되는 순환 구조를 형성한다.

에너지와 자원 관리(resource management) 역시 지능형 제어의 중요한 요소이다. 물리적 에이전트는 제한된 배터리 용량, 계산 자원, 통신 대역폭(communication bandwidth), 액추에이터 수명, 시간을 가지고 작동한다. 소프트웨어 에이전트도 메모리, 처리 예산(processing budget), 외부 도구 비용, 지연시간(latency)과 같은 자원 제약을 갖는다. 따라서 효과적인 행동 선택은 작업 성공뿐 아니라 이를 달성하기 위해 소비되는 자원까지 함께 최적화해야 한다.

여러 목표를 동시에 만족시켜야 하는 경우 다목적 제어(multi-objective control)가 필요하다. 성능, 안전, 에너지 효율, 속도, 정밀도, 편의성, 정보 획득량(information gain), 장기적인 시스템 건전성(system health)은 서로 충돌할 수 있다. AGI 제어기는 하나의 고정된 지표만 최적화하는 것이 아니라 상황에 따라 이러한 요소 사이의 균형을 조정해야 한다. 이를 위해 효용 추정(utility estimation), 정책 선택, 제약조건 처리, 메타 수준 추론(meta-level reasoning)이 서로 조정되어야 한다.

행동 실행은 다시 학습에 사용되는 새로운 경험을 생성한다. 각각의 관측-행동-전이(observation-action-transition) 시퀀스는 환경 동역학, 정책의 효과, 제어기의 정확도, 예상하지 못한 조건에 관한 정보를 제공한다. 성공적인 궤적은 효과적인 기술을 강화하는 데 사용될 수 있고, 실패는 지각, 계획, 월드 모델링, 제어의 한계를 드러낸다. 따라서 행동 계층은 실행 메커니즘인 동시에 지속적으로 훈련 데이터를 생성하는 원천이다.

Control [w/Code] 구현은 상태 입력(state input), 행동 생성(action generation), 실행(execution), 피드백, 안전 모니터링을 연결하는 모듈형 인터페이스(modular interface)를 중심으로 구성할 수 있다. 제어기는 목표 상태 또는 작업 명령을 입력받고, 선택된 정책이나 제어 법칙(control law)에 따라 행동을 계산하며, 환경 또는 액추에이터 인터페이스로 명령을 전송한다. 이후 결과 상태를 관측하고 작업이 완료되거나 중단될 때까지 이 과정을 반복한다.

이러한 구현에서는 상위 수준 행동 인터페이스(high-level action interface)와 플랫폼 특화 제어(platform-specific control)의 세부사항을 분리하는 것이 유용하다. 동일한 추론 시스템은 기반 에이전트가 모바일 로봇(mobile robot), 매니퓰레이터(manipulator), 소프트웨어 에이전트, 자율주행차(autonomous vehicle), 시뮬레이션 시스템 중 무엇이든 가능한 한 동일한 추상 명령을 사용할 수 있어야 한다. 어댑터 계층(adapter layer)은 추상 기술을 플랫폼별 명령으로 변환하여 지능 구성 요소를 다양한 체화 환경에서 재사용할 수 있게 한다.

AGI에서 효과적인 행동 및 제어는 하나의 범용 알고리즘보다 여러 메커니즘의 조정(coordination)을 필요로 한다. 고전적 피드백 제어는 정밀성과 안정성을 제공하고, 학습된 정책은 적응성을 제공하며, 계획은 장기적 구조를 제공하고, 월드 모델은 미래 예측을 담당한다. 안전 메커니즘은 행동을 제한하고, 기억과 학습은 미래 의사결정을 개선하며, 피드백은 현재 실행 과정에서 발생하는 오류를 지속적으로 보정한다.

완전한 행동 시스템은 결국 지각-추론-계획-행동(perception--reasoning--planning--action) 루프를 완성한다. 에이전트는 세계를 관측하고 내부 상태를 구성하며, 가능한 미래를 예측하고, 목표 지향 행동(goal-directed action)을 선택하여 제어를 통해 실행한 뒤 그 결과를 다시 관측하고 지식을 갱신한다. 이 순환을 반복함으로써 지능적 행동은 변화하는 조건에 적응하고, 물리적 또는 계산적 현실에 기반하며, 환경 변화에 지속적으로 대응할 수 있다.

AGI 관점에서 성공적인 제어는 단순히 정확한 움직임이나 명령 실행을 의미하지 않는다. 그것은 추상적인 의도(abstract intention)를 신뢰할 수 있고, 적응적이며, 안전하고, 문맥에 민감한(context-sensitive) 세계와의 상호작용으로 변환하는 능력이다. 행동 및 제어가 지각, 기억, 월드 모델링, 추론, 계획, 학습, 평가와 긴밀하게 통합될 때 내부의 지능은 의미 있는 현실 세계의 결과(real-world outcome)를 만들어낼 수 있는 자율 행동(autonomous behavior)으로 전환된다.

## 03.06. Meta Cognition

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

메타인지(Metacognition)는 지능형 시스템이 자신의 인지 활동(cognitive activity)을 표현하고, 관찰하고, 평가하며, 조절할 수 있는 능력이다. 단순히 환경을 지각하거나 외부 문제를 해결하는 것에서 그치지 않고, 메타인지 에이전트(metacognitive agent)는 자신이 현재 상황을 얼마나 잘 이해하고 있는지, 추론이 신뢰할 만한지, 어떤 지식이 부족한지, 현재 전략을 계속 유지해야 하는지 또는 변경해야 하는지를 스스로 추정한다.

AGI 아키텍처에서 메타인지는 지각(perception), 기억(memory), 추론(reasoning), 계획(planning), 학습(learning), 행동(action)을 가로지르는 감독 계층(supervisory layer)으로 기능한다. 이러한 구성 요소들이 신념(belief), 예측(prediction), 계획, 행동을 생성하면 메타인지 시스템은 그 품질과 일관성(consistency)을 평가한다. 따라서 메타인지는 일반적인 인지를 대체하는 것이 아니라 인지를 감시하고, 인지 자원과 전략의 사용 방식을 변경할 수 있는 신호를 제공한다.

객체 수준 인지(object-level cognition)와 메타 수준 인지(meta-level cognition)를 구분하면 메타인지의 역할을 이해하는 데 유용하다. 객체 수준 프로세스는 객체 인식, 질문에 대한 답변, 경로 선택, 로봇 제어와 같은 당면 과제를 해결한다. 반면 메타 수준 프로세스는 인식 결과가 불확실한지, 답변을 뒷받침하는 근거가 충분한지, 선택된 경로가 여전히 적절한지와 같이 이러한 인지 과정 자체에 대해 추론한다.

자기 모니터링(self-monitoring)은 가장 기본적인 메타인지 기능 가운데 하나이다. 지능형 에이전트는 신뢰도(confidence), 불확실성(uncertainty), 작업 진행 상태(task progress), 자원 소비(resource consumption), 예측 정확도(prediction accuracy), 내부 일관성(internal consistency)에 대한 추정치를 유지해야 한다. 이러한 추정치는 현재 인지가 얼마나 신뢰할 수 있는지를 알려준다. 자신의 근거가 약한 상황을 인식하지 못한 채 답을 생성하는 시스템에는 강건한 범용 지능에 필요한 중요한 능력이 결여되어 있다.

신뢰도 추정(confidence estimation)은 단순히 내부 활성값이나 확률의 크기를 그대로 나타내는 것이어서는 안 된다. 능력 있는 시스템은 예측을 충분히 뒷받침할 수 있는 익숙한 상황과 자신의 모델이 신뢰하기 어려울 수 있는 낯선 상황을 구별해야 한다. 보정(calibration)은 표현된 신뢰도와 실제 정확성을 연결하여 추가적인 추론, 관측, 검색(retrieval), 시뮬레이션(simulation), 외부 지원이 필요한지를 에이전트가 판단할 수 있도록 한다.

오류 탐지(error detection)는 모니터링을 불확실성에서 명시적인 불일치(discrepancy)로 확장한다. 시스템은 예측과 실제 관측, 계획된 진행과 실제 진행, 검색된 지식과 현재 증거 또는 서로 독립적인 여러 추론 경로를 비교할 수 있다. 의미 있는 불일치가 발견되면 이는 내부 가정(assumption), 표현(representation), 모델, 전략 또는 행동을 다시 검토해야 할 가능성을 나타내는 메타인지 신호(metacognitive signal)가 된다.

메타인지는 전략 선택(strategy selection)도 지원한다. 많은 문제는 직접적인 패턴 인식(pattern recognition), 검색, 기호적 추론(symbolic reasoning), 시뮬레이션, 탐색(search), 계획, 실험 또는 도구 사용(tool use)을 통해 해결할 수 있다. AGI 시스템은 모든 문제에 동일한 계산 절차를 적용하는 대신 현재 상황에 어떤 전략이 적절한지 추정하고, 기존 접근법이 효과적이지 않다는 증거가 나타나면 전략을 전환할 수 있어야 한다.

이러한 능력은 적응형 계산(adaptive computation)을 가능하게 한다. 단순하고 익숙한 상황에서는 저비용의 처리만 필요할 수 있지만, 새롭거나 모호하거나 안전이 중요한 상황에서는 더 깊은 추론과 추가 검증이 필요할 수 있다. 따라서 메타인지는 추정된 난이도, 불확실성, 위험에 따라 계산 노력을 조절하여 제한된 처리 자원을 가장 높은 기대 효과를 제공하는 영역에 할당할 수 있게 한다.

성찰(reflection)은 보다 숙고적인 형태의 메타인지 처리이다. 중간 결과를 생성한 후 시스템은 가정을 검토하고, 모순(contradiction)을 식별하고, 대안을 다시 고려하며, 결과가 원래의 목표를 만족하는지 평가할 수 있다. 성찰은 행동 이전, 실행 도중 또는 완료 이후에 수행될 수 있으며, 즉각적인 오류 수정뿐 아니라 향후 추론 전략의 장기적인 개선도 가능하게 한다.

그러나 무제한적인 성찰이 반드시 유익한 것은 아니다. 반복적인 재검토는 시간과 계산 자원을 소비하고, 이미 충분히 적절한 해결책을 불필요하게 변경할 수도 있다. 따라서 메타인지 시스템에는 추가적인 추론이 충분한 가치를 제공할 가능성이 있는지를 판단하는 종료 기준(stopping criteria)이 필요하다. 더 생각할 것인지에 대한 결정 자체가 기대되는 개선 효과, 비용, 긴급성(urgency), 위험을 고려하는 최적화 문제(optimization problem)가 된다.

자기평가(self-evaluation)는 시간에 따른 비교를 필요로 하기 때문에 기억은 메타인지에서 필수적이다. 일화 기억(episodic memory)은 이전의 의사결정, 실패, 수정, 성공적인 전략을 보존할 수 있으며, 의미 기억(semantic memory)은 특정 조건에서 어떤 접근법이 효과적인지를 일반화된 지식으로 저장할 수 있다. 에이전트는 이러한 기록을 이용하여 반복적으로 발생하는 실수를 인식하고 모든 문제를 완전히 새로운 상황으로 취급하는 것을 피할 수 있다.

메타인지는 기억 연산(memory operation) 자체도 조절할 수 있다. 시스템은 어떤 경험을 장기 기억에 저장할 가치가 있는지, 검색된 기억 가운데 무엇이 현재 상황과 관련되는지, 어떤 정보를 통합(consolidation)해야 하는지, 오래된 지식에 어느 정도 낮은 가중치를 부여해야 하는지를 결정할 수 있다. 이러한 의미에서 메타인지는 추론뿐 아니라 작업 과정과 지속적인 지식 구조 사이의 정보 흐름도 관리한다.

장기 계획은 예상한 대로 정확하게 진행되는 경우가 드물기 때문에 계획 역시 메타 수준 모니터링(meta-level monitoring)의 도움을 받는다. 시스템은 주요 이정표(milestone)를 감시하고, 계획과 실제 상황의 편차를 탐지하며, 남아 있는 불확실성을 추정하고, 재계획(replanning)이 필요한지를 판단할 수 있다. 작은 편차는 지역적으로 처리하고 큰 변화는 상위 수준 추론으로 되돌려 보내 불필요한 재계획과 이미 무효화된 계획에 대한 맹목적인 고수를 모두 방지할 수 있다.

행동 및 제어(Action and Control) 역시 메타인지 감독을 필요로 한다. 행동을 실행하기 전에 시스템은 예상 결과, 신뢰도, 가역성(reversibility), 안전성을 평가할 수 있다. 실행 중에는 결과가 허용 가능한 범위 안에 유지되는지 감시한다. 신뢰도가 낮아지거나 예상하지 못한 조건이 나타나면 에이전트는 속도를 낮추거나, 정지하거나, 추가 정보를 수집하거나, 지원을 요청하거나, 보다 안전한 메커니즘으로 제어권을 이전할 수 있다.

월드 모델(world model)은 메타인지 정보를 제공하는 또 하나의 중요한 원천이다. 월드 모델이 생성한 예측을 실제 관측과 비교하면 모델의 신뢰성을 측정할 수 있다. 지속적인 예측 오차(prediction error)는 환경이 변화했거나 모델이 불완전하다는 것을 의미할 수 있다. 에이전트는 이에 따라 불확실한 예측에 대한 의존도를 낮추고 추가적인 관측이나 학습을 우선할 수 있다.

메타인지는 학습과 밀접하게 연결된다. 지능형 시스템은 무엇을 학습해야 하는지만이 아니라 언제 그리고 왜 학습이 필요한지도 판단해야 하기 때문이다. 반복적인 실패는 부족한 기술(skill), 제대로 표현되지 않은 개념, 부정확한 동역학(dynamics), 불충분한 훈련 데이터를 나타낼 수 있다. 메타 수준 시스템은 이러한 결함을 식별하고 성능 저하의 주요 원인이 되는 구성 요소를 중심으로 학습을 유도할 수 있다.

이러한 관계는 자연스럽게 메타학습(meta-learning), 즉 학습하는 방법을 학습하는 것(learning to learn)으로 이어진다. 메타학습은 작업별 매개변수(task-specific parameter)만 최적화하는 것이 아니라 적응이 어떻게 이루어지는지를 결정하는 메커니즘 자체를 개선하려 한다. 여러 작업에 걸친 경험을 통해 어떤 초기화(initialization), 표현, 최적화 전략, 기억 메커니즘 또는 적응 규칙(adaptation rule)이 새로운 작업을 더욱 효율적으로 학습하게 하는지를 시스템이 학습할 수 있다. 첨부 구조에서는 Meta_Cognition과 MetaLearning [w/Code]이 명시적으로 연결되어 있다.

MetaLearning [w/Code] 구현에서는 내부 학습 과정(inner learning process)과 외부 최적화 과정(outer optimization process)을 통해 이러한 구분을 표현할 수 있다. 내부 과정은 특정 작업이나 환경에 모델을 적응시키고, 외부 과정은 여러 작업에 걸친 적응 성능을 평가하여 초기 모델 또는 학습 절차를 수정한다. 따라서 목표는 하나의 작업에서 더 높은 성능을 얻는 것만이 아니라 미래의 다양한 작업에서 능력을 더욱 효과적으로 획득할 수 있는 역량을 향상시키는 것이다.

최적화 기반 메타학습(optimization-based meta-learning)은 적은 횟수의 업데이트만으로 새로운 상황에 적응할 수 있는 매개변수를 탐색할 수 있다. 메트릭 기반 접근법(metric-based approach)은 처음 접하는 사례와 이전 사례를 효율적으로 비교할 수 있는 표현 공간(representation space)을 학습한다. 기억 기반 접근법(memory-based approach)은 작업 패턴을 보존하고 유용한 과거 경험을 빠르게 검색하여 관련된 새로운 상황에서 필요한 추가 학습량을 줄인다.

AGI에서 메타학습은 빠른 매개변수 적응을 넘어 확장되어야 한다. 에이전트는 문제 유형에 따라 어떤 추론 전략이 가장 효과적인지, 어떤 도구를 선택해야 하는지, 얼마나 많은 계산 자원을 할당해야 하는지, 언제 외부 정보가 필요한지 또는 언제 학습된 정책을 신뢰해야 하는지를 학습할 수 있다. 따라서 메타학습은 하나의 예측 모델을 조정하는 것을 넘어 아키텍처 자체의 적응 행동(adaptive behavior)을 개선하는 메커니즘이 된다.

자기평가에는 적절한 평가 기준(evaluation criteria)이 필요하다. 자율 시스템에서는 정확도만으로 충분하지 않을 수 있으며 강건성(robustness), 효율성, 불확실성, 안전성, 일관성, 목표에 대한 진행 정도, 자원 사용량도 고려해야 한다. 작업마다 이러한 기준의 중요성이 달라질 수 있다. 따라서 메타인지는 현재 목표와 운용 문맥(operational context)에 따라 인지 활동을 판단할 수 있는 평가 모델(evaluation model)에 의존한다.

성숙한 시스템은 해결 가능한 불확실성(correctable uncertainty)과 근본적인 지식 부족(lack of knowledge)도 구별해야 한다. 어떤 경우에는 추가적인 계산을 통해 모호성을 해결할 수 있지만, 다른 경우에는 새로운 관측, 외부 지식, 실험 또는 인간의 지도가 필요하다. 이러한 차이를 인식하면 불필요한 내부 추론을 방지하고 생각만으로 문제를 해결할 수 없는 상황에서 정보 수집 행동(information-gathering action)을 선택할 수 있다.

메타인지 제어(metacognitive control)는 전체 인지 아키텍처에 걸쳐 피드백 루프(feedback loop)를 형성한다. 인지 모듈이 결과를 생성하면 메타 수준 시스템이 이를 평가하고, 제어 신호를 통해 이후의 처리 과정을 변경한다. 시스템은 더 많은 정보를 검색하거나, 추론 방법을 변경하거나, 추가적인 계산 자원을 할당하거나, 계획을 수정하거나, 모델을 갱신하거나, 위험한 행동을 억제하거나, 새로운 학습을 시작할 수 있다. 이후 그 결과는 다시 평가된다.

이러한 루프는 지속적인 운용(continual operation)에서 특히 중요하다. AGI 에이전트는 초기 훈련에서 예상하지 못했던 작업을 접하면서 장기간 작동할 수 있다. 고정된 처리 정책(fixed processing policy)만으로는 미래의 모든 상황에 최적으로 대응할 수 없다. 메타인지는 에이전트가 새로운 상황을 인식하고, 성능 저하를 탐지하며, 전략을 재구성하고, 조건이 바뀔 때마다 전체 시스템을 다시 설계하지 않고도 축적된 경험을 활용할 수 있게 한다.

그러나 메타인지는 안전과 외부 목표에 의해 제한되어야 한다. 학습 전략, 자원 할당 또는 내부 정책을 수정할 수 있는 시스템에는 어떤 적응이 허용되는지를 정의하는 경계(boundary)가 필요하다. 모니터링, 감사 가능성(auditability), 인간 감독(human oversight), 보호된 안전 제약(protected safety constraint)을 통해 인지 성능을 개선하는 과정에서 시스템이 따라야 할 목표나 제한 조건이 은밀하게 변경되는 것을 방지할 수 있다.

통합된 AGI 아키텍처에서 메타인지는 결국 인지에 대한 인지(cognition about cognition)와 인지의 제어(control of cognition)가 결합된 것으로 이해할 수 있다. 메타인지는 내부 프로세스를 관찰하고, 신뢰도와 불확실성을 추정하고, 오류를 탐지하며, 진행 상태를 평가하고, 전략을 선택하고, 자원을 조절하고, 성찰을 시작하며, 학습 방향을 결정하고, 언제 외부의 도움이 필요한지를 판단한다. 메타학습은 경험을 통해 이러한 적응 메커니즘 자체를 개선함으로써 이 능력을 더욱 확장한다.

메타인지의 장기적인 중요성은 지능이 자신의 한계 자체를 관리할 수 있게 된다는 데 있다. 범용 에이전트가 모든 환경에 대한 완전한 지식이나 완벽한 모델을 가질 수는 없지만, 자신이 무엇을 알고 있는지 인식하고, 무엇을 모르는지 식별하며, 각각의 상황에 적절한 방법을 선택하고, 실패로부터 학습하며, 학습하는 방법 자체를 개선하는 능력은 지속적으로 발전시킬 수 있다. 이러한 자기조절 능력(self-regulatory capacity)은 작업 특화 능력(task-specific competence)에서 적응형 범용 지능(adaptive general intelligence)으로 발전하기 위한 핵심적인 연결 고리가 된다.

## 03.07. Unified Agent Model [w/Code]

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

통합 에이전트 모델(Unified Agent Model)은 지각(perception), 기억(memory), 추론(reasoning), 계획(planning), 학습(learning), 메타인지(metacognition), 행동(action), 제어(control)를 하나의 운영 아키텍처(operational architecture)로 통합한다. 이러한 능력을 서로 독립적인 모듈로 취급하는 대신, 에이전트는 공유 표현(shared representation), 상태 추정(state estimate), 목표(goal), 피드백 루프(feedback loop)를 통해 각 기능을 조정한다. 그 목적은 변화하는 작업과 환경 속에서 관측하고, 이해하고, 결정하고, 행동하고, 평가하고, 적응하는 하나의 지속적으로 작동하는 시스템을 만드는 것이다.

지각(perception)은 에이전트에게 외부 세계와 내부 상태에 대한 정보를 제공한다. 센서 입력(sensor input), 언어, 이미지, 공간 정보, 시스템 상태 또는 다른 에이전트의 메시지는 지각 모듈을 통해 해석 가능한 표현으로 변환된다. 이러한 표현은 단순한 데이터의 집합이 아니라 현재 상황을 설명하는 구조화된 상태(state)로 정리되며, 이후 기억, 추론, 계획, 행동 선택의 공통 입력으로 사용된다.

통합 모델에서는 지각 결과가 독립적으로 소비되는 것이 아니라 기억(memory)과 결합된다. 현재의 관측은 과거의 경험, 학습된 지식, 이전 작업의 결과와 비교되며, 이를 통해 현재 상황에 대한 더 풍부한 해석이 가능해진다. 기억은 에이전트가 모든 상황을 처음부터 다시 분석하는 것을 방지하고, 이미 경험한 패턴이나 유사한 문제를 빠르게 재사용할 수 있게 한다.

단기 기억(short-term memory) 또는 작업 기억(working memory)은 현재 작업과 직접 관련된 정보를 유지한다. 장기 기억(long-term memory)은 반복적으로 사용할 수 있는 경험과 지식을 저장하며, 일화 기억(episodic memory)은 특정 사건과 그 결과를 보존하고, 의미 기억(semantic memory)은 일반화된 개념과 사실을 저장한다. 통합 에이전트는 이러한 여러 기억 체계를 상황에 따라 선택적으로 검색하고 갱신해야 한다.

추론(reasoning)은 현재 상태와 기억에서 얻은 지식을 바탕으로 의미를 해석하고 관계를 발견하며 가능한 결론을 생성한다. 이 과정에는 논리적 추론(logical reasoning), 확률적 추론(probabilistic reasoning), 인과 추론(causal reasoning), 신경망 기반 추론(neural reasoning), 시뮬레이션(simulation)이 함께 사용될 수 있다. 통합 모델의 중요한 특징은 하나의 추론 방식만 고정적으로 사용하는 것이 아니라 문제의 특성에 따라 여러 방식을 조합할 수 있다는 점이다.

계획(planning)은 추론을 행동 가능한 미래 구조로 변환한다. 에이전트는 현재 상태와 목표 사이의 차이를 분석하고, 이를 줄이기 위한 일련의 행동을 구성한다. 계획은 단일 행동의 선택이 아니라 여러 단계로 구성된 장기적인 행동 시퀀스(action sequence)를 다룰 수 있으며, 하위 목표(subgoal), 자원, 시간, 위험, 제약조건을 함께 고려한다.

통합 에이전트에서 계획은 고정된 스크립트(script)가 아니라 지속적으로 수정되는 구조이다. 환경이 예상과 다르게 변하거나 새로운 정보가 발견되면 기존 계획을 유지할 것인지, 일부만 수정할 것인지, 전면적으로 재계획(replanning)할 것인지 결정해야 한다. 이러한 동적 계획 능력은 개방형 환경(open environment)에서 장기간 자율적으로 작동하기 위한 핵심 조건이다.

월드 모델(world model)은 통합 에이전트 내부에서 미래를 예측하는 중요한 메커니즘으로 작동한다. 에이전트는 현재 상태와 가능한 행동을 입력으로 받아 이후 상태가 어떻게 변화할지를 예측할 수 있다. 여러 후보 행동을 실제로 수행하기 전에 내부적으로 시뮬레이션함으로써, 비용이 크거나 위험한 행동을 줄이고 더 유리한 전략을 선택할 수 있다.

월드 모델은 단순한 물리적 상태 변화만을 예측하는 것이 아니라 다른 에이전트의 반응, 작업의 진행, 자원의 변화, 목표 달성 가능성까지 포함할 수 있다. 이러한 예측 능력이 추론과 계획에 연결되면 에이전트는 현재 관측에 반응하는 수준을 넘어 미래의 가능성을 비교하면서 행동할 수 있다. 이는 반응형 시스템(reactive system)과 계획형 지능(planning intelligence)을 구분하는 중요한 요소이다.

학습(learning)은 통합 모델이 경험에 따라 변화하도록 만든다. 에이전트는 지도 학습(supervised learning), 강화 학습(reinforcement learning), 자기지도 학습(self-supervised learning), 모방 학습(imitation learning), 메타학습(meta-learning)을 다양한 형태로 결합할 수 있다. 각각의 학습 방식은 표현, 지식, 정책, 예측 모델, 행동 기술을 서로 다른 방식으로 개선한다.

중요한 점은 학습이 별도의 오프라인 훈련 단계에만 존재하지 않는다는 것이다. 에이전트가 환경과 상호작용하면서 생성하는 관측, 행동, 성공, 실패, 예측 오차, 보상은 모두 새로운 학습 데이터가 될 수 있다. 따라서 통합 에이전트는 실행과 학습을 연결하여 행동 경험이 다음 의사결정의 품질을 지속적으로 개선하도록 해야 한다.

메타인지(metacognition)는 이러한 모든 인지 과정 위에서 감독 기능(supervisory function)을 수행한다. 시스템은 현재 추론이 충분한지, 계획이 신뢰할 수 있는지, 기억이 관련성이 있는지, 행동이 안전한지, 추가 계산이나 새로운 정보가 필요한지를 평가할 수 있다. 메타인지는 단순한 자기평가를 넘어 어떤 인지 전략을 사용할지 결정하는 제어 계층(control layer)의 역할을 한다.

통합 에이전트에서는 신뢰도(confidence)와 불확실성(uncertainty)이 중요한 내부 상태로 취급된다. 시스템이 자신의 예측이나 판단에 확신이 낮다면 추가적인 정보를 수집하거나, 더 많은 추론을 수행하거나, 대안을 검토하거나, 외부 지원을 요청할 수 있다. 이러한 불확실성 인식(uncertainty awareness)은 단순히 답을 생성하는 시스템과 자신의 한계를 관리하는 지능형 에이전트를 구분한다.

행동 선택(action selection)은 목표, 계획, 현재 상태, 월드 모델의 예측, 안전 제약(safety constraint)을 결합하여 다음 행동을 결정한다. 행동은 물리적 움직임뿐 아니라 도구 호출(tool invocation), 정보 검색, 통신, 소프트웨어 연산, 데이터 수정, 다른 에이전트와의 협력까지 포함할 수 있다. 따라서 통합 에이전트의 행동 공간(action space)은 매우 넓을 수 있다.

행동 및 제어(Action and Control) 모듈은 선택된 행동을 실제 실행 가능한 명령으로 변환한다. 상위 수준에서는 작업이나 기술(skill)을 선택하고, 중간 수준에서는 경로 또는 하위 행동을 구성하며, 하위 수준에서는 정확한 제어 신호를 생성한다. 이러한 계층 구조는 높은 수준의 장기 목표와 빠른 실시간 제어를 하나의 시스템 안에서 동시에 처리할 수 있게 한다.

피드백(feedback)은 통합 에이전트 전체를 하나의 폐루프 시스템(closed-loop system)으로 만든다. 행동이 실행되면 환경은 변화하고 새로운 관측이 발생한다. 에이전트는 예상한 결과와 실제 결과를 비교하여 계획, 월드 모델, 정책, 기억을 갱신한다. 이 과정에서 생성되는 예측 오차(prediction error)는 무엇이 잘못되었는지 알려주는 중요한 신호가 된다.

에이전트의 핵심 운영 구조는 관측(Observe), 이해(Understand), 예측(Predict), 계획(Plan), 행동(Act), 평가(Evaluate), 학습(Learn)의 반복적인 순환으로 이해할 수 있다. 이러한 단계들은 반드시 순차적으로만 작동하는 것은 아니다. 실제 시스템에서는 여러 과정이 병렬적으로 수행되며, 필요에 따라 일부 단계가 생략되거나 반복될 수 있다.

장기적인 자율성(long-term autonomy)을 위해서는 목표 관리(goal management)가 필요하다. 단기적인 행동이 성공적이라도 장기 목표와 충돌할 수 있기 때문에 에이전트는 여러 시간 범위에 걸친 목표를 동시에 관리해야 한다. 최상위 목표는 방향을 제공하고, 중간 목표는 작업을 분해하며, 즉각적인 목표는 현재 행동을 결정한다.

여러 목표가 서로 충돌하는 경우에는 우선순위(priority)와 효용(utility)을 평가해야 한다. 안전, 임무 성공, 자원 절약, 시간, 정확성, 사회적 규칙 등이 동시에 고려될 수 있다. 통합 에이전트는 단순히 하나의 보상값만 최대화하는 것이 아니라 현재 상황에 적절한 균형을 판단하고 그에 따라 행동을 선택해야 한다.

자원 관리(resource management)도 통합 에이전트의 중요한 부분이다. 계산 능력, 메모리, 에너지, 통신 대역폭, 시간, 외부 도구 비용은 모두 제한되어 있다. 따라서 에이전트는 언제 깊은 추론이 필요한지, 언제 빠른 반응이 충분한지, 어떤 모델이나 도구를 사용할지 스스로 조절해야 한다. 이는 메타인지와 실행 시스템이 직접 연결되는 부분이다.

기술(skill)은 복잡한 행동을 재사용 가능한 단위로 추상화한다. 이동, 검색, 조작, 설명, 질문, 협상, 검사와 같은 기술은 내부적으로 여러 단계의 지각, 추론, 계획, 제어를 포함할 수 있다. 통합 에이전트는 이러한 기술을 조합하여 새로운 작업을 수행하고, 성공적인 조합을 기억하여 이후 더 효율적으로 재사용할 수 있다.

툴 사용(tool use)은 현대적인 통합 에이전트에서 특히 중요하다. 모든 기능을 내부 모델만으로 수행할 필요는 없으며, 계산기, 검색 시스템, 데이터베이스, 코드 실행기, 로봇 인터페이스, 외부 API와 같은 도구를 활용할 수 있다. 핵심은 어떤 도구를 언제 사용해야 하는지를 추론하고, 결과를 검증하며, 전체 목표와 연결하는 능력이다.

다중 에이전트 환경(multi-agent environment)에서는 통합 에이전트가 다른 지능형 시스템과 상호작용할 수 있어야 한다. 다른 에이전트의 목표와 상태를 추정하고, 정보를 교환하고, 역할을 분담하고, 협력하거나 경쟁할 수 있어야 한다. 이 경우 통합 모델은 개인 에이전트 내부의 인지만이 아니라 사회적 추론(social reasoning)과 협력 계획(collaborative planning)까지 확장된다.

안전(safety)은 모든 계층을 가로지르는 구조로 통합되어야 한다. 계획 단계에서는 위험한 목표를 제한하고, 행동 선택에서는 금지된 행동을 제거하며, 실행 단계에서는 물리적 또는 논리적 안전 한계를 적용하고, 메타인지 단계에서는 전체 행동이 의도된 목표와 일치하는지 감시해야 한다. 안전을 단일 후처리 모듈로 분리하면 하나의 실패가 전체 시스템에 직접 영향을 줄 수 있다.

인간 감독(human oversight)은 완전한 자율성과 반대되는 개념이라기보다 통합 에이전트의 제어 구조에 포함될 수 있다. 에이전트는 자신의 불확실성이 높거나 위험 수준이 허용 기준을 넘는 경우 인간에게 판단을 요청할 수 있다. 반대로 충분히 익숙하고 안전한 상황에서는 자율적으로 행동하여 인간의 개입을 최소화할 수 있다.

Unified Agent Model [w/Code]의 구현은 각 기능을 명확한 인터페이스(interface)로 분리하면서도 공통 상태 표현을 공유하도록 설계할 수 있다. 관측 상태, 기억 검색 결과, 목표, 계획, 행동 후보, 불확실성, 실행 결과를 구조화된 데이터 형태로 유지하면 각 모듈이 동일한 에이전트 상태(agent state)를 기반으로 협력할 수 있다.

실제 코드에서는 중앙 에이전트 루프(agent loop)가 이러한 모듈을 조정할 수 있다. 루프는 환경을 관측하고, 내부 상태를 갱신하고, 필요한 기억을 검색하고, 추론과 계획을 수행하며, 행동을 선택하고 실행한 후 결과를 평가한다. 새로운 경험은 기억과 학습 시스템으로 전달되며, 메타인지 모듈은 전체 과정의 신뢰성과 효율성을 지속적으로 감시할 수 있다.

그러나 모든 기능을 하나의 거대한 모델에 완전히 결합해야 한다는 의미는 아니다. 실제 AGI 시스템은 신경망, 기호 시스템, 검색 시스템, 데이터베이스, 제어기, 도구 인터페이스와 같은 서로 다른 기술을 모듈 형태로 결합할 가능성이 높다. 중요한 것은 내부 구현 방식이 아니라 이러한 구성 요소가 하나의 목표 지향적 에이전트(goal-directed agent)처럼 일관되게 작동하는가에 있다.

통합의 핵심은 공유 상태(shared state), 공통 목표(common goal), 지속적인 피드백, 조정 메커니즘(coordination mechanism)에 있다. 지각이 다른 상태 표현을 사용하고, 계획이 기억의 내용을 알 수 없으며, 행동 결과가 학습으로 전달되지 않는다면 개별 모듈의 성능이 높더라도 시스템 수준의 지능은 제한된다. 반대로 각 구성 요소가 서로의 정보를 활용하면 전체 시스템은 개별 기능의 단순한 합보다 더 높은 적응 능력을 나타낼 수 있다.

궁극적으로 통합 에이전트 모델은 AGI의 다양한 핵심 메커니즘을 하나의 지속적인 인지-행동 순환(cognition-action cycle)으로 결합하는 구조이다. 에이전트는 세계를 관측하고, 경험과 지식을 검색하고, 상황을 추론하고, 미래를 예측하고, 계획을 세우고, 행동하며, 그 결과를 평가하고 학습한다. 메타인지는 이 모든 과정의 품질과 자원 사용을 감시하고 필요한 경우 전략을 변경한다.

AGI 관점에서 이러한 통합은 단순한 소프트웨어 모듈 연결 이상의 의미를 갖는다. 범용 지능은 각각 뛰어난 지각, 추론 또는 계획 모듈 하나에서 발생하기보다 다양한 능력이 시간에 따라 서로 정보를 교환하고, 오류를 수정하고, 경험으로부터 학습하며, 목표에 맞게 행동하는 지속적인 시스템 수준의 상호작용에서 나타날 가능성이 높다. 통합 에이전트 모델은 이러한 개별 능력을 적응적이고 자율적인 하나의 지능으로 결합하기 위한 핵심 아키텍처라고 볼 수 있다.
