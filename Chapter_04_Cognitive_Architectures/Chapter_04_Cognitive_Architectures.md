**Volume 47. Artificial General Intelligence**


# Chapter 04. Cognitive Architectures

##  

## 04.00. What is Cognitive Architecture

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

A cognitive architecture is an organized framework that specifies how the major mechanisms of an intelligent system interact to produce coherent cognition and behavior. Rather than describing a single algorithm, model, or neural network, it defines how perception, memory, reasoning, learning, planning, action, and control exchange information over time. It therefore provides a system-level structure for understanding and engineering intelligence.

The concept originates from attempts to explain cognition as a coordinated collection of processes rather than an isolated capability. Human intelligence depends on many mechanisms operating together: sensory information must be interpreted, relevant knowledge retrieved, alternatives evaluated, decisions formed, and actions executed. Cognitive architecture seeks to capture this organization in a computational form that can support persistent and adaptive intelligent behavior.

A cognitive architecture differs from a conventional AI model in scope. A model may perform classification, prediction, language generation, or policy estimation, while an architecture determines how multiple models and computational processes cooperate. It defines representations, information flows, control mechanisms, memory access, decision cycles, and interfaces through which specialized capabilities become components of a larger cognitive system.

Perception provides the architecture with observations about the external environment and the agent itself. Raw sensory signals, language, images, spatial measurements, or digital events must be transformed into representations that other cognitive mechanisms can use. The architecture determines how these representations are maintained, combined with prior knowledge, and updated when new evidence changes the interpretation of the current situation.

Memory provides continuity beyond the immediate observation. Working memory can preserve information required during an active task, while long-term memory can maintain knowledge and experience across longer periods. Episodic, semantic, and procedural forms of memory may serve different functions. A cognitive architecture specifies how information enters memory, how relevant content is retrieved, and how retrieved knowledge influences ongoing cognition.

Reasoning transforms available information into conclusions, explanations, hypotheses, and decisions. Depending on the architecture, this process may involve symbolic rules, probabilistic inference, neural computation, causal models, search, simulation, or combinations of these methods. The architectural question is not only how reasoning occurs, but also when it should be invoked and how its results affect other processes.

Planning organizes cognition across future time. Once an agent possesses an estimate of its current state and a desired objective, it must determine which sequence of actions can reduce the difference between them. Cognitive architectures can represent goals, subgoals, alternative strategies, dependencies, constraints, and expected outcomes, allowing behavior to extend beyond immediate stimulus-response relationships.

Learning enables the architecture to change through experience. New observations can improve representations, successful actions can strengthen policies, failures can reveal incorrect assumptions, and repeated experiences can create reusable knowledge or skills. Learning therefore affects multiple architectural components rather than existing only as a separate training process performed before the intelligent system begins operating.

Action connects internal cognition with external consequences. Decisions and plans must eventually be translated into commands that affect an environment, whether through physical movement, communication, software operations, or tool use. The consequences of these actions generate new observations, creating a closed interaction loop in which cognition influences the world and the changed world subsequently influences cognition.

Control mechanisms determine which cognitive processes should operate at a particular moment. An intelligent system cannot necessarily perform every possible reasoning, retrieval, planning, and learning operation simultaneously. The architecture therefore needs mechanisms for attention, prioritization, task switching, resource allocation, interruption, and synchronization so that limited computational resources are directed toward currently important problems.

This requirement makes cognitive architecture fundamentally temporal. Intelligence unfolds through sequences of internal and external events rather than through one isolated computation. Observations arrive, memories become active, goals change, reasoning processes generate intermediate results, plans are revised, actions occur, and feedback returns. Architecture defines how these processes remain coordinated as the system continuously evolves.

A useful distinction exists between cognitive content and cognitive process. Content includes beliefs, observations, goals, memories, predictions, and representations of objects or situations. Processes operate on this content by retrieving, transforming, comparing, evaluating, storing, or acting upon it. A cognitive architecture must define both what kinds of information exist internally and how operations can modify that information.

Representation is therefore a central architectural problem. Information may be represented symbolically, numerically, probabilistically, geometrically, through distributed neural embeddings, or through combinations of these forms. Different representations support different operations efficiently. Modern architectures increasingly need mechanisms that allow structured knowledge, learned representations, sensory states, and action-related information to coexist and interact.

Traditional symbolic cognitive architectures emphasize explicit knowledge structures and operations over them. Rules, symbols, goals, and production systems can provide interpretable mechanisms for reasoning and problem solving. Such architectures demonstrate how complex behavior can emerge from repeated cycles of matching internal conditions with applicable operations, although manually constructing comprehensive symbolic knowledge can become difficult at large scale.

Connectionist approaches instead emphasize distributed representations and learned transformations. Neural networks can acquire complex mappings directly from data and provide strong capabilities in perception, language, prediction, and representation learning. Their internal knowledge is generally less explicitly structured than symbolic systems, but their ability to learn statistical regularities makes them important components of contemporary cognitive architectures.

Hybrid cognitive architectures attempt to combine these complementary strengths. Learned neural components may interpret sensory information and generate flexible representations, while structured memory, planners, reasoning mechanisms, or explicit constraints provide organization and control. The objective is not necessarily to divide intelligence into purely neural and symbolic regions, but to use different computational mechanisms where their properties are most advantageous.

Modern foundation models introduce another architectural possibility because one large learned model can support multiple cognitive functions. A language or multimodal foundation model may contribute to perception, reasoning, planning, knowledge retrieval, communication, and tool selection. Nevertheless, broad model capability does not eliminate architectural requirements such as persistent memory, environmental interaction, execution monitoring, safety constraints, and long-term goal management.

Cognitive architecture is therefore particularly important when transforming a model into an agent. A model normally receives an input and produces an output, whereas an agent must maintain state across time, pursue goals, choose actions, observe consequences, and adapt its future behavior. The architecture provides the persistent mechanisms required to transform episodic model inference into continuing goal-directed interaction.

The agent\'s internal state serves as a shared context connecting different mechanisms. It may contain current observations, active goals, retrieved memories, beliefs, uncertainty estimates, plans, available resources, and recent actions. When components operate over a compatible state representation, information produced by perception can influence reasoning, reasoning can influence planning, and execution results can update memory and learning.

World models can extend this internal state by representing how relevant aspects of the environment change. Instead of reasoning only from the current observation, the architecture can predict future states under candidate actions. Such predictions support planning, counterfactual reasoning, risk assessment, and proactive behavior. Prediction errors produced after execution can then reveal where the internal model requires correction or additional learning.

Metacognition adds another level of architectural organization by allowing the system to evaluate its own cognitive activity. Confidence, uncertainty, reasoning quality, plan progress, resource usage, and error signals can become objects of monitoring. A metacognitive mechanism can determine whether additional reasoning is necessary, whether another strategy should be selected, or whether external assistance should be requested.

Attention is similarly architectural because it determines which subset of available information receives processing priority. Complex environments contain more information than an agent can process equally at every moment. Attention can prioritize observations, memories, goals, or internal hypotheses according to relevance and urgency, helping the architecture control computational load while maintaining responsiveness to significant changes.

Hierarchical organization provides another solution to complexity. High-level mechanisms can reason about abstract goals and strategies, while lower levels handle skills, trajectories, or immediate control. Different levels can operate at different temporal frequencies and degrees of abstraction. This allows long-horizon deliberation to coexist with rapid reactive behavior without forcing a single mechanism to manage every detail.

Feedback loops are essential because cognition must remain grounded in actual outcomes. A plan produces an action, the action changes the environment, and the resulting observation reveals whether expectations were correct. The architecture can use this discrepancy to modify state estimates, revise plans, update models, or initiate learning. Closed-loop cognition therefore replaces rigid execution with continuous adaptation.

Resource management becomes increasingly important as architectures grow more capable. Reasoning, simulation, retrieval, perception, and model inference consume time, energy, memory, and computational capacity. An architecture can allocate these resources dynamically, using inexpensive processing for routine situations while activating deeper reasoning or additional models when uncertainty, novelty, or risk justifies the added cost.

Safety must also be represented at the architectural level. Constraints can influence goals, planning, action selection, execution, and learning rather than being applied only after a response has been produced. Monitoring mechanisms can detect abnormal states, prevent forbidden actions, interrupt unsafe execution, and request human oversight when confidence is insufficient. Distributed safeguards provide multiple opportunities to prevent undesirable behavior.

For AGI, cognitive architecture ultimately provides the organizational foundation that connects specialized intelligence into persistent agency. Intelligence is not merely the ability to generate an accurate prediction or sophisticated answer; it requires maintaining context, integrating knowledge, selecting goals, anticipating consequences, acting, detecting errors, and learning across time. Architecture determines how these abilities become one coherent system.

The resulting cognitive cycle can be viewed as an ongoing interaction among observation, state construction, memory retrieval, reasoning, prediction, planning, action, evaluation, and learning. These processes may operate sequentially, concurrently, or hierarchically depending on the situation. Their coordination allows the system to remain responsive to immediate events while preserving longer-term objectives and accumulated knowledge.

A cognitive architecture should therefore be understood as the structural and operational blueprint of an intelligent agent. It specifies what major cognitive mechanisms exist, what information they maintain, how they communicate, when they operate, and how feedback changes future processing. For increasingly general AI systems, this architectural perspective is essential because intelligence depends not only on capable components, but on how those components cooperate as a unified adaptive system.

인지 아키텍처(Cognitive Architecture)는 지능형 시스템의 주요 메커니즘들이 어떻게 상호작용하여 일관된 인지(cognition)와 행동(behavior)을 만들어내는지를 규정하는 체계적인 프레임워크(framework)이다. 하나의 알고리즘, 모델 또는 신경망(neural network)을 설명하는 것이 아니라 지각(perception), 기억(memory), 추론(reasoning), 학습(learning), 계획(planning), 행동(action), 제어(control)가 시간의 흐름에 따라 어떻게 정보를 교환하는지를 정의한다. 따라서 지능을 이해하고 구현하기 위한 시스템 수준의 구조(system-level structure)를 제공한다.

이 개념은 인지를 하나의 독립된 능력이 아니라 서로 조정되는 여러 과정의 집합으로 설명하려는 시도에서 출발한다. 인간의 지능은 여러 메커니즘이 함께 작동하는 것에 의존한다. 감각 정보(sensory information)를 해석하고, 관련 지식을 검색하며, 대안을 평가하고, 의사결정을 형성한 뒤 행동을 실행해야 한다. 인지 아키텍처는 이러한 조직 구조를 지속적이고 적응적인 지능 행동을 지원할 수 있는 계산적 형태(computational form)로 구현하려 한다.

인지 아키텍처는 범위(scope) 측면에서 일반적인 인공지능 모델(AI model)과 다르다. 하나의 모델은 분류(classification), 예측(prediction), 언어 생성(language generation), 정책 추정(policy estimation)을 수행할 수 있지만, 아키텍처는 여러 모델과 계산 과정이 어떻게 협력하는지를 결정한다. 또한 전문화된 능력이 더 큰 인지 시스템의 구성 요소가 될 수 있도록 표현, 정보 흐름, 제어 메커니즘, 기억 접근, 의사결정 주기(decision cycle), 인터페이스(interface)를 정의한다.

지각(perception)은 외부 환경과 에이전트(agent) 자체에 관한 관측 정보를 아키텍처에 제공한다. 원시 감각 신호(raw sensory signal), 언어, 이미지, 공간 측정값 또는 디지털 사건(digital event)은 다른 인지 메커니즘이 사용할 수 있는 표현(representation)으로 변환되어야 한다. 아키텍처는 이러한 표현을 어떻게 유지하고, 기존 지식과 결합하며, 새로운 증거가 현재 상황에 대한 해석을 변화시킬 때 어떻게 갱신할지를 결정한다.

기억(memory)은 즉각적인 관측을 넘어서는 연속성(continuity)을 제공한다. 작업 기억(working memory)은 현재 수행 중인 작업에 필요한 정보를 유지할 수 있고, 장기 기억(long-term memory)은 오랜 기간 동안 지식과 경험을 보존할 수 있다. 일화 기억(episodic memory), 의미 기억(semantic memory), 절차 기억(procedural memory)은 서로 다른 기능을 담당할 수 있다. 인지 아키텍처는 정보가 기억에 어떻게 저장되고, 관련 내용이 어떻게 검색되며, 검색된 지식이 현재의 인지 과정에 어떻게 영향을 미치는지를 규정한다.

추론(reasoning)은 이용 가능한 정보를 결론, 설명, 가설(hypothesis), 의사결정으로 변환한다. 아키텍처에 따라 이러한 과정에는 기호 규칙(symbolic rule), 확률적 추론(probabilistic inference), 신경망 계산(neural computation), 인과 모델(causal model), 탐색(search), 시뮬레이션(simulation) 또는 이러한 방법들의 조합이 사용될 수 있다. 아키텍처의 핵심 문제는 추론이 어떻게 수행되는가뿐만 아니라 언제 추론을 수행하고 그 결과가 다른 인지 과정에 어떻게 영향을 미치는가까지 포함한다.

계획(planning)은 미래 시간에 걸쳐 인지 활동을 조직한다. 에이전트가 현재 상태에 대한 추정과 원하는 목표(objective)를 가지고 있다면 두 상태 사이의 차이를 줄이기 위해 어떤 행동 순서를 수행해야 하는지 결정해야 한다. 인지 아키텍처는 목표(goal), 하위 목표(subgoal), 대안 전략(alternative strategy), 의존관계(dependency), 제약조건(constraint), 예상 결과를 표현함으로써 단순한 자극-반응 관계(stimulus-response relationship)를 넘어서는 행동을 가능하게 한다.

학습(learning)은 경험을 통해 아키텍처 자체가 변화할 수 있도록 한다. 새로운 관측은 표현을 개선할 수 있고, 성공적인 행동은 정책(policy)을 강화할 수 있으며, 실패는 잘못된 가정을 발견하게 하고, 반복적인 경험은 재사용 가능한 지식이나 기술(skill)을 형성할 수 있다. 따라서 학습은 지능형 시스템이 작동하기 전에 수행되는 별도의 훈련 과정에만 존재하는 것이 아니라 여러 아키텍처 구성 요소에 지속적으로 영향을 미친다.

행동(action)은 내부 인지와 외부의 결과를 연결한다. 의사결정과 계획은 결국 물리적 움직임, 통신, 소프트웨어 연산 또는 도구 사용(tool use)을 통해 환경에 영향을 주는 명령으로 변환되어야 한다. 이러한 행동의 결과는 새로운 관측을 발생시키며, 인지가 세계에 영향을 미치고 변화된 세계가 다시 인지에 영향을 주는 폐쇄형 상호작용 루프(closed interaction loop)를 형성한다.

제어 메커니즘(control mechanism)은 특정 시점에 어떤 인지 과정이 작동해야 하는지를 결정한다. 지능형 시스템이 가능한 모든 추론, 검색, 계획, 학습 연산을 동시에 수행할 수 있는 것은 아니다. 따라서 아키텍처에는 제한된 계산 자원을 현재 중요한 문제에 집중할 수 있도록 주의(attention), 우선순위 설정(prioritization), 작업 전환(task switching), 자원 할당(resource allocation), 중단(interruption), 동기화(synchronization)를 관리하는 메커니즘이 필요하다.

이러한 요구사항으로 인해 인지 아키텍처는 본질적으로 시간적(temporal) 특성을 갖는다. 지능은 하나의 고립된 계산으로 발생하는 것이 아니라 내부 및 외부 사건의 연속적인 흐름을 통해 전개된다. 관측이 들어오고, 기억이 활성화되고, 목표가 변경되며, 추론 과정에서 중간 결과가 생성되고, 계획이 수정되고, 행동이 수행된 뒤 피드백(feedback)이 돌아온다. 아키텍처는 시스템이 지속적으로 변화하는 동안 이러한 과정들이 어떻게 조정 상태를 유지하는지를 정의한다.

인지 내용(cognitive content)과 인지 과정(cognitive process)을 구분하는 것도 유용하다. 인지 내용에는 신념(belief), 관측, 목표, 기억, 예측, 객체나 상황에 대한 표현이 포함된다. 인지 과정은 이러한 내용을 검색하고, 변환하고, 비교하고, 평가하고, 저장하거나 이를 기반으로 행동한다. 따라서 인지 아키텍처는 내부에 어떤 종류의 정보가 존재하는지와 그 정보를 어떤 연산을 통해 변화시킬 수 있는지를 모두 정의해야 한다.

따라서 표현(representation)은 핵심적인 아키텍처 문제이다. 정보는 기호적(symbolic), 수치적(numerical), 확률적(probabilistic), 기하학적(geometric) 형태 또는 분산 신경 임베딩(distributed neural embedding)으로 표현될 수 있으며, 이러한 방법들을 결합할 수도 있다. 서로 다른 표현은 서로 다른 연산을 효율적으로 지원한다. 현대의 아키텍처는 구조화된 지식, 학습된 표현, 감각 상태, 행동 관련 정보가 공존하고 상호작용할 수 있는 메커니즘을 점점 더 필요로 한다.

전통적인 기호적 인지 아키텍처(symbolic cognitive architecture)는 명시적인 지식 구조와 이를 대상으로 수행되는 연산을 강조한다. 규칙(rule), 기호(symbol), 목표, 생성 시스템(production system)은 추론과 문제 해결을 위한 해석 가능한 메커니즘을 제공할 수 있다. 이러한 아키텍처는 내부 조건과 적용 가능한 연산을 반복적으로 대응시키는 순환을 통해 복잡한 행동이 발생할 수 있음을 보여주지만, 대규모의 포괄적인 기호 지식을 사람이 직접 구축하는 것은 어려울 수 있다.

연결주의 접근법(connectionist approach)은 이와 달리 분산 표현(distributed representation)과 학습된 변환(learned transformation)을 강조한다. 신경망은 데이터로부터 복잡한 대응 관계를 직접 학습하고 지각, 언어, 예측, 표현 학습(representation learning)에서 강력한 능력을 제공할 수 있다. 내부 지식은 일반적으로 기호 시스템보다 명시적인 구조를 갖지 않지만, 통계적 규칙성(statistical regularity)을 학습하는 능력으로 인해 현대 인지 아키텍처의 중요한 구성 요소가 된다.

하이브리드 인지 아키텍처(hybrid cognitive architecture)는 이러한 상호보완적인 장점을 결합하려 한다. 학습된 신경망 구성 요소는 감각 정보를 해석하고 유연한 표현을 생성하며, 구조화된 기억, 계획 시스템, 추론 메커니즘 또는 명시적인 제약조건은 조직화와 제어를 제공할 수 있다. 목표는 지능을 순수하게 신경망 영역과 기호 영역으로 나누는 것이 아니라 각각의 계산 메커니즘이 가진 장점을 가장 효과적인 위치에서 활용하는 것이다.

현대의 파운데이션 모델(foundation model)은 하나의 대규모 학습 모델이 여러 인지 기능을 지원할 수 있다는 또 다른 아키텍처 가능성을 제공한다. 언어 또는 멀티모달 파운데이션 모델(multimodal foundation model)은 지각, 추론, 계획, 지식 검색, 통신, 도구 선택에 기여할 수 있다. 그러나 광범위한 모델 능력이 지속적 기억, 환경 상호작용, 실행 모니터링, 안전 제약, 장기 목표 관리와 같은 아키텍처 요구사항을 제거하는 것은 아니다.

따라서 인지 아키텍처는 하나의 모델을 에이전트(agent)로 전환할 때 특히 중요하다. 일반적인 모델은 입력을 받아 출력을 생성하지만, 에이전트는 시간에 걸쳐 상태를 유지하고, 목표를 추구하며, 행동을 선택하고, 결과를 관측하며, 미래의 행동을 적응적으로 변경해야 한다. 아키텍처는 일회적인 모델 추론(model inference)을 지속적인 목표 지향 상호작용(goal-directed interaction)으로 전환하는 데 필요한 영속적 메커니즘을 제공한다.

에이전트의 내부 상태(internal state)는 서로 다른 메커니즘을 연결하는 공유 문맥(shared context)의 역할을 한다. 여기에는 현재 관측, 활성화된 목표, 검색된 기억, 신념, 불확실성 추정(uncertainty estimate), 계획, 사용 가능한 자원, 최근 행동이 포함될 수 있다. 구성 요소들이 호환 가능한 상태 표현을 기반으로 작동하면 지각 정보가 추론에 영향을 주고, 추론 결과가 계획에 영향을 주며, 실행 결과가 기억과 학습을 갱신할 수 있다.

월드 모델(world model)은 환경의 관련 요소가 어떻게 변화하는지를 표현함으로써 이러한 내부 상태를 확장할 수 있다. 현재 관측만을 기반으로 추론하는 대신 아키텍처는 후보 행동(candidate action)에 따른 미래 상태를 예측할 수 있다. 이러한 예측은 계획, 반사실적 추론(counterfactual reasoning), 위험 평가(risk assessment), 선제적 행동(proactive behavior)을 지원한다. 실행 후 발생하는 예측 오차(prediction error)는 내부 모델에서 수정하거나 추가 학습해야 하는 부분을 알려줄 수 있다.

메타인지(metacognition)는 시스템이 자신의 인지 활동을 평가할 수 있게 함으로써 또 하나의 아키텍처 계층을 추가한다. 신뢰도(confidence), 불확실성(uncertainty), 추론 품질, 계획 진행 상태, 자원 사용량, 오류 신호(error signal)를 모니터링 대상으로 만들 수 있다. 메타인지 메커니즘은 추가적인 추론이 필요한지, 다른 전략을 선택해야 하는지 또는 외부 지원을 요청해야 하는지를 판단할 수 있다.

주의(attention) 역시 사용 가능한 정보 가운데 어떤 부분을 우선적으로 처리할지를 결정한다는 점에서 아키텍처적 기능이다. 복잡한 환경에는 에이전트가 모든 순간에 동일한 수준으로 처리할 수 있는 것보다 훨씬 많은 정보가 존재한다. 주의는 관련성과 긴급성(urgency)에 따라 관측, 기억, 목표 또는 내부 가설(hypothesis)의 우선순위를 정함으로써 계산 부하를 관리하면서 중요한 변화에 대한 대응성을 유지하도록 한다.

계층적 조직(hierarchical organization)은 복잡성을 해결하는 또 다른 방법을 제공한다. 상위 수준 메커니즘은 추상적인 목표와 전략을 추론하고, 하위 수준에서는 기술, 궤적(trajectory), 즉각적인 제어를 처리할 수 있다. 각 계층은 서로 다른 시간적 빈도와 추상화 수준에서 작동할 수 있다. 이를 통해 하나의 메커니즘이 모든 세부사항을 처리하지 않고도 장기적인 숙고(deliberation)와 빠른 반응형 행동(reactive behavior)을 함께 구현할 수 있다.

피드백 루프(feedback loop)는 인지가 실제 결과에 기반을 유지해야 하기 때문에 필수적이다. 계획은 행동을 만들고, 행동은 환경을 변화시키며, 그 결과 발생한 관측은 기존의 예상이 정확했는지를 알려준다. 아키텍처는 이러한 차이를 이용하여 상태 추정을 수정하고, 계획을 변경하고, 모델을 갱신하거나, 새로운 학습을 시작할 수 있다. 따라서 폐루프 인지(closed-loop cognition)는 고정된 실행을 지속적인 적응으로 전환한다.

인지 아키텍처의 능력이 증가할수록 자원 관리(resource management)의 중요성도 커진다. 추론, 시뮬레이션, 검색, 지각, 모델 추론은 시간, 에너지, 메모리, 계산 자원을 소비한다. 아키텍처는 일상적인 상황에서는 비용이 낮은 처리를 사용하고, 불확실성이나 새로움(novelty), 위험이 추가 비용을 정당화하는 경우 더 깊은 추론이나 추가 모델을 활성화하는 방식으로 이러한 자원을 동적으로 할당할 수 있다.

안전(safety) 역시 아키텍처 수준에서 표현되어야 한다. 제약조건은 응답이 생성된 이후에만 적용되는 것이 아니라 목표, 계획, 행동 선택, 실행, 학습에 영향을 미칠 수 있다. 모니터링 메커니즘은 비정상 상태를 탐지하고, 금지된 행동을 방지하고, 위험한 실행을 중단하며, 신뢰도가 충분하지 않은 경우 인간 감독(human oversight)을 요청할 수 있다. 분산된 안전장치(distributed safeguard)는 바람직하지 않은 행동을 방지할 수 있는 여러 단계의 기회를 제공한다.

AGI에서 인지 아키텍처는 궁극적으로 전문화된 지능 능력을 지속적인 에이전시(persistent agency)로 연결하는 조직적 기반을 제공한다. 지능은 단순히 정확한 예측이나 정교한 답변을 생성하는 능력만을 의미하지 않는다. 문맥을 유지하고, 지식을 통합하고, 목표를 선택하고, 결과를 예측하고, 행동하며, 오류를 탐지하고, 시간의 흐름에 따라 학습할 수 있어야 한다. 아키텍처는 이러한 능력들이 하나의 일관된 시스템으로 결합되는 방식을 결정한다.

그 결과 나타나는 인지 순환(cognitive cycle)은 관측, 상태 구성(state construction), 기억 검색, 추론, 예측, 계획, 행동, 평가(evaluation), 학습 사이에서 지속적으로 이루어지는 상호작용으로 이해할 수 있다. 이러한 과정은 상황에 따라 순차적, 병렬적 또는 계층적으로 작동할 수 있다. 이들의 조정을 통해 시스템은 축적된 지식과 장기적인 목표를 유지하면서도 즉각적으로 발생하는 사건에 대응할 수 있다.

따라서 인지 아키텍처는 지능형 에이전트의 구조적·운영적 청사진(structural and operational blueprint)으로 이해할 수 있다. 어떤 주요 인지 메커니즘이 존재하는지, 어떤 정보를 유지하는지, 서로 어떻게 통신하는지, 언제 작동하는지, 피드백이 이후의 처리 과정을 어떻게 변화시키는지를 정의한다. 점차 범용화되는 AI 시스템에서 이러한 아키텍처적 관점은 매우 중요하며, 지능은 개별 구성 요소의 능력뿐 아니라 그 구성 요소들이 하나의 통합된 적응형 시스템(unified adaptive system)으로 어떻게 협력하는지에 의해 결정된다.

##  

## 04.01. ACT R

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

ACT-R, or Adaptive Control of Thought---Rational, is a cognitive architecture designed to model how human cognition emerges from the coordinated operation of memory, perception, learning, and action. Rather than treating intelligence as a single computational function, ACT-R represents cognition as a collection of specialized modules that exchange information through a central production system, producing goal-directed behavior over time.

The architecture is based on the idea that human cognition contains both declarative knowledge and procedural knowledge. Declarative knowledge represents facts, concepts, and remembered experiences, while procedural knowledge specifies how cognition and action should proceed under particular conditions. ACT-R separates these forms because knowing that something is true is fundamentally different from knowing how to perform an operation or accomplish a task.

Declarative knowledge is stored in declarative memory as structures called chunks. A chunk represents a unit of information containing attributes and values, such as an object, event, goal, relationship, or previously encountered situation. Chunks can be retrieved when they match the requirements of the current task, allowing past knowledge to influence present reasoning without requiring the entire memory system to be searched explicitly.

Memory retrieval in ACT-R is not purely symbolic or deterministic. Each chunk has an activation level that reflects factors such as previous use, recency, frequency, and contextual relevance. Highly activated chunks are more likely to be retrieved quickly, while weakly activated information may require more time or fail to be recalled. This mechanism allows the architecture to reproduce important characteristics of human memory, including forgetting and practice effects.

Procedural knowledge is represented through production rules, commonly expressed as condition-action relationships. A production examines the information currently available in different cognitive buffers and determines whether its conditions are satisfied. If selected, it performs an action such as changing a goal, requesting information from memory, directing attention, or initiating a motor operation. Cognition emerges from repeated cycles of production selection and execution.

Buffers are critical because they provide limited interfaces between the production system and specialized cognitive modules. Rather than allowing every component to access all internal information simultaneously, each module places a small amount of currently relevant information into a buffer. The production system evaluates these buffer contents, making ACT-R cognition strongly dependent on limited-capacity information flow rather than unlimited global access.

A goal buffer maintains information about the agent\'s current objective or problem state. Declarative memory provides retrieved knowledge through a retrieval buffer, while perceptual modules provide information about visual or auditory input. Motor modules support interaction with the environment. Through these interfaces, symbolic reasoning, memory retrieval, perception, and action become coordinated within a repeated cognitive cycle.

ACT-R therefore offers an example of modular cognitive architecture. Specialized systems handle functions such as memory, vision, motor control, and goal representation, while the production system coordinates their operation. This separation allows each mechanism to exhibit different timing and processing characteristics while still contributing to unified behavior. Intelligence arises from interaction among modules rather than from one undifferentiated processing mechanism.

Time is an important part of ACT-R modeling. Cognitive operations such as retrieving a memory, shifting visual attention, selecting a production, or executing a movement require measurable amounts of time. Consequently, ACT-R models can predict not only which behavior may occur but also how long particular cognitive operations may take. This has made the architecture useful for comparing computational models with human reaction-time and task-performance data.

Learning occurs in several parts of the architecture. Repeated retrieval changes the accessibility of declarative knowledge, while repeated successful behavior can influence procedural processing. Production utilities can represent the expected usefulness of alternative actions, enabling the system to prefer rules that have historically produced better results. Experience therefore changes both what information is easily available and which cognitive operations are likely to be selected.

ACT-R also provides mechanisms through which complex skills can gradually become more efficient. Early performance may require several explicit steps involving memory retrieval and deliberate reasoning, while repeated practice can lead to increasingly direct procedural behavior. This reflects an important aspect of human skill acquisition: tasks that initially demand substantial conscious processing can eventually become faster and more automatic through repeated experience.

The architecture can be understood as a continuous perception-cognition-action loop. Environmental information enters through perceptual modules, relevant knowledge is retrieved, production rules determine the next cognitive operation, and motor or external actions modify the environment. New observations then enter the architecture again. This recurrent structure makes cognition an ongoing interaction process rather than a single input-output transformation.

One important contribution of ACT-R is its attempt to connect symbolic cognition with quantitative constraints. Chunks and productions provide structured symbolic representations, while activation, retrieval latency, production utility, and timing introduce numerical mechanisms. ACT-R is therefore not simply a classical rule-based system; it combines symbolic organization with subsymbolic quantities that influence which memories and actions become behaviorally available.

This symbolic-subsymbolic combination is relevant to modern discussions of general intelligence. Purely symbolic systems provide explicit structures for goals and reasoning but often struggle with flexible learning from raw data, while neural systems learn rich statistical representations but may lack explicit cognitive organization. ACT-R demonstrates an architectural principle in which structured cognitive processes can coexist with graded, experience-sensitive mechanisms.

Nevertheless, ACT-R was developed primarily as a theory and computational framework for human cognition rather than as a direct blueprint for contemporary AGI. Its modules and assumptions are intended to explain psychological behavior under controlled tasks. Modern AGI systems must additionally address large-scale multimodal perception, foundation models, open-ended learning, world modeling, tool use, long-term autonomy, and operation in highly complex environments.

For AGI research, ACT-R is therefore especially valuable as an architectural reference. It shows how memory, goals, perception, procedural knowledge, learning, and action can be organized around clearly defined interfaces and processing cycles. The important lesson is not necessarily that AGI should reproduce ACT-R exactly, but that general intelligence requires mechanisms that coordinate specialized cognitive functions while preserving persistent goals and internal state.

ACT-R also highlights the importance of bounded cognition. The architecture does not assume unlimited memory access, instantaneous reasoning, or cost-free decision making. Retrieval takes time, information availability is constrained, and competing actions must be selected. These restrictions create behavior that is more realistic than an idealized agent with perfect access to all knowledge and unlimited computation, and they remain relevant when designing resource-aware artificial agents.

A modern interpretation could connect ACT-R\'s declarative memory with structured long-term memory or retrieval systems, production rules with policy or orchestration mechanisms, goal buffers with agent state, and perceptual modules with multimodal foundation models. Such mappings are conceptual rather than direct equivalences, but they illustrate how classical cognitive-architecture ideas can inform contemporary systems that combine learned models with explicit memory and control.

Metacognitive mechanisms can further extend this architecture by monitoring retrieval confidence, strategy effectiveness, resource consumption, and task progress. Although basic ACT-R cognition focuses primarily on coordinated object-level processing, broader AGI architectures can place supervisory mechanisms above similar cognitive loops. These mechanisms can determine when additional retrieval, reasoning, replanning, or external assistance is required.

World models provide another extension that becomes particularly important for autonomous agents. ACT-R-style goal and production mechanisms can organize behavior, while learned predictive models estimate how external states may evolve. Combining explicit cognitive control with predictive representations would allow an agent not only to react according to current knowledge but also to evaluate possible future consequences before committing to an action.

The production-cycle perspective also demonstrates how complex behavior can emerge incrementally. An agent does not need to solve an entire problem in one computation. Instead, each cycle updates a small portion of the cognitive state, retrieves information, selects an operation, or changes a goal. Repeated cycles can collectively produce multi-step reasoning and behavior, providing an architectural alternative to treating intelligence as a single monolithic inference process.

In the broader cognitive-architecture landscape, ACT-R represents a highly influential example of how cognition can be decomposed while remaining integrated. Its distinction between declarative and procedural knowledge, modular processing, limited buffers, subsymbolic activation, utility-based selection, learning, and explicit timing provides a coherent framework for studying how multiple cognitive mechanisms jointly produce observable behavior.

From an AGI perspective, the enduring significance of ACT-R lies in its system-level view of intelligence. General intelligence requires more than powerful prediction or language generation; it requires persistent goals, accessible knowledge, controlled information flow, adaptive decision mechanisms, learning from experience, and continuous interaction with an environment. ACT-R provides an important historical and conceptual foundation for understanding how such mechanisms can be organized into a unified cognitive architecture.

ACT-R(Adaptive Control of Thought---Rational)는 인간의 인지(human cognition)가 기억(memory), 지각(perception), 학습(learning), 행동(action)의 조정된 작동을 통해 어떻게 나타나는지를 모델링하기 위해 설계된 인지 아키텍처(cognitive architecture)이다. ACT-R은 지능을 하나의 계산 기능으로 취급하지 않고, 중앙 생성 시스템(central production system)을 통해 정보를 교환하는 전문화된 여러 모듈(module)의 집합으로 표현하며, 이를 통해 시간에 따른 목표 지향 행동(goal-directed behavior)을 만들어낸다.

이 아키텍처는 인간의 인지가 선언적 지식(declarative knowledge)과 절차적 지식(procedural knowledge)을 모두 포함한다는 개념을 기반으로 한다. 선언적 지식은 사실, 개념, 기억된 경험을 표현하며, 절차적 지식은 특정 조건에서 인지와 행동이 어떻게 진행되어야 하는지를 규정한다. ACT-R은 어떤 사실이 참이라는 것을 아는 것과 어떤 연산을 수행하거나 작업을 완수하는 방법을 아는 것은 근본적으로 다르기 때문에 이 두 형태의 지식을 구분한다.

선언적 지식(declarative knowledge)은 청크(chunk)라고 불리는 구조의 형태로 선언적 기억(declarative memory)에 저장된다. 하나의 청크는 객체, 사건, 목표, 관계 또는 이전에 경험한 상황과 같은 정보를 속성(attribute)과 값(value)의 형태로 포함하는 정보 단위를 나타낸다. 청크는 현재 작업의 요구조건과 일치할 때 검색될 수 있으며, 이를 통해 전체 기억 시스템을 명시적으로 모두 탐색하지 않고도 과거의 지식이 현재의 추론에 영향을 줄 수 있다.

ACT-R의 기억 검색(memory retrieval)은 순수하게 기호적(symbolic)이거나 결정론적(deterministic)이지 않다. 각각의 청크에는 이전 사용, 최근성(recency), 빈도(frequency), 문맥적 관련성(contextual relevance)과 같은 요소를 반영하는 활성화 수준(activation level)이 존재한다. 활성화 수준이 높은 청크는 더 빠르게 검색될 가능성이 높으며, 활성화가 약한 정보는 더 많은 시간이 필요하거나 회상에 실패할 수도 있다. 이를 통해 망각(forgetting)과 연습 효과(practice effect)를 포함한 인간 기억의 중요한 특성을 재현할 수 있다.

절차적 지식(procedural knowledge)은 일반적으로 조건-행동 관계(condition-action relationship)로 표현되는 생성 규칙(production rule)을 통해 나타난다. 하나의 생성 규칙은 여러 인지 버퍼(cognitive buffer)에 현재 존재하는 정보를 검사하고 자신의 조건이 충족되는지를 판단한다. 선택된 규칙은 목표를 변경하거나, 기억에서 정보를 요청하거나, 주의를 전환하거나, 운동 동작(motor operation)을 시작하는 등의 행동을 수행한다. 인지는 이러한 생성 규칙의 선택과 실행이 반복되는 순환을 통해 형성된다.

버퍼(buffer)는 생성 시스템과 전문화된 인지 모듈 사이에서 제한된 인터페이스(interface)를 제공하기 때문에 매우 중요하다. 모든 구성 요소가 모든 내부 정보에 동시에 접근하도록 허용하는 대신 각 모듈은 현재 관련성이 높은 소량의 정보만 버퍼에 배치한다. 생성 시스템은 이러한 버퍼의 내용을 평가하며, 이에 따라 ACT-R의 인지는 제한 없는 전역 접근(unlimited global access)이 아니라 제한된 용량의 정보 흐름(limited-capacity information flow)에 크게 의존한다.

목표 버퍼(goal buffer)는 에이전트(agent)의 현재 목표 또는 문제 상태(problem state)에 관한 정보를 유지한다. 선언적 기억은 검색 버퍼(retrieval buffer)를 통해 검색된 지식을 제공하고, 지각 모듈(perceptual module)은 시각 또는 청각 입력에 대한 정보를 제공한다. 운동 모듈(motor module)은 환경과의 상호작용을 지원한다. 이러한 인터페이스를 통해 기호적 추론, 기억 검색, 지각, 행동이 반복적인 인지 순환(cognitive cycle) 안에서 서로 조정된다.

따라서 ACT-R은 모듈형 인지 아키텍처(modular cognitive architecture)의 한 사례를 제공한다. 전문화된 시스템은 기억, 시각, 운동 제어, 목표 표현(goal representation)과 같은 기능을 담당하고, 생성 시스템(production system)은 이들의 작동을 조정한다. 이러한 분리를 통해 각 메커니즘은 서로 다른 시간적 특성과 처리 특성을 유지하면서도 통합된 행동에 기여할 수 있다. 지능은 하나의 분리되지 않은 처리 메커니즘이 아니라 여러 모듈 사이의 상호작용에서 발생한다.

시간(time)은 ACT-R 모델링에서 중요한 요소이다. 기억 검색, 시각적 주의(visual attention)의 이동, 생성 규칙의 선택, 움직임 실행과 같은 인지 연산에는 측정 가능한 시간이 필요하다. 따라서 ACT-R 모델은 어떤 행동이 발생할지를 예측할 뿐 아니라 특정 인지 연산에 얼마나 많은 시간이 필요한지도 예측할 수 있다. 이러한 특성으로 인해 ACT-R은 계산 모델(computational model)을 인간의 반응 시간(reaction time) 및 작업 수행 데이터(task-performance data)와 비교하는 데 유용하게 활용되어 왔다.

학습(learning)은 아키텍처의 여러 부분에서 발생한다. 반복적인 검색은 선언적 지식의 접근성(accessibility)을 변화시키고, 반복적으로 성공한 행동은 절차적 처리(procedural processing)에 영향을 줄 수 있다. 생성 효용(production utility)은 대안 행동의 예상 유용성(expected usefulness)을 표현할 수 있으며, 이를 통해 시스템은 과거에 더 좋은 결과를 만들어낸 규칙을 선호할 수 있다. 따라서 경험은 어떤 정보에 쉽게 접근할 수 있는지뿐 아니라 어떤 인지 연산이 선택될 가능성이 높은지도 변화시킨다.

ACT-R은 복잡한 기술(skill)이 점차 효율적으로 변화하는 과정도 설명할 수 있는 메커니즘을 제공한다. 초기 수행에서는 기억 검색과 숙고적 추론(deliberative reasoning)을 포함한 여러 명시적인 단계가 필요할 수 있지만, 반복적인 연습을 통해 점차 직접적인 절차적 행동(procedural behavior)으로 변화할 수 있다. 이는 처음에는 상당한 의식적 처리가 필요했던 작업이 반복적인 경험을 통해 점차 빠르고 자동적으로 수행되는 인간의 기술 습득(skill acquisition)의 중요한 특성을 반영한다.

이 아키텍처는 지속적인 지각-인지-행동 순환(perception-cognition-action loop)으로 이해할 수 있다. 환경 정보는 지각 모듈을 통해 입력되고, 관련 지식이 검색되며, 생성 규칙이 다음 인지 연산을 결정하고, 운동 또는 외부 행동이 환경을 변화시킨다. 이후 새로운 관측이 다시 아키텍처로 입력된다. 이러한 반복 구조는 인지를 단일한 입력-출력 변환(input-output transformation)이 아니라 지속적인 상호작용 과정으로 만든다.

ACT-R의 중요한 기여 가운데 하나는 기호적 인지(symbolic cognition)를 정량적 제약(quantitative constraint)과 연결하려는 시도이다. 청크와 생성 규칙은 구조화된 기호 표현(symbolic representation)을 제공하며, 활성화(activation), 검색 지연시간(retrieval latency), 생성 효용, 시간적 처리 특성은 수치적 메커니즘을 도입한다. 따라서 ACT-R은 단순한 고전적 규칙 기반 시스템(rule-based system)이 아니라 어떤 기억과 행동이 실제 행동으로 나타날지를 결정하는 기호적 조직과 하위기호적 수량(subsymbolic quantity)을 결합한다.

이러한 기호적-하위기호적 결합(symbolic-subsymbolic combination)은 현대의 범용 지능(general intelligence)에 관한 논의와도 관련이 있다. 순수한 기호 시스템은 목표와 추론을 위한 명시적인 구조를 제공하지만 원시 데이터(raw data)로부터 유연하게 학습하는 데 어려움을 겪는 경우가 많다. 반면 신경망 시스템(neural system)은 풍부한 통계적 표현을 학습하지만 명시적인 인지 조직(cognitive organization)이 부족할 수 있다. ACT-R은 구조화된 인지 과정과 경험에 따라 변화하는 연속적 메커니즘이 공존할 수 있다는 아키텍처 원리를 보여준다.

그러나 ACT-R은 현대적인 AGI를 직접 구현하기 위한 청사진이라기보다 주로 인간 인지에 관한 이론과 계산 프레임워크(computational framework)로 개발되었다. ACT-R의 모듈과 가정은 통제된 작업에서 나타나는 인간의 심리적 행동을 설명하기 위한 것이다. 현대 AGI 시스템은 이에 더해 대규모 멀티모달 지각(multimodal perception), 파운데이션 모델(foundation model), 개방형 학습(open-ended learning), 월드 모델링(world modeling), 도구 사용(tool use), 장기 자율성(long-term autonomy), 복잡한 환경에서의 운용을 처리해야 한다.

따라서 AGI 연구에서 ACT-R은 특히 아키텍처적 참고 모델(architectural reference)로서 가치가 있다. ACT-R은 기억, 목표, 지각, 절차적 지식, 학습, 행동이 명확하게 정의된 인터페이스와 처리 순환을 중심으로 어떻게 조직될 수 있는지를 보여준다. 중요한 교훈은 AGI가 ACT-R을 그대로 재현해야 한다는 것이 아니라, 범용 지능을 위해서는 지속적인 목표와 내부 상태를 유지하면서 전문화된 인지 기능들을 조정하는 메커니즘이 필요하다는 것이다.

ACT-R은 제한된 인지(bounded cognition)의 중요성도 강조한다. 이 아키텍처는 무제한적인 기억 접근, 즉각적인 추론 또는 비용이 없는 의사결정을 가정하지 않는다. 기억 검색에는 시간이 필요하고, 이용 가능한 정보에는 제약이 있으며, 서로 경쟁하는 행동 가운데 하나를 선택해야 한다. 이러한 제약은 모든 지식과 무제한 계산 자원에 완벽하게 접근할 수 있는 이상화된 에이전트보다 현실적인 행동을 만들어내며, 자원 인식형 인공지능 에이전트(resource-aware artificial agent)를 설계할 때도 여전히 중요한 의미를 갖는다.

현대적인 관점에서는 ACT-R의 선언적 기억을 구조화된 장기 기억(structured long-term memory)이나 검색 시스템(retrieval system)에, 생성 규칙을 정책(policy)이나 오케스트레이션 메커니즘(orchestration mechanism)에, 목표 버퍼를 에이전트 상태(agent state)에, 지각 모듈을 멀티모달 파운데이션 모델(multimodal foundation model)에 대응시켜 생각할 수 있다. 이러한 대응은 직접적인 등가 관계가 아니라 개념적인 연결이지만, 고전적 인지 아키텍처의 아이디어가 학습 모델과 명시적 기억 및 제어를 결합하는 현대 시스템에 어떻게 활용될 수 있는지를 보여준다.

메타인지 메커니즘(metacognitive mechanism)은 검색 신뢰도(retrieval confidence), 전략의 효과성, 자원 소비, 작업 진행 상태를 모니터링함으로써 이러한 아키텍처를 더욱 확장할 수 있다. 기본적인 ACT-R 인지는 주로 조정된 객체 수준 처리(object-level processing)에 초점을 맞추지만, 보다 광범위한 AGI 아키텍처에서는 이와 유사한 인지 순환 위에 감독 메커니즘(supervisory mechanism)을 배치할 수 있다. 이를 통해 추가적인 검색, 추론, 재계획(replanning) 또는 외부 지원이 필요한 시점을 결정할 수 있다.

월드 모델(world model)은 자율 에이전트(autonomous agent)에서 특히 중요해지는 또 다른 확장 요소를 제공한다. ACT-R 방식의 목표 및 생성 메커니즘은 행동을 조직하고, 학습된 예측 모델(predictive model)은 외부 상태가 어떻게 변화할지를 추정할 수 있다. 명시적인 인지 제어(explicit cognitive control)와 예측 표현(predictive representation)을 결합하면 에이전트는 현재 지식에 따라 반응하는 것뿐 아니라 행동을 실행하기 전에 가능한 미래 결과를 평가할 수 있다.

생성 순환 관점(production-cycle perspective)은 복잡한 행동이 점진적으로 발생할 수 있다는 점도 보여준다. 에이전트는 하나의 계산 과정에서 전체 문제를 한꺼번에 해결할 필요가 없다. 대신 각각의 순환에서 인지 상태의 일부를 갱신하거나, 정보를 검색하거나, 하나의 연산을 선택하거나, 목표를 변경할 수 있다. 이러한 순환이 반복적으로 축적되면서 다단계 추론(multi-step reasoning)과 행동이 생성되며, 이는 지능을 하나의 거대한 단일 추론(monolithic inference) 과정으로 취급하는 방식과 다른 아키텍처적 접근법을 제공한다.

보다 광범위한 인지 아키텍처의 관점에서 ACT-R은 인지를 분해하면서도 통합된 상태를 유지하는 방법을 보여주는 매우 영향력 있는 사례이다. 선언적 지식과 절차적 지식의 구분, 모듈형 처리(modular processing), 제한된 버퍼, 하위기호적 활성화(subsymbolic activation), 효용 기반 선택(utility-based selection), 학습, 명시적인 시간 모델링(explicit timing)은 여러 인지 메커니즘이 함께 관측 가능한 행동을 생성하는 방식을 연구하기 위한 일관된 프레임워크를 제공한다.

AGI 관점에서 ACT-R이 갖는 지속적인 중요성은 지능을 시스템 수준(system-level)에서 바라본다는 점에 있다. 범용 지능은 강력한 예측이나 언어 생성만으로 이루어지는 것이 아니라 지속적인 목표, 접근 가능한 지식, 통제된 정보 흐름, 적응적인 의사결정 메커니즘, 경험으로부터의 학습, 환경과의 지속적인 상호작용을 필요로 한다. ACT-R은 이러한 메커니즘들이 하나의 통합된 인지 아키텍처(unified cognitive architecture)로 어떻게 조직될 수 있는지를 이해하는 데 중요한 역사적·개념적 기반을 제공한다.

##  

## 04.02. SOAR

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

SOAR is a general cognitive architecture designed to model intelligent behavior through a unified set of mechanisms for problem solving, reasoning, learning, memory, and action. Rather than assigning every task to a separate algorithm, SOAR attempts to provide a common computational framework in which many forms of cognition can emerge from repeated decision cycles. Its central objective is to support agents that pursue goals, solve unfamiliar problems, and improve through experience.

The architecture represents cognition as interaction between an agent\'s current state, available operators, goals, and knowledge. A state describes the situation currently understood by the agent, while operators represent possible transformations that can move that state toward a desired result. Intelligence emerges as the system continuously evaluates its situation, proposes possible operators, selects among them, and applies the selected operator.

Problem spaces provide an important conceptual structure in SOAR. A problem can be represented through a collection of possible states and operators capable of transforming one state into another. The agent begins from a current state and attempts to reach a state satisfying its goal. Problem solving therefore becomes structured search through possible transformations rather than an isolated computation producing an answer immediately.

SOAR\'s working memory maintains information relevant to the agent\'s current cognitive situation. It can contain representations of goals, environmental observations, intermediate reasoning results, selected operators, and other contextual information. Working memory changes continuously as cognition progresses, providing a dynamic internal state upon which the architecture\'s decision mechanisms operate.

Long-term procedural knowledge is primarily represented through production rules. Productions specify conditions under which particular conclusions, preferences, or actions become applicable. When information in working memory satisfies the conditions of a production, that production can contribute new information or preferences. Large numbers of productions can operate together, allowing previously acquired knowledge to guide current decisions.

The decision procedure coordinates competing possibilities generated by procedural knowledge. Productions may propose several operators and express preferences concerning which operator should be selected. SOAR evaluates these preferences and chooses an operator when the available knowledge provides sufficient guidance. This mechanism separates knowledge about possible actions from the architectural process responsible for resolving alternatives.

A decision cycle repeatedly transforms the agent\'s cognitive state. Relevant productions match working-memory contents, possible operators are proposed and evaluated, preferences accumulate, and the decision mechanism selects an operator. The selected operator is then applied, changing either the internal problem state or the external environment. The resulting state becomes the basis for another cycle, producing continuous goal-directed cognition.

One of SOAR\'s distinctive concepts is the impasse. An impasse occurs when existing knowledge is insufficient to make progress, such as when no operator can be selected, several alternatives remain equally preferred, or the chosen operator cannot be applied directly. Instead of treating this situation merely as failure, SOAR automatically creates a substate in which the system attempts to resolve the difficulty.

Substates introduce hierarchical problem solving. The original problem remains active while a secondary problem is created to determine how the impasse should be resolved. This secondary reasoning may itself encounter another impasse and generate another substate. SOAR can therefore construct a hierarchy of reasoning dynamically, allowing complex problem decomposition to emerge when existing knowledge cannot directly determine the next action.

Once a subproblem has been solved, the acquired result can influence the higher-level problem. This mechanism provides an important connection between deliberate problem solving and learning. The system does not need every possible solution encoded beforehand; when its current knowledge becomes insufficient, additional reasoning can generate information that allows the original decision process to continue.

Chunking is SOAR\'s classical learning mechanism for converting the results of problem solving into reusable procedural knowledge. When reasoning within a substate produces a useful result, SOAR can create a new production that captures relevant conditions and the resulting conclusion. If a similar situation occurs later, the newly learned production may provide the required knowledge directly, avoiding the previous sequence of deliberate reasoning.

This process allows experience to transform slow problem solving into faster behavior. Initially, an unfamiliar situation may require search, intermediate reasoning, and several substates. After appropriate knowledge has been learned through chunking, similar situations can be handled more directly. SOAR therefore illustrates how repeated experience can compile reasoning results into procedural knowledge that improves future performance.

SOAR also includes mechanisms for other forms of long-term memory. Semantic memory can preserve general facts and relationships that are not necessarily encoded as procedural rules, while episodic memory can retain information about previous states and experiences. These memory systems allow the agent to retrieve relevant knowledge or previous situations when the current problem cannot be solved effectively using procedural knowledge alone.

Episodic memory is particularly useful for reasoning from experience. An agent may retrieve a previous situation resembling its current state and examine what happened after earlier decisions. Such information can contribute to planning, prediction, and problem solving without requiring every past experience to be converted immediately into a production rule. This provides a complementary mechanism to procedural learning.

Semantic memory provides more generalized knowledge about concepts, entities, and relationships. Whereas episodic memory concerns particular experiences, semantic memory supports knowledge that can apply across many situations. Together with procedural memory and working memory, these mechanisms provide SOAR with several forms of knowledge that can contribute differently to cognition while remaining coordinated by the same architecture.

Perception and action connect SOAR\'s internal decision process to an external environment. Perceptual mechanisms place relevant environmental information into internal representations, while selected operators can ultimately produce external actions. The environment then changes and supplies new observations. SOAR can consequently operate as a closed-loop agent whose cognition repeatedly alternates between internal decision processes and environmental interaction.

Operators need not always correspond directly to physical actions. An operator may represent an internal reasoning step, retrieval request, planning operation, task transformation, or externally executed behavior. This flexibility allows the same architectural decision mechanism to coordinate both cognition and action. Internal thinking and external behavior can therefore be represented within a common operator-centered framework.

Goals provide direction to this processing. Rather than responding only to immediate stimuli, a SOAR agent can maintain desired states and organize decisions according to progress toward them. Goals may generate subgoals when difficulties arise, creating hierarchical structures that support complex tasks. This organization allows short-term operator selection to remain connected to broader problem-solving objectives.

SOAR has also been extended with reinforcement learning mechanisms. Reinforcement learning can modify numeric preferences associated with operator selection according to rewards received from interaction. This complements symbolic production knowledge by allowing experience to influence which actions are preferred when several alternatives are available, creating a bridge between structured cognitive control and value-based adaptation.

This combination illustrates an important characteristic of cognitive architectures: multiple learning mechanisms can operate over different kinds of knowledge. Chunking can compile problem-solving results into productions, reinforcement learning can improve operator preferences, episodic learning can preserve experiences, and semantic learning can expand general knowledge. Learning therefore modifies the architecture through several complementary pathways.

SOAR\'s architecture emphasizes that intelligence can emerge from repeated local decisions rather than requiring a complete solution to be generated in a single inference. Each decision cycle addresses the current cognitive situation, while persistent working memory and goals maintain continuity. Over many cycles, sequences of operator selections can produce extended reasoning, planning, problem solving, and interaction with the environment.

From a modern AI perspective, this recurrent architecture resembles important aspects of agentic systems. A contemporary agent may maintain state, retrieve memory, generate candidate actions, evaluate alternatives, use tools, observe results, and repeat the process. SOAR provides a much earlier and more explicitly structured example of how such continuing cognition can be organized around persistent state and iterative decisions.

However, SOAR should not be interpreted as a direct implementation blueprint for modern AGI. It was developed primarily as a symbolic cognitive architecture and does not by itself provide the large-scale learned perception and representation capabilities associated with modern foundation models. Multimodal perception, neural world models, large-scale self-supervised learning, and flexible language understanding require additional mechanisms or integration with learned components.

A modern hybrid architecture could therefore use neural models for perception, representation, prediction, and language while retaining SOAR-like mechanisms for persistent goals, explicit state, operator selection, hierarchical problem solving, and procedural learning. Such a combination could connect the statistical generalization capabilities of learned models with structured mechanisms for long-duration reasoning and controlled action.

The impasse mechanism is especially relevant to contemporary ideas about adaptive computation. Routine situations can be handled using existing knowledge without extensive reasoning, while difficult situations automatically trigger additional processing. This creates a form of conditional computational depth: the system expends greater reasoning effort when its current knowledge is insufficient rather than applying maximum computation to every situation.

SOAR also demonstrates the value of converting successful deliberation into reusable competence. If an agent repeatedly solves similar problems through expensive reasoning, preserving the resulting strategy can reduce future computational cost. Modern systems may implement this principle differently through skill learning, policy distillation, memory, cached plans, or learned procedures, but the underlying objective remains similar.

Metacognitive mechanisms can extend this principle further by monitoring uncertainty, progress, resource use, and strategy effectiveness. An advanced agent could detect that repeated impasses indicate missing knowledge, inadequate representations, or poor planning strategies. It could then decide whether to search memory, invoke another reasoning method, gather information, request assistance, or initiate additional learning.

World models can provide another complementary extension. SOAR\'s operator-centered reasoning determines what transformations might be considered, while a learned world model can predict the likely consequences of candidate actions. Combining explicit goal-directed operator selection with predictive simulation could enable an agent to evaluate possible futures before committing to costly or irreversible actions.

The enduring importance of SOAR lies in its attempt to explain intelligence through a coherent architecture rather than through a collection of unrelated task-specific programs. Working memory maintains current context, productions provide procedural knowledge, operators structure decisions, impasses trigger deeper reasoning, substates support hierarchical problem solving, and learning converts experience into knowledge that improves subsequent behavior.

From an AGI perspective, SOAR provides a valuable architectural lesson: general intelligence requires continuity across perception, memory, reasoning, learning, goals, and action. An intelligent agent must know what situation it is in, determine what alternatives are available, recognize when existing knowledge is insufficient, reason further when necessary, preserve useful discoveries, and repeatedly use feedback to improve future decisions.

SOAR는 문제 해결(problem solving), 추론(reasoning), 학습(learning), 기억(memory), 행동(action)을 위한 통합된 메커니즘을 통해 지능적 행동(intelligent behavior)을 모델링하도록 설계된 범용 인지 아키텍처(general cognitive architecture)이다. 각각의 작업에 별도의 알고리즘을 할당하는 대신, SOAR는 반복적인 의사결정 순환(decision cycle)을 통해 다양한 형태의 인지가 나타날 수 있는 공통 계산 프레임워크(computational framework)를 제공한다. 핵심 목표는 에이전트가 목표를 추구하고, 익숙하지 않은 문제를 해결하며, 경험을 통해 개선될 수 있도록 하는 것이다.

이 아키텍처는 에이전트의 현재 상태(current state), 사용 가능한 연산자(operator), 목표(goal), 지식(knowledge) 사이의 상호작용으로 인지를 표현한다. 상태는 에이전트가 현재 이해하고 있는 상황을 설명하며, 연산자는 해당 상태를 원하는 결과로 이동시킬 수 있는 가능한 변환(transformation)을 나타낸다. 시스템이 지속적으로 상황을 평가하고, 가능한 연산자를 제안하고, 그중 하나를 선택하고 적용하면서 지능적 행동이 나타난다.

문제 공간(problem space)은 SOAR에서 중요한 개념적 구조를 제공한다. 하나의 문제는 가능한 상태들의 집합과 한 상태를 다른 상태로 변환할 수 있는 연산자들의 집합으로 표현될 수 있다. 에이전트는 현재 상태에서 시작하여 목표를 만족하는 상태에 도달하려고 한다. 따라서 문제 해결은 하나의 계산으로 즉시 답을 생성하는 것이 아니라 가능한 상태 변환을 통한 구조화된 탐색(structured search)이 된다.

SOAR의 작업 기억(working memory)은 에이전트의 현재 인지 상황과 관련된 정보를 유지한다. 여기에는 목표, 환경 관측(environmental observation), 중간 추론 결과, 선택된 연산자, 기타 문맥 정보(contextual information)의 표현이 포함될 수 있다. 작업 기억은 인지가 진행됨에 따라 지속적으로 변화하며, 아키텍처의 의사결정 메커니즘이 작동하는 동적인 내부 상태(dynamic internal state)를 제공한다.

장기 절차적 지식(long-term procedural knowledge)은 주로 생성 규칙(production rule)을 통해 표현된다. 생성 규칙은 특정한 결론, 선호도(preference), 행동이 어떤 조건에서 적용될 수 있는지를 규정한다. 작업 기억의 정보가 생성 규칙의 조건을 만족하면 해당 규칙은 새로운 정보나 선호도를 제공할 수 있다. 다수의 생성 규칙이 함께 작동하면서 이전에 획득한 지식이 현재의 의사결정을 안내할 수 있다.

의사결정 절차(decision procedure)는 절차적 지식에서 생성된 서로 경쟁하는 가능성을 조정한다. 생성 규칙은 여러 연산자를 제안하고 어떤 연산자를 선택해야 하는지에 관한 선호도를 표현할 수 있다. SOAR는 이러한 선호도를 평가하고 사용 가능한 지식이 충분한 지침을 제공할 때 하나의 연산자를 선택한다. 이 메커니즘은 가능한 행동에 관한 지식과 대안들을 결정하는 아키텍처적 처리 과정을 분리한다.

의사결정 순환(decision cycle)은 에이전트의 인지 상태를 반복적으로 변화시킨다. 관련된 생성 규칙이 작업 기억의 내용과 일치하고, 가능한 연산자가 제안되고 평가되며, 선호도가 축적된 뒤 의사결정 메커니즘이 하나의 연산자를 선택한다. 선택된 연산자가 적용되면 내부 문제 상태 또는 외부 환경이 변화하고, 그 결과 상태가 다음 순환의 기반이 되어 지속적인 목표 지향 인지(goal-directed cognition)가 만들어진다.

SOAR의 독특한 개념 가운데 하나는 교착 상태(impasse)이다. 교착 상태는 기존 지식만으로 진행하기 어려운 경우에 발생한다. 예를 들어 선택 가능한 연산자가 없거나, 여러 대안이 동일한 수준으로 선호되거나, 선택된 연산자를 직접 적용할 수 없는 경우가 이에 해당한다. SOAR는 이러한 상황을 단순한 실패로 처리하지 않고 문제를 해결하기 위한 하위 상태(substate)를 자동으로 생성한다.

하위 상태(substate)는 계층적 문제 해결(hierarchical problem solving)을 가능하게 한다. 원래의 문제를 활성 상태로 유지하면서 교착 상태를 어떻게 해결할지를 결정하기 위한 두 번째 문제가 생성된다. 이러한 보조 추론 과정에서 다시 교착 상태가 발생하면 또 다른 하위 상태가 만들어질 수 있다. 따라서 SOAR는 기존 지식만으로 다음 행동을 직접 결정할 수 없을 때 동적으로 추론 계층(reasoning hierarchy)을 구성하여 복잡한 문제를 분해할 수 있다.

하위 문제가 해결되면 획득된 결과는 상위 수준의 문제에 영향을 줄 수 있다. 이러한 메커니즘은 숙고적 문제 해결(deliberative problem solving)과 학습 사이에 중요한 연결을 제공한다. 시스템은 가능한 모든 해결책을 사전에 인코딩할 필요가 없다. 현재 지식이 충분하지 않을 경우 추가적인 추론을 수행하여 원래의 의사결정 과정을 계속 진행할 수 있는 정보를 생성할 수 있다.

청킹(chunking)은 문제 해결 결과를 재사용 가능한 절차적 지식으로 변환하는 SOAR의 전통적인 학습 메커니즘이다. 하위 상태에서 수행된 추론이 유용한 결과를 생성하면 SOAR는 관련 조건과 그 결과를 포착하는 새로운 생성 규칙을 만들 수 있다. 이후 유사한 상황이 발생하면 새롭게 학습된 생성 규칙이 필요한 지식을 직접 제공하여 이전에 수행했던 숙고적 추론 과정을 반복하지 않도록 할 수 있다.

이러한 과정은 경험을 통해 느린 문제 해결을 더욱 빠른 행동으로 전환할 수 있게 한다. 처음 접하는 상황에서는 탐색(search), 중간 추론, 여러 하위 상태가 필요할 수 있다. 그러나 청킹을 통해 적절한 지식을 학습한 이후에는 유사한 상황을 보다 직접적으로 처리할 수 있다. 따라서 SOAR는 반복적인 경험이 추론 결과를 절차적 지식으로 컴파일(compile)하여 미래의 성능을 향상시키는 방식을 보여준다.

SOAR는 다른 형태의 장기 기억(long-term memory)을 위한 메커니즘도 포함한다. 의미 기억(semantic memory)은 반드시 절차적 규칙으로 인코딩되지 않는 일반적인 사실과 관계를 보존할 수 있으며, 일화 기억(episodic memory)은 이전 상태와 경험에 관한 정보를 유지할 수 있다. 이러한 기억 시스템을 통해 절차적 지식만으로 현재 문제를 효과적으로 해결할 수 없을 때 관련 지식이나 과거 상황을 검색할 수 있다.

일화 기억(episodic memory)은 경험을 기반으로 추론하는 데 특히 유용하다. 에이전트는 현재 상태와 유사한 이전 상황을 검색하고 과거의 의사결정 이후 어떤 일이 발생했는지를 살펴볼 수 있다. 이러한 정보는 모든 과거 경험을 즉시 생성 규칙으로 변환하지 않고도 계획, 예측, 문제 해결에 활용될 수 있다. 이는 절차적 학습(procedural learning)을 보완하는 메커니즘을 제공한다.

의미 기억(semantic memory)은 개념, 개체(entity), 관계에 대한 보다 일반화된 지식을 제공한다. 일화 기억이 특정 경험에 관한 것이라면 의미 기억은 다양한 상황에 적용할 수 있는 지식을 지원한다. 이러한 메커니즘은 절차적 기억(procedural memory), 작업 기억과 함께 서로 다른 형태의 지식이 인지 과정에 서로 다른 방식으로 기여하면서 동일한 아키텍처 안에서 조정될 수 있도록 한다.

지각(perception)과 행동(action)은 SOAR의 내부 의사결정 과정을 외부 환경과 연결한다. 지각 메커니즘은 관련 환경 정보를 내부 표현으로 전달하고, 선택된 연산자는 궁극적으로 외부 행동을 발생시킬 수 있다. 이후 환경이 변화하면서 새로운 관측을 제공한다. 따라서 SOAR는 내부 의사결정 과정과 환경과의 상호작용을 반복하는 폐루프 에이전트(closed-loop agent)로 작동할 수 있다.

연산자(operator)가 반드시 물리적 행동과 직접 대응할 필요는 없다. 연산자는 내부 추론 단계, 기억 검색 요청, 계획 연산, 작업 변환(task transformation) 또는 외부에서 실행되는 행동을 나타낼 수 있다. 이러한 유연성으로 동일한 아키텍처적 의사결정 메커니즘이 인지와 행동을 모두 조정할 수 있다. 따라서 내부 사고(internal thinking)와 외부 행동을 공통된 연산자 중심 프레임워크(operator-centered framework) 안에서 표현할 수 있다.

목표(goal)는 이러한 처리 과정에 방향성을 제공한다. SOAR 에이전트는 즉각적인 자극에만 반응하는 것이 아니라 원하는 상태를 유지하고 해당 상태를 향한 진행 정도에 따라 의사결정을 구성할 수 있다. 어려움이 발생하면 목표에서 하위 목표(subgoal)가 생성되어 복잡한 작업을 지원하는 계층 구조를 형성할 수 있다. 이를 통해 단기적인 연산자 선택이 보다 광범위한 문제 해결 목표와 연결된다.

SOAR는 강화 학습(Reinforcement Learning) 메커니즘을 포함하도록 확장되었다. 강화 학습은 환경과의 상호작용에서 받은 보상(reward)에 따라 연산자 선택과 관련된 수치적 선호도(numeric preference)를 수정할 수 있다. 이는 여러 대안 가운데 어떤 행동을 선호할지를 경험을 통해 조정할 수 있게 함으로써 기호적 생성 지식(symbolic production knowledge)을 보완하고, 구조화된 인지 제어와 가치 기반 적응(value-based adaptation)을 연결한다.

이러한 결합은 인지 아키텍처의 중요한 특징을 보여준다. 서로 다른 종류의 지식에 여러 학습 메커니즘이 작동할 수 있다. 청킹은 문제 해결 결과를 생성 규칙으로 컴파일하고, 강화 학습은 연산자 선호도를 개선하며, 일화 학습(episodic learning)은 경험을 보존하고, 의미 학습(semantic learning)은 일반화된 지식을 확장할 수 있다. 따라서 학습은 여러 상호보완적인 경로를 통해 아키텍처를 변화시킨다.

SOAR 아키텍처는 하나의 추론에서 완전한 해결책을 생성하지 않더라도 반복적인 지역적 의사결정(local decision)을 통해 지능이 나타날 수 있음을 강조한다. 각각의 의사결정 순환은 현재의 인지 상황을 처리하고, 지속적인 작업 기억과 목표는 여러 순환에 걸친 연속성을 유지한다. 많은 순환에 걸쳐 이루어지는 연산자 선택의 연속은 장기적인 추론, 계획, 문제 해결, 환경과의 상호작용을 만들어낼 수 있다.

현대 인공지능의 관점에서 이러한 반복적 아키텍처(recurrent architecture)는 에이전트형 시스템(agentic system)의 중요한 특징과 유사하다. 현대적인 에이전트는 상태를 유지하고, 기억을 검색하고, 후보 행동을 생성하고, 대안을 평가하고, 도구를 사용하고, 결과를 관측한 뒤 이 과정을 반복할 수 있다. SOAR는 이러한 지속적인 인지가 영속적인 상태(persistent state)와 반복적인 의사결정을 중심으로 어떻게 조직될 수 있는지를 훨씬 이전부터 명시적으로 보여준 사례이다.

그러나 SOAR를 현대 AGI의 직접적인 구현 청사진으로 해석해서는 안 된다. SOAR는 주로 기호적 인지 아키텍처(symbolic cognitive architecture)로 개발되었으며, 현대의 파운데이션 모델(foundation model)과 관련된 대규모 학습 기반 지각 및 표현 능력을 자체적으로 제공하는 것은 아니다. 멀티모달 지각(multimodal perception), 신경망 기반 월드 모델(neural world model), 대규모 자기지도 학습(self-supervised learning), 유연한 언어 이해에는 추가적인 메커니즘이나 학습 기반 구성 요소와의 통합이 필요하다.

따라서 현대적인 하이브리드 아키텍처(hybrid architecture)는 지각, 표현, 예측, 언어에 신경망 모델을 사용하면서 지속적인 목표, 명시적인 상태, 연산자 선택, 계층적 문제 해결, 절차적 학습에는 SOAR와 유사한 메커니즘을 활용할 수 있다. 이러한 결합은 학습 모델의 통계적 일반화(statistical generalization) 능력과 장기간의 추론 및 통제된 행동을 위한 구조화된 메커니즘을 연결할 수 있다.

교착 상태(impasse) 메커니즘은 현대적인 적응형 계산(adaptive computation)의 개념과 특히 관련성이 높다. 일상적인 상황은 광범위한 추론 없이 기존 지식을 이용하여 처리할 수 있지만, 어려운 상황에서는 자동으로 추가적인 처리가 시작된다. 이는 일종의 조건부 계산 깊이(conditional computational depth)를 형성하여 모든 상황에 최대 계산량을 적용하는 대신 현재 지식이 충분하지 않을 때 더 많은 추론 자원을 사용하도록 한다.

SOAR는 성공적인 숙고(deliberation)를 재사용 가능한 능력으로 변환하는 것의 가치도 보여준다. 에이전트가 비용이 많이 드는 추론을 통해 유사한 문제를 반복적으로 해결한다면 그 결과로 얻은 전략을 보존하여 미래의 계산 비용을 줄일 수 있다. 현대 시스템에서는 기술 학습(skill learning), 정책 증류(policy distillation), 기억, 캐시된 계획(cached plan), 학습된 절차 등 다른 방법으로 구현할 수 있지만 근본적인 목적은 유사하다.

메타인지 메커니즘(metacognitive mechanism)은 불확실성, 진행 상태, 자원 사용, 전략 효과성을 모니터링함으로써 이러한 원리를 더욱 확장할 수 있다. 고급 에이전트는 반복적인 교착 상태가 지식 부족, 부적절한 표현, 또는 좋지 않은 계획 전략을 의미한다는 것을 탐지할 수 있다. 이후 기억을 검색하거나, 다른 추론 방법을 호출하거나, 정보를 수집하거나, 외부 지원을 요청하거나, 추가적인 학습을 시작할지를 결정할 수 있다.

월드 모델(world model)은 또 다른 상호보완적 확장 요소를 제공할 수 있다. SOAR의 연산자 중심 추론은 어떤 변환을 고려해야 하는지를 결정하고, 학습된 월드 모델은 후보 행동의 가능한 결과를 예측할 수 있다. 명시적인 목표 지향 연산자 선택(goal-directed operator selection)을 예측 시뮬레이션(predictive simulation)과 결합하면 비용이 크거나 되돌릴 수 없는 행동을 실행하기 전에 가능한 미래를 평가할 수 있다.

SOAR의 지속적인 중요성은 서로 관련 없는 작업별 프로그램들의 집합이 아니라 일관된 아키텍처를 통해 지능을 설명하려는 시도에 있다. 작업 기억은 현재 문맥을 유지하고, 생성 규칙은 절차적 지식을 제공하며, 연산자는 의사결정을 구조화한다. 교착 상태는 더 깊은 추론을 시작하고, 하위 상태는 계층적 문제 해결을 지원하며, 학습은 경험을 이후의 행동을 개선하는 지식으로 변환한다.

AGI 관점에서 SOAR는 중요한 아키텍처적 교훈을 제공한다. 범용 지능(general intelligence)은 지각, 기억, 추론, 학습, 목표, 행동 사이의 연속성을 필요로 한다. 지능형 에이전트는 자신이 어떤 상황에 있는지 파악하고, 어떤 대안을 사용할 수 있는지 결정하며, 기존 지식이 충분하지 않은 시점을 인식하고, 필요하면 추가적으로 추론하며, 유용한 발견을 보존하고, 피드백을 반복적으로 활용하여 미래의 의사결정을 개선할 수 있어야 한다.

##  

## 04.03. Global Workspace Theory

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

Global Workspace Theory describes cognition as a distributed system in which many specialized processes operate largely in parallel while a limited-capacity workspace enables selected information to become globally available. Rather than assuming that every cognitive process communicates directly with every other process, the theory proposes a shared informational arena through which particularly relevant content can influence memory, reasoning, planning, attention, learning, and action.

The theory is strongly associated with Bernard Baars and was originally developed as a functional account of conscious access. Its central metaphor resembles a theater: numerous cognitive processes operate outside the spotlight, while attention selects a relatively small amount of information for entry into a global workspace. Once selected, that information can be broadcast broadly to otherwise specialized systems distributed throughout the cognitive architecture.

Specialized processors perform much of cognition without requiring global access. Visual processing may identify objects, language mechanisms may interpret words, memory systems may retrieve associations, and motor systems may prepare possible actions simultaneously. These processes can remain locally specialized and computationally efficient. The global workspace becomes important when information produced by one subsystem must coordinate behavior across several other subsystems.

Competition for access is therefore a fundamental mechanism. Many representations, goals, sensory events, memories, and internally generated hypotheses may simultaneously seek broader influence, but only a limited subset can dominate the workspace at a particular moment. Attention, salience, novelty, task relevance, emotional significance, and current goals can affect this competition, allowing important information to gain temporary priority over competing cognitive contents.

When information gains access to the workspace, it becomes globally broadcast. The purpose of broadcasting is not merely to copy information everywhere, but to make selected content available to multiple systems that can use it differently. Memory may associate it with previous experience, reasoning may derive implications, planning may revise future actions, learning may update internal models, and action systems may alter behavior in response to the same globally accessible content.

This architecture creates an important distinction between local processing and global availability. A representation can influence specialized processing without becoming globally accessible, while information entering the workspace can coordinate multiple cognitive functions. The distinction provides a way to explain why intelligent systems can perform many operations automatically while only a relatively small amount of information becomes the focus of integrated, flexible processing at any moment.

Working memory is closely related to the workspace but should not necessarily be treated as identical to it. Working memory maintains information needed for ongoing tasks, whereas global workspace mechanisms emphasize widespread availability and broadcasting. Information maintained in working memory may become globally influential when task demands require it, while globally broadcast information can subsequently modify the contents maintained for continuing reasoning or planning.

Attention acts as a major gateway to global access. An environment can contain far more sensory information than an agent can process through expensive integrated reasoning. Attention prioritizes information according to current goals and significant events, reducing the effective cognitive workload. Bottom-up signals can capture attention because of novelty or sudden change, while top-down control can prioritize information because it is relevant to an active objective.

The workspace can also contain internally generated information rather than only sensory observations. Retrieved memories, imagined situations, intermediate reasoning results, predicted outcomes, unresolved conflicts, and planned actions can compete for global access. Consequently, cognition can shift from externally driven perception toward internally driven deliberation without requiring a fundamentally different architectural mechanism for coordinating the participating cognitive systems.

Memory and the global workspace interact bidirectionally. Globally available information can trigger retrieval of related episodic or semantic knowledge, while retrieved memories can themselves become candidates for global broadcasting. This recurrent relationship allows present observations to activate relevant past experience and allows remembered information to reshape the interpretation of current events. Cognition therefore develops through repeated interaction between present state and stored knowledge.

Reasoning can use workspace contents as a shared context. When a problem representation becomes globally available, several specialized mechanisms may contribute candidate explanations, associations, predictions, or solutions. Their outputs can compete for subsequent access, creating an iterative reasoning process. Complex reasoning can consequently emerge through successive workspace states rather than requiring one module to perform an entire reasoning sequence internally.

Planning can operate in a similar manner. A goal may enter the workspace and activate mechanisms capable of proposing actions or subgoals. Candidate plans can be evaluated according to constraints, predicted consequences, memory, and current resources. The selected plan or intermediate result can then become globally available, triggering the next stage of processing. Workspace dynamics can therefore coordinate multi-step goal-directed cognition.

A world model can greatly strengthen this process by producing predictions about possible future states. Candidate actions represented in the workspace can be evaluated through internal simulation, and predicted consequences can compete for attention before physical execution occurs. If a predicted outcome indicates danger, failure, or opportunity, that information can be broadcast to planning and control systems and alter the agent\'s behavior before an external consequence occurs.

Action selection represents the point at which globally coordinated cognition can influence the environment. A selected intention or plan can activate appropriate motor, software, communication, or tool-use mechanisms. After execution, new observations return through perception and can compete for workspace access. The resulting cycle links perception, global coordination, decision, action, and feedback into a continuously operating cognitive loop.

Unexpected events are especially important because they may interrupt the current workspace state. A significant prediction error, sudden environmental change, or failure of an ongoing action can acquire high priority and displace previously dominant content. This allows the system to shift rapidly from routine execution toward reevaluation and replanning. Global workspace mechanisms can therefore support both stable goal pursuit and flexible interruption.

Learning can occur throughout these cycles. Globally broadcast information provides a potentially valuable training signal because it represents content judged relevant to current cognition. Associations between workspace states, actions, predictions, and outcomes can strengthen future processing. Repeated experience can make frequently successful operations more automatic, reducing their need for global coordination and preserving limited workspace capacity for novel or difficult problems.

This distinction between automatic and controlled processing has significant architectural value. Familiar tasks can often be handled by specialized learned mechanisms with little global involvement, while unfamiliar, ambiguous, conflicting, or strategically important situations recruit the workspace. Computational resources can therefore be concentrated where coordination is needed instead of forcing every cognitive operation through an expensive central reasoning mechanism.

Global Workspace Theory does not require the workspace to contain a complete representation of the entire cognitive system. Its power comes precisely from selective access. Only information currently important for coordination needs to become globally available, while enormous amounts of lower-level processing can remain distributed. This produces an architecture that combines specialization with integration rather than replacing specialized modules with one universal processor.

For artificial intelligence, this principle suggests a possible mechanism for orchestrating heterogeneous components. Perception networks, language models, memory systems, planners, world models, reasoning engines, and controllers could operate as specialized processes. A workspace could maintain selected shared content, while attention and competition determine which outputs receive broader distribution. Broadcasting would then allow independently implemented components to coordinate around a common cognitive context.

A computational implementation might represent the workspace as a structured shared state containing active observations, goals, hypotheses, retrieved memories, uncertainty estimates, and candidate actions. Specialized modules could read relevant workspace information and submit new candidate content. An attention or arbitration mechanism could score these candidates and select information for broader broadcasting, after which participating modules update their local processing.

Such an implementation requires careful control because unrestricted broadcasting could overwhelm the architecture. Every observation or intermediate activation should not become globally distributed. Selection mechanisms must consider relevance, confidence, novelty, urgency, expected information value, and computational cost. The workspace consequently functions not simply as shared memory but as a dynamically controlled communication bottleneck.

This bottleneck can be advantageous. Limited global capacity forces the system to prioritize, preventing every cognitive subsystem from continuously exchanging unlimited information with every other subsystem. The architecture can maintain large amounts of parallel local computation while reserving expensive cross-system coordination for selected information. This resembles a resource-management strategy as much as a theory of cognitive access.

Metacognition can operate above or through the workspace by monitoring which information dominates processing, how confident the system is, whether reasoning is progressing, and whether conflicts remain unresolved. Metacognitive signals may themselves gain global access, allowing the system to recognize uncertainty or failure. The agent can then allocate more computation, retrieve additional evidence, change strategy, or request external assistance.

The relationship between Global Workspace Theory and consciousness requires careful interpretation in artificial systems. The theory was developed partly to explain conscious access in humans, but implementing workspace-like broadcasting in an AI system would not by itself establish that the system possesses subjective experience. For engineering purposes, its mechanisms can be studied independently as principles for selective information integration, attention, coordination, and cognitive control.

Modern neural approaches inspired by global workspace ideas can use learned representations and attention mechanisms rather than relying exclusively on symbolic information. Multiple specialized networks may process different modalities or tasks, while a shared latent workspace enables communication between them. Learned gating mechanisms can determine which representations enter the shared space and which specialized systems receive the resulting broadcast.

Foundation models create another possible interpretation. A powerful multimodal model could participate in workspace processing as a general reasoning or representation mechanism while persistent memory, perception, planning, control, and tools remain separate architectural components. The workspace would then coordinate information among these mechanisms rather than assuming that a single foundation model must internally implement every aspect of cognition.

In an embodied AGI system, workspace dynamics could connect multiple temporal scales. Fast perception and control processes may operate continuously without requiring deliberate reasoning, while unusual events trigger global broadcasting and slower planning. Strategic goals may influence attention from the top down, while urgent sensory changes interrupt from the bottom up. This interaction allows rapid reactions and long-horizon cognition to coexist.

Global Workspace Theory therefore provides an important architectural principle for AGI: distributed specialization and global integration do not have to be opposing approaches. Specialized mechanisms can perform efficient local computation, while selective broadcasting creates temporary system-wide coordination when required. Intelligence can emerge from repeated transitions between parallel local processing and globally accessible cognitive states.

From a cognitive architecture perspective, the enduring significance of Global Workspace Theory lies in its explanation of how many independent processes can behave as a coherent agent. Competition determines what becomes globally important, attention regulates access, broadcasting distributes selected information, specialized systems contribute interpretations and actions, and feedback produces the next workspace state. This recurrent cycle offers a powerful conceptual framework for integrating perception, memory, reasoning, planning, learning, and action into unified adaptive cognition.

글로벌 워크스페이스 이론(Global Workspace Theory)은 많은 전문화된 처리 과정(specialized process)이 대부분 병렬적으로 작동하는 동시에, 제한된 용량의 워크스페이스(workspace)를 통해 선택된 정보가 시스템 전체에서 사용 가능해지는 인지 구조를 설명한다. 모든 인지 과정이 서로 직접 통신한다고 가정하는 대신, 특히 중요한 정보가 기억(memory), 추론(reasoning), 계획(planning), 주의(attention), 학습(learning), 행동(action)에 영향을 줄 수 있도록 공유 정보 공간(shared informational arena)을 제공한다고 본다.

이 이론은 버나드 바스(Bernard Baars)와 밀접하게 관련되어 있으며, 원래 의식적 접근(conscious access)을 기능적으로 설명하기 위해 발전하였다. 핵심적인 비유는 극장(theater)과 유사하다. 수많은 인지 과정이 스포트라이트 밖에서 작동하고, 주의가 비교적 적은 양의 정보를 선택하여 글로벌 워크스페이스에 진입시킨다. 선택된 정보는 인지 아키텍처 전체에 분산된 전문 시스템으로 광범위하게 방송(broadcast)될 수 있다.

전문화된 처리기(specialized processor)는 글로벌 접근(global access)을 요구하지 않고도 인지 활동의 상당 부분을 수행한다. 시각 처리는 객체를 식별하고, 언어 메커니즘은 단어를 해석하며, 기억 시스템은 연관 정보를 검색하고, 운동 시스템은 가능한 행동을 동시에 준비할 수 있다. 이러한 과정은 지역적으로 전문화된 상태를 유지하면서 효율적으로 작동하며, 하나의 하위 시스템에서 생성된 정보가 여러 다른 하위 시스템의 행동을 조정해야 할 때 글로벌 워크스페이스가 중요해진다.

따라서 접근권을 얻기 위한 경쟁(competition)은 근본적인 메커니즘이다. 많은 표현(representation), 목표(goal), 감각 사건(sensory event), 기억, 내부적으로 생성된 가설(hypothesis)이 동시에 더 넓은 영향력을 얻으려고 경쟁할 수 있지만, 특정 순간에는 제한된 일부만이 워크스페이스를 지배할 수 있다. 주의, 현저성(salience), 새로움(novelty), 작업 관련성(task relevance), 정서적 중요성(emotional significance), 현재 목표 등이 이러한 경쟁에 영향을 주어 중요한 정보가 일시적으로 우선권을 갖도록 한다.

정보가 워크스페이스에 접근하면 전역적으로 방송(global broadcast)된다. 방송의 목적은 단순히 정보를 모든 곳에 복사하는 것이 아니라 선택된 내용을 서로 다른 방식으로 활용할 수 있는 여러 시스템에서 사용 가능하도록 만드는 것이다. 기억은 이를 이전 경험과 연결하고, 추론은 함의를 도출하며, 계획은 미래 행동을 수정하고, 학습은 내부 모델을 갱신하며, 행동 시스템은 동일한 전역 정보에 대응하여 행동을 변화시킬 수 있다.

이러한 아키텍처는 지역 처리(local processing)와 전역 가용성(global availability)을 구분한다. 하나의 표현은 전역적으로 접근 가능한 상태가 되지 않더라도 전문화된 처리 과정에 영향을 줄 수 있지만, 워크스페이스에 진입한 정보는 여러 인지 기능을 조정할 수 있다. 이러한 구분은 지능형 시스템이 많은 연산을 자동적으로 수행하면서도 특정 순간에는 비교적 적은 양의 정보만이 통합적이고 유연한 처리의 중심이 되는 이유를 설명할 수 있다.

작업 기억(working memory)은 워크스페이스와 밀접하게 관련되지만 반드시 동일한 것으로 간주할 필요는 없다. 작업 기억은 현재 수행 중인 작업에 필요한 정보를 유지하는 반면, 글로벌 워크스페이스 메커니즘은 정보의 광범위한 가용성과 방송을 강조한다. 작업 기억에 유지되는 정보는 작업 요구에 따라 전역적인 영향력을 가질 수 있으며, 전역적으로 방송된 정보는 이후 지속적인 추론이나 계획을 위해 유지되는 작업 기억의 내용을 변경할 수 있다.

주의(attention)는 글로벌 접근으로 들어가는 주요 관문(gateway)으로 작동한다. 환경에는 에이전트(agent)가 비용이 높은 통합 추론을 통해 처리할 수 있는 양보다 훨씬 많은 감각 정보가 존재할 수 있다. 주의는 현재 목표와 중요한 사건에 따라 정보를 우선순위화하여 실질적인 인지 작업량을 줄인다. 상향식 신호(bottom-up signal)는 새로움이나 갑작스러운 변화로 주의를 끌 수 있고, 하향식 제어(top-down control)는 활성 목표와 관련된 정보를 우선적으로 선택할 수 있다.

워크스페이스에는 감각 관측뿐 아니라 내부적으로 생성된 정보도 포함될 수 있다. 검색된 기억, 상상된 상황, 중간 추론 결과, 예측된 결과, 해결되지 않은 충돌(conflict), 계획된 행동 등이 글로벌 접근을 위해 경쟁할 수 있다. 따라서 인지는 외부에서 유도되는 지각에서 내부적으로 유도되는 숙고(deliberation)로 전환될 수 있으며, 이때 참여하는 인지 시스템을 조정하기 위해 근본적으로 다른 아키텍처 메커니즘을 필요로 하지 않는다.

기억과 글로벌 워크스페이스는 양방향으로 상호작용한다. 전역적으로 사용 가능한 정보는 관련된 일화 기억(episodic memory)이나 의미 지식(semantic knowledge)의 검색을 유발할 수 있으며, 검색된 기억 자체가 글로벌 방송의 후보가 될 수도 있다. 이러한 반복적인 관계를 통해 현재 관측은 관련된 과거 경험을 활성화하고, 기억된 정보는 현재 사건의 해석을 다시 변화시킬 수 있다. 따라서 인지는 현재 상태와 저장된 지식 사이의 반복적인 상호작용을 통해 발전한다.

추론(reasoning)은 워크스페이스의 내용을 공유 문맥(shared context)으로 사용할 수 있다. 문제에 대한 표현이 전역적으로 사용 가능해지면 여러 전문화된 메커니즘이 후보 설명, 연관성, 예측 또는 해결책을 제공할 수 있다. 이들의 출력은 다음 글로벌 접근을 위해 다시 경쟁할 수 있으며, 이를 통해 반복적인 추론 과정(iterative reasoning process)이 형성된다. 따라서 복잡한 추론은 하나의 모듈이 전체 추론 과정을 내부적으로 수행하지 않더라도 연속적인 워크스페이스 상태를 통해 나타날 수 있다.

계획(planning)도 이와 유사하게 작동할 수 있다. 하나의 목표가 워크스페이스에 진입하면 행동이나 하위 목표(subgoal)를 제안할 수 있는 메커니즘을 활성화할 수 있다. 후보 계획(candidate plan)은 제약조건(constraint), 예상 결과, 기억, 현재 자원에 따라 평가될 수 있다. 선택된 계획이나 중간 결과는 다시 전역적으로 사용 가능해져 다음 처리 단계를 유발할 수 있다. 따라서 워크스페이스의 동역학(workspace dynamics)은 여러 단계의 목표 지향 인지(goal-directed cognition)를 조정할 수 있다.

월드 모델(world model)은 가능한 미래 상태에 대한 예측을 생성함으로써 이러한 과정을 크게 강화할 수 있다. 워크스페이스에 표현된 후보 행동을 내부 시뮬레이션(internal simulation)을 통해 평가하고, 예측된 결과가 실제 행동 이전에 주의를 얻기 위해 경쟁할 수 있다. 예상 결과가 위험, 실패 또는 기회를 나타내면 해당 정보가 계획 및 제어 시스템에 방송되어 외부 결과가 실제로 발생하기 전에 에이전트의 행동을 변경할 수 있다.

행동 선택(action selection)은 전역적으로 조정된 인지가 환경에 영향을 미치는 지점이다. 선택된 의도(intention)나 계획은 적절한 운동, 소프트웨어, 통신 또는 도구 사용(tool use) 메커니즘을 활성화할 수 있다. 실행 이후 새로운 관측이 지각을 통해 돌아오고 다시 워크스페이스 접근을 위해 경쟁한다. 이러한 순환은 지각, 전역 조정, 의사결정, 행동, 피드백(feedback)을 지속적으로 작동하는 인지 루프(cognitive loop)로 연결한다.

예상하지 못한 사건은 현재의 워크스페이스 상태를 중단시킬 수 있기 때문에 특히 중요하다. 큰 예측 오차(prediction error), 갑작스러운 환경 변화 또는 진행 중인 행동의 실패는 높은 우선순위를 획득하여 이전에 지배적이던 내용을 대체할 수 있다. 이를 통해 시스템은 일상적인 실행에서 빠르게 재평가와 재계획(replanning)으로 전환할 수 있다. 따라서 글로벌 워크스페이스 메커니즘은 안정적인 목표 추구와 유연한 중단 및 전환을 모두 지원할 수 있다.

학습(learning)은 이러한 순환 전체에서 발생할 수 있다. 전역적으로 방송되는 정보는 현재 인지 과정에서 중요하다고 판단된 내용을 나타내기 때문에 잠재적으로 가치 있는 학습 신호(training signal)를 제공한다. 워크스페이스 상태, 행동, 예측, 결과 사이의 연관성은 미래의 처리 과정을 강화할 수 있다. 반복적인 경험을 통해 자주 성공하는 연산은 더욱 자동화되어 글로벌 조정의 필요성이 감소하고, 제한된 워크스페이스 용량을 새롭거나 어려운 문제에 사용할 수 있게 된다.

자동 처리(automatic processing)와 통제 처리(controlled processing)의 이러한 구분은 아키텍처적으로 중요한 의미를 갖는다. 익숙한 작업은 글로벌 개입이 거의 없이 전문화된 학습 메커니즘을 통해 처리될 수 있지만, 익숙하지 않거나 모호하거나 서로 충돌하거나 전략적으로 중요한 상황에서는 워크스페이스가 활용된다. 따라서 모든 인지 연산을 비용이 높은 중앙 추론 메커니즘으로 처리하지 않고 조정이 필요한 영역에 계산 자원을 집중할 수 있다.

글로벌 워크스페이스 이론은 워크스페이스가 전체 인지 시스템을 완전하게 표현해야 한다고 요구하지 않는다. 오히려 그 힘은 선택적 접근(selective access)에서 나온다. 현재 조정에 중요한 정보만 전역적으로 사용 가능하면 되고, 방대한 양의 하위 수준 처리는 분산된 상태로 유지될 수 있다. 따라서 이 아키텍처는 전문화된 모듈을 하나의 범용 처리기로 대체하는 대신 전문화(specialization)와 통합(integration)을 결합한다.

인공지능 관점에서 이러한 원리는 서로 이질적인 구성 요소를 오케스트레이션(orchestration)하는 가능한 메커니즘을 제시한다. 지각 네트워크(perception network), 언어 모델(language model), 기억 시스템, 계획 시스템, 월드 모델, 추론 엔진(reasoning engine), 제어기는 전문화된 처리 과정으로 작동할 수 있다. 워크스페이스는 선택된 공유 정보를 유지하고, 주의와 경쟁을 통해 어떤 출력이 더 넓게 배포될지를 결정할 수 있다. 방송을 통해 독립적으로 구현된 구성 요소들은 공통 인지 문맥(common cognitive context)을 중심으로 조정될 수 있다.

계산적 구현(computational implementation)에서는 워크스페이스를 활성 관측, 목표, 가설, 검색된 기억, 불확실성 추정(uncertainty estimate), 후보 행동을 포함하는 구조화된 공유 상태(structured shared state)로 표현할 수 있다. 전문화된 모듈은 관련 워크스페이스 정보를 읽고 새로운 후보 내용을 제출할 수 있다. 주의 또는 중재 메커니즘(arbitration mechanism)은 이러한 후보를 평가하고 더 넓게 방송할 정보를 선택하며, 이후 참여 모듈들이 자신의 지역 처리를 갱신하도록 할 수 있다.

이러한 구현에는 신중한 제어가 필요하다. 제한 없는 방송은 아키텍처를 과부하 상태로 만들 수 있기 때문이다. 모든 관측이나 중간 활성값이 전역적으로 배포되어서는 안 된다. 선택 메커니즘은 관련성, 신뢰도(confidence), 새로움, 긴급성(urgency), 기대 정보 가치(expected information value), 계산 비용을 고려해야 한다. 따라서 워크스페이스는 단순한 공유 기억(shared memory)이 아니라 동적으로 제어되는 통신 병목(dynamic communication bottleneck)으로 기능한다.

이러한 병목(bottleneck)은 오히려 장점이 될 수 있다. 제한된 전역 용량은 시스템이 우선순위를 정하도록 강제하며, 모든 인지 하위 시스템이 다른 모든 시스템과 무제한으로 정보를 지속적으로 교환하는 것을 방지한다. 아키텍처는 많은 양의 병렬 지역 계산(parallel local computation)을 유지하면서 선택된 정보에 대해서만 비용이 높은 시스템 간 조정을 수행할 수 있다. 이는 인지 접근 이론인 동시에 자원 관리 전략(resource-management strategy)과도 유사하다.

메타인지(metacognition)는 어떤 정보가 현재 처리를 지배하고 있는지, 시스템의 신뢰도가 어느 정도인지, 추론이 제대로 진행되고 있는지, 해결되지 않은 충돌이 남아 있는지를 감시함으로써 워크스페이스의 상위 또는 내부에서 작동할 수 있다. 메타인지 신호 자체가 글로벌 접근을 획득하여 시스템이 불확실성이나 실패를 인식하도록 할 수도 있다. 이후 에이전트는 추가 계산을 할당하거나, 추가 증거를 검색하거나, 전략을 변경하거나, 외부 지원을 요청할 수 있다.

글로벌 워크스페이스 이론과 의식(consciousness)의 관계는 인공지능 시스템에서 신중하게 해석해야 한다. 이 이론은 부분적으로 인간의 의식적 접근을 설명하기 위해 개발되었지만, AI 시스템에 워크스페이스와 유사한 방송 메커니즘을 구현한다고 해서 그 시스템이 주관적 경험(subjective experience)을 가진다는 사실이 입증되는 것은 아니다. 공학적 관점에서는 선택적 정보 통합, 주의, 조정, 인지 제어를 위한 원리로서 이러한 메커니즘을 독립적으로 연구할 수 있다.

글로벌 워크스페이스 개념에서 영감을 받은 현대적인 신경망 접근법(neural approach)은 기호 정보만을 사용하는 대신 학습된 표현(learned representation)과 주의 메커니즘(attention mechanism)을 사용할 수 있다. 여러 전문화된 신경망이 서로 다른 모달리티(modality)나 작업을 처리하고, 공유 잠재 워크스페이스(shared latent workspace)를 통해 서로 통신할 수 있다. 학습된 게이팅 메커니즘(gating mechanism)은 어떤 표현이 공유 공간에 진입하고 어떤 전문 시스템이 방송 결과를 받을지를 결정할 수 있다.

파운데이션 모델(foundation model)은 또 다른 가능한 해석을 제공한다. 강력한 멀티모달 모델(multimodal model)이 일반적인 추론이나 표현 메커니즘으로 워크스페이스 처리에 참여하면서 지속적 기억(persistent memory), 지각, 계획, 제어, 도구는 별도의 아키텍처 구성 요소로 유지될 수 있다. 이 경우 하나의 파운데이션 모델이 인지의 모든 측면을 내부적으로 구현한다고 가정하는 대신 워크스페이스가 이러한 메커니즘 사이의 정보를 조정한다.

체화형 AGI 시스템(embodied AGI system)에서는 워크스페이스 동역학이 여러 시간 척도(temporal scale)를 연결할 수 있다. 빠른 지각과 제어 과정은 숙고적 추론 없이 지속적으로 작동하고, 비정상적인 사건이 발생하면 글로벌 방송과 느린 계획 과정이 활성화될 수 있다. 전략적 목표는 하향식으로 주의에 영향을 주고, 긴급한 감각 변화는 상향식으로 기존 처리를 중단시킬 수 있다. 이를 통해 빠른 반응과 장기적인 인지가 함께 존재할 수 있다.

따라서 글로벌 워크스페이스 이론은 AGI를 위한 중요한 아키텍처 원리를 제공한다. 분산된 전문화(distributed specialization)와 전역 통합(global integration)은 서로 대립하는 접근법일 필요가 없다. 전문화된 메커니즘은 효율적인 지역 계산을 수행하고, 선택적 방송(selective broadcasting)은 필요한 순간에 일시적인 시스템 전체의 조정을 형성할 수 있다. 지능은 병렬적인 지역 처리와 전역적으로 접근 가능한 인지 상태 사이의 반복적인 전환을 통해 나타날 수 있다.

인지 아키텍처(cognitive architecture)의 관점에서 글로벌 워크스페이스 이론이 지속적으로 중요한 이유는 수많은 독립적인 처리 과정이 어떻게 하나의 일관된 에이전트(coherent agent)처럼 행동할 수 있는지를 설명한다는 데 있다. 경쟁은 무엇이 전역적으로 중요해질지를 결정하고, 주의는 접근을 조절하며, 방송은 선택된 정보를 배포하고, 전문화된 시스템은 해석과 행동을 제공하며, 피드백은 다음 워크스페이스 상태를 생성한다. 이러한 반복적 순환은 지각, 기억, 추론, 계획, 학습, 행동을 하나의 통합된 적응형 인지(unified adaptive cognition)로 결합하기 위한 강력한 개념적 프레임워크를 제공한다.

##  

## 04.04. Predictive Processing

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

Predictive processing is a cognitive framework in which an intelligent system continuously generates expectations about incoming information and compares those expectations with actual observations. Rather than treating perception as a passive process that simply receives sensory data, predictive processing views cognition as an active cycle of prediction, observation, error detection, and model revision. The system attempts to anticipate what it is likely to experience before the evidence fully arrives.

At the center of this framework is an internal generative model that represents possible causes of sensory observations and relationships among states of the environment. The model predicts what sensory signals should occur under a particular interpretation of the world. Actual observations are then compared with these predictions, allowing discrepancies to reveal where the current internal representation fails to explain the available evidence.

The difference between predicted and observed information is commonly described as prediction error. A small prediction error indicates that the internal model adequately explains the current observation, whereas a large error suggests that something unexpected has occurred. Prediction errors therefore provide important signals for updating beliefs, redirecting attention, modifying internal representations, or initiating new actions that gather additional information.

Prediction and prediction error can be organized hierarchically. Higher levels represent relatively abstract, slowly changing structures such as objects, situations, contexts, goals, or causal relationships, while lower levels represent increasingly detailed sensory features. Predictions flow downward through the hierarchy, while discrepancies between prediction and observation propagate upward and influence higher-level interpretations.

This hierarchical organization allows cognition to integrate information across multiple levels of abstraction. A high-level expectation about a situation can constrain how lower-level sensory signals are interpreted, while unexpected sensory evidence can force revision of the higher-level interpretation. Perception therefore emerges from continuous interaction between top-down predictions and bottom-up evidence rather than from a strictly one-directional processing pipeline.

Prior knowledge plays an important role because predictions depend on what the system already believes about the world. Previous experiences, learned regularities, contextual information, and current goals influence which explanations are considered likely. The same sensory input can therefore produce different interpretations depending on context because perception reflects both incoming evidence and expectations generated from the internal model.

Uncertainty determines how strongly predictions and observations should influence inference. Not every prediction or sensory measurement is equally reliable. Predictive processing frameworks often describe this through precision, which represents the estimated reliability of a signal or prediction error. High-precision evidence receives greater influence, while uncertain information contributes less strongly to updating the current internal state.

Attention can be interpreted partly as the regulation of this precision. Rather than merely selecting a location or object for processing, attention can increase the importance assigned to particular prediction errors. Information judged relevant to current goals, potentially dangerous, novel, or highly informative can therefore exert stronger influence over inference, enabling limited cognitive resources to focus on observations that are most likely to require model revision.

When predictions accurately explain observations, much of the incoming information becomes redundant. The system does not need to repeatedly reconstruct every familiar feature from the beginning because expected structure is already represented internally. Computational effort can instead concentrate on deviations from expectation. This provides an important efficiency principle for biological cognition and potentially for resource-constrained artificial agents.

Unexpected events have the opposite effect. A sudden obstacle, unfamiliar object, surprising behavior, or major environmental change generates prediction errors that cannot be easily explained by the current model. These errors can increase attention and trigger deeper processing, memory retrieval, reasoning, replanning, or additional perception. The system consequently shifts computational resources from routine prediction toward resolving uncertainty.

Predictive processing can therefore support adaptive allocation of computation. In stable and highly predictable environments, many processes may operate with relatively low deliberative effort because incoming information closely matches expectations. When uncertainty or prediction error increases, more expensive cognitive mechanisms can be activated. This creates a possible architectural basis for dynamically adjusting computational intensity according to environmental complexity.

Memory contributes by providing the experiences and statistical regularities from which predictions are constructed. Episodic memory can recall similar past situations, semantic memory can supply general knowledge, and learned procedural structures can provide expectations about action outcomes. Prediction can also guide memory retrieval by determining which previous experiences are currently relevant to explaining an observation or anticipating future events.

Learning updates the generative model so that future predictions become more accurate. Repeated prediction errors indicate that existing representations or transition models do not adequately capture environmental structure. Parameters, representations, causal relationships, or policies can then be modified. Learning can consequently be understood as reducing systematic prediction error across repeated encounters rather than merely memorizing individual observations.

Self-supervised learning has a natural connection with predictive processing because the environment itself can provide training targets. A system can predict missing information, future observations, hidden states, temporal transitions, or relationships among different modalities and compare those predictions with subsequently available evidence. Large quantities of unlabeled experience can therefore be transformed into learning signals without requiring explicit human annotation for every observation.

Temporal prediction extends this principle from current sensory interpretation to future states. Given a representation of the present situation, the system can estimate what is likely to occur after a short or long interval. Such predictions allow an agent to detect abnormal transitions, anticipate environmental changes, and prepare appropriate responses before an event becomes immediately observable.

Actions can also be incorporated into prediction. Instead of estimating only how the world will evolve passively, the model can predict how different candidate actions will change future states. This transforms predictive processing into an important component of planning. The agent can internally evaluate possible trajectories and compare their expected consequences before selecting an action that best supports its goals.

Active inference extends the relationship between prediction and action further. Prediction errors can be reduced either by changing the internal model to better explain observations or by acting on the environment so that observations become more consistent with expected or preferred states. Action therefore becomes part of the inference process rather than merely an output produced after perception and reasoning have finished.

This creates a continuous perception-action loop. The agent predicts observations, receives sensory evidence, evaluates prediction errors, updates its state estimate, selects an action, and observes the resulting environmental change. Each action creates new evidence for evaluating the internal model. Perception, prediction, learning, and control consequently become tightly interconnected rather than functioning as independent sequential modules.

A world model provides a practical computational realization of many predictive-processing principles. It can encode latent states, environmental dynamics, objects, relationships, and action-conditioned transitions. Instead of processing only raw observations, an intelligent agent can maintain a compact internal representation of what exists, what is changing, and what is likely to happen next.

Latent-state prediction is particularly useful because predicting every raw sensory value may be unnecessarily expensive. An agent can transform high-dimensional camera, LiDAR, audio, or other sensor streams into compact representations and predict their future evolution. These latent representations can preserve information important for decision making while reducing the computational burden associated with direct prediction in raw sensory space.

Multimodal predictive processing can integrate information from several sensing channels. Vision, depth, LiDAR, proprioception, language, audio, and other modalities can provide complementary evidence about a shared environmental state. Predictions generated from one modality can help interpret another, while disagreement among modalities can expose uncertainty, sensor failure, or previously unseen situations.

Predictive processing is also closely related to anomaly detection. If a system has learned the normal dynamics of an environment, events that generate persistent or unusually large prediction errors can be treated as anomalous. This is useful for autonomous robots, industrial inspection, monitoring systems, and safety-critical agents because unusual conditions can be detected even when every possible failure has not been explicitly labeled beforehand.

For embodied intelligence, prediction must operate at multiple temporal scales. Fast predictions can support stabilization, collision avoidance, and immediate control, while medium-horizon predictions can support navigation and manipulation. Longer-horizon predictions can contribute to task planning, resource management, and strategic decisions. A hierarchical predictive architecture can coordinate these timescales while preserving responsiveness to immediate events.

Predictive processing can also interact with metacognition. The agent can monitor the magnitude, persistence, and distribution of prediction errors to estimate whether its internal model remains trustworthy. Repeated unexplained errors may indicate unfamiliar conditions or model failure. The system can then increase observation frequency, invoke stronger reasoning, switch models, slow its behavior, request assistance, or initiate additional learning.

This mechanism has important implications for computational efficiency in autonomous AI. A robot traveling through a familiar and predictable environment may not require maximum processing from every model at every moment. When observations closely match predictions, some expensive reasoning or perception processes can operate less frequently. Significant prediction errors can reactivate deeper processing when the environment becomes uncertain or dangerous.

However, reducing computation requires careful safety design. A highly confident prediction can still be wrong, particularly under distribution shift or rare events. Critical sensors and safety controllers may therefore need to remain continuously active even when higher-level cognition enters a lower-computation mode. Predictive processing should regulate expensive cognition without eliminating independent mechanisms required for detecting unexpected hazards.

Modern neural networks provide powerful mechanisms for implementing predictive representations. Transformers, recurrent networks, state-space models, latent dynamics models, generative models, and multimodal encoders can learn temporal and structural regularities from large datasets. These models can generate predictions over observations or latent states, while prediction errors provide signals for representation learning and adaptation.

Predictive processing does not imply that intelligence should only minimize immediate sensory error. An effective agent must preserve goals, explore uncertain environments, acquire useful information, and sometimes tolerate short-term prediction errors to achieve better long-term outcomes. Prediction therefore needs to operate together with planning, reward, curiosity, memory, uncertainty estimation, and safety constraints within a broader cognitive architecture.

Within AGI, predictive processing provides a unifying connection among perception, learning, world modeling, planning, and action. Perception becomes inference about hidden causes, learning improves the internal generative model, world modeling predicts state transitions, planning compares possible futures, and action changes future observations. The same predictive principle can consequently contribute to several cognitive functions that otherwise appear separate.

The broader architectural significance is that an intelligent agent does not merely react to the present. It continuously anticipates what should happen, measures where reality differs from expectation, and uses those differences to decide where additional cognition is required. Predictive processing therefore offers a foundation for adaptive, resource-aware intelligence in which prediction guides perception, prediction error drives correction, and experience progressively improves the agent\'s model of the world.

예측 처리(Predictive Processing)는 지능형 시스템이 들어오는 정보에 대한 기대를 지속적으로 생성하고, 이러한 기대를 실제 관측(actual observation)과 비교하는 인지 프레임워크(cognitive framework)이다. 지각(perception)을 단순히 감각 데이터를 수동적으로 받아들이는 과정으로 보는 대신, 예측 처리는 인지를 예측(prediction), 관측(observation), 오류 탐지(error detection), 모델 수정(model revision)이 반복되는 능동적 순환으로 본다. 시스템은 증거가 완전히 도착하기 전에 무엇을 경험할 가능성이 높은지를 미리 예측하려 한다.

이 프레임워크의 중심에는 감각 관측(sensory observation)의 가능한 원인과 환경 상태 사이의 관계를 표현하는 내부 생성 모델(internal generative model)이 존재한다. 이 모델은 특정한 세계 해석에 따라 어떤 감각 신호가 발생해야 하는지를 예측한다. 실제 관측은 이러한 예측과 비교되며, 그 차이를 통해 현재의 내부 표현(internal representation)이 이용 가능한 증거를 제대로 설명하지 못하는 부분을 발견할 수 있다.

예측된 정보와 실제로 관측된 정보 사이의 차이는 일반적으로 예측 오차(prediction error)라고 한다. 작은 예측 오차는 내부 모델이 현재 관측을 적절하게 설명하고 있음을 의미하지만, 큰 오차는 예상하지 못한 사건이 발생했음을 의미한다. 따라서 예측 오차는 신념(belief)을 갱신하고, 주의를 전환하고, 내부 표현을 수정하거나, 추가적인 정보를 수집하기 위한 새로운 행동을 시작하게 하는 중요한 신호가 된다.

예측(prediction)과 예측 오차(prediction error)는 계층적으로 구성될 수 있다. 상위 계층은 객체, 상황, 문맥(context), 목표 또는 인과관계와 같이 비교적 추상적이고 느리게 변화하는 구조를 표현하며, 하위 계층으로 갈수록 보다 세부적인 감각 특징을 표현한다. 예측은 계층을 따라 하향식(top-down)으로 전달되고, 예측과 관측 사이의 차이는 상향식(bottom-up)으로 전달되어 상위 수준의 해석에 영향을 준다.

이러한 계층적 조직(hierarchical organization)을 통해 인지는 여러 추상화 수준에 걸쳐 정보를 통합할 수 있다. 상황에 대한 상위 수준의 기대는 하위 수준의 감각 신호가 어떻게 해석될지를 제한할 수 있으며, 예상하지 못한 감각적 증거는 상위 수준의 해석을 수정하도록 만들 수 있다. 따라서 지각은 엄격한 단방향 처리 파이프라인이 아니라 하향식 예측과 상향식 증거가 지속적으로 상호작용하면서 형성된다.

사전 지식(prior knowledge)은 예측이 시스템이 이미 세계에 대해 가지고 있는 믿음에 의존하기 때문에 중요한 역할을 한다. 이전 경험, 학습된 규칙성(learned regularity), 문맥 정보, 현재 목표는 어떤 설명이 더 가능성이 높은지에 영향을 준다. 따라서 동일한 감각 입력이라도 문맥에 따라 다르게 해석될 수 있으며, 이는 지각이 들어오는 증거뿐 아니라 내부 모델에서 생성된 기대에도 영향을 받기 때문이다.

불확실성(uncertainty)은 예측과 관측이 추론에 어느 정도 영향을 주어야 하는지를 결정한다. 모든 예측이나 감각 측정이 동일한 수준의 신뢰성을 가지는 것은 아니다. 예측 처리 프레임워크에서는 이를 정밀도(precision)라는 개념으로 설명하는 경우가 많으며, 정밀도는 신호 또는 예측 오차의 추정된 신뢰성을 나타낸다. 높은 정밀도의 증거는 더 큰 영향을 주고, 불확실한 정보는 현재 내부 상태를 갱신하는 데 상대적으로 적은 영향을 준다.

주의(attention)는 부분적으로 이러한 정밀도를 조절하는 과정으로 해석할 수 있다. 단순히 처리할 위치나 객체를 선택하는 것이 아니라 특정 예측 오차에 부여되는 중요도를 증가시킬 수 있다. 현재 목표와 관련되거나, 잠재적으로 위험하거나, 새롭거나, 높은 정보 가치를 가진 정보는 추론에 더 강한 영향을 줄 수 있으며, 이를 통해 제한된 인지 자원을 내부 모델 수정이 가장 필요한 관측에 집중시킬 수 있다.

예측이 관측을 정확하게 설명하면 들어오는 정보의 상당 부분은 중복적(redundant)이 된다. 예상된 구조가 이미 내부적으로 표현되어 있기 때문에 시스템은 익숙한 모든 특징을 처음부터 반복해서 재구성할 필요가 없다. 대신 계산 자원을 예상과 다른 부분에 집중할 수 있다. 이는 생물학적 인지뿐 아니라 자원이 제한된 인공지능 에이전트(resource-constrained artificial agent)에도 중요한 효율성 원리를 제공한다.

예상하지 못한 사건은 반대의 효과를 만든다. 갑작스러운 장애물, 익숙하지 않은 객체, 놀라운 행동 또는 큰 환경 변화는 현재 모델로 쉽게 설명할 수 없는 예측 오차를 생성한다. 이러한 오류는 주의를 증가시키고 더 깊은 처리, 기억 검색(memory retrieval), 추론, 재계획(replanning), 추가 지각을 활성화할 수 있다. 따라서 시스템은 계산 자원을 일상적인 예측에서 불확실성을 해결하는 방향으로 전환한다.

따라서 예측 처리는 계산 자원의 적응적 할당(adaptive allocation of computation)을 지원할 수 있다. 안정적이고 예측 가능성이 높은 환경에서는 들어오는 정보가 기대와 거의 일치하기 때문에 많은 과정이 비교적 적은 숙고적 계산(deliberative computation)으로 작동할 수 있다. 반대로 불확실성이나 예측 오차가 증가하면 비용이 높은 인지 메커니즘을 활성화할 수 있다. 이는 환경의 복잡성에 따라 계산 강도를 동적으로 조절하는 아키텍처적 기반을 제공할 수 있다.

기억(memory)은 예측을 구성하는 경험과 통계적 규칙성(statistical regularity)을 제공한다. 일화 기억(episodic memory)은 과거의 유사한 상황을 회상할 수 있고, 의미 기억(semantic memory)은 일반적인 지식을 제공하며, 학습된 절차적 구조(procedural structure)는 행동 결과에 대한 기대를 제공할 수 있다. 예측은 또한 현재 관측을 설명하거나 미래 사건을 예상하는 데 어떤 과거 경험이 관련되는지를 결정함으로써 기억 검색을 안내할 수 있다.

학습(learning)은 미래의 예측을 더욱 정확하게 만들도록 생성 모델(generative model)을 갱신한다. 반복적인 예측 오차는 기존의 표현이나 상태 전이 모델(state transition model)이 환경 구조를 충분히 포착하지 못하고 있음을 의미한다. 이에 따라 매개변수(parameter), 표현, 인과관계 또는 정책(policy)을 수정할 수 있다. 따라서 학습은 개별 관측을 단순히 기억하는 것이 아니라 반복되는 경험에서 체계적인 예측 오차를 감소시키는 과정으로 이해할 수 있다.

자기지도 학습(self-supervised learning)은 환경 자체가 학습 목표(training target)를 제공할 수 있다는 점에서 예측 처리와 자연스럽게 연결된다. 시스템은 누락된 정보, 미래 관측, 숨겨진 상태(hidden state), 시간적 전이(temporal transition), 서로 다른 모달리티(modality) 사이의 관계를 예측하고 이후 이용 가능해진 실제 증거와 비교할 수 있다. 따라서 모든 관측에 명시적인 인간 라벨(annotation)을 제공하지 않더라도 방대한 비라벨 경험(unlabeled experience)을 학습 신호로 변환할 수 있다.

시간적 예측(temporal prediction)은 이러한 원리를 현재의 감각 해석에서 미래 상태로 확장한다. 현재 상황에 대한 표현이 주어지면 시스템은 짧거나 긴 시간 이후에 어떤 일이 발생할 가능성이 높은지를 추정할 수 있다. 이러한 예측을 통해 에이전트는 비정상적인 상태 전이를 탐지하고, 환경 변화를 예상하며, 사건이 직접 관측되기 전에 적절한 대응을 준비할 수 있다.

행동(action) 역시 예측 과정에 포함될 수 있다. 세계가 수동적으로 어떻게 변화할지만 추정하는 대신, 모델은 서로 다른 후보 행동(candidate action)이 미래 상태를 어떻게 변화시킬지를 예측할 수 있다. 이를 통해 예측 처리는 계획(planning)의 중요한 구성 요소가 된다. 에이전트는 가능한 궤적(trajectory)을 내부적으로 평가하고 예상 결과를 비교한 뒤 자신의 목표를 가장 잘 지원하는 행동을 선택할 수 있다.

능동 추론(active inference)은 예측과 행동 사이의 관계를 더욱 확장한다. 예측 오차는 내부 모델을 변경하여 관측을 더 잘 설명하는 방법으로 감소시킬 수도 있고, 환경에 행동을 가하여 실제 관측이 예상되거나 선호되는 상태와 더욱 일치하도록 만드는 방법으로 감소시킬 수도 있다. 따라서 행동은 지각과 추론이 끝난 이후 생성되는 단순한 출력이 아니라 추론 과정 자체의 일부가 된다.

이를 통해 지속적인 지각-행동 순환(perception-action loop)이 형성된다. 에이전트는 관측을 예측하고, 감각적 증거를 수신하고, 예측 오차를 평가하고, 상태 추정(state estimate)을 갱신하고, 행동을 선택한 뒤 그 결과로 나타나는 환경 변화를 관측한다. 각각의 행동은 내부 모델을 평가하기 위한 새로운 증거를 생성한다. 따라서 지각, 예측, 학습, 제어는 서로 독립적인 순차 모듈이 아니라 밀접하게 연결된 과정이 된다.

월드 모델(world model)은 예측 처리의 많은 원리를 실용적인 계산 형태로 구현할 수 있다. 월드 모델은 잠재 상태(latent state), 환경 동역학(environmental dynamics), 객체, 관계, 행동 조건부 상태 전이(action-conditioned transition)를 인코딩할 수 있다. 지능형 에이전트는 원시 관측만을 처리하는 대신 무엇이 존재하고, 무엇이 변화하고 있으며, 다음에 어떤 일이 일어날 가능성이 높은지를 나타내는 압축된 내부 표현을 유지할 수 있다.

잠재 상태 예측(latent-state prediction)은 모든 원시 감각값을 직접 예측하는 것이 불필요하게 많은 계산 비용을 요구할 수 있기 때문에 특히 유용하다. 에이전트는 고차원 카메라, 라이다(LiDAR), 오디오 또는 다른 센서 스트림을 압축된 표현으로 변환하고 그 미래 변화를 예측할 수 있다. 이러한 잠재 표현(latent representation)은 의사결정에 중요한 정보를 유지하면서 원시 감각 공간에서 직접 예측하는 계산 부담을 감소시킬 수 있다.

멀티모달 예측 처리(multimodal predictive processing)는 여러 감지 채널의 정보를 통합할 수 있다. 시각(vision), 깊이(depth), 라이다, 고유수용감각(proprioception), 언어, 오디오 및 기타 모달리티는 공유된 환경 상태에 대한 상호보완적인 증거를 제공한다. 하나의 모달리티에서 생성된 예측은 다른 모달리티를 해석하는 데 도움을 줄 수 있으며, 모달리티 사이의 불일치는 불확실성, 센서 고장(sensor failure), 또는 이전에 경험하지 못한 상황을 드러낼 수 있다.

예측 처리는 이상 탐지(anomaly detection)와도 밀접하게 관련된다. 시스템이 환경의 정상적인 동역학을 학습했다면 지속적으로 발생하거나 비정상적으로 큰 예측 오차를 생성하는 사건을 이상 상태(anomaly)로 판단할 수 있다. 이는 가능한 모든 고장 상황을 사전에 명시적으로 라벨링하지 않아도 비정상적인 조건을 탐지할 수 있기 때문에 자율 로봇, 산업 검사, 모니터링 시스템, 안전 중요 에이전트(safety-critical agent)에 유용하다.

체화 지능(embodied intelligence)에서는 여러 시간 척도(temporal scale)에 걸쳐 예측이 이루어져야 한다. 빠른 예측은 안정화(stabilization), 충돌 회피(collision avoidance), 즉각적인 제어를 지원하고, 중간 시간 범위의 예측은 내비게이션과 조작(manipulation)을 지원할 수 있다. 장기 예측은 작업 계획, 자원 관리, 전략적 의사결정에 기여할 수 있다. 계층적 예측 아키텍처(hierarchical predictive architecture)는 즉각적인 사건에 대한 대응성을 유지하면서 이러한 시간 척도를 조정할 수 있다.

예측 처리는 메타인지(metacognition)와도 상호작용할 수 있다. 에이전트는 예측 오차의 크기, 지속성, 분포를 모니터링하여 자신의 내부 모델이 여전히 신뢰할 수 있는지를 평가할 수 있다. 반복적으로 설명되지 않는 오류는 익숙하지 않은 조건이나 모델 실패(model failure)를 의미할 수 있다. 그러면 시스템은 관측 빈도를 증가시키고, 더 강력한 추론을 호출하고, 모델을 전환하거나, 행동 속도를 낮추고, 지원을 요청하거나, 추가적인 학습을 시작할 수 있다.

이러한 메커니즘은 자율 인공지능(autonomous AI)의 계산 효율성 측면에서 중요한 의미를 갖는다. 익숙하고 예측 가능한 환경을 이동하는 로봇은 모든 순간에 모든 모델을 최대 성능으로 처리할 필요가 없을 수 있다. 관측이 예측과 밀접하게 일치하면 비용이 높은 일부 추론이나 지각 과정을 더 낮은 빈도로 실행할 수 있다. 환경이 불확실하거나 위험해져 큰 예측 오차가 발생하면 더 깊은 처리를 다시 활성화할 수 있다.

그러나 계산량을 감소시키는 과정에는 신중한 안전 설계(safety design)가 필요하다. 높은 신뢰도를 가진 예측도 분포 변화(distribution shift)나 희귀 사건(rare event)에서는 잘못될 수 있다. 따라서 상위 수준의 인지가 낮은 계산 모드로 전환되더라도 핵심 센서와 안전 제어기(safety controller)는 지속적으로 활성화되어야 할 수 있다. 예측 처리는 예상하지 못한 위험을 탐지하는 독립적인 안전 메커니즘을 제거하는 것이 아니라 비용이 높은 인지 과정의 사용을 조절해야 한다.

현대 신경망(neural network)은 예측 표현(predictive representation)을 구현하기 위한 강력한 메커니즘을 제공한다. 트랜스포머(Transformer), 순환 신경망(recurrent network), 상태 공간 모델(state-space model), 잠재 동역학 모델(latent dynamics model), 생성 모델(generative model), 멀티모달 인코더(multimodal encoder)는 대규모 데이터에서 시간적·구조적 규칙성을 학습할 수 있다. 이러한 모델은 관측이나 잠재 상태에 대한 예측을 생성하며, 예측 오차는 표현 학습과 적응을 위한 신호가 될 수 있다.

예측 처리는 지능이 단순히 즉각적인 감각 오차만을 최소화해야 한다는 것을 의미하지 않는다. 효과적인 에이전트는 목표를 유지하고, 불확실한 환경을 탐색하고, 유용한 정보를 획득하며, 더 나은 장기 결과를 얻기 위해 단기적인 예측 오차를 때로는 허용해야 한다. 따라서 예측은 보다 광범위한 인지 아키텍처(cognitive architecture) 안에서 계획, 보상(reward), 호기심(curiosity), 기억, 불확실성 추정, 안전 제약과 함께 작동해야 한다.

AGI에서 예측 처리는 지각, 학습, 월드 모델링(world modeling), 계획, 행동 사이를 연결하는 통합 원리를 제공한다. 지각은 숨겨진 원인(hidden cause)에 대한 추론이 되고, 학습은 내부 생성 모델을 개선하며, 월드 모델링은 상태 전이를 예측하고, 계획은 가능한 미래를 비교하며, 행동은 미래의 관측을 변화시킨다. 따라서 동일한 예측 원리가 서로 독립적으로 보이는 여러 인지 기능에 공통적으로 기여할 수 있다.

보다 넓은 아키텍처적 의미에서 지능형 에이전트는 단순히 현재 상황에 반응하는 존재가 아니다. 앞으로 어떤 일이 발생해야 하는지를 지속적으로 예상하고, 현실이 예상과 어디에서 다른지를 측정하며, 그 차이를 이용하여 어느 부분에 추가적인 인지가 필요한지를 결정한다. 따라서 예측 처리는 예측이 지각을 안내하고, 예측 오차가 수정을 유도하며, 경험이 에이전트의 월드 모델을 점진적으로 개선하는 적응형·자원 인식 지능(adaptive, resource-aware intelligence)의 기반을 제공한다.

##  

## 04.05. NeuroSymbolic Architectures

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

NeuroSymbolic Architectures combine neural learning with symbolic representation and reasoning to create intelligent systems that can learn from complex data while manipulating explicit knowledge. Neural networks provide perception, pattern recognition, representation learning, and statistical generalization, whereas symbolic mechanisms provide structured concepts, logical relationships, rules, constraints, and compositional reasoning. Their integration seeks to capture complementary strengths that neither paradigm provides easily on its own.

Neural approaches are highly effective at learning representations directly from large amounts of sensory or linguistic data. Images, speech, video, text, LiDAR, and multimodal observations can be transformed into distributed representations that capture complex statistical regularities. However, these learned representations may not explicitly expose objects, relations, causal structures, constraints, or rules required for systematic reasoning and long-horizon decision making.

Symbolic approaches represent knowledge through discrete and interpretable structures such as symbols, predicates, rules, graphs, programs, ontologies, and logical expressions. They can support explicit reasoning, variable binding, compositionality, constraint satisfaction, and manipulation of abstract relationships. Their weakness is that symbolic knowledge is difficult to construct directly from noisy, high-dimensional observations and can require substantial manual engineering when used without learning mechanisms.

A NeuroSymbolic architecture attempts to connect these two representational regimes. Neural components transform raw observations into learned features or structured candidates, while symbolic components organize selected information into entities, attributes, relationships, rules, and goals. Information can also flow in the opposite direction, allowing symbolic knowledge or constraints to influence neural inference, learning, attention, and action selection.

The neural-to-symbolic interface is therefore a central architectural problem. A vision network may detect objects and estimate their properties, but a reasoning system may require representations such as object identity, spatial relation, ownership, accessibility, or causal dependency. The architecture must convert uncertain neural outputs into structures that symbolic mechanisms can manipulate without discarding important information about confidence and ambiguity.

Symbol grounding addresses the relationship between abstract symbols and observations or actions in the environment. A symbol such as "door," "blocked," or "reachable" becomes useful to an embodied agent only when it can be connected to perceptual evidence and operational consequences. Neural perception can help ground symbols in sensory experience, while symbolic structures can preserve stable meanings and relationships across changing observations.

Knowledge graphs provide one possible bridge between neural and symbolic processing. Entities can represent objects, people, locations, concepts, or events, while edges represent relationships among them. Neural models can extract or predict graph content from observations, and symbolic reasoning can traverse or transform the resulting structure. Graph neural networks can further provide differentiable processing over relational structures, creating intermediate forms between purely neural and purely symbolic computation.

Logical rules provide another important mechanism. Rules can express relationships such as prerequisites, exclusions, safety conditions, causal dependencies, or task procedures. Neural systems may estimate whether the conditions represented by a rule are satisfied, while symbolic reasoning determines the consequences. This allows uncertain perception to interact with explicit domain knowledge without requiring every relationship to be rediscovered statistically from data.

Constraints are particularly valuable in safety-critical and physically grounded systems. A neural model may propose actions according to learned probabilities, while symbolic constraints can reject actions that violate physical limits, operational policies, task requirements, or safety rules. Rather than treating safety as a final filter, NeuroSymbolic architectures can incorporate constraints during planning and reasoning so that invalid possibilities are removed before execution.

Neural and symbolic components can also cooperate during learning. Symbolic knowledge can provide weak supervision, structural priors, consistency requirements, or additional training objectives. For example, a neural model may be penalized when its predictions violate known relationships between entities. This can reduce the amount of labeled data required and encourage representations that are compatible with domain knowledge rather than relying exclusively on statistical correlations.

Differentiable reasoning attempts to make some symbolic-like operations compatible with gradient-based learning. Logical relationships, rule applications, relational operations, or program structures can be approximated using differentiable mechanisms so that learning signals propagate through multiple reasoning stages. This creates a spectrum of architectures ranging from clearly separated neural and symbolic modules to deeply integrated systems in which structured reasoning itself becomes partially learnable.

Program induction provides another route toward NeuroSymbolic intelligence. Instead of generating only a direct answer or action, a neural model can infer a sequence of structured operations or a small program describing how a problem should be solved. The resulting program can then be executed by a symbolic interpreter. This separates learning how to construct a solution procedure from deterministically executing that procedure.

Compositionality is a major motivation for NeuroSymbolic systems. Human reasoning can combine familiar concepts and operations into configurations that may never have been encountered during training. Symbolic representations naturally support such recombination because variables, relations, and rules can be applied systematically. Neural models provide flexible learned representations, while symbolic composition can improve generalization to novel combinations of known concepts.

Systematic generalization is closely related to this capability. A model that learns a relationship in one context should ideally apply the same abstract relationship to different objects or situations. Pure pattern recognition may sometimes depend too strongly on statistical similarity to training examples. Explicit relational representations can help separate the structure of a problem from the specific entities occupying that structure.

Memory can also be organized NeuroSymbolically. Neural embeddings provide efficient similarity-based retrieval, while symbolic structures preserve explicit facts, relations, temporal events, and dependencies. An agent may first retrieve candidate memories using neural similarity and then use symbolic reasoning to determine which retrieved information satisfies the requirements of the current problem. This combines flexible retrieval with structured verification.

Planning benefits strongly from this integration. Neural models can estimate action feasibility, cost, value, or likely outcomes, while symbolic planners represent goals, preconditions, effects, and constraints. Candidate plans can therefore exploit learned experience without abandoning explicit task structure. When environments are uncertain, neural prediction can estimate likely transitions while symbolic mechanisms maintain the logical organization of the plan.

World models provide another important integration point. Neural world models can learn latent dynamics from high-dimensional observations, while symbolic world models represent persistent objects, relationships, events, and causal structures. A hybrid world model may therefore maintain both continuous latent representations and explicit relational state, allowing an agent to predict detailed dynamics while reasoning about abstract consequences.

Causal reasoning is particularly important because correlation alone is insufficient for many intelligent decisions. Neural networks can discover statistical regularities and candidate dependencies, while symbolic causal models can represent interventions, mechanisms, and structured relationships. Combining these capabilities can support reasoning about what may happen naturally and what may happen if the agent deliberately changes some aspect of the environment.

Uncertainty must remain visible across the neural-symbolic boundary. Neural perception rarely produces perfectly certain classifications or state estimates, and symbolic reasoning should not automatically treat uncertain outputs as unquestionable facts. Probabilistic logic, confidence-weighted facts, alternative hypotheses, or belief distributions can preserve uncertainty while still allowing structured reasoning to operate over the available evidence.

This is especially important for robotics and embodied intelligence. A robot may perceive several possible objects, estimate uncertain positions, infer navigability, and reason about task constraints simultaneously. Neural perception handles noisy sensory input, while symbolic representations describe goals, spatial relationships, task rules, and safety conditions. The architecture must continuously revise these structures as new observations arrive.

A NeuroSymbolic agent can therefore operate through a repeated perception-reasoning-action cycle. Neural perception converts observations into candidate entities and states, symbolic reasoning integrates them with knowledge and goals, planning selects structured actions, and control executes them. The resulting observations return to the neural system, while discrepancies between expected and actual outcomes update both learned representations and explicit knowledge.

Language provides another natural bridge. Large language models can interpret instructions, extract entities and relationships, generate candidate plans, and translate between natural language and structured representations. Symbolic systems can then verify constraints, execute formal procedures, or maintain persistent knowledge. The language model provides flexibility, while structured mechanisms reduce dependence on unconstrained generation for tasks requiring reliable state management.

Foundation models can consequently become components of a larger NeuroSymbolic architecture rather than complete architectures by themselves. A multimodal foundation model may provide broad perception and reasoning capabilities, while external memory, knowledge graphs, planners, rule systems, verification mechanisms, and controllers provide persistent structure. The resulting system combines learned generalization with explicit architectural organization.

Tool use can also be represented NeuroSymbolically. Neural models may determine which tool is relevant from natural-language context, while symbolic descriptions specify tool capabilities, input requirements, preconditions, and expected outputs. Planning mechanisms can organize several tool operations into a structured workflow and verify whether intermediate results satisfy the conditions required for subsequent operations.

Metacognition can monitor interactions between neural and symbolic processes. The system may detect when neural confidence is too low for symbolic commitment, when logical constraints conflict with model predictions, or when a plan repeatedly fails despite high predicted success. Such conflicts provide signals for additional observation, deeper reasoning, alternative hypotheses, model switching, or human assistance.

NeuroSymbolic architectures also provide opportunities for improved explainability. A neural network\'s internal representation may be difficult to interpret directly, but symbolic structures can expose which entities, relationships, rules, constraints, and goals contributed to a decision. This does not automatically make the entire system transparent, but it can provide inspectable intermediate representations and reasoning traces useful for debugging, validation, and safety analysis.

Efficiency is another potential advantage. Neural networks need not perform every stage of reasoning through repeated high-cost inference if some knowledge can be represented as compact rules or reusable symbolic procedures. Conversely, symbolic search can be reduced when neural models provide strong candidate predictions or heuristics. Each paradigm can therefore reduce computational burdens that would be expensive for the other.

The main difficulty lies in integration rather than simply placing two systems side by side. Representations must remain compatible, uncertainty must cross interfaces correctly, learning must not violate essential constraints, and symbolic structures must adapt when the environment changes. Poorly designed interfaces can create brittle pipelines in which errors from neural perception propagate into symbolic reasoning as incorrect facts.

Modern NeuroSymbolic research therefore spans many architectural designs rather than one standardized solution. Some systems use neural perception followed by symbolic reasoning, others embed logical constraints into neural training, and others learn programs, graphs, relational representations, or differentiable reasoning mechanisms. The common principle is that learned statistical intelligence and structured reasoning should cooperate rather than being treated as mutually exclusive alternatives.

For AGI, this combination is attractive because general intelligence requires both adaptation and structure. An agent must learn from incomplete experience, recognize unfamiliar patterns, and operate under uncertainty, while also preserving goals, relationships, constraints, causal knowledge, and reusable procedures. Neural computation provides flexible learning, while symbolic computation provides mechanisms for manipulating explicit structure across extended reasoning processes.

The broader significance of NeuroSymbolic Architectures is therefore their attempt to unify two complementary views of intelligence. Intelligence can emerge from learning distributed representations from experience, but it also requires the ability to organize knowledge, reason over relationships, compose familiar concepts in new ways, obey constraints, and explain structured decisions. Integrating these capabilities offers a promising architectural direction toward adaptive, reliable, and increasingly general intelligent agents.

뉴로심볼릭 아키텍처(NeuroSymbolic Architectures)는 복잡한 데이터로부터 학습하면서 동시에 명시적인 지식(explicit knowledge)을 조작할 수 있는 지능형 시스템을 만들기 위해 신경망 학습(neural learning)과 기호적 표현 및 추론(symbolic representation and reasoning)을 결합한다. 신경망은 지각(perception), 패턴 인식(pattern recognition), 표현 학습(representation learning), 통계적 일반화(statistical generalization)를 제공하고, 기호적 메커니즘은 구조화된 개념, 논리적 관계, 규칙, 제약조건, 조합적 추론(compositional reasoning)을 제공한다. 이러한 통합은 어느 한 패러다임만으로는 쉽게 얻기 어려운 상호보완적 강점을 결합하려는 것이다.

신경망 접근법(neural approach)은 대량의 감각 데이터나 언어 데이터로부터 직접 표현을 학습하는 데 매우 효과적이다. 이미지, 음성, 비디오, 텍스트, 라이다(LiDAR), 멀티모달 관측(multimodal observation)은 복잡한 통계적 규칙성을 포착하는 분산 표현(distributed representation)으로 변환될 수 있다. 그러나 이러한 학습된 표현은 체계적인 추론과 장기적인 의사결정에 필요한 객체, 관계, 인과 구조, 제약조건 또는 규칙을 명시적으로 드러내지 못할 수 있다.

기호적 접근법(symbolic approach)은 기호(symbol), 술어(predicate), 규칙(rule), 그래프(graph), 프로그램(program), 온톨로지(ontology), 논리 표현(logical expression)과 같이 이산적이고 해석 가능한 구조를 통해 지식을 표현한다. 이러한 방식은 명시적 추론, 변수 바인딩(variable binding), 조합성(compositionality), 제약조건 충족(constraint satisfaction), 추상적 관계의 조작을 지원할 수 있다. 그러나 학습 메커니즘 없이 사용하면 잡음이 많고 고차원적인 관측으로부터 기호 지식을 직접 구성하기 어렵고 상당한 수작업 엔지니어링이 필요할 수 있다.

뉴로심볼릭 아키텍처는 이러한 두 가지 표현 체계(representational regime)를 연결하려 한다. 신경망 구성 요소는 원시 관측(raw observation)을 학습된 특징이나 구조화된 후보 정보로 변환하고, 기호적 구성 요소는 선택된 정보를 개체(entity), 속성(attribute), 관계, 규칙, 목표로 조직한다. 정보는 반대 방향으로도 흐를 수 있으며, 기호적 지식이나 제약조건이 신경망 추론, 학습, 주의(attention), 행동 선택(action selection)에 영향을 줄 수 있다.

따라서 신경망-기호 인터페이스(neural-to-symbolic interface)는 핵심적인 아키텍처 문제이다. 비전 네트워크(vision network)가 객체를 탐지하고 그 속성을 추정하더라도, 추론 시스템은 객체 정체성(object identity), 공간 관계(spatial relation), 소유 관계, 접근 가능성(accessibility), 인과적 의존관계(causal dependency)와 같은 표현을 요구할 수 있다. 아키텍처는 신뢰도와 모호성(ambiguity)에 관한 중요한 정보를 잃지 않으면서 불확실한 신경망 출력을 기호적 메커니즘이 조작할 수 있는 구조로 변환해야 한다.

기호 접지(symbol grounding)는 추상적인 기호와 환경의 관측 또는 행동 사이의 관계를 다룬다. 문(door), 차단됨(blocked), 도달 가능함(reachable)과 같은 기호는 감각적 증거 및 실제 행동 결과와 연결될 수 있을 때 체화형 에이전트(embodied agent)에게 의미를 갖는다. 신경망 기반 지각은 기호를 감각 경험에 접지하는 데 도움을 줄 수 있으며, 기호적 구조는 변화하는 관측에서도 안정적인 의미와 관계를 유지할 수 있다.

지식 그래프(knowledge graph)는 신경망 처리와 기호적 처리를 연결하는 하나의 방법을 제공한다. 개체는 객체, 사람, 위치, 개념 또는 사건을 나타낼 수 있고, 엣지(edge)는 이들 사이의 관계를 표현한다. 신경망 모델은 관측으로부터 그래프의 내용을 추출하거나 예측할 수 있고, 기호적 추론은 생성된 구조를 탐색하거나 변환할 수 있다. 그래프 신경망(Graph Neural Network)은 관계 구조 위에서 미분 가능한 처리(differentiable processing)를 제공하여 순수 신경망 계산과 순수 기호 계산 사이의 중간 형태를 만들 수 있다.

논리 규칙(logical rule)은 또 다른 중요한 메커니즘을 제공한다. 규칙은 선행조건(prerequisite), 배타 조건(exclusion), 안전 조건(safety condition), 인과적 의존관계 또는 작업 절차를 표현할 수 있다. 신경망 시스템은 규칙에 표현된 조건이 충족되는지를 추정하고, 기호적 추론은 그 결과를 결정할 수 있다. 이를 통해 불확실한 지각이 모든 관계를 데이터에서 통계적으로 다시 학습할 필요 없이 명시적인 도메인 지식(domain knowledge)과 상호작용할 수 있다.

제약조건(constraint)은 안전 중요 시스템(safety-critical system)과 물리적으로 접지된 시스템에서 특히 중요하다. 신경망 모델은 학습된 확률에 따라 행동을 제안할 수 있지만, 기호적 제약조건은 물리적 한계, 운영 정책, 작업 요구사항 또는 안전 규칙을 위반하는 행동을 거부할 수 있다. 뉴로심볼릭 아키텍처는 안전을 최종적인 필터로만 취급하지 않고 계획과 추론 과정에 제약조건을 포함하여 실행 전에 유효하지 않은 가능성을 제거할 수 있다.

신경망 구성 요소와 기호적 구성 요소는 학습 과정에서도 협력할 수 있다. 기호적 지식은 약한 지도 학습(weak supervision), 구조적 사전정보(structural prior), 일관성 요구조건(consistency requirement), 추가적인 학습 목표(training objective)를 제공할 수 있다. 예를 들어 신경망 모델의 예측이 개체 사이의 알려진 관계를 위반하면 페널티를 부여할 수 있다. 이를 통해 필요한 라벨 데이터의 양을 줄이고 순수한 통계적 상관관계에만 의존하지 않는 도메인 지식과 호환되는 표현을 학습하도록 유도할 수 있다.

미분 가능 추론(differentiable reasoning)은 일부 기호적 연산을 경사 기반 학습(gradient-based learning)과 호환되도록 만들려는 접근법이다. 논리적 관계, 규칙 적용, 관계 연산 또는 프로그램 구조를 미분 가능한 메커니즘으로 근사하여 학습 신호가 여러 추론 단계를 통과할 수 있도록 한다. 이를 통해 명확하게 분리된 신경망 및 기호 모듈부터 구조화된 추론 자체가 부분적으로 학습 가능한 깊이 통합된 시스템까지 다양한 형태의 아키텍처를 구성할 수 있다.

프로그램 귀납(program induction)은 뉴로심볼릭 지능으로 향하는 또 다른 경로를 제공한다. 신경망 모델이 직접적인 답이나 행동만 생성하는 대신 문제를 해결하는 방법을 설명하는 구조화된 연산의 순서 또는 작은 프로그램을 추론할 수 있다. 이후 생성된 프로그램은 기호적 인터프리터(symbolic interpreter)를 통해 실행될 수 있다. 이를 통해 해결 절차를 구성하는 방법을 학습하는 과정과 해당 절차를 결정론적으로 실행하는 과정을 분리할 수 있다.

조합성(compositionality)은 뉴로심볼릭 시스템을 개발하는 주요 동기 가운데 하나이다. 인간의 추론은 학습 과정에서 직접 경험하지 못했던 구성으로 익숙한 개념과 연산을 결합할 수 있다. 기호적 표현은 변수, 관계, 규칙을 체계적으로 적용할 수 있기 때문에 이러한 재조합을 자연스럽게 지원한다. 신경망 모델이 유연한 학습 표현을 제공하고 기호적 조합이 알려진 개념들의 새로운 조합에 대한 일반화 능력을 향상시킬 수 있다.

체계적 일반화(systematic generalization)는 이러한 능력과 밀접하게 관련된다. 하나의 문맥에서 어떤 관계를 학습한 모델이라면 이상적으로는 동일한 추상적 관계를 다른 객체나 상황에도 적용할 수 있어야 한다. 순수한 패턴 인식은 학습 사례와의 통계적 유사성에 지나치게 의존할 수 있다. 명시적인 관계 표현(explicit relational representation)은 문제의 구조와 해당 구조를 구성하는 특정 개체를 분리하는 데 도움을 줄 수 있다.

기억(memory) 역시 뉴로심볼릭 방식으로 구성할 수 있다. 신경망 임베딩(neural embedding)은 유사도 기반 검색(similarity-based retrieval)을 효율적으로 제공하고, 기호적 구조는 명시적인 사실, 관계, 시간적 사건, 의존관계를 보존한다. 에이전트는 먼저 신경망 유사도를 이용하여 후보 기억을 검색하고, 이후 기호적 추론을 사용하여 검색된 정보 가운데 어떤 것이 현재 문제의 요구조건을 만족하는지를 결정할 수 있다. 이를 통해 유연한 검색과 구조화된 검증을 결합한다.

계획(planning)은 이러한 통합으로부터 큰 이점을 얻을 수 있다. 신경망 모델은 행동의 실행 가능성(feasibility), 비용(cost), 가치(value), 예상 결과를 추정하고, 기호적 계획 시스템(symbolic planner)은 목표, 사전조건(precondition), 효과(effect), 제약조건을 표현할 수 있다. 따라서 후보 계획은 명시적인 작업 구조를 유지하면서 학습된 경험을 활용할 수 있다. 환경이 불확실한 경우에는 신경망 예측이 가능한 상태 전이를 추정하고 기호적 메커니즘이 계획의 논리적 구조를 유지할 수 있다.

월드 모델(world model)은 또 다른 중요한 통합 지점을 제공한다. 신경망 월드 모델(neural world model)은 고차원 관측으로부터 잠재 동역학(latent dynamics)을 학습할 수 있고, 기호적 월드 모델(symbolic world model)은 지속적으로 존재하는 객체, 관계, 사건, 인과 구조를 표현할 수 있다. 따라서 하이브리드 월드 모델(hybrid world model)은 연속적인 잠재 표현과 명시적인 관계 상태를 함께 유지하여 에이전트가 세부적인 동역학을 예측하면서 추상적인 결과에 대해 추론하도록 할 수 있다.

인과 추론(causal reasoning)은 상관관계만으로는 많은 지능적 의사결정을 수행하기에 충분하지 않기 때문에 특히 중요하다. 신경망은 통계적 규칙성과 잠재적인 의존관계를 발견할 수 있고, 기호적 인과 모델(symbolic causal model)은 개입(intervention), 메커니즘, 구조화된 관계를 표현할 수 있다. 이러한 능력을 결합하면 자연스럽게 어떤 일이 발생할지뿐 아니라 에이전트가 환경의 일부를 의도적으로 변경했을 때 어떤 일이 발생할지에 대해서도 추론할 수 있다.

불확실성(uncertainty)은 신경망과 기호 시스템의 경계를 넘어 계속 유지되어야 한다. 신경망 지각은 완벽하게 확실한 분류나 상태 추정을 생성하는 경우가 드물며, 기호적 추론이 불확실한 출력을 무조건적인 사실로 처리해서는 안 된다. 확률적 논리(probabilistic logic), 신뢰도 가중 사실(confidence-weighted fact), 대안 가설(alternative hypothesis), 신념 분포(belief distribution)를 이용하면 불확실성을 유지하면서도 이용 가능한 증거에 대해 구조화된 추론을 수행할 수 있다.

이는 로보틱스(robotics)와 체화 지능(embodied intelligence)에서 특히 중요하다. 로봇은 여러 개의 가능한 객체를 인식하고, 불확실한 위치를 추정하며, 이동 가능성(navigability)을 판단하고, 동시에 작업 제약조건을 추론해야 할 수 있다. 신경망 지각은 잡음이 존재하는 감각 입력을 처리하고, 기호적 표현은 목표, 공간 관계, 작업 규칙, 안전 조건을 설명한다. 새로운 관측이 들어올 때마다 아키텍처는 이러한 구조를 지속적으로 수정해야 한다.

따라서 뉴로심볼릭 에이전트(NeuroSymbolic agent)는 반복적인 지각-추론-행동 순환(perception-reasoning-action cycle)을 통해 작동할 수 있다. 신경망 지각은 관측을 후보 개체와 상태로 변환하고, 기호적 추론은 이를 지식 및 목표와 통합하며, 계획 시스템은 구조화된 행동을 선택하고, 제어 시스템은 이를 실행한다. 실행 결과의 관측은 다시 신경망 시스템으로 돌아오며, 예상 결과와 실제 결과 사이의 차이는 학습된 표현과 명시적 지식을 모두 갱신하는 데 사용될 수 있다.

언어(language)는 두 체계를 연결하는 또 다른 자연스러운 연결 지점을 제공한다. 대규모 언어 모델(Large Language Model)은 지시를 해석하고, 개체와 관계를 추출하고, 후보 계획을 생성하며, 자연어와 구조화된 표현 사이를 변환할 수 있다. 이후 기호적 시스템은 제약조건을 검증하고, 형식적인 절차를 실행하거나, 지속적인 지식을 유지할 수 있다. 언어 모델은 유연성을 제공하고, 구조화된 메커니즘은 신뢰성 높은 상태 관리가 필요한 작업에서 제약되지 않은 생성에 대한 의존도를 줄인다.

따라서 파운데이션 모델(foundation model)은 그 자체가 완전한 아키텍처라기보다 더 큰 뉴로심볼릭 아키텍처의 구성 요소가 될 수 있다. 멀티모달 파운데이션 모델(multimodal foundation model)은 광범위한 지각과 추론 능력을 제공하고, 외부 기억(external memory), 지식 그래프, 계획 시스템, 규칙 시스템, 검증 메커니즘(verification mechanism), 제어기는 지속적인 구조를 제공할 수 있다. 결과적으로 학습된 일반화 능력과 명시적인 아키텍처 조직을 결합한 시스템을 구성할 수 있다.

도구 사용(tool use) 역시 뉴로심볼릭 방식으로 표현할 수 있다. 신경망 모델은 자연어 문맥을 바탕으로 어떤 도구가 적절한지를 판단하고, 기호적 설명은 도구의 기능, 입력 요구사항, 사전조건, 예상 출력을 정의할 수 있다. 계획 메커니즘은 여러 도구의 연산을 구조화된 워크플로(workflow)로 구성하고 중간 결과가 이후 연산에 필요한 조건을 충족하는지를 검증할 수 있다.

메타인지(metacognition)는 신경망 처리와 기호적 처리 사이의 상호작용을 감시할 수 있다. 시스템은 신경망의 신뢰도가 기호적 사실로 확정하기에 너무 낮은 경우, 논리적 제약조건이 모델의 예측과 충돌하는 경우, 또는 높은 성공 가능성을 예측한 계획이 반복적으로 실패하는 경우를 탐지할 수 있다. 이러한 충돌은 추가 관측, 더 깊은 추론, 대안 가설, 모델 전환(model switching), 인간의 지원을 요청하는 신호로 활용될 수 있다.

뉴로심볼릭 아키텍처는 설명 가능성(explainability)을 개선할 수 있는 기회도 제공한다. 신경망의 내부 표현은 직접 해석하기 어려울 수 있지만, 기호적 구조는 어떤 개체, 관계, 규칙, 제약조건, 목표가 의사결정에 기여했는지를 보여줄 수 있다. 이것이 전체 시스템을 자동으로 투명하게 만드는 것은 아니지만, 디버깅(debugging), 검증(validation), 안전 분석에 활용할 수 있는 검사 가능한 중간 표현과 추론 경로(reasoning trace)를 제공할 수 있다.

효율성(efficiency) 역시 잠재적인 장점이다. 일부 지식을 압축된 규칙이나 재사용 가능한 기호적 절차로 표현할 수 있다면 신경망이 높은 비용의 추론을 반복하면서 모든 추론 단계를 수행할 필요가 없다. 반대로 신경망 모델이 강력한 후보 예측이나 휴리스틱(heuristic)을 제공하면 기호적 탐색의 범위를 줄일 수 있다. 따라서 각 패러다임은 상대방에게 비용이 많이 드는 계산 부담을 감소시킬 수 있다.

가장 큰 어려움은 단순히 두 시스템을 나란히 배치하는 것이 아니라 실제로 통합(integration)하는 데 있다. 표현은 서로 호환되어야 하고, 불확실성이 인터페이스를 정확하게 통과해야 하며, 학습이 필수적인 제약조건을 위반해서는 안 되고, 환경이 변화하면 기호적 구조도 적응해야 한다. 인터페이스가 제대로 설계되지 않으면 신경망 지각의 오류가 잘못된 사실로 기호적 추론에 전달되는 취약한 파이프라인(brittle pipeline)이 만들어질 수 있다.

따라서 현대 뉴로심볼릭 연구(NeuroSymbolic research)는 하나의 표준화된 해결책이 아니라 다양한 아키텍처 설계를 포함한다. 일부 시스템은 신경망 지각 이후 기호적 추론을 수행하고, 다른 시스템은 논리적 제약조건을 신경망 학습에 포함하며, 또 다른 시스템은 프로그램, 그래프, 관계 표현 또는 미분 가능 추론 메커니즘을 학습한다. 공통적인 원리는 학습된 통계적 지능(learned statistical intelligence)과 구조화된 추론(structured reasoning)을 상호 배타적인 대안으로 보지 않고 서로 협력하도록 만드는 것이다.

AGI 관점에서 이러한 결합이 매력적인 이유는 범용 지능(general intelligence)이 적응(adaptation)과 구조(structure)를 모두 필요로 하기 때문이다. 에이전트는 불완전한 경험으로부터 학습하고, 익숙하지 않은 패턴을 인식하고, 불확실한 조건에서 작동하면서도 목표, 관계, 제약조건, 인과 지식, 재사용 가능한 절차를 유지해야 한다. 신경망 계산은 유연한 학습을 제공하고, 기호 계산(symbolic computation)은 장기간의 추론 과정에서 명시적인 구조를 조작하는 메커니즘을 제공한다.

따라서 뉴로심볼릭 아키텍처의 보다 넓은 의미는 지능에 관한 두 가지 상호보완적인 관점을 통합하려는 시도에 있다. 지능은 경험으로부터 분산 표현을 학습함으로써 나타날 수 있지만, 동시에 지식을 조직하고, 관계를 추론하고, 익숙한 개념을 새로운 방식으로 조합하고, 제약조건을 준수하며, 구조화된 의사결정을 설명할 수 있는 능력이 필요하다. 이러한 능력들의 통합은 적응적이고 신뢰할 수 있으며 점차 범용화되는 지능형 에이전트(adaptive, reliable, and increasingly general intelligent agent)를 향한 유망한 아키텍처 방향을 제공한다.

##  

## 04.06. LLM based Agents

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

Large Language Model based agents use a language model as a central reasoning and decision component within a larger autonomous system. Instead of generating a single response to a prompt, the model participates in a repeated loop of observing a situation, interpreting goals, reasoning about alternatives, selecting actions, using tools, evaluating results, and continuing until a task is completed or another termination condition is reached.

The Large Language Model provides a flexible interface between natural language, knowledge, reasoning, and action. Because the model has learned broad statistical relationships from large-scale data, it can interpret diverse instructions and generate context-sensitive responses without requiring a separate handcrafted program for every task. However, the language model alone does not constitute a complete agent; memory, tools, planning, control, and environmental interaction must surround it.

An LLM-based agent typically begins with observations from a user, software environment, database, sensor system, or another agent. These observations are converted into a context that the language model can interpret. The model combines the current observation with instructions, goals, previous actions, retrieved knowledge, and system constraints to determine what information is relevant and what should happen next.

Goals provide persistent direction across multiple interactions. A conventional language-model request may end after one generated answer, whereas an agent can maintain an objective across many reasoning and action cycles. The goal may be decomposed into smaller subgoals, each requiring different information or tools. This allows the system to perform tasks whose solutions cannot reasonably be produced through a single inference step.

Planning transforms goals into possible sequences of actions. The model can identify dependencies, determine which information must be obtained first, generate intermediate objectives, and revise plans when assumptions prove incorrect. Planning may be performed explicitly through structured representations or implicitly through language-model reasoning, but reliable agents often benefit from separating plan generation, execution, monitoring, and revision.

Reasoning allows the agent to interpret ambiguous situations and choose among alternative actions. The LLM can combine information from the current context with retrieved knowledge and intermediate results to construct candidate solutions. Reasoning does not guarantee correctness, however, so agent architectures commonly combine generative reasoning with external verification, structured constraints, executable tools, or specialized models.

Tool use extends the agent beyond the information contained in the model\'s parameters. Search engines, databases, calculators, code execution environments, APIs, simulators, robotic controllers, and enterprise software can become external capabilities. The LLM determines when a tool is required, constructs an appropriate request, interprets the returned result, and incorporates that information into subsequent reasoning.

This creates an important separation between knowing and doing. The language model may understand that a particular operation is necessary without performing that operation internally. Instead, it can invoke a specialized tool designed for the task. Such modularity allows deterministic computation, current information retrieval, physical control, and domain-specific operations to complement the probabilistic generative capabilities of the model.

Memory provides continuity beyond the immediate context window. Short-term memory can preserve information relevant to the current task, while long-term memory can store previous experiences, user preferences, learned procedures, or domain knowledge. Retrieval mechanisms select relevant memories when needed, preventing the model from having to include the entire history of the agent in every inference.

Episodic memory can preserve particular interactions, decisions, outcomes, and failures. When a similar situation appears later, the agent can retrieve earlier episodes and use them as evidence for selecting an action. Semantic memory can preserve generalized facts and relationships, while procedural memory can represent reusable workflows, skills, or strategies developed through repeated task execution.

Retrieval-Augmented Generation can function as an important memory mechanism for LLM agents. Instead of relying exclusively on information encoded during model training, the agent retrieves relevant documents, records, knowledge fragments, or previous experiences and places them into the active context. The LLM can then reason using information that is more current, domain-specific, or task-specific than its parametric knowledge.

Reflection introduces a mechanism for examining previous reasoning or behavior. After producing a result, the agent may evaluate whether its assumptions were justified, whether tool outputs support its conclusion, or whether the task has actually been completed. When problems are detected, the agent can revise its reasoning, modify its plan, invoke another tool, or repeat part of the task with additional information.

Self-evaluation can be strengthened through external verification. Rather than asking the same language model to generate and judge everything, an architecture may use deterministic validators, separate critic models, symbolic constraints, tests, simulators, or human feedback. This reduces dependence on unconstrained self-assessment and creates checkpoints where important decisions can be validated before execution.

The agent loop can therefore be represented conceptually as observation, context construction, reasoning, planning, action, feedback, and state update. Each cycle changes the information available to the agent. The next decision is conditioned not only on the original request but also on what happened during previous actions. This recurrent structure transforms a language model from a response generator into a component of an interactive control process.

Uncertainty is critical within this loop. Language models can produce fluent outputs even when evidence is incomplete or incorrect, so linguistic confidence cannot be treated as reliable epistemic confidence. Agent systems need mechanisms for identifying missing information, conflicting evidence, unreliable tool results, unfamiliar situations, and actions whose consequences are difficult to reverse.

When uncertainty is high, the agent can gather additional evidence rather than immediately committing to an action. It may search another source, request clarification, inspect the environment, compare alternatives, invoke a specialized model, or escalate the decision to a human operator. This ability to recognize when additional information is needed is essential for moving from conversational fluency toward reliable autonomous behavior.

Structured state representations can improve reliability by separating persistent facts from temporary generated text. Goals, constraints, plans, completed actions, pending tasks, environmental states, permissions, and uncertainties can be stored explicitly. The LLM then operates over this structured state rather than attempting to reconstruct the entire situation from an unstructured conversation history during every reasoning cycle.

A world model can further extend the architecture by representing how an environment changes over time. The LLM may reason about semantic goals and high-level strategies, while a learned or structured world model predicts the consequences of candidate actions. The agent can compare possible futures before acting, enabling planning that depends not only on language knowledge but also on predicted environmental dynamics.

For embodied agents, this separation becomes particularly important. Low-level perception and motor control require continuous processing with strict timing constraints that language models are not naturally designed to satisfy. Vision networks, localization systems, motion planners, safety controllers, and real-time control loops can therefore operate independently, while the LLM manages higher-level task interpretation, reasoning, planning, and coordination.

An embodied LLM agent might receive structured descriptions from perception rather than every raw sensor value. It can reason that an object must be collected, determine which navigation or manipulation skill is required, and invoke the appropriate controller. Feedback from execution then reports whether the action succeeded, failed, or produced an unexpected condition requiring replanning.

Hierarchical control helps separate these different timescales. Fast reactive control can handle stabilization, collision avoidance, and immediate safety, while slower deliberative processes handle task planning and semantic reasoning. The LLM can occupy a higher layer of this hierarchy, issuing goals or selecting skills without directly controlling every actuator command. This improves both computational efficiency and operational safety.

Skill libraries provide reusable capabilities between high-level reasoning and low-level execution. A skill may represent navigation to a location, grasping an object, querying a database, generating a report, or operating a software service. The agent selects and parameterizes these skills according to the current goal, allowing complex behavior to emerge from combinations of previously implemented capabilities.

Learning can occur when successful experiences are converted into reusable skills or memories. If the agent repeatedly solves similar tasks through expensive reasoning, the resulting workflow can be stored and retrieved later. This resembles procedural learning: deliberate problem solving gradually becomes reusable competence. Failed experiences can likewise provide information about conditions under which particular strategies should not be applied.

Multi-agent architectures extend the concept by allowing several LLM-based agents to cooperate. Different agents may specialize in planning, research, coding, verification, simulation, or execution. They can exchange intermediate results and divide complex tasks according to their capabilities. However, adding agents does not automatically improve performance because communication overhead, duplicated reasoning, conflicting decisions, and error propagation must be controlled.

Coordination therefore requires explicit roles, shared state, communication protocols, task allocation, and mechanisms for resolving disagreement. A supervisory agent may distribute tasks and integrate results, or agents may negotiate responsibilities dynamically. In physical systems, coordination additionally requires temporal synchronization, resource management, spatial constraints, communication reliability, and shared representations of the environment.

Security becomes increasingly important as agents gain access to external tools. An LLM that can read information, execute software, communicate externally, or control machines requires carefully defined permissions. Tool interfaces should restrict available operations, validate parameters, isolate sensitive resources, record actions, and require additional authorization for operations with significant or irreversible consequences.

Human oversight remains important for decisions that exceed the agent\'s authority or confidence. Human-in-the-loop mechanisms can define checkpoints where approval is required, while human-on-the-loop supervision can monitor largely autonomous operation and intervene when necessary. The appropriate degree of autonomy depends on task risk, reversibility, environmental uncertainty, and the reliability of available safety mechanisms.

Metacognition can coordinate these mechanisms by monitoring progress, uncertainty, computational cost, failures, and remaining objectives. The agent can ask whether the current strategy is working, whether more information is necessary, whether another tool would be more appropriate, or whether continuing autonomous execution remains safe. This creates a control layer concerned not only with solving the task but also with managing the reasoning process itself.

Resource-aware operation is especially important when large models are computationally expensive. Routine situations may be handled using cached results, smaller models, specialized policies, or previously learned skills, while difficult situations invoke stronger reasoning models. An agent architecture can therefore dynamically allocate computational resources according to novelty, uncertainty, risk, and task complexity.

This principle connects LLM agents with predictive processing and cognitive architectures. When observations match expectations and familiar procedures remain successful, expensive deliberation may be unnecessary. Unexpected events, conflicting evidence, failed actions, or large prediction errors can trigger deeper reasoning. The LLM becomes one component within an adaptive architecture that increases cognitive effort when circumstances demand it.

LLM-based agents also connect naturally with NeuroSymbolic architectures. The language model can interpret flexible natural-language instructions and generate candidate plans, while symbolic components maintain rules, constraints, permissions, knowledge graphs, and formal task states. Neural flexibility can therefore be combined with structured verification, reducing the need to trust unrestricted language generation for every decision.

From an AGI perspective, the significance of LLM-based agents lies less in conversational ability than in the transition from generation to persistent agency. Memory creates continuity, goals create direction, planning organizes future behavior, tools provide external capabilities, world models support prediction, reflection supports correction, and action connects internal reasoning to consequential changes in an environment.

A mature LLM-based agent should therefore not be understood simply as an LLM surrounded by many tools. It is an integrated cognitive architecture in which the language model contributes semantic reasoning and flexible generalization while memory, planning, perception, verification, world modeling, control, safety, and learning provide complementary functions. General intelligence increasingly emerges from how these mechanisms cooperate across time rather than from any single model operating in isolation.

대규모 언어 모델 기반 에이전트(Large Language Model based agents)는 더 큰 자율 시스템(autonomous system) 안에서 언어 모델(language model)을 핵심 추론 및 의사결정 구성 요소로 사용한다. 단일 프롬프트(prompt)에 한 번의 응답을 생성하는 대신, 모델은 상황을 관측하고, 목표를 해석하고, 대안을 추론하고, 행동을 선택하고, 도구를 사용하고, 결과를 평가한 뒤 작업이 완료되거나 다른 종료 조건이 충족될 때까지 이 과정을 반복하는 순환에 참여한다.

대규모 언어 모델(Large Language Model)은 자연어, 지식, 추론, 행동 사이를 연결하는 유연한 인터페이스(interface)를 제공한다. 모델은 대규모 데이터로부터 광범위한 통계적 관계를 학습했기 때문에 모든 작업에 별도의 수작업 프로그램을 만들지 않고도 다양한 지시를 해석하고 문맥에 맞는 응답을 생성할 수 있다. 그러나 언어 모델만으로 완전한 에이전트가 구성되는 것은 아니며, 기억(memory), 도구(tool), 계획(planning), 제어(control), 환경 상호작용(environmental interaction)이 이를 둘러싸고 있어야 한다.

LLM 기반 에이전트(LLM-based agent)는 일반적으로 사용자, 소프트웨어 환경, 데이터베이스, 센서 시스템 또는 다른 에이전트로부터 관측(observation)을 받는 것으로 시작한다. 이러한 관측은 언어 모델이 해석할 수 있는 문맥(context)으로 변환된다. 모델은 현재 관측을 지시사항, 목표, 이전 행동, 검색된 지식, 시스템 제약조건과 결합하여 어떤 정보가 관련성이 있으며 다음에 무엇을 수행해야 하는지를 결정한다.

목표(goal)는 여러 상호작용에 걸쳐 지속적인 방향성을 제공한다. 일반적인 언어 모델 요청은 하나의 답변을 생성한 뒤 종료될 수 있지만, 에이전트는 여러 추론 및 행동 순환에 걸쳐 하나의 목적(objective)을 유지할 수 있다. 목표는 더 작은 하위 목표(subgoal)로 분해될 수 있으며, 각각의 하위 목표에는 서로 다른 정보나 도구가 필요할 수 있다. 이를 통해 단일 추론 단계만으로는 현실적으로 해결하기 어려운 작업을 수행할 수 있다.

계획(planning)은 목표를 가능한 행동 순서(sequence of actions)로 변환한다. 모델은 의존관계(dependency)를 식별하고, 어떤 정보를 먼저 획득해야 하는지를 결정하며, 중간 목표를 생성하고, 기존 가정이 잘못된 것으로 밝혀지면 계획을 수정할 수 있다. 계획은 구조화된 표현을 통해 명시적으로 수행될 수도 있고 언어 모델의 추론을 통해 암묵적으로 수행될 수도 있지만, 신뢰성 높은 에이전트는 계획 생성, 실행, 모니터링, 수정 과정을 분리함으로써 이점을 얻는 경우가 많다.

추론(reasoning)은 에이전트가 모호한 상황을 해석하고 여러 대안 행동 가운데 하나를 선택할 수 있도록 한다. LLM은 현재 문맥의 정보를 검색된 지식 및 중간 결과와 결합하여 후보 해결책(candidate solution)을 구성할 수 있다. 그러나 추론이 항상 정확성을 보장하는 것은 아니므로 에이전트 아키텍처(agent architecture)는 생성적 추론을 외부 검증(external verification), 구조화된 제약조건, 실행 가능한 도구 또는 전문화된 모델과 결합하는 경우가 많다.

도구 사용(tool use)은 에이전트의 능력을 모델 매개변수(parameter)에 포함된 정보 이상으로 확장한다. 검색 엔진, 데이터베이스, 계산기, 코드 실행 환경, API, 시뮬레이터(simulator), 로봇 제어기(robotic controller), 기업용 소프트웨어 등이 외부 능력(external capability)이 될 수 있다. LLM은 도구가 필요한 시점을 결정하고, 적절한 요청을 구성하고, 반환된 결과를 해석한 뒤 해당 정보를 이후의 추론에 통합한다.

이는 앎(knowing)과 실행(doing) 사이에 중요한 분리를 만든다. 언어 모델은 특정 연산이 필요하다는 사실을 이해하면서도 그 연산을 내부적으로 직접 수행하지 않을 수 있다. 대신 해당 작업을 위해 설계된 전문 도구를 호출할 수 있다. 이러한 모듈성(modularity)은 결정론적 계산, 최신 정보 검색, 물리적 제어, 도메인 특화 연산이 모델의 확률적 생성 능력(probabilistic generative capability)을 보완할 수 있도록 한다.

기억(memory)은 즉각적인 문맥 창(context window)을 넘어 연속성을 제공한다. 단기 기억(short-term memory)은 현재 작업에 관련된 정보를 유지할 수 있고, 장기 기억(long-term memory)은 이전 경험, 사용자 선호, 학습된 절차 또는 도메인 지식을 저장할 수 있다. 검색 메커니즘(retrieval mechanism)은 필요한 순간에 관련 기억을 선택하여 모든 추론 과정에서 에이전트의 전체 이력을 문맥에 포함할 필요가 없도록 한다.

일화 기억(episodic memory)은 특정 상호작용, 의사결정, 결과, 실패를 보존할 수 있다. 이후 유사한 상황이 나타나면 에이전트는 이전 일화를 검색하여 행동을 선택하기 위한 증거로 사용할 수 있다. 의미 기억(semantic memory)은 일반화된 사실과 관계를 보존할 수 있으며, 절차적 기억(procedural memory)은 반복적인 작업 수행을 통해 개발된 재사용 가능한 워크플로(workflow), 기술(skill), 전략(strategy)을 표현할 수 있다.

검색 증강 생성(Retrieval-Augmented Generation)은 LLM 에이전트의 중요한 기억 메커니즘으로 기능할 수 있다. 에이전트는 모델 학습 과정에서 매개변수에 인코딩된 정보에만 의존하지 않고 관련 문서, 기록, 지식 조각 또는 이전 경험을 검색하여 활성 문맥(active context)에 배치한다. 이후 LLM은 자신의 매개변수적 지식(parametric knowledge)보다 최신이거나 도메인 및 작업에 특화된 정보를 활용하여 추론할 수 있다.

성찰(reflection)은 이전의 추론이나 행동을 검토하는 메커니즘을 제공한다. 결과를 생성한 이후 에이전트는 자신의 가정이 정당했는지, 도구의 출력이 결론을 뒷받침하는지, 또는 실제로 작업이 완료되었는지를 평가할 수 있다. 문제가 발견되면 추론을 수정하고, 계획을 변경하고, 다른 도구를 호출하거나, 추가적인 정보를 이용하여 작업의 일부를 다시 수행할 수 있다.

자기 평가(self-evaluation)는 외부 검증을 통해 더욱 강화될 수 있다. 동일한 언어 모델에게 모든 것을 생성하고 평가하도록 하는 대신, 아키텍처는 결정론적 검증기(deterministic validator), 별도의 비평 모델(critic model), 기호적 제약조건(symbolic constraint), 테스트, 시뮬레이터 또는 인간 피드백(human feedback)을 사용할 수 있다. 이를 통해 제약 없는 자기 평가에 대한 의존성을 낮추고 중요한 의사결정을 실행 전에 검증할 수 있는 확인 지점(checkpoint)을 만든다.

따라서 에이전트 순환(agent loop)은 개념적으로 관측, 문맥 구성(context construction), 추론, 계획, 행동, 피드백(feedback), 상태 갱신(state update)으로 표현할 수 있다. 각각의 순환은 에이전트가 사용할 수 있는 정보를 변화시킨다. 다음 의사결정은 최초의 요청뿐 아니라 이전 행동에서 실제로 어떤 일이 발생했는지를 기반으로 이루어진다. 이러한 반복 구조는 언어 모델을 단순한 응답 생성기에서 상호작용형 제어 과정(interactive control process)의 구성 요소로 변화시킨다.

불확실성(uncertainty)은 이러한 순환에서 매우 중요하다. 언어 모델은 증거가 불완전하거나 잘못된 경우에도 유창한 출력을 생성할 수 있으므로 언어적으로 표현되는 확신을 신뢰할 수 있는 인식론적 신뢰도(epistemic confidence)로 간주해서는 안 된다. 에이전트 시스템은 누락된 정보, 서로 충돌하는 증거, 신뢰할 수 없는 도구 결과, 익숙하지 않은 상황, 되돌리기 어려운 결과를 발생시키는 행동을 식별하는 메커니즘을 필요로 한다.

불확실성이 높으면 에이전트는 즉시 행동을 확정하는 대신 추가적인 증거를 수집할 수 있다. 다른 정보원을 검색하거나, 명확한 설명을 요청하거나, 환경을 추가로 관측하거나, 대안을 비교하거나, 전문화된 모델을 호출하거나, 의사결정을 인간 운영자에게 에스컬레이션(escalation)할 수 있다. 추가 정보가 필요한 시점을 인식하는 능력은 대화의 유창성을 넘어 신뢰성 높은 자율 행동으로 발전하기 위해 필수적이다.

구조화된 상태 표현(structured state representation)은 지속적인 사실과 일시적으로 생성된 텍스트를 분리하여 신뢰성을 향상시킬 수 있다. 목표, 제약조건, 계획, 완료된 행동, 대기 중인 작업, 환경 상태, 권한(permission), 불확실성을 명시적으로 저장할 수 있다. 그러면 LLM은 매번 추론할 때 구조화되지 않은 전체 대화 기록으로부터 상황 전체를 다시 구성하는 대신 이러한 구조화된 상태를 기반으로 작동할 수 있다.

월드 모델(world model)은 시간이 지나면서 환경이 어떻게 변화하는지를 표현하여 아키텍처를 더욱 확장할 수 있다. LLM은 의미론적 목표와 상위 수준 전략을 추론하고, 학습되거나 구조화된 월드 모델은 후보 행동의 결과를 예측할 수 있다. 에이전트는 행동하기 전에 가능한 미래를 비교함으로써 언어적 지식뿐 아니라 예측된 환경 동역학(environmental dynamics)에 기반한 계획을 수행할 수 있다.

체화형 에이전트(embodied agent)에서는 이러한 분리가 특히 중요하다. 저수준 지각과 운동 제어(motor control)는 엄격한 시간 제약 아래 지속적으로 처리되어야 하며, 언어 모델은 본질적으로 이러한 작업을 위해 설계된 것은 아니다. 따라서 비전 네트워크, 위치추정 시스템(localization system), 모션 플래너(motion planner), 안전 제어기(safety controller), 실시간 제어 루프(real-time control loop)는 독립적으로 작동하고, LLM은 상위 수준의 작업 해석, 추론, 계획, 조정을 담당할 수 있다.

체화형 LLM 에이전트는 모든 원시 센서값(raw sensor value)을 직접 입력받는 대신 지각 시스템에서 생성된 구조화된 설명을 받을 수 있다. 에이전트는 특정 객체를 수집해야 한다고 판단하고, 어떤 내비게이션 또는 조작 기술(manipulation skill)이 필요한지를 결정한 뒤 적절한 제어기를 호출할 수 있다. 실행 피드백은 행동의 성공, 실패 또는 예상하지 못한 조건의 발생 여부를 알려주고 필요하면 재계획(replanning)을 유발한다.

계층적 제어(hierarchical control)는 서로 다른 시간 척도를 분리하는 데 도움을 준다. 빠른 반응형 제어(reactive control)는 안정화, 충돌 회피, 즉각적인 안전을 담당하고, 느린 숙고적 처리(deliberative process)는 작업 계획과 의미론적 추론을 담당할 수 있다. LLM은 이 계층의 상위 수준에 위치하여 모든 액추에이터 명령을 직접 제어하지 않고 목표를 전달하거나 기술을 선택할 수 있다. 이는 계산 효율성과 운용 안전성을 모두 향상시킨다.

기술 라이브러리(skill library)는 상위 수준 추론과 저수준 실행 사이에서 재사용 가능한 능력을 제공한다. 하나의 기술은 특정 위치로 이동하기, 객체 잡기, 데이터베이스 질의, 보고서 생성 또는 소프트웨어 서비스 운영 등을 나타낼 수 있다. 에이전트는 현재 목표에 따라 이러한 기술을 선택하고 매개변수화(parameterization)하여 이미 구현된 능력들을 조합함으로써 복잡한 행동을 생성할 수 있다.

성공적인 경험이 재사용 가능한 기술이나 기억으로 변환될 때 학습(learning)이 이루어질 수 있다. 에이전트가 비용이 높은 추론을 통해 유사한 작업을 반복적으로 해결한다면 그 결과의 워크플로를 저장하고 이후 다시 검색할 수 있다. 이는 절차적 학습(procedural learning)과 유사하며, 숙고적 문제 해결이 점차 재사용 가능한 능력으로 변화한다. 실패한 경험 역시 특정 전략을 적용해서는 안 되는 조건에 관한 정보를 제공할 수 있다.

멀티 에이전트 아키텍처(multi-agent architecture)는 여러 LLM 기반 에이전트가 협력하도록 개념을 확장한다. 서로 다른 에이전트가 계획, 조사, 코딩, 검증, 시뮬레이션, 실행 등에 특화될 수 있다. 에이전트들은 중간 결과를 교환하고 자신의 능력에 따라 복잡한 작업을 분담할 수 있다. 그러나 에이전트 수를 늘리는 것이 자동으로 성능을 향상시키는 것은 아니며, 통신 비용, 중복 추론, 상충하는 의사결정, 오류 전파(error propagation)를 제어해야 한다.

따라서 조정(coordination)을 위해서는 명시적인 역할, 공유 상태(shared state), 통신 프로토콜(communication protocol), 작업 할당(task allocation), 의견 불일치를 해결하는 메커니즘이 필요하다. 감독 에이전트(supervisory agent)가 작업을 분배하고 결과를 통합하거나, 여러 에이전트가 동적으로 역할을 협상할 수 있다. 물리적 시스템에서는 여기에 시간 동기화(temporal synchronization), 자원 관리, 공간적 제약조건, 통신 신뢰성, 공유된 환경 표현도 필요하다.

에이전트가 외부 도구에 접근할수록 보안(security)은 더욱 중요해진다. 정보를 읽고, 소프트웨어를 실행하고, 외부와 통신하거나 기계를 제어할 수 있는 LLM에는 명확하게 정의된 권한이 필요하다. 도구 인터페이스는 사용 가능한 연산을 제한하고, 매개변수를 검증하며, 민감한 자원을 격리하고, 행동을 기록하며, 중대한 결과를 초래하거나 되돌리기 어려운 연산에는 추가적인 승인을 요구해야 한다.

에이전트의 권한이나 신뢰도를 넘어서는 의사결정에는 인간 감독(human oversight)이 중요하다. 인간 참여형(Human-in-the-loop) 메커니즘은 승인이 필요한 확인 지점을 정의할 수 있으며, 인간 감독형(Human-on-the-loop) 방식은 대부분 자율적으로 이루어지는 작업을 모니터링하고 필요한 경우 개입할 수 있다. 적절한 자율성 수준은 작업의 위험도, 가역성(reversibility), 환경의 불확실성, 사용 가능한 안전 메커니즘의 신뢰성에 따라 달라진다.

메타인지(metacognition)는 진행 상황, 불확실성, 계산 비용, 실패, 남아 있는 목표를 모니터링하여 이러한 메커니즘을 조정할 수 있다. 에이전트는 현재 전략이 제대로 작동하는지, 추가 정보가 필요한지, 다른 도구가 더 적절한지, 자율 실행을 계속하는 것이 안전한지를 평가할 수 있다. 이를 통해 단순히 작업을 해결하는 것뿐 아니라 추론 과정 자체를 관리하는 제어 계층(control layer)이 형성된다.

대규모 모델의 계산 비용이 높은 경우에는 자원 인식형 운용(resource-aware operation)이 특히 중요하다. 일상적인 상황은 캐시된 결과(cached result), 소형 모델, 전문화된 정책(policy), 이전에 학습된 기술을 이용하여 처리하고, 어려운 상황에서만 더 강력한 추론 모델을 호출할 수 있다. 따라서 에이전트 아키텍처는 새로움(novelty), 불확실성, 위험, 작업 복잡도에 따라 계산 자원을 동적으로 할당할 수 있다.

이러한 원리는 LLM 에이전트를 예측 처리(predictive processing) 및 인지 아키텍처(cognitive architecture)와 연결한다. 관측이 예상과 일치하고 익숙한 절차가 계속 성공한다면 비용이 높은 숙고 과정이 필요하지 않을 수 있다. 예상하지 못한 사건, 상충하는 증거, 실패한 행동 또는 큰 예측 오차(prediction error)가 발생하면 더 깊은 추론을 활성화할 수 있다. 따라서 LLM은 상황에 따라 인지적 계산량을 증가시키는 적응형 아키텍처(adaptive architecture)의 하나의 구성 요소가 된다.

LLM 기반 에이전트는 뉴로심볼릭 아키텍처(NeuroSymbolic architecture)와도 자연스럽게 연결된다. 언어 모델은 유연한 자연어 지시를 해석하고 후보 계획을 생성하며, 기호적 구성 요소는 규칙, 제약조건, 권한, 지식 그래프(knowledge graph), 형식적인 작업 상태를 유지할 수 있다. 이를 통해 신경망의 유연성과 구조화된 검증(structured verification)을 결합하여 모든 의사결정에서 제약 없는 언어 생성에 의존할 필요성을 줄일 수 있다.

AGI 관점에서 LLM 기반 에이전트의 중요성은 대화 능력 자체보다 생성(generation)에서 지속적 에이전시(persistent agency)로의 전환에 있다. 기억은 연속성을 만들고, 목표는 방향성을 제공하며, 계획은 미래 행동을 조직하고, 도구는 외부 능력을 제공하며, 월드 모델은 예측을 지원하고, 성찰은 오류 수정을 지원하며, 행동은 내부 추론을 환경의 실제 변화와 연결한다.

따라서 성숙한 LLM 기반 에이전트는 단순히 많은 도구로 둘러싸인 LLM으로 이해해서는 안 된다. 이는 언어 모델이 의미론적 추론(semantic reasoning)과 유연한 일반화(flexible generalization)를 제공하고, 기억, 계획, 지각, 검증, 월드 모델링(world modeling), 제어, 안전, 학습이 상호보완적인 기능을 제공하는 통합 인지 아키텍처(integrated cognitive architecture)이다. 범용 지능은 점차 하나의 모델이 고립된 상태로 작동하는 것보다 이러한 메커니즘들이 시간에 걸쳐 어떻게 협력하는가에서 나타난다.

##  

## 04.07. MultiAgent Systems

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

![](images/image10.png){width="7.268055555555556in" height="7.268055555555556in"}

Multi-Agent Systems are computational architectures in which multiple autonomous agents interact within a shared environment to pursue individual, cooperative, or partially overlapping goals. Instead of concentrating perception, reasoning, planning, and action within one centralized intelligence, capabilities are distributed across several agents. System-level intelligence can therefore emerge from communication, coordination, specialization, negotiation, and collective adaptation among interacting entities.

An agent in a multi-agent system maintains some degree of autonomy over its observations, internal state, decisions, and actions. Agents may be software processes, AI models, robots, vehicles, sensors, digital services, or combinations of these forms. Each agent typically observes only part of the environment and possesses limited knowledge, resources, or capabilities, making cooperation valuable when problems exceed what any individual agent can solve efficiently.

The environment provides the shared context in which agents operate. It may be a physical space such as a warehouse, road network, factory, battlefield, or city, or a digital environment such as a simulation, network, market, or information system. Actions performed by one agent can modify environmental states observed by others, creating indirect interaction even when agents do not communicate explicitly.

Communication provides a direct mechanism for exchanging information between agents. Messages may contain observations, beliefs, goals, intentions, plans, requests, warnings, task assignments, or confidence estimates. Effective communication requires more than transferring raw data because bandwidth, latency, reliability, security, and computational cost may constrain information exchange. Agents must therefore determine what information is important enough to communicate and when communication is necessary.

Coordination organizes the actions of multiple agents so that their behaviors do not interfere unnecessarily and can contribute to shared objectives. Agents may coordinate spatial movement, resource usage, task execution, sensing, manipulation, or information gathering. Without coordination, individually reasonable actions can produce congestion, duplication, conflict, unsafe interactions, or inefficient use of shared resources.

Cooperation occurs when agents actively contribute toward a common objective. Different agents can provide complementary capabilities, allowing the group to divide a complex task into smaller components. One agent may specialize in perception, another in planning, another in verification, and another in execution. In robotic systems, different physical agents may instead specialize according to mobility, payload, sensing capability, endurance, or manipulation ability.

Task allocation determines which agent should perform which part of a collective objective. Allocation can consider capability, location, workload, energy, expected completion time, risk, communication quality, and resource availability. Centralized assignment can provide globally informed decisions, while decentralized allocation allows agents to negotiate or independently select tasks based on local information and changing conditions.

Centralized multi-agent architectures use a coordinator or supervisory component to maintain global information and distribute tasks. This can simplify planning and conflict resolution because one component has a broader view of system state. However, the coordinator can become a computational bottleneck, communication dependency, or single point of failure, particularly when the number of agents increases or communication becomes unreliable.

Decentralized architectures distribute decision authority among agents. Each agent reasons from local observations and exchanged information while adapting its behavior to other agents. Such systems can provide greater robustness and scalability because operation does not depend entirely on a central controller. Their difficulty lies in achieving coherent global behavior when no individual agent possesses complete information about the entire system.

Hybrid architectures combine centralized and decentralized mechanisms. Strategic goals, policies, or large-scale task allocation may be managed centrally, while local navigation, collision avoidance, immediate coordination, and failure recovery are handled autonomously by individual agents. This hierarchy can preserve global direction while allowing fast responses to local events without continuously consulting a central authority.

Shared state is important when agents must maintain a consistent understanding of the environment. This state may include maps, object locations, task status, resource availability, detected hazards, agent positions, or shared goals. Maintaining perfect consistency is often impossible in distributed environments, so systems must tolerate delayed, incomplete, or conflicting information while determining which observations are sufficiently recent and trustworthy.

Distributed perception allows several agents to combine observations that would be incomplete individually. Multiple robots can observe an environment from different viewpoints, extend sensing coverage, reduce occlusion, and provide redundancy. Sensor fusion across agents can improve environmental understanding, but it requires spatial alignment, temporal synchronization, uncertainty management, data association, and efficient communication between distributed sensing platforms.

Distributed mapping and localization are important examples in mobile robotics. Individual agents can build local maps while exchanging selected landmarks, features, poses, or map segments with others. The collective system can gradually construct a larger shared representation. Challenges arise from accumulated localization error, inconsistent coordinate frames, duplicate landmarks, communication delays, and incorrect loop closures between observations made by different agents.

Planning in a multi-agent system must consider not only environmental dynamics but also the expected behavior of other agents. A path that is optimal for one robot may interfere with another robot\'s route, while several agents may compete for the same resource. Multi-agent planning therefore involves joint constraints, temporal dependencies, collision avoidance, resource conflicts, and predictions about how other agents are likely to behave.

Negotiation provides a mechanism for resolving situations in which several agents have competing preferences or resource requirements. Agents may exchange proposals, bids, priorities, or alternative plans until an acceptable allocation is reached. Auction-based mechanisms, contract-based approaches, consensus algorithms, and distributed optimization can provide structured methods for coordinating decisions without requiring a single agent to dictate every action.

Consensus is required when multiple agents need to agree on a common value, state, decision, or objective despite distributed information. Agents repeatedly exchange local estimates and adjust them according to information received from neighbors. Consensus mechanisms are useful for formation control, distributed estimation, synchronized decisions, shared beliefs, and cooperative planning, although their performance depends strongly on communication topology and network reliability.

Emergent behavior is a defining property of many Multi-Agent Systems. Complex global patterns can arise from relatively simple local interaction rules without being explicitly programmed at the system level. Swarm formation, collective exploration, traffic organization, distributed coverage, and cooperative transport illustrate how local decisions can produce coordinated group behavior. Emergence can increase scalability but can also make system-level behavior difficult to predict or verify.

Multi-agent reinforcement learning extends reinforcement learning to environments containing multiple learning agents. Each agent learns policies from interaction while the behavior of other agents becomes part of its effective environment. This creates a non-stationary learning problem because the environment changes as other agents update their own policies. Cooperative rewards, competitive rewards, or mixed objectives can produce fundamentally different learning dynamics.

Centralized Training with Decentralized Execution provides one strategy for addressing this challenge. During training, agents may use global information, shared observations, or the states and actions of other agents to learn coordinated behavior. During deployment, each agent executes its policy using only locally available information. This approach enables richer coordination during learning while preserving decentralized operation when communication or centralized computation is unavailable.

Credit assignment becomes difficult when many agents contribute to a shared outcome. If a team succeeds or fails, the learning system must determine how much each agent\'s behavior contributed to the result. Poor credit assignment can encourage passive behavior or unstable cooperation. Value decomposition, counterfactual evaluation, difference rewards, and agent-specific feedback provide possible mechanisms for identifying individual contributions to collective performance.

Communication itself can be learned. Instead of relying entirely on manually designed message formats, agents can learn what information to transmit, which recipients require it, and when communication is valuable. Learned communication can reduce bandwidth and discover task-specific protocols, but the resulting representations may be difficult for humans to interpret and must remain robust to packet loss, changing team composition, and unfamiliar situations.

LLM-based Multi-Agent Systems introduce language models as autonomous or semi-autonomous participants. Different LLM agents can assume roles such as planner, researcher, critic, programmer, verifier, or coordinator. Natural language provides a flexible communication medium, allowing agents to exchange reasoning results and delegate tasks. However, repeated language-model communication can increase computational cost and propagate unsupported assumptions between agents.

Role specialization can improve multi-agent performance when responsibilities are clearly separated. A planning agent can decompose objectives, specialist agents can solve individual components, and a verification agent can examine results before execution. Specialization reduces the requirement for every agent to perform every type of reasoning, but excessive fragmentation can create communication overhead and make responsibility for errors difficult to identify.

Shared memory can provide continuity across cooperating agents. Instead of repeatedly transmitting complete histories, agents can write relevant observations, decisions, plans, and results into a common memory system. Other agents retrieve information according to their tasks. Shared memory must nevertheless manage provenance, permissions, conflicting updates, stale information, and uncertainty so that incorrect information does not silently become accepted collective knowledge.

World models can support coordinated prediction by representing how the environment and other agents may evolve. Each agent can maintain a local world model, while selected states or predictions are exchanged with teammates. Alternatively, a shared model can provide common environmental dynamics. Predicting other agents\' intentions is particularly important because their actions can significantly change the future states available to the entire group.

Multi-robot systems bring additional physical constraints that do not appear in purely digital agent systems. Robots have finite battery capacity, limited sensing range, mechanical constraints, communication dead zones, localization uncertainty, and collision risks. Coordination must therefore operate under real-time physical constraints while preserving safe local autonomy when communication with other robots or central infrastructure is temporarily unavailable.

Resilience is one of the major motivations for distributed intelligence. If one agent fails, remaining agents may redistribute its tasks and continue operating. Communication networks can reroute information, and redundant sensing can compensate for lost observations. Achieving this robustness requires explicit failure detection, degraded-operation modes, dynamic task reallocation, and architectures that avoid unnecessary dependence on individual agents.

Safety becomes more complicated as autonomous agents interact. A safe action for one agent considered independently may create unsafe conditions when combined with another agent\'s action. Multi-agent safety therefore requires local safety constraints together with mechanisms for shared collision avoidance, resource exclusion, priority management, emergency signaling, and coordinated stopping. Critical protections should remain operational even when higher-level communication fails.

Trust and security are equally important because agents act on information received from others. A malfunctioning, compromised, or inaccurate agent can distribute incorrect state estimates or harmful instructions throughout the system. Authentication, access control, message validation, anomaly detection, provenance tracking, and confidence estimation help prevent distributed communication from becoming a channel through which errors propagate across the entire architecture.

Scalability depends on controlling interaction complexity. If every agent continuously communicates with every other agent, communication and computation can grow rapidly as the population increases. Hierarchical organization, local neighborhoods, event-triggered communication, compressed representations, selective information sharing, and dynamic team formation can reduce this burden while preserving the information required for effective coordination.

Hierarchical Multi-Agent Systems can organize agents into teams, clusters, or command levels. Local agents solve immediate problems, team coordinators integrate regional information, and higher-level components manage strategic objectives. Such architectures reduce the need for global communication at every decision step and provide a practical way to connect fast local autonomy with slower system-wide planning.

Multi-Agent Systems also provide a natural architecture for combining heterogeneous intelligence. One agent may use symbolic planning, another may use reinforcement learning, another may use an LLM, and another may implement deterministic control. Agents do not need identical internal architectures as long as they can exchange meaningful state and coordinate actions through compatible protocols. The collective system can therefore combine specialized forms of intelligence.

Metacognition can operate at both individual and collective levels. Individual agents can monitor their own confidence, progress, resource state, and failures, while supervisory or distributed mechanisms evaluate team-level performance. The system can detect duplicated effort, communication breakdown, conflicting plans, or agents operating outside their competence and respond through replanning, role reassignment, additional verification, or human intervention.

From an AGI perspective, Multi-Agent Systems demonstrate that general intelligence does not necessarily need to reside inside a single monolithic model. Complex capabilities can emerge from communities of specialized agents that share knowledge, divide tasks, reason collectively, and adapt their organization. This resembles many biological and human systems in which distributed individuals create capabilities that exceed those of any isolated participant.

The broader architectural significance of Multi-Agent Systems lies in transforming intelligence from an individual computation problem into a coordination problem. Perception, memory, reasoning, planning, learning, and action can be distributed across interacting entities, while communication and shared representations connect them into a coherent system. Effective collective intelligence therefore depends not only on how capable each agent is, but on how reliably the agents cooperate, coordinate, learn, and recover together.

멀티 에이전트 시스템(Multi-Agent Systems)은 여러 자율 에이전트(autonomous agent)가 공유 환경(shared environment)에서 상호작용하면서 개별적 목표, 협력적 목표 또는 부분적으로 중첩되는 목표를 추구하는 계산 아키텍처(computational architecture)이다. 지각(perception), 추론(reasoning), 계획(planning), 행동(action)을 하나의 중앙화된 지능에 집중시키는 대신 여러 에이전트에 능력을 분산한다. 따라서 시스템 수준의 지능은 상호작용하는 개체들 사이의 통신, 조정, 전문화, 협상, 집단적 적응을 통해 나타날 수 있다.

멀티 에이전트 시스템에서 하나의 에이전트(agent)는 자신의 관측, 내부 상태, 의사결정, 행동에 대해 일정 수준의 자율성(autonomy)을 유지한다. 에이전트는 소프트웨어 프로세스, AI 모델, 로봇, 차량, 센서, 디지털 서비스 또는 이러한 형태들의 조합일 수 있다. 각각의 에이전트는 일반적으로 환경의 일부만 관측하며 제한된 지식, 자원 또는 능력을 가지므로, 하나의 에이전트가 효율적으로 해결하기 어려운 문제에서는 협력이 중요한 가치를 갖는다.

환경(environment)은 에이전트들이 작동하는 공유 문맥(shared context)을 제공한다. 환경은 창고, 도로망, 공장, 전장, 도시와 같은 물리적 공간일 수도 있고, 시뮬레이션, 네트워크, 시장, 정보 시스템과 같은 디지털 환경일 수도 있다. 하나의 에이전트가 수행한 행동은 다른 에이전트가 관측하는 환경 상태를 변화시킬 수 있으므로, 에이전트들이 명시적으로 통신하지 않더라도 환경을 통해 간접적인 상호작용이 발생할 수 있다.

통신(communication)은 에이전트 사이에서 정보를 직접 교환하기 위한 메커니즘을 제공한다. 메시지에는 관측, 신념(belief), 목표, 의도(intention), 계획, 요청, 경고, 작업 할당 또는 신뢰도 추정(confidence estimate)이 포함될 수 있다. 효과적인 통신은 단순한 원시 데이터 전송 이상의 문제이며, 대역폭, 지연시간(latency), 신뢰성, 보안, 계산 비용 등이 정보 교환을 제한할 수 있다. 따라서 에이전트는 어떤 정보가 통신할 만큼 중요한지와 언제 통신이 필요한지를 판단해야 한다.

조정(coordination)은 여러 에이전트의 행동이 불필요하게 서로 방해하지 않으면서 공유 목표에 기여하도록 행동을 조직한다. 에이전트들은 공간 이동, 자원 사용, 작업 실행, 감지, 조작(manipulation), 정보 수집을 조정할 수 있다. 조정이 없다면 개별적으로 합리적인 행동이라도 혼잡, 중복 작업, 충돌, 안전하지 않은 상호작용 또는 공유 자원의 비효율적인 사용을 발생시킬 수 있다.

협력(cooperation)은 여러 에이전트가 공통 목표를 달성하기 위해 적극적으로 기여할 때 발생한다. 서로 다른 에이전트는 상호보완적인 능력을 제공하여 복잡한 작업을 더 작은 구성 요소로 분할할 수 있다. 하나의 에이전트는 지각에, 다른 에이전트는 계획에, 또 다른 에이전트는 검증에, 다른 에이전트는 실행에 특화될 수 있다. 로봇 시스템에서는 각각의 물리적 에이전트가 이동성, 적재 능력, 감지 능력, 운용 지속시간 또는 조작 능력에 따라 전문화될 수도 있다.

작업 할당(task allocation)은 집단 목표의 어떤 부분을 어떤 에이전트가 수행해야 하는지를 결정한다. 할당 과정에서는 능력, 위치, 작업 부하, 에너지, 예상 완료 시간, 위험, 통신 품질, 자원 가용성을 고려할 수 있다. 중앙집중식 할당(centralized assignment)은 전역적인 정보를 이용한 의사결정을 제공할 수 있고, 분산식 할당(decentralized allocation)은 에이전트가 지역 정보와 변화하는 상황을 기반으로 협상하거나 독립적으로 작업을 선택하도록 할 수 있다.

중앙집중식 멀티 에이전트 아키텍처(centralized multi-agent architecture)는 전역 정보를 유지하고 작업을 분배하는 조정자(coordinator) 또는 감독 구성 요소(supervisory component)를 사용한다. 하나의 구성 요소가 시스템 상태를 폭넓게 파악하기 때문에 계획과 충돌 해결을 단순화할 수 있다. 그러나 에이전트 수가 증가하거나 통신 신뢰성이 저하되면 조정자가 계산 병목(computational bottleneck), 통신 의존점 또는 단일 장애점(single point of failure)이 될 수 있다.

분산형 아키텍처(decentralized architecture)는 의사결정 권한을 여러 에이전트에 분산한다. 각 에이전트는 지역 관측과 교환된 정보를 기반으로 추론하고 다른 에이전트의 행동에 맞추어 자신의 행동을 조정한다. 이러한 시스템은 중앙 제어기에 완전히 의존하지 않기 때문에 더 높은 강건성(robustness)과 확장성(scalability)을 제공할 수 있다. 그러나 어느 하나의 에이전트도 전체 시스템에 대한 완전한 정보를 갖지 않는 상황에서 일관된 전역 행동을 달성해야 한다는 어려움이 있다.

하이브리드 아키텍처(hybrid architecture)는 중앙집중식과 분산식 메커니즘을 결합한다. 전략적 목표, 정책 또는 대규모 작업 할당은 중앙에서 관리하고, 지역 내비게이션(local navigation), 충돌 회피, 즉각적인 조정, 장애 복구는 개별 에이전트가 자율적으로 처리할 수 있다. 이러한 계층 구조는 중앙 기관에 지속적으로 문의하지 않고도 지역 사건에 빠르게 대응하면서 전역적인 방향성을 유지할 수 있다.

에이전트들이 환경에 대한 일관된 이해를 유지해야 하는 경우 공유 상태(shared state)가 중요하다. 공유 상태에는 지도, 객체 위치, 작업 상태, 자원 가용성, 탐지된 위험, 에이전트 위치 또는 공유 목표가 포함될 수 있다. 분산 환경에서는 완벽한 일관성을 유지하기 어려운 경우가 많으므로 시스템은 지연되거나 불완전하거나 서로 충돌하는 정보를 허용하면서 어떤 관측이 충분히 최신이고 신뢰할 수 있는지를 판단해야 한다.

분산 지각(distributed perception)을 사용하면 여러 에이전트가 개별적으로는 불완전한 관측을 결합할 수 있다. 여러 로봇은 서로 다른 시점(viewpoint)에서 환경을 관측하고, 감지 범위를 확장하고, 가려짐(occlusion)을 감소시키며, 중복성(redundancy)을 제공할 수 있다. 에이전트 간 센서 융합(sensor fusion)은 환경 이해를 향상시킬 수 있지만 공간 정렬(spatial alignment), 시간 동기화(temporal synchronization), 불확실성 관리, 데이터 연관(data association), 분산 감지 플랫폼 사이의 효율적인 통신이 필요하다.

분산 매핑 및 위치추정(distributed mapping and localization)은 이동 로봇에서 중요한 사례이다. 개별 에이전트는 지역 지도를 생성하면서 선택된 랜드마크, 특징, 자세(pose) 또는 지도 영역을 다른 에이전트와 교환할 수 있다. 집단 시스템은 점차 더 큰 공유 표현을 구성할 수 있다. 그러나 누적된 위치추정 오차, 일치하지 않는 좌표계, 중복 랜드마크, 통신 지연, 서로 다른 에이전트의 관측 사이에서 발생하는 잘못된 루프 클로저(loop closure)와 같은 문제가 발생한다.

멀티 에이전트 시스템의 계획(planning)은 환경 동역학뿐 아니라 다른 에이전트의 예상 행동도 고려해야 한다. 하나의 로봇에 최적인 경로가 다른 로봇의 경로를 방해할 수 있고, 여러 에이전트가 동일한 자원을 놓고 경쟁할 수도 있다. 따라서 멀티 에이전트 계획은 공동 제약조건(joint constraint), 시간적 의존관계, 충돌 회피, 자원 충돌, 다른 에이전트가 어떻게 행동할 가능성이 있는지에 대한 예측을 포함한다.

협상(negotiation)은 여러 에이전트가 서로 경쟁하는 선호도나 자원 요구사항을 가진 상황을 해결하는 메커니즘을 제공한다. 에이전트는 수용 가능한 할당이 이루어질 때까지 제안, 입찰(bid), 우선순위 또는 대안 계획을 교환할 수 있다. 경매 기반 메커니즘(auction-based mechanism), 계약 기반 접근법(contract-based approach), 합의 알고리즘(consensus algorithm), 분산 최적화(distributed optimization)는 하나의 에이전트가 모든 행동을 지시하지 않고 의사결정을 조정하기 위한 구조화된 방법을 제공한다.

합의(consensus)는 분산된 정보를 가진 여러 에이전트가 공통된 값, 상태, 의사결정 또는 목표에 동의해야 할 때 필요하다. 에이전트들은 지역 추정값을 반복적으로 교환하고 이웃 에이전트로부터 받은 정보에 따라 이를 조정한다. 합의 메커니즘은 대형 제어(formation control), 분산 추정(distributed estimation), 동기화된 의사결정, 공유 신념, 협력적 계획에 유용하지만 그 성능은 통신 토폴로지(communication topology)와 네트워크 신뢰성에 크게 의존한다.

창발적 행동(emergent behavior)은 많은 멀티 에이전트 시스템의 대표적인 특성이다. 시스템 수준에서 명시적으로 프로그래밍하지 않더라도 비교적 단순한 지역 상호작용 규칙으로부터 복잡한 전역 패턴이 나타날 수 있다. 군집 형성(swarm formation), 집단 탐색, 교통 조직, 분산 영역 커버리지(distributed coverage), 협력 운송은 지역 의사결정이 조정된 집단 행동을 만들어내는 사례이다. 창발성은 확장성을 향상시킬 수 있지만 시스템 수준의 행동을 예측하거나 검증하기 어렵게 만들 수도 있다.

멀티 에이전트 강화 학습(Multi-Agent Reinforcement Learning)은 여러 학습 에이전트가 존재하는 환경으로 강화 학습을 확장한다. 각각의 에이전트는 상호작용을 통해 정책(policy)을 학습하며, 다른 에이전트의 행동은 자신의 실질적인 환경의 일부가 된다. 다른 에이전트도 자신의 정책을 지속적으로 갱신하기 때문에 환경 자체가 변화하는 비정상성 학습 문제(non-stationary learning problem)가 발생한다. 협력 보상, 경쟁 보상 또는 혼합 목표는 서로 근본적으로 다른 학습 동역학을 만들 수 있다.

중앙집중식 학습과 분산 실행(Centralized Training with Decentralized Execution)은 이러한 문제를 해결하기 위한 하나의 전략이다. 학습 과정에서는 에이전트들이 전역 정보, 공유 관측 또는 다른 에이전트의 상태와 행동을 이용하여 조정된 행동을 학습할 수 있다. 배포 이후에는 각각의 에이전트가 지역적으로 이용 가능한 정보만을 사용하여 자신의 정책을 실행한다. 이를 통해 학습 중에는 풍부한 협력을 활용하면서 통신이나 중앙 계산을 사용할 수 없는 상황에서도 분산 운용을 유지할 수 있다.

기여도 할당(credit assignment)은 여러 에이전트가 하나의 공유 결과에 기여할 때 어려워진다. 팀 전체가 성공하거나 실패했을 때 학습 시스템은 각 에이전트의 행동이 결과에 어느 정도 기여했는지를 판단해야 한다. 부적절한 기여도 할당은 소극적인 행동이나 불안정한 협력을 유발할 수 있다. 가치 분해(value decomposition), 반사실적 평가(counterfactual evaluation), 차등 보상(difference reward), 에이전트별 피드백 등이 개별 행동이 집단 성능에 미친 영향을 식별하는 방법을 제공한다.

통신 자체도 학습될 수 있다. 수작업으로 설계된 메시지 형식에만 의존하는 대신 에이전트는 어떤 정보를 전송해야 하는지, 어떤 수신자에게 필요한지, 언제 통신하는 것이 가치 있는지를 학습할 수 있다. 학습된 통신(learned communication)은 대역폭을 줄이고 작업에 특화된 프로토콜을 발견할 수 있지만, 생성된 표현이 인간에게 해석하기 어려울 수 있으며 패킷 손실, 변화하는 팀 구성, 익숙하지 않은 상황에서도 강건성을 유지해야 한다.

LLM 기반 멀티 에이전트 시스템(LLM-based Multi-Agent Systems)은 언어 모델을 자율적 또는 반자율적 참여자로 도입한다. 서로 다른 LLM 에이전트가 계획자(planner), 조사자(researcher), 비평가(critic), 프로그래머(programmer), 검증자(verifier), 조정자(coordinator)와 같은 역할을 맡을 수 있다. 자연어는 유연한 통신 매체를 제공하여 에이전트들이 추론 결과를 교환하고 작업을 위임할 수 있게 한다. 그러나 반복적인 언어 모델 통신은 계산 비용을 증가시키고 근거가 부족한 가정을 에이전트 사이에 전파할 수 있다.

역할 전문화(role specialization)는 책임이 명확하게 분리되어 있을 때 멀티 에이전트 성능을 향상시킬 수 있다. 계획 에이전트가 목표를 분해하고, 전문 에이전트가 개별 구성 요소를 해결하며, 검증 에이전트가 실행 전에 결과를 검사할 수 있다. 전문화는 모든 에이전트가 모든 종류의 추론을 수행해야 할 필요성을 줄이지만, 지나친 세분화는 통신 오버헤드(communication overhead)를 발생시키고 오류에 대한 책임 소재를 식별하기 어렵게 만들 수 있다.

공유 기억(shared memory)은 협력하는 에이전트 사이에 연속성을 제공할 수 있다. 전체 이력을 반복적으로 전송하는 대신 에이전트는 관련 관측, 의사결정, 계획, 결과를 공통 기억 시스템에 기록할 수 있다. 다른 에이전트는 자신의 작업에 따라 필요한 정보를 검색한다. 그러나 공유 기억은 출처 추적(provenance), 권한, 충돌하는 갱신, 오래된 정보(stale information), 불확실성을 관리하여 잘못된 정보가 조용히 집단 지식으로 받아들여지지 않도록 해야 한다.

월드 모델(world model)은 환경과 다른 에이전트가 앞으로 어떻게 변화할지를 표현하여 협력적 예측을 지원할 수 있다. 각각의 에이전트가 지역 월드 모델(local world model)을 유지하면서 선택된 상태나 예측을 팀원과 교환할 수도 있고, 공유 모델(shared model)이 공통 환경 동역학을 제공할 수도 있다. 특히 다른 에이전트의 의도(intention)를 예측하는 것이 중요한데, 이들의 행동이 전체 그룹이 이용할 수 있는 미래 상태를 크게 변화시킬 수 있기 때문이다.

멀티 로봇 시스템(multi-robot system)에는 순수한 디지털 에이전트 시스템에는 존재하지 않는 추가적인 물리적 제약조건이 있다. 로봇은 제한된 배터리 용량, 제한된 감지 범위, 기계적 제약조건, 통신 음영 지역, 위치추정 불확실성, 충돌 위험을 가진다. 따라서 조정은 실시간 물리적 제약 아래에서 작동해야 하며, 다른 로봇이나 중앙 인프라와의 통신이 일시적으로 불가능해지는 경우에도 안전한 지역 자율성(local autonomy)을 유지해야 한다.

회복탄력성(resilience)은 분산 지능(distributed intelligence)을 사용하는 주요 동기 가운데 하나이다. 하나의 에이전트가 고장 나더라도 나머지 에이전트가 해당 작업을 재분배하여 운용을 계속할 수 있다. 통신 네트워크는 정보 전달 경로를 변경할 수 있고, 중복된 감지는 손실된 관측을 보완할 수 있다. 이러한 강건성을 달성하려면 명시적인 장애 탐지(failure detection), 성능 저하 운용 모드(degraded-operation mode), 동적 작업 재할당, 특정 에이전트에 대한 불필요한 의존성을 피하는 아키텍처가 필요하다.

자율 에이전트들이 상호작용하면서 안전(safety)은 더욱 복잡해진다. 하나의 에이전트만 독립적으로 고려하면 안전한 행동이라도 다른 에이전트의 행동과 결합될 경우 위험한 조건을 만들 수 있다. 따라서 멀티 에이전트 안전은 지역 안전 제약조건과 함께 공유 충돌 회피, 자원 배타(resource exclusion), 우선순위 관리, 비상 신호, 협력 정지(coordinated stopping)를 위한 메커니즘을 필요로 한다. 중요한 보호 기능은 상위 수준의 통신이 실패하더라도 계속 작동해야 한다.

에이전트가 다른 에이전트로부터 받은 정보를 기반으로 행동하기 때문에 신뢰(trust)와 보안(security) 역시 중요하다. 오작동하거나 손상되었거나 부정확한 에이전트가 잘못된 상태 추정이나 위험한 지시를 시스템 전체에 전파할 수 있다. 인증(authentication), 접근 제어(access control), 메시지 검증, 이상 탐지(anomaly detection), 출처 추적, 신뢰도 추정은 분산 통신이 전체 아키텍처에 오류를 확산시키는 경로가 되는 것을 방지하는 데 도움을 준다.

확장성(scalability)은 상호작용 복잡도를 제어하는 데 달려 있다. 모든 에이전트가 다른 모든 에이전트와 지속적으로 통신하면 에이전트 수가 증가할수록 통신량과 계산량이 빠르게 증가할 수 있다. 계층적 조직(hierarchical organization), 지역 이웃(local neighborhood), 이벤트 기반 통신(event-triggered communication), 압축 표현(compressed representation), 선택적 정보 공유, 동적 팀 구성(dynamic team formation)을 통해 효과적인 조정에 필요한 정보를 유지하면서 이러한 부담을 줄일 수 있다.

계층형 멀티 에이전트 시스템(Hierarchical Multi-Agent Systems)은 에이전트를 팀, 클러스터(cluster) 또는 명령 계층(command level)으로 구성할 수 있다. 지역 에이전트는 즉각적인 문제를 해결하고, 팀 조정자는 지역 정보를 통합하며, 상위 수준 구성 요소는 전략적 목표를 관리한다. 이러한 아키텍처는 모든 의사결정 단계에서 전역 통신을 수행할 필요성을 줄이고 빠른 지역 자율성과 느린 시스템 전체 계획을 연결하는 실용적인 방법을 제공한다.

멀티 에이전트 시스템은 서로 다른 형태의 지능을 결합하기 위한 자연스러운 아키텍처도 제공한다. 하나의 에이전트는 기호적 계획(symbolic planning)을 사용하고, 다른 에이전트는 강화 학습을 사용하며, 또 다른 에이전트는 LLM을 사용하고, 다른 에이전트는 결정론적 제어(deterministic control)를 구현할 수 있다. 의미 있는 상태를 교환하고 호환 가능한 프로토콜을 통해 행동을 조정할 수 있다면 모든 에이전트가 동일한 내부 아키텍처를 가질 필요는 없다. 따라서 집단 시스템은 전문화된 여러 형태의 지능을 결합할 수 있다.

메타인지(metacognition)는 개별 수준과 집단 수준 모두에서 작동할 수 있다. 개별 에이전트는 자신의 신뢰도, 진행 상황, 자원 상태, 실패를 모니터링하고, 감독 메커니즘 또는 분산 메커니즘은 팀 전체의 성능을 평가할 수 있다. 시스템은 중복 작업, 통신 장애, 상충하는 계획 또는 자신의 능력 범위를 벗어나 작동하는 에이전트를 탐지하고 재계획, 역할 재할당, 추가 검증 또는 인간 개입을 통해 대응할 수 있다.

AGI 관점에서 멀티 에이전트 시스템은 범용 지능(general intelligence)이 반드시 하나의 거대한 단일 모델(monolithic model) 내부에 존재해야 하는 것은 아니라는 점을 보여준다. 복잡한 능력은 지식을 공유하고, 작업을 분담하고, 집단적으로 추론하며, 자신의 조직을 적응시키는 전문화된 에이전트들의 공동체로부터 나타날 수 있다. 이는 분산된 개별 구성원이 고립된 하나의 참여자가 가진 능력을 넘어서는 집단적 능력을 만들어내는 많은 생물학적 시스템 및 인간 사회와 유사하다.

멀티 에이전트 시스템의 더 넓은 아키텍처적 의미는 지능을 개별적인 계산 문제에서 조정 문제(coordination problem)로 확장한다는 데 있다. 지각, 기억, 추론, 계획, 학습, 행동은 상호작용하는 여러 개체에 분산될 수 있으며, 통신과 공유 표현(shared representation)은 이들을 하나의 일관된 시스템으로 연결한다. 따라서 효과적인 집단 지능(collective intelligence)은 각각의 에이전트가 얼마나 뛰어난가뿐 아니라 에이전트들이 얼마나 신뢰성 있게 협력하고, 조정하고, 학습하고, 함께 장애로부터 복구할 수 있는가에 의해 결정된다.

##  

## 04.08. Cognitive Loop Design

![](images/image11.png){width="7.268055555555556in" height="7.268055555555556in"}

Cognitive Loop Design defines how an intelligent agent repeatedly transforms observations into understanding, decisions, actions, and learning. Rather than treating intelligence as a single inference operation, it organizes cognition as a continuous closed-loop process in which every action changes the environment and produces new observations. The agent therefore operates through recurrent interaction rather than through isolated input-output computation.

The cognitive loop begins with observation, where information is acquired from the external environment, internal system state, memory, users, tools, or other agents. Observations may include sensory signals, language, events, task status, errors, resource conditions, and feedback from previous actions. Because raw observations can be noisy, incomplete, redundant, or uncertain, they must be transformed before higher-level reasoning can reliably use them.

Perception converts observations into meaningful internal representations. Neural models may detect objects, recognize patterns, estimate states, interpret language, or fuse multimodal information. In embodied systems, perception may combine cameras, LiDAR, radar, proprioception, localization, and environmental maps. The objective is not merely to recognize data but to construct a task-relevant interpretation of what is currently happening.

State estimation integrates current perception with previous knowledge to determine the agent\'s best representation of the present situation. Since observations rarely reveal the complete state of an environment, the agent must infer hidden variables and maintain beliefs about uncertain conditions. The resulting state may contain objects, relationships, goals, constraints, resources, agent status, uncertainties, and relevant temporal information.

Memory provides continuity between successive cognitive cycles. Working memory maintains information required for the current reasoning process, episodic memory stores previous experiences and outcomes, semantic memory preserves generalized knowledge, and procedural memory contains reusable skills or strategies. Retrieval mechanisms select relevant information so that the agent can interpret the current situation in the context of what it has previously learned.

Attention determines which information deserves computational resources during a particular cycle. An agent may receive more observations than it can process with equal depth, making selective processing necessary. Novel events, high uncertainty, prediction errors, safety risks, goal-relevant changes, and unexpected behavior can receive higher priority, while familiar and stable conditions may be processed through less computationally expensive mechanisms.

Goal management defines what the agent is attempting to achieve and how competing objectives should be prioritized. Goals may originate from users, system policies, long-term missions, environmental conditions, or internally generated subgoals. A cognitive architecture must preserve goals across multiple cycles while allowing priorities to change when new evidence, risks, opportunities, or constraints appear.

Reasoning interprets the current state relative to goals and knowledge. The agent may infer relationships, diagnose problems, compare alternatives, resolve inconsistencies, or determine what additional information is required. Neural reasoning, symbolic reasoning, probabilistic inference, causal models, language models, or combinations of these mechanisms can participate depending on the architecture and the nature of the problem.

Prediction extends reasoning into the future by estimating how the environment may evolve. A world model can predict state transitions resulting from environmental dynamics, other agents, or the agent\'s own actions. Instead of responding only to the present observation, the cognitive loop can evaluate possible future states and determine whether candidate actions are likely to move the system toward desired outcomes.

Planning converts goals and predictions into organized sequences of actions. The planner may decompose a large objective into subgoals, evaluate alternative paths, estimate costs and risks, and identify required resources. Plans should not be treated as immutable scripts because environmental conditions can change. They are hypotheses about future action that must remain subject to continuous monitoring and revision.

Decision making selects which action, plan, tool, or skill should be executed next. Selection can depend on expected value, uncertainty, safety, resource cost, urgency, learned policy, symbolic constraints, and predicted outcomes. In complex architectures, decision making may arbitrate between fast reactive responses and slower deliberative reasoning, allowing the system to adapt its computational effort to the difficulty of the situation.

Action translates cognitive decisions into effects on the environment. For software agents, an action may involve querying a database, calling an API, generating a message, executing code, or modifying a digital state. For embodied agents, actions may include navigation, manipulation, communication, sensing, or control commands. Execution should occur through interfaces that clearly define capabilities, permissions, constraints, and expected feedback.

Control connects high-level intentions with reliable execution. A cognitive agent should generally avoid using expensive deliberative reasoning for every low-level operation. Hierarchical control can separate strategic cognition from fast reactive processes, allowing specialized controllers to handle stabilization, tracking, collision avoidance, or motor commands while higher cognitive layers determine goals, tasks, and behavioral strategies.

Feedback closes the cognitive loop. After an action is executed, the agent observes its consequences and compares actual outcomes with predicted outcomes. Successful predictions increase confidence in the current model, while discrepancies create prediction errors that indicate incomplete knowledge, environmental change, execution failure, or incorrect assumptions. These errors become important signals for adaptation.

Monitoring continuously evaluates whether execution remains consistent with goals, constraints, and expected progress. The system can detect stalled plans, repeated failures, unexpected environmental changes, resource depletion, communication loss, or deteriorating confidence. Monitoring prevents the architecture from blindly continuing a previously selected plan when evidence indicates that the underlying assumptions are no longer valid.

Reflection operates at a higher level by evaluating the reasoning process itself. The agent may examine why a decision failed, whether an inappropriate tool was selected, whether important evidence was ignored, or whether its world model is inaccurate. Reflection can trigger replanning, memory retrieval, additional observation, alternative reasoning strategies, or escalation to another agent or human operator.

Learning converts experience from completed cognitive cycles into future capability. Prediction errors, rewards, corrections, successful plans, failed actions, and human feedback can update neural models, policies, memories, world models, or reusable skills. The cognitive loop therefore becomes not only a mechanism for controlling behavior but also the primary pathway through which experience modifies subsequent cognition.

A central design principle is that not every cognitive cycle requires the same computational effort. Stable and predictable situations can often be handled through learned policies, cached solutions, reactive control, or lightweight prediction. When novelty, uncertainty, conflict, risk, or prediction error increases, the architecture can activate deeper reasoning, larger models, broader memory retrieval, simulation, or more extensive planning.

This creates an adaptive cognitive loop in which computational intensity varies according to environmental demand. A robot traveling through a familiar, empty corridor may rely primarily on perception and routine control, while an unexpected obstacle or ambiguous situation can activate additional world-model prediction and planning. Cognitive resources are therefore allocated according to informational significance rather than consumed uniformly at every moment.

Prediction error can serve as an important trigger for this adaptive allocation. When expected and observed states remain closely aligned, the system has evidence that its current models and policies are functioning adequately. Large deviations indicate that the environment or internal model requires additional attention. This provides a practical connection between cognitive loop design, predictive processing, active inference, and resource-aware AI.

Multiple timescales can coexist within the same architecture. Millisecond-level control loops can maintain physical stability, perception loops can update environmental state several times per second, planning loops can operate over seconds or minutes, and strategic reasoning can address much longer horizons. Attempting to force all cognitive processes into one uniform update frequency would be computationally inefficient and operationally fragile.

Hierarchical cognitive loops therefore allow different levels of intelligence to operate at appropriate temporal scales. Lower layers handle immediate sensorimotor interactions, intermediate layers manage skills and local plans, and higher layers maintain goals, strategies, semantic reasoning, and long-term context. Information moves upward when significant events require broader reasoning and downward when strategic decisions must be converted into executable behavior.

Event-driven cognition can complement periodic processing. Instead of executing every cognitive function at a fixed rate, specific events can activate particular modules. A sudden obstacle can trigger safety planning, a communication failure can activate network recovery, a large prediction error can trigger world-model reassessment, and completion of a subgoal can activate the next planning stage. This reduces unnecessary computation while preserving responsiveness.

Metacognition provides supervisory control over the cognitive loop itself. It can monitor uncertainty, progress, computational cost, confidence, model performance, and remaining objectives. The agent can determine whether to continue the current strategy, gather more information, invoke a stronger reasoning process, switch models, reduce computational effort, request assistance, or terminate an activity when further processing provides little value.

Safety must remain integrated throughout the loop rather than appearing only after a decision has been generated. Perception should identify hazards, planning should respect safety constraints, action interfaces should enforce operational limits, and monitoring should detect dangerous deviations. Independent safety mechanisms may override higher-level cognition when immediate physical or digital risks require deterministic intervention.

Human oversight can be incorporated as another path through the loop. When uncertainty, risk, authority requirements, or ethical constraints exceed predefined thresholds, the agent can request clarification or approval. Human feedback then becomes a new observation that modifies state, goals, plans, or constraints. This allows autonomy to vary dynamically instead of being defined as an all-or-nothing architectural property.

In Multi-Agent Systems, cognitive loops operate simultaneously across several agents. Each agent maintains its own perception, reasoning, planning, action, and learning cycle while communication connects local loops into a larger collective process. Shared observations, intentions, plans, and predictions can influence other agents, creating a system-level cognitive loop that emerges from coordinated local intelligence.

LLM-based agents can occupy the deliberative portions of this architecture. A language model can interpret goals, reason about structured state, retrieve knowledge, generate plans, select tools, and reflect on outcomes. However, reliable cognitive loop design places the LLM alongside memory, world models, verification, deterministic control, safety mechanisms, and external tools rather than expecting the language model to perform every cognitive function directly.

NeuroSymbolic mechanisms can further strengthen the loop by combining learned perception with explicit knowledge and constraints. Neural models provide flexible interpretation of complex observations, while symbolic representations maintain goals, rules, relationships, permissions, and task states. The cognitive loop becomes the operational framework through which these different forms of intelligence continuously exchange information.

For embodied and Physical AI systems, Cognitive Loop Design provides the bridge between perception and autonomous behavior. Sensors describe the changing world, state estimation constructs an internal representation, memory provides context, world models predict consequences, planners organize future behavior, controllers execute actions, and feedback reveals whether expectations were correct. Intelligence emerges from the continuous coordination of these processes.

From an AGI perspective, the cognitive loop provides a temporal architecture for integrating otherwise separate cognitive capabilities. Perception without memory lacks continuity, reasoning without action cannot affect the environment, planning without feedback cannot adapt, and learning without interaction lacks grounded experience. The loop connects these functions so that cognition becomes an ongoing process of understanding, predicting, acting, evaluating, and improving.

A mature Cognitive Loop Design therefore resembles a dynamically regulated hierarchy of interacting loops rather than a simple linear pipeline. Fast reactive mechanisms operate continuously, deliberative reasoning activates when needed, memory connects experience across time, world models anticipate consequences, metacognition regulates computational effort, and learning modifies future behavior. Such a design provides a foundation for adaptive, efficient, safe, and increasingly autonomous intelligent systems.

인지 순환 설계(Cognitive Loop Design)는 지능형 에이전트(intelligent agent)가 관측을 이해, 의사결정, 행동, 학습으로 반복적으로 변환하는 방식을 정의한다. 지능을 하나의 추론 연산으로 취급하는 대신, 모든 행동이 환경을 변화시키고 새로운 관측을 생성하는 지속적인 폐루프 과정(closed-loop process)으로 인지를 구성한다. 따라서 에이전트는 고립된 입력-출력 계산이 아니라 환경과의 반복적인 상호작용을 통해 작동한다.

인지 순환(cognitive loop)은 외부 환경, 내부 시스템 상태, 기억, 사용자, 도구 또는 다른 에이전트로부터 정보를 획득하는 관측(observation)에서 시작된다. 관측에는 감각 신호, 언어, 사건, 작업 상태, 오류, 자원 상태, 이전 행동의 피드백 등이 포함될 수 있다. 원시 관측(raw observation)은 잡음이 많거나 불완전하고 중복되거나 불확실할 수 있으므로 상위 수준의 추론에서 안정적으로 사용하기 전에 적절한 형태로 변환되어야 한다.

지각(perception)은 관측을 의미 있는 내부 표현(internal representation)으로 변환한다. 신경망 모델은 객체를 탐지하고, 패턴을 인식하고, 상태를 추정하고, 언어를 해석하거나, 멀티모달 정보(multimodal information)를 융합할 수 있다. 체화형 시스템(embodied system)에서 지각은 카메라, 라이다(LiDAR), 레이더(radar), 고유수용감각(proprioception), 위치추정(localization), 환경 지도를 결합할 수 있다. 목적은 단순한 데이터 인식이 아니라 현재 상황에 대한 작업 관련 해석을 구성하는 것이다.

상태 추정(state estimation)은 현재의 지각과 이전 지식을 통합하여 현재 상황에 대한 에이전트의 최선의 표현을 결정한다. 관측만으로 환경의 완전한 상태를 파악하기 어려운 경우가 많기 때문에 에이전트는 숨겨진 변수(hidden variable)를 추론하고 불확실한 조건에 대한 신념(belief)을 유지해야 한다. 결과적인 상태에는 객체, 관계, 목표, 제약조건, 자원, 에이전트 상태, 불확실성, 관련 시간 정보가 포함될 수 있다.

기억(memory)은 연속적인 인지 순환 사이에 지속성을 제공한다. 작업 기억(working memory)은 현재 추론 과정에 필요한 정보를 유지하고, 일화 기억(episodic memory)은 이전 경험과 결과를 저장하며, 의미 기억(semantic memory)은 일반화된 지식을 보존하고, 절차적 기억(procedural memory)은 재사용 가능한 기술이나 전략을 포함한다. 검색 메커니즘(retrieval mechanism)은 관련 정보를 선택하여 에이전트가 과거에 학습한 내용을 바탕으로 현재 상황을 해석할 수 있도록 한다.

주의(attention)는 특정 인지 순환에서 어떤 정보에 계산 자원을 할당해야 하는지를 결정한다. 에이전트가 동일한 깊이로 처리할 수 있는 양보다 많은 관측을 받을 수 있기 때문에 선택적 처리(selective processing)가 필요하다. 새로운 사건, 높은 불확실성, 예측 오차(prediction error), 안전 위험, 목표와 관련된 변화, 예상하지 못한 행동에는 높은 우선순위를 부여하고, 익숙하고 안정적인 조건은 계산 비용이 낮은 메커니즘으로 처리할 수 있다.

목표 관리(goal management)는 에이전트가 무엇을 달성하려고 하는지와 서로 경쟁하는 목표의 우선순위를 어떻게 결정할지를 정의한다. 목표는 사용자, 시스템 정책, 장기 임무, 환경 조건 또는 내부적으로 생성된 하위 목표(subgoal)에서 비롯될 수 있다. 인지 아키텍처(cognitive architecture)는 여러 순환에 걸쳐 목표를 유지하면서 새로운 증거, 위험, 기회 또는 제약조건이 나타날 경우 우선순위를 변경할 수 있어야 한다.

추론(reasoning)은 현재 상태를 목표 및 지식과 관련하여 해석한다. 에이전트는 관계를 추론하고, 문제를 진단하고, 대안을 비교하고, 불일치를 해결하거나, 추가적으로 어떤 정보가 필요한지를 판단할 수 있다. 아키텍처와 문제의 특성에 따라 신경망 추론(neural reasoning), 기호적 추론(symbolic reasoning), 확률적 추론(probabilistic inference), 인과 모델(causal model), 언어 모델(language model) 또는 이들의 조합이 사용될 수 있다.

예측(prediction)은 환경이 앞으로 어떻게 변화할 수 있는지를 추정함으로써 추론을 미래로 확장한다. 월드 모델(world model)은 환경 동역학(environmental dynamics), 다른 에이전트 또는 자신의 행동으로 발생하는 상태 전이(state transition)를 예측할 수 있다. 인지 순환은 현재 관측에만 반응하는 대신 가능한 미래 상태를 평가하고 후보 행동이 시스템을 원하는 결과로 이동시킬 가능성이 있는지를 판단할 수 있다.

계획(planning)은 목표와 예측을 조직된 행동 순서(sequence of actions)로 변환한다. 계획 시스템(planner)은 큰 목표를 하위 목표로 분해하고, 대안 경로를 평가하고, 비용과 위험을 추정하며, 필요한 자원을 식별할 수 있다. 환경 조건은 변화할 수 있으므로 계획을 변경할 수 없는 고정된 스크립트로 취급해서는 안 된다. 계획은 지속적인 모니터링과 수정의 대상이 되는 미래 행동에 대한 가설로 이해해야 한다.

의사결정(decision making)은 다음에 실행할 행동, 계획, 도구 또는 기술(skill)을 선택한다. 선택은 기대 가치(expected value), 불확실성, 안전, 자원 비용, 긴급성, 학습된 정책(policy), 기호적 제약조건(symbolic constraint), 예측 결과에 따라 달라질 수 있다. 복잡한 아키텍처에서 의사결정은 빠른 반응형 응답과 느린 숙고적 추론(deliberative reasoning) 사이를 조정하여 상황의 난이도에 맞게 계산량을 변화시킬 수 있다.

행동(action)은 인지적 의사결정을 환경에 영향을 주는 결과로 변환한다. 소프트웨어 에이전트에서는 데이터베이스 질의, API 호출, 메시지 생성, 코드 실행 또는 디지털 상태 변경 등이 행동이 될 수 있다. 체화형 에이전트에서는 내비게이션, 조작(manipulation), 통신, 감지 또는 제어 명령이 포함될 수 있다. 실행은 기능, 권한, 제약조건, 예상 피드백을 명확하게 정의하는 인터페이스를 통해 이루어져야 한다.

제어(control)는 상위 수준의 의도와 신뢰성 있는 실행을 연결한다. 인지 에이전트가 모든 저수준 연산에 비용이 높은 숙고적 추론을 사용하는 것은 일반적으로 바람직하지 않다. 계층적 제어(hierarchical control)는 전략적 인지를 빠른 반응형 과정과 분리하여 전문화된 제어기가 안정화, 추종, 충돌 회피 또는 모터 명령을 처리하고, 상위 인지 계층은 목표, 작업, 행동 전략을 결정하도록 할 수 있다.

피드백(feedback)은 인지 순환을 닫는다. 행동이 실행된 이후 에이전트는 그 결과를 관측하고 실제 결과를 예측 결과와 비교한다. 성공적인 예측은 현재 모델에 대한 신뢰도를 높이는 반면, 불일치는 불완전한 지식, 환경 변화, 실행 실패 또는 잘못된 가정을 나타내는 예측 오차를 생성한다. 이러한 오차는 적응(adaptation)을 위한 중요한 신호가 된다.

모니터링(monitoring)은 실행이 목표, 제약조건, 예상 진행 상황과 일치하는지를 지속적으로 평가한다. 시스템은 정체된 계획, 반복되는 실패, 예상하지 못한 환경 변화, 자원 고갈, 통신 손실 또는 신뢰도 저하를 탐지할 수 있다. 모니터링은 기존 가정이 더 이상 유효하지 않다는 증거가 나타났음에도 이전에 선택된 계획을 아키텍처가 무조건 계속 실행하는 것을 방지한다.

성찰(reflection)은 추론 과정 자체를 평가하는 더 높은 수준의 기능이다. 에이전트는 의사결정이 왜 실패했는지, 부적절한 도구가 선택되었는지, 중요한 증거를 무시했는지 또는 월드 모델이 부정확한지를 검토할 수 있다. 성찰은 재계획(replanning), 기억 검색, 추가 관측, 대안적 추론 전략 또는 다른 에이전트나 인간 운영자에게 에스컬레이션(escalation)하는 과정을 유발할 수 있다.

학습(learning)은 완료된 인지 순환에서 얻은 경험을 미래의 능력으로 변환한다. 예측 오차, 보상(reward), 수정 사항, 성공한 계획, 실패한 행동, 인간 피드백을 이용하여 신경망 모델, 정책, 기억, 월드 모델 또는 재사용 가능한 기술을 갱신할 수 있다. 따라서 인지 순환은 행동을 제어하기 위한 메커니즘일 뿐 아니라 경험이 이후의 인지를 변화시키는 핵심적인 경로가 된다.

핵심적인 설계 원칙은 모든 인지 순환이 동일한 수준의 계산 노력을 필요로 하지 않는다는 것이다. 안정적이고 예측 가능한 상황은 학습된 정책, 캐시된 해결책(cached solution), 반응형 제어 또는 경량 예측(lightweight prediction)을 통해 처리할 수 있다. 새로움(novelty), 불확실성, 충돌, 위험 또는 예측 오차가 증가하면 더 깊은 추론, 더 큰 모델, 광범위한 기억 검색, 시뮬레이션 또는 보다 정교한 계획을 활성화할 수 있다.

이를 통해 환경의 요구에 따라 계산 강도가 달라지는 적응형 인지 순환(adaptive cognitive loop)이 형성된다. 익숙하고 비어 있는 복도를 이동하는 로봇은 주로 지각과 일상적인 제어에 의존할 수 있지만, 예상하지 못한 장애물이나 모호한 상황이 발생하면 추가적인 월드 모델 예측과 계획을 활성화할 수 있다. 따라서 인지 자원은 모든 순간에 균일하게 소비되는 것이 아니라 정보의 중요도에 따라 할당된다.

예측 오차(prediction error)는 이러한 적응형 자원 할당을 위한 중요한 트리거(trigger)로 사용될 수 있다. 예상 상태와 관측 상태가 지속적으로 일치한다면 시스템은 현재의 모델과 정책이 적절하게 작동하고 있다는 증거를 갖게 된다. 큰 편차가 발생하면 환경이나 내부 모델에 추가적인 주의가 필요하다는 것을 의미한다. 이는 인지 순환 설계와 예측 처리(predictive processing), 능동 추론(active inference), 자원 인식형 AI(resource-aware AI)를 실질적으로 연결한다.

하나의 아키텍처 안에는 여러 시간 척도(timescale)가 동시에 존재할 수 있다. 밀리초 수준의 제어 루프는 물리적 안정성을 유지하고, 지각 루프는 초당 여러 번 환경 상태를 갱신하며, 계획 루프는 수초 또는 수분 단위로 작동하고, 전략적 추론은 훨씬 긴 시간 범위를 다룰 수 있다. 모든 인지 과정을 하나의 동일한 갱신 주기로 강제하면 계산적으로 비효율적이고 운용적으로 취약한 시스템이 될 수 있다.

따라서 계층적 인지 순환(hierarchical cognitive loop)은 서로 다른 수준의 지능이 적절한 시간 척도에서 작동하도록 한다. 하위 계층은 즉각적인 감각운동 상호작용(sensorimotor interaction)을 처리하고, 중간 계층은 기술과 지역 계획을 관리하며, 상위 계층은 목표, 전략, 의미론적 추론(semantic reasoning), 장기 문맥을 유지한다. 중요한 사건이 광범위한 추론을 필요로 하면 정보가 상위 계층으로 전달되고, 전략적 의사결정이 실행 가능한 행동으로 변환되어야 하면 정보가 하위 계층으로 전달된다.

이벤트 기반 인지(event-driven cognition)는 주기적 처리(periodic processing)를 보완할 수 있다. 모든 인지 기능을 고정된 빈도로 실행하는 대신 특정 사건이 특정 모듈을 활성화하도록 할 수 있다. 갑작스러운 장애물은 안전 계획을, 통신 장애는 네트워크 복구를, 큰 예측 오차는 월드 모델 재평가를, 하위 목표의 완료는 다음 계획 단계를 활성화할 수 있다. 이를 통해 불필요한 계산을 줄이면서도 상황 변화에 대한 반응성을 유지할 수 있다.

메타인지(metacognition)는 인지 순환 자체에 대한 감독 제어(supervisory control)를 제공한다. 메타인지는 불확실성, 진행 상황, 계산 비용, 신뢰도, 모델 성능, 남아 있는 목표를 모니터링할 수 있다. 에이전트는 현재 전략을 계속할지, 추가 정보를 수집할지, 더 강력한 추론 과정을 호출할지, 모델을 전환할지, 계산량을 줄일지, 도움을 요청할지 또는 추가 처리가 거의 가치를 제공하지 않을 때 활동을 종료할지를 결정할 수 있다.

안전(safety)은 의사결정이 생성된 이후에만 적용되는 것이 아니라 전체 순환에 통합되어야 한다. 지각은 위험을 식별해야 하고, 계획은 안전 제약조건을 준수해야 하며, 행동 인터페이스는 운용 한계를 강제하고, 모니터링은 위험한 편차를 탐지해야 한다. 즉각적인 물리적 또는 디지털 위험으로 인해 결정론적 개입(deterministic intervention)이 필요한 경우 독립적인 안전 메커니즘이 상위 수준 인지를 무시하고 개입할 수 있다.

인간 감독(human oversight)은 인지 순환을 통과하는 또 다른 경로로 포함될 수 있다. 불확실성, 위험, 권한 요구사항 또는 윤리적 제약조건이 사전에 정의된 임계값을 초과하면 에이전트가 명확한 설명이나 승인을 요청할 수 있다. 인간의 피드백은 새로운 관측으로 작용하여 상태, 목표, 계획 또는 제약조건을 수정한다. 이를 통해 자율성(autonomy)을 전부 허용하거나 전부 금지하는 속성이 아니라 상황에 따라 동적으로 변화하는 속성으로 구성할 수 있다.

멀티 에이전트 시스템(Multi-Agent Systems)에서는 여러 에이전트에서 인지 순환이 동시에 작동한다. 각각의 에이전트는 자신의 지각, 추론, 계획, 행동, 학습 순환을 유지하면서 통신을 통해 지역 순환(local loop)을 더 큰 집단적 과정으로 연결한다. 공유된 관측, 의도, 계획, 예측은 다른 에이전트에 영향을 줄 수 있으며, 조정된 지역 지능으로부터 시스템 수준의 인지 순환(system-level cognitive loop)이 형성될 수 있다.

LLM 기반 에이전트(LLM-based agent)는 이러한 아키텍처의 숙고적 부분(deliberative portion)을 담당할 수 있다. 언어 모델은 목표를 해석하고, 구조화된 상태에 대해 추론하고, 지식을 검색하고, 계획을 생성하고, 도구를 선택하고, 결과를 성찰할 수 있다. 그러나 신뢰성 높은 인지 순환 설계에서는 언어 모델이 모든 인지 기능을 직접 수행하도록 하기보다 LLM을 기억, 월드 모델, 검증, 결정론적 제어, 안전 메커니즘, 외부 도구와 함께 배치한다.

뉴로심볼릭 메커니즘(NeuroSymbolic mechanism)은 학습된 지각과 명시적 지식 및 제약조건을 결합하여 인지 순환을 더욱 강화할 수 있다. 신경망 모델은 복잡한 관측에 대한 유연한 해석을 제공하고, 기호적 표현(symbolic representation)은 목표, 규칙, 관계, 권한, 작업 상태를 유지한다. 인지 순환은 이러한 서로 다른 형태의 지능이 지속적으로 정보를 교환하는 운용 프레임워크(operational framework)가 된다.

체화 지능(embodied intelligence) 및 피지컬 AI(Physical AI) 시스템에서 인지 순환 설계는 지각과 자율 행동 사이의 연결을 제공한다. 센서는 변화하는 세계를 설명하고, 상태 추정은 내부 표현을 구성하며, 기억은 문맥을 제공하고, 월드 모델은 결과를 예측하며, 계획 시스템은 미래 행동을 조직하고, 제어기는 행동을 실행하며, 피드백은 예측이 정확했는지를 알려준다. 지능은 이러한 과정들의 지속적인 조정으로부터 나타난다.

AGI 관점에서 인지 순환은 서로 분리되어 보이는 인지 능력을 통합하기 위한 시간적 아키텍처(temporal architecture)를 제공한다. 기억 없는 지각은 연속성이 부족하고, 행동 없는 추론은 환경에 영향을 줄 수 없으며, 피드백 없는 계획은 적응할 수 없고, 상호작용 없는 학습은 실제 환경에 기반한 경험(grounded experience)을 얻기 어렵다. 인지 순환은 이러한 기능을 연결하여 인지를 이해하고, 예측하고, 행동하고, 평가하고, 개선하는 지속적인 과정으로 만든다.

따라서 성숙한 인지 순환 설계(Cognitive Loop Design)는 단순한 선형 파이프라인(linear pipeline)이 아니라 동적으로 조절되는 상호작용형 계층적 순환(hierarchy of interacting loops)에 가깝다. 빠른 반응형 메커니즘은 지속적으로 작동하고, 숙고적 추론은 필요할 때 활성화되며, 기억은 시간에 걸쳐 경험을 연결하고, 월드 모델은 결과를 예측하며, 메타인지는 계산 노력을 조절하고, 학습은 미래 행동을 변화시킨다. 이러한 설계는 적응적이고 효율적이며 안전하고 점차 높은 자율성을 갖는 지능형 시스템의 기반을 제공한다.
