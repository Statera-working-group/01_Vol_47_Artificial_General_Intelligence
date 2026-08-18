**Volume 47. Artificial General Intelligence**


# Chapter 01. Foundations of AGI

##  

## 01.00. What is Intelligence

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

Intelligence can be understood as the capacity of an agent to acquire information, construct useful representations, learn from experience, reason about situations, and select actions that improve its ability to achieve goals. This definition deliberately extends beyond solving puzzles or producing correct answers. Intelligence concerns how effectively a system converts perception, knowledge, memory, and experience into adaptive behavior across changing environments.

A central characteristic of intelligence is adaptation. An intelligent agent cannot depend entirely on fixed responses because the world continuously presents unfamiliar states, incomplete information, and unexpected events. It must detect meaningful changes, revise internal assumptions, and modify its behavior. Adaptation therefore connects perception and learning with action, allowing accumulated experience to influence future decisions rather than merely recording the past.

Learning is one mechanism through which adaptation becomes possible. Experience provides observations, outcomes, errors, rewards, demonstrations, and interactions from which an intelligent system can extract regularities. Effective learning does more than memorize individual examples. It discovers structures that remain useful beyond the original training conditions, enabling knowledge acquired in one situation to support behavior in another situation with different details.

This ability leads to generalization, one of the most important distinctions between narrow competence and general intelligence. A system may perform exceptionally well on a predefined task while failing when the environment, objective, or representation changes. General intelligence requires transferable knowledge that can be recombined and applied to unfamiliar problems. For this reason, the AGI structure places generalization and transfer immediately after the foundational discussion of intelligence.

Perception provides another foundation. An intelligent agent must transform raw observations into representations that preserve information relevant to decisions. Humans integrate vision, hearing, touch, language, proprioception, and prior knowledge, while artificial systems may integrate images, text, audio, sensor streams, databases, or machine states. Intelligence depends not simply on receiving these signals but on interpreting relationships among them and constructing coherent descriptions of situations.

Memory allows intelligence to operate across time. Without memory, every observation would effectively become a new beginning. Short-term information supports immediate reasoning, while longer-term memory preserves knowledge, experiences, skills, relationships, and strategies. An intelligent system must also determine what should be stored, retrieved, updated, compressed, or forgotten. Memory is therefore an active computational resource rather than merely a passive archive of historical information.

Reasoning enables an agent to derive conclusions that are not explicitly contained in its immediate observations. It can combine facts, evaluate hypotheses, infer hidden causes, estimate consequences, compare alternatives, and detect inconsistencies. Reasoning may be logical, probabilistic, causal, neural, symbolic, or hybrid. For general intelligence, the important property is not commitment to one reasoning mechanism but the flexible selection and integration of mechanisms appropriate to different problems.

Planning extends reasoning into the future. Instead of responding only to the present state, an intelligent agent can represent possible future states and evaluate sequences of actions leading toward desired outcomes. Planning becomes increasingly important as tasks require long horizons, delayed rewards, resource constraints, or interactions with other agents. Intelligence therefore involves prediction not merely for knowing what may happen, but for deciding what should be done next.

Goals give intelligence direction. An agent may possess sophisticated perception and prediction yet behave ineffectively if it cannot connect those capabilities to objectives. Goal-directed intelligence evaluates states and actions relative to desired outcomes, constraints, priorities, and costs. In biological systems, goals may emerge from survival, motivation, social interaction, and learned preferences. Artificial agents receive or construct objectives through tasks, reward functions, instructions, policies, and higher-level plans.

Uncertainty is unavoidable because intelligent agents rarely possess complete knowledge of their environments. Observations may be noisy, future events uncertain, causal relationships partially known, and other agents unpredictable. Intelligence consequently requires calibrated decision-making under incomplete information. Rather than demanding certainty before acting, an intelligent system estimates possibilities, manages risk, gathers additional evidence when useful, and updates beliefs when observations contradict previous expectations.

An important perspective is that intelligence is relational rather than purely internal. Whether behavior appears intelligent depends partly on the environment, available resources, objectives, and time constraints. A strategy effective in one environment may fail in another. Intelligence can therefore be viewed as the ability of an agent to maintain effective interaction with a range of environments, especially when those environments contain novelty, uncertainty, complexity, and changing requirements.

Embodiment further emphasizes this interaction. For humans, animals, robots, and autonomous machines, intelligence develops through repeated perception-action cycles in which actions change the world and produce new observations. The agent learns not only what objects and events are, but what can be done with them and what consequences actions produce. This relationship explains why embodiment, world models, reasoning, planning, and control become closely connected when intelligence is considered from an AGI perspective.

A world model provides an internal basis for prediction and simulation. Instead of learning only direct mappings from inputs to outputs, an intelligent system can represent entities, states, relationships, dynamics, and possible transitions. Such representations allow the agent to ask implicitly what is happening, why it is happening, what may happen next, and how an intervention could change the outcome. World models therefore connect perception with reasoning, planning, causality, and action.

Language introduces another powerful dimension because it allows knowledge to be represented, communicated, recombined, and transmitted across individuals and generations. Modern language models demonstrate that large amounts of conceptual and procedural structure can emerge from learning statistical relationships in language. Yet linguistic competence alone does not define general intelligence. Robust AGI also requires grounding, persistent memory, adaptation, planning, interaction, and reliable action beyond static language prediction.

Intelligence should therefore not be reduced to a single algorithm, model architecture, benchmark score, or cognitive faculty. It is better understood as an integrated capability emerging from coordinated perception, representation, memory, learning, reasoning, prediction, planning, action, and self-monitoring. The broader AGI structure reflects this systems perspective by progressing from foundations toward core mechanisms, cognitive architectures, engineering, evaluation, real-world operation, and eventually unified intelligent agents.

Human intelligence illustrates how these capabilities can operate at different timescales. Fast perceptual and habitual processes handle familiar situations efficiently, while slower reasoning can become active when novelty, ambiguity, conflict, or danger increases. Memory supplies prior experience, attention allocates limited computational resources, and metacognitive processes can evaluate uncertainty or mistakes. General intelligence may therefore require dynamic allocation of computation rather than uniform processing of every situation.

Transfer is especially important because a generally intelligent system should reuse previous knowledge instead of relearning every task from the beginning. Concepts, skills, causal relationships, strategies, and representations learned in one domain should provide useful structure in another. Successful transfer requires identifying which aspects of previous experience remain invariant and which must be adapted. This capability turns accumulated experience into a reusable foundation for increasingly efficient future learning.

Another defining feature is compositionality. Intelligent systems can construct complex solutions by combining simpler concepts and skills. Knowledge about objects, space, causality, language, tools, social behavior, and physical dynamics can be reorganized according to the current problem. Such recombination greatly expands the number of situations an agent can address without requiring explicit training for every possible combination, making compositional representations particularly valuable for scalable general intelligence.

Metacognition adds the ability to reason about the agent\'s own cognitive processes. An intelligent system may estimate whether it knows something, recognize uncertainty, detect contradictions, evaluate the quality of a plan, or decide that additional information is required. This creates a feedback loop in which reasoning itself becomes subject to monitoring and adjustment. In AGI, such mechanisms may support reflection, error correction, strategy selection, continual learning, and eventually forms of controlled self-improvement.

Intelligence is consequently better viewed as a continuum of adaptive competence than as a binary property that a system either possesses or lacks. Different agents may exhibit different combinations of memory, reasoning, creativity, transfer, autonomy, social understanding, and physical competence. AGI research asks whether these capabilities can be integrated into systems whose competence remains effective across a sufficiently broad range of tasks and environments rather than within one carefully bounded domain.

The engineering challenge is therefore not simply to make individual components more powerful. A general intelligent agent must coordinate perception, memory, knowledge, reasoning, planning, learning, and action through continuous feedback. Information discovered by perception must update representations; representations must support prediction; predictions must guide plans; actions must test those plans; and resulting observations must modify future behavior. Intelligence emerges from this closed adaptive loop as much as from any individual model.

Ultimately, intelligence can be characterized as the capacity to build useful models of the world, learn from interaction, transfer knowledge across contexts, reason under uncertainty, anticipate consequences, pursue goals, and continually adapt behavior when reality differs from expectation. This broad conception provides the conceptual foundation for studying AGI, while later topics can separately examine human versus artificial intelligence, generalization, reasoning, learning, embodiment, world models, knowledge, representation, and their eventual integration.

지능(Intelligence)은 에이전트(agent)가 정보를 획득하고, 유용한 표상(representation)을 구성하며, 경험으로부터 학습하고, 상황을 추론하며, 목표 달성 능력을 향상시키는 행동을 선택하는 역량으로 이해할 수 있다. 이러한 정의는 단순히 문제를 풀거나 정답을 생성하는 능력을 넘어선다. 지능은 지각(perception), 지식(knowledge), 기억(memory), 경험(experience)을 변화하는 환경에서 적응적 행동(adaptive behavior)으로 얼마나 효과적으로 변환하는가와 관련된다.

지능의 핵심적인 특성 가운데 하나는 적응(Adaptation)이다. 지능적인 에이전트는 세계가 끊임없이 새로운 상태, 불완전한 정보, 예상하지 못한 사건을 제시하기 때문에 고정된 반응에만 의존할 수 없다. 의미 있는 변화를 감지하고 내부의 가정(assumption)을 수정하며 행동을 변화시켜야 한다. 따라서 적응은 지각과 학습을 행동과 연결하여, 축적된 경험이 단순히 과거를 기록하는 데 그치지 않고 미래의 의사결정(decision-making)에 영향을 미치도록 한다.

학습(Learning)은 이러한 적응을 가능하게 하는 주요 메커니즘(mechanism)이다. 경험은 관찰(observation), 결과(outcome), 오류(error), 보상(reward), 시범(demonstration), 상호작용(interaction)을 제공하며, 지능적인 시스템은 이를 통해 규칙성과 구조를 추출할 수 있다. 효과적인 학습은 개별 사례를 단순히 암기하는 것을 넘어선다. 학습 당시의 조건을 벗어나서도 유용한 구조를 발견함으로써, 한 상황에서 습득한 지식을 세부 조건이 다른 새로운 상황에서도 활용할 수 있게 한다.

이러한 능력은 일반화(Generalization)로 이어지며, 일반화는 협소한 능력(narrow competence)과 일반지능(general intelligence)을 구분하는 가장 중요한 요소 중 하나이다. 시스템이 미리 정의된 특정 작업에서는 뛰어난 성능을 보이면서도 환경, 목표 또는 표현 방식이 달라지면 실패할 수 있다. 일반지능은 새로운 문제에 재조합하여 적용할 수 있는 전이 가능한 지식(transferable knowledge)을 필요로 한다. 이러한 이유로 AGI 구조에서는 지능의 기초적 논의 직후에 일반화와 전이(generalization and transfer)를 다룬다.

지각(Perception)은 또 다른 중요한 기반을 제공한다. 지능적인 에이전트는 원시 관찰(raw observation)을 의사결정에 필요한 정보를 보존하는 표상(representation)으로 변환해야 한다. 인간은 시각, 청각, 촉각, 언어, 고유수용감각(proprioception), 사전 지식(prior knowledge)을 통합하며, 인공 시스템은 이미지, 텍스트, 오디오, 센서 스트림(sensor stream), 데이터베이스, 기계 상태(machine state)를 통합할 수 있다. 지능은 이러한 신호를 단순히 받아들이는 것이 아니라 신호 사이의 관계를 해석하고 상황에 대한 일관된 표현을 구성하는 능력에 의존한다.

기억(Memory)은 지능이 시간의 흐름을 넘어 작동할 수 있도록 한다. 기억이 없다면 모든 관찰은 사실상 새로운 시작이 된다. 단기 정보(short-term information)는 즉각적인 추론을 지원하고, 장기 기억(long-term memory)은 지식, 경험, 기술, 관계, 전략을 보존한다. 또한 지능적인 시스템은 무엇을 저장하고, 검색하며, 갱신하고, 압축하거나 잊어야 하는지를 결정해야 한다. 따라서 기억은 단순한 과거 정보의 수동적 저장소가 아니라 능동적인 계산 자원(computational resource)이다.

추론(Reasoning)은 에이전트가 현재의 관찰에 명시적으로 포함되어 있지 않은 결론을 도출할 수 있도록 한다. 사실을 결합하고, 가설을 평가하며, 숨겨진 원인을 추론하고, 결과를 예측하며, 대안을 비교하고, 모순을 발견할 수 있다. 추론은 논리적(logical), 확률적(probabilistic), 인과적(causal), 신경망 기반(neural), 기호적(symbolic), 또는 하이브리드(hybrid) 방식으로 이루어질 수 있다. 일반지능에서 중요한 것은 하나의 추론 메커니즘에 의존하는 것이 아니라 서로 다른 문제에 적합한 메커니즘을 유연하게 선택하고 통합하는 것이다.

계획(Planning)은 추론을 미래로 확장한다. 지능적인 에이전트는 현재 상태에 단순히 반응하는 대신 가능한 미래 상태(future state)를 표현하고 원하는 결과로 이어지는 일련의 행동을 평가할 수 있다. 장기적인 작업(long-horizon task), 지연된 보상(delayed reward), 자원 제약(resource constraint), 다른 에이전트와의 상호작용이 포함될수록 계획의 중요성은 커진다. 따라서 지능에서 예측(prediction)은 단순히 미래에 무엇이 일어날지를 아는 것이 아니라 다음에 무엇을 해야 하는지를 결정하기 위한 과정이기도 하다.

목표(Goal)는 지능에 방향성을 부여한다. 에이전트가 정교한 지각과 예측 능력을 갖추고 있더라도 이를 목표와 연결하지 못하면 효과적으로 행동하기 어렵다. 목표지향적 지능(goal-directed intelligence)은 원하는 결과, 제약조건, 우선순위, 비용을 기준으로 상태와 행동을 평가한다. 생물학적 시스템의 목표는 생존, 동기, 사회적 상호작용, 학습된 선호에서 발생할 수 있으며, 인공 에이전트의 목표는 작업, 보상함수(reward function), 명령(instruction), 정책(policy), 상위 수준 계획(high-level plan)을 통해 주어지거나 구성될 수 있다.

불확실성(Uncertainty)은 지능적인 에이전트가 환경에 대한 완전한 지식을 갖는 경우가 거의 없기 때문에 피할 수 없다. 관찰에는 잡음이 존재하고, 미래 사건은 불확실하며, 인과관계는 부분적으로만 알려져 있고, 다른 에이전트의 행동은 예측하기 어려울 수 있다. 따라서 지능은 불완전한 정보에서의 적절한 의사결정(calibrated decision-making)을 요구한다. 지능적인 시스템은 행동하기 전에 완전한 확실성을 요구하기보다 가능성을 추정하고 위험을 관리하며, 필요한 경우 추가 정보를 수집하고 새로운 관찰이 기존 예측과 충돌하면 믿음(belief)을 갱신한다.

중요한 관점 가운데 하나는 지능이 순수하게 내부적인 특성이라기보다 관계적 특성(relational property)을 가진다는 것이다. 어떤 행동이 지능적으로 보이는지는 환경, 이용 가능한 자원, 목표, 시간적 제약과 부분적으로 관련된다. 한 환경에서 효과적인 전략이 다른 환경에서는 실패할 수 있다. 따라서 지능은 다양한 환경과 효과적인 상호작용을 유지하는 능력으로 볼 수 있으며, 특히 새로움(novelty), 불확실성, 복잡성, 변화하는 요구조건을 포함하는 환경에서 이러한 능력이 중요해진다.

체화(Embodiment)는 이러한 상호작용을 더욱 강조한다. 인간, 동물, 로봇, 자율기계(autonomous machine)의 지능은 행동이 세계를 변화시키고 그 결과 새로운 관찰이 발생하는 반복적인 지각-행동 순환(perception-action loop)을 통해 발달한다. 에이전트는 사물과 사건이 무엇인지만 학습하는 것이 아니라 그것을 이용하여 무엇을 할 수 있고, 특정 행동이 어떤 결과를 발생시키는지도 학습한다. 이러한 관계는 AGI 관점에서 체화, 월드 모델(world model), 추론, 계획, 제어(control)가 밀접하게 연결되는 이유를 설명한다.

월드 모델(World Model)은 예측과 시뮬레이션(simulation)을 위한 내부적 기반을 제공한다. 지능적인 시스템은 입력에서 출력으로의 직접적인 매핑(mapping)만을 학습하는 대신 개체(entity), 상태(state), 관계(relationship), 동역학(dynamics), 가능한 상태 전이(state transition)를 표현할 수 있다. 이러한 표현을 통해 에이전트는 암묵적으로 현재 무엇이 일어나고 있는지, 왜 발생하는지, 다음에는 무엇이 발생할 가능성이 있는지, 그리고 개입(intervention)이 결과를 어떻게 변화시킬 수 있는지를 판단할 수 있다. 따라서 월드 모델은 지각을 추론, 계획, 인과성(causality), 행동과 연결한다.

언어(Language)는 지식이 표현되고, 전달되고, 재조합되며, 개인과 세대를 넘어 전승될 수 있도록 한다는 점에서 지능에 또 다른 강력한 차원을 제공한다. 현대의 언어 모델(language model)은 언어의 통계적 관계를 학습함으로써 방대한 개념적·절차적 구조를 습득할 수 있음을 보여준다. 그러나 언어적 능력만으로 일반지능을 정의할 수는 없다. 강건한 AGI(robust AGI)는 언어 예측을 넘어 접지(grounding), 지속적 기억(persistent memory), 적응, 계획, 상호작용, 신뢰할 수 있는 행동을 필요로 한다.

따라서 지능은 하나의 알고리즘(algorithm), 모델 아키텍처(model architecture), 벤치마크 점수(benchmark score), 또는 특정 인지 기능(cognitive faculty)으로 축소해서 이해해서는 안 된다. 지능은 지각, 표상, 기억, 학습, 추론, 예측, 계획, 행동, 자기 모니터링(self-monitoring)이 서로 조정되어 발생하는 통합적 능력(integrated capability)으로 이해하는 것이 적절하다. 보다 넓은 AGI 구조가 기초 이론에서 핵심 메커니즘, 인지 아키텍처(cognitive architecture), 엔지니어링, 평가, 현실 세계의 작동, 그리고 통합 지능형 에이전트(unified intelligent agent)로 발전하는 것도 이러한 시스템적 관점(system perspective)을 반영한다.

인간 지능(Human Intelligence)은 이러한 능력들이 서로 다른 시간 규모(timescale)에서 작동할 수 있음을 보여준다. 빠른 지각 및 습관적 처리(habitual processing)는 익숙한 상황을 효율적으로 처리하는 반면, 새로움, 모호성, 충돌 또는 위험이 증가하면 보다 느린 추론 과정이 활성화될 수 있다. 기억은 과거 경험을 제공하고, 주의(attention)는 제한된 계산 자원을 배분하며, 메타인지(metacognition)는 불확실성이나 오류를 평가할 수 있다. 따라서 일반지능은 모든 상황을 동일하게 처리하기보다 계산 자원을 동적으로 할당(dynamic allocation of computation)하는 능력을 필요로 할 수 있다.

전이(Transfer)는 일반지능 시스템이 모든 작업을 처음부터 다시 학습하는 대신 기존 지식을 재사용해야 한다는 점에서 특히 중요하다. 한 영역에서 학습된 개념, 기술, 인과관계, 전략, 표상은 다른 영역에서도 유용한 구조를 제공할 수 있어야 한다. 성공적인 전이를 위해서는 과거 경험 가운데 어떤 요소가 불변(invariant)으로 유지되는지와 어떤 요소가 새로운 상황에 맞게 적응되어야 하는지를 구분해야 한다. 이러한 능력은 축적된 경험을 미래의 학습을 더욱 효율적으로 만드는 재사용 가능한 기반으로 전환한다.

또 다른 핵심 특성은 조합성(Compositionality)이다. 지능적인 시스템은 단순한 개념과 기술을 결합하여 복잡한 해결책을 구성할 수 있다. 객체, 공간, 인과성, 언어, 도구, 사회적 행동, 물리적 동역학에 대한 지식을 현재 문제에 맞게 재구성할 수 있다. 이러한 재조합 능력은 가능한 모든 조합을 명시적으로 학습하지 않고도 에이전트가 처리할 수 있는 상황의 범위를 크게 확장하므로, 조합적 표상(compositional representation)은 확장 가능한 일반지능에 특히 중요하다.

메타인지(Metacognition)는 에이전트 자신의 인지 과정(cognitive process)에 대해 추론하는 능력을 추가한다. 지능적인 시스템은 자신이 어떤 정보를 알고 있는지를 평가하고, 불확실성을 인식하며, 모순을 탐지하고, 계획의 품질을 평가하거나, 추가 정보가 필요하다고 판단할 수 있다. 이를 통해 추론 과정 자체가 모니터링과 조정의 대상이 되는 피드백 루프(feedback loop)가 형성된다. AGI에서 이러한 메커니즘은 성찰(reflection), 오류 수정(error correction), 전략 선택(strategy selection), 지속학습(continual learning), 궁극적으로는 통제된 자기개선(controlled self-improvement)을 지원할 수 있다.

따라서 지능은 시스템이 가지고 있거나 가지고 있지 않은 이분법적인 속성(binary property)이라기보다 적응적 역량(adaptive competence)의 연속체(continuum)로 보는 것이 적절하다. 서로 다른 에이전트는 기억, 추론, 창의성(creativity), 전이, 자율성(autonomy), 사회적 이해(social understanding), 물리적 능력(physical competence)을 서로 다른 조합으로 나타낼 수 있다. AGI 연구는 이러한 능력들이 하나의 시스템으로 통합되어, 세밀하게 제한된 특정 영역이 아니라 충분히 광범위한 작업과 환경에서도 효과적인 역량을 유지할 수 있는지를 탐구한다.

따라서 엔지니어링 과제(engineering challenge)는 개별 구성요소(component)를 단순히 더욱 강력하게 만드는 것만이 아니다. 일반지능 에이전트는 지속적인 피드백을 통해 지각, 기억, 지식, 추론, 계획, 학습, 행동을 서로 조정해야 한다. 지각을 통해 발견된 정보는 표상을 갱신해야 하고, 표상은 예측을 지원해야 하며, 예측은 계획을 안내해야 한다. 행동은 이러한 계획을 현실에서 시험하고, 그 결과로 얻어진 새로운 관찰은 다시 미래의 행동을 수정해야 한다. 지능은 특정한 하나의 모델뿐 아니라 이러한 폐쇄형 적응 순환(closed adaptive loop) 전체에서 출현한다.

궁극적으로 지능(Intelligence)은 유용한 세계 모델을 구축하고, 상호작용으로부터 학습하며, 서로 다른 맥락 사이에서 지식을 전이하고, 불확실성 속에서 추론하며, 행동의 결과를 예측하고, 목표를 추구하며, 현실이 예상과 다를 때 지속적으로 행동을 적응시키는 능력으로 정의할 수 있다. 이러한 광범위한 지능의 개념은 AGI 연구의 개념적 기반을 제공하며, 이후에는 인간지능과 인공지능(human vs. artificial intelligence), 일반화, 추론, 학습, 체화, 월드 모델, 지식, 표상, 그리고 이들을 하나의 시스템으로 통합하는 방법을 각각 구체적으로 다룰 수 있다.

##  

## 01.01. Human vs Artificial Intelligence

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

Human intelligence emerges from biological systems shaped by evolution, development, embodiment, social interaction, and continuous experience. Artificial intelligence is engineered through computational architectures, algorithms, data, optimization, and explicitly designed objectives. Both can perceive information, learn patterns, solve problems, and select actions, yet the mechanisms producing these abilities differ fundamentally in origin, organization, constraints, and interaction with the world.

The human brain operates as a massively parallel biological network whose cognition is inseparable from perception, memory, emotion, motivation, bodily regulation, and action. Human learning occurs continuously while an individual interacts with physical and social environments. Artificial intelligence typically separates these functions into computational components such as perception models, memory systems, reasoning modules, planners, policies, and external tools that engineers integrate into a larger architecture.

Humans demonstrate remarkable generalization from relatively limited experience. A person can learn a concept in one context, recognize analogous structures elsewhere, and combine previous knowledge to address unfamiliar situations. Modern AI can also generalize, especially after large-scale pretraining, but its reliability often depends strongly on the distribution represented by training data. Out-of-distribution situations can reveal brittle assumptions that were hidden during conventional evaluation.

Artificial intelligence has important advantages in computational scale. Machines can process enormous datasets, perform numerical operations at high speed, replicate learned parameters precisely, search large spaces, and communicate digital information without the biological limitations of human memory. Once trained, a model can often be duplicated across thousands of machines. Human knowledge, by contrast, must usually be transferred indirectly through language, demonstration, education, imitation, and cultural artifacts.

Human intelligence has advantages in adaptive integration. Perception, commonsense knowledge, physical experience, goals, social understanding, and contextual reasoning interact continuously. Humans routinely interpret incomplete situations using background knowledge that may never have been explicitly taught. Artificial systems often require carefully constructed representations, training distributions, prompts, retrieval mechanisms, tools, or environmental feedback to achieve comparable contextual flexibility across substantially different tasks.

Embodiment represents another major difference. Human cognition develops through a body that moves, senses, acts, experiences consequences, and maintains biological needs. Concepts such as distance, force, danger, balance, ownership, cooperation, and causality become connected to physical and social experience. Artificial intelligence may operate entirely in digital environments or become embodied through robots, autonomous vehicles, drones, sensors, and actuators, creating different forms of grounding and experience.

Human learning combines many learning paradigms naturally. People learn from direct instruction, observation, imitation, exploration, rewards, mistakes, language, social feedback, and self-generated goals without treating these mechanisms as completely separate systems. Artificial intelligence historically divides learning into supervised, unsupervised, self-supervised, reinforcement, imitation, and other paradigms. AGI research increasingly seeks architectures capable of combining these modes within persistent learning processes.

Memory also differs substantially. Human memory is reconstructive, selective, associative, and imperfect. Forgetting can remove details while preserving concepts and meaningful relationships. Artificial systems can store exact digital information, but possessing stored information does not guarantee intelligent retrieval or understanding. AGI therefore requires mechanisms that decide what information matters, how it should be represented, when it should be retrieved, and how retrieved knowledge should influence reasoning and action.

Humans reason with a mixture of deliberate and intuitive processes. Familiar situations may trigger rapid judgments, while unfamiliar or difficult problems can recruit slower analysis, mental simulation, comparison, and planning. Artificial intelligence similarly benefits from adaptive computation rather than applying maximum processing to every observation. Future general systems may allocate reasoning depth, memory retrieval, simulation, and planning according to novelty, uncertainty, risk, and expected value.

Energy efficiency reveals another striking contrast. The human brain performs perception, learning, control, memory, and reasoning with comparatively modest biological power consumption. Large artificial models may require substantial computational infrastructure during training and inference. AI nevertheless offers engineering advantages because computation can be specialized, distributed, accelerated, compressed, or selectively activated. Efficient intelligence therefore concerns not only capability but the allocation of computational resources according to task demands.

Humans possess strong commonsense expectations about objects, agents, space, time, intentions, and everyday causality. Much of this knowledge is accumulated through years of interaction and cultural learning rather than explicit formal instruction. Artificial systems can acquire extensive statistical and factual knowledge from large datasets, but statistical association does not automatically provide reliable causal understanding. Robust intelligence must distinguish correlation, prediction, intervention, and consequence when circumstances change.

Language highlights both similarities and differences. Humans use language as one component of a broader cognitive system grounded in perception, action, memory, social relationships, and shared environments. Large language models can acquire powerful linguistic representations from enormous text corpora and demonstrate reasoning-like capabilities through language. However, language competence alone does not guarantee persistent goals, grounded world understanding, autonomous learning, long-term memory, or reliable physical interaction.

Human intelligence is deeply social. People infer intentions, cooperate, compete, teach, imitate, negotiate, follow norms, and construct shared knowledge. Intelligence therefore develops within communities rather than exclusively inside individual brains. Artificial intelligence is increasingly entering similar multi-agent contexts through human-AI collaboration, AI agents, robotic teams, and interacting software systems. General intelligence may consequently require models of other agents as well as models of the physical environment.

Artificial intelligence differs from humans in reproducibility and scalability. Human cognitive abilities vary between individuals and cannot be copied exactly, whereas trained artificial models can be replicated and deployed across different hardware platforms. Multiple artificial agents may also share databases, models, tools, and retrieved information almost instantaneously. This creates the possibility of collective machine intelligence whose information-sharing mechanisms operate differently from biological societies.

Humans remain highly capable when goals are ambiguous. They can negotiate objectives, reinterpret instructions, infer unstated intentions, and abandon inappropriate plans when circumstances change. Artificial systems are often more dependent on the quality of their objective functions, prompts, reward signals, policies, or system constraints. A major AGI challenge is therefore developing agents that can reason about goals themselves rather than merely optimizing a fixed objective supplied externally.

Another difference concerns continual learning. Humans normally acquire new knowledge throughout life without repeatedly retraining the entire brain from a static dataset. New experiences modify existing knowledge while much previous competence remains available. Artificial neural systems can suffer catastrophic forgetting or require carefully managed updates. Continual learning for AGI must preserve useful knowledge while integrating new information, adapting to distribution changes, and correcting previously learned misconceptions.

Creativity demonstrates that intelligence involves more than reproduction of prior experience. Humans generate new explanations, tools, stories, strategies, designs, and scientific hypotheses by recombining existing concepts under new constraints. Generative AI can similarly produce novel combinations across text, images, code, and other representations. The deeper challenge is connecting generation with evaluation, experimentation, causal understanding, long-term objectives, and real-world feedback so that novelty becomes purposeful innovation.

Metacognition is another important capability. Humans can recognize confusion, estimate confidence, reconsider assumptions, seek assistance, and change strategies when progress fails. Artificial systems increasingly incorporate reflection, uncertainty estimation, verification, critique, and iterative reasoning mechanisms. For AGI, metacognition may become a control layer that determines when an agent should continue reasoning, retrieve knowledge, invoke tools, simulate alternatives, request assistance, or revise its internal model.

Neither human nor artificial intelligence should be treated as a single scalar quantity. Humans display uneven combinations of linguistic, spatial, mathematical, social, motor, creative, and practical abilities. Artificial systems also exhibit capability profiles that vary across domains. Comparing intelligence therefore requires examining generalization, adaptability, sample efficiency, reasoning, memory, autonomy, robustness, embodiment, social interaction, computational cost, and the range of environments in which competence remains effective.

The most productive path toward AGI may not require reproducing the human brain exactly. Biological intelligence provides important principles such as continual learning, hierarchical processing, predictive modeling, selective attention, memory consolidation, adaptive computation, embodiment, and perception-action feedback. Artificial systems can combine these principles with capabilities unavailable to biology, including exact digital memory, high-speed computation, global communication, scalable simulation, and large external knowledge stores.

Human and artificial intelligence can therefore be viewed as different implementations of adaptive information processing rather than as simple competitors on a single scale. Humans provide a demonstrated example of broadly capable embodied intelligence, while AI explores alternative computational mechanisms capable of exceeding biological limitations in selected dimensions. AGI research seeks to understand which principles are essential for general competence and which are merely consequences of biological implementation.

Ultimately, the comparison reveals that general intelligence depends less on matching humans' component by component than on integrating capabilities into a coherent adaptive agent. Such a system must perceive, remember, learn, generalize, reason, plan, act, communicate, manage uncertainty, and revise its behavior through experience. Understanding the complementary strengths and limitations of human and artificial intelligence therefore provides a foundation for designing systems that move from specialized AI toward increasingly general intelligence.

인간 지능(Human Intelligence)은 진화(evolution), 발달(development), 체화(embodiment), 사회적 상호작용(social interaction), 지속적인 경험에 의해 형성된 생물학적 시스템(biological system)에서 출현한다. 인공지능(Artificial Intelligence)은 계산 아키텍처(computational architecture), 알고리즘(algorithm), 데이터(data), 최적화(optimization), 명시적으로 설계된 목표를 통해 공학적으로 만들어진다. 둘 모두 정보를 지각하고, 패턴을 학습하며, 문제를 해결하고, 행동을 선택할 수 있지만 이러한 능력을 만들어내는 메커니즘은 기원, 구성, 제약조건, 세계와의 상호작용 측면에서 근본적인 차이를 가진다.

인간의 뇌(human brain)는 대규모 병렬 생물학적 네트워크(massively parallel biological network)로 작동하며, 인간의 인지는 지각(perception), 기억(memory), 감정(emotion), 동기(motivation), 신체 조절(bodily regulation), 행동(action)과 분리될 수 없다. 인간의 학습은 개인이 물리적·사회적 환경과 상호작용하는 동안 지속적으로 이루어진다. 반면 인공지능은 일반적으로 이러한 기능을 지각 모델, 기억 시스템, 추론 모듈, 계획기(planner), 정책(policy), 외부 도구와 같은 계산 구성요소로 분리하고, 엔지니어가 이를 더 큰 아키텍처로 통합한다.

인간은 비교적 제한된 경험으로부터 뛰어난 일반화(Generalization) 능력을 보여준다. 사람은 한 맥락에서 개념을 학습한 후 다른 영역에서 유사한 구조를 인식하고, 기존 지식을 결합하여 익숙하지 않은 상황을 해결할 수 있다. 현대 AI 역시 특히 대규모 사전학습(large-scale pretraining)을 통해 일반화할 수 있지만, 그 신뢰성은 학습 데이터가 표현하는 분포(distribution)에 크게 의존하는 경우가 많다. 분포 외 상황(out-of-distribution situation)은 기존 평가에서는 드러나지 않았던 취약한 가정을 노출할 수 있다.

인공지능은 계산 규모(computational scale)에서 중요한 장점을 가진다. 기계는 방대한 데이터셋을 처리하고, 수치 연산을 고속으로 수행하며, 학습된 매개변수(parameter)를 정확하게 복제하고, 거대한 탐색 공간을 조사하며, 인간 기억의 생물학적 한계 없이 디지털 정보를 전달할 수 있다. 한번 학습된 모델은 수천 대의 기계에 복제될 수도 있다. 반면 인간의 지식은 일반적으로 언어, 시범(demonstration), 교육, 모방(imitation), 문화적 산출물(cultural artifact)을 통해 간접적으로 전달되어야 한다.

인간 지능은 적응적 통합(adaptive integration)에서 강점을 가진다. 지각, 상식적 지식(commonsense knowledge), 물리적 경험, 목표, 사회적 이해, 맥락적 추론(contextual reasoning)이 지속적으로 상호작용한다. 인간은 명시적으로 학습하지 않은 배경지식을 활용하여 불완전한 상황을 일상적으로 해석한다. 반면 인공지능 시스템은 서로 크게 다른 작업에서 유사한 맥락적 유연성(contextual flexibility)을 확보하기 위해 정교하게 구성된 표상(representation), 학습 분포, 프롬프트(prompt), 검색 메커니즘(retrieval mechanism), 도구 또는 환경 피드백을 필요로 하는 경우가 많다.

체화(Embodiment)는 또 다른 중요한 차이를 나타낸다. 인간의 인지는 움직이고, 감각하고, 행동하며, 결과를 경험하고, 생물학적 필요를 유지하는 신체를 통해 발달한다. 거리, 힘, 위험, 균형, 소유, 협력, 인과성(causality)과 같은 개념은 물리적·사회적 경험과 연결된다. 인공지능은 완전히 디지털 환경에서 작동할 수도 있고, 로봇, 자율주행차, 드론, 센서, 액추에이터(actuator)를 통해 체화되어 서로 다른 형태의 접지(grounding)와 경험을 형성할 수도 있다.

인간의 학습은 다양한 학습 패러다임(learning paradigm)을 자연스럽게 결합한다. 사람은 직접적인 교육, 관찰, 모방, 탐색, 보상, 실수, 언어, 사회적 피드백, 스스로 생성한 목표를 통해 학습하며, 이러한 메커니즘을 완전히 분리된 시스템으로 취급하지 않는다. 인공지능은 역사적으로 학습을 지도학습(supervised learning), 비지도학습(unsupervised learning), 자기지도학습(self-supervised learning), 강화학습(reinforcement learning), 모방학습(imitation learning) 등으로 구분해 왔다. AGI 연구에서는 이러한 방식을 지속적인 학습 과정 안에서 결합할 수 있는 아키텍처를 점차 추구하고 있다.

기억(Memory) 역시 상당한 차이가 있다. 인간의 기억은 재구성적(reconstructive)이고 선택적이며 연상적(associative)이고 불완전하다. 망각(forgetting)은 세부 정보를 제거하면서도 개념과 의미 있는 관계를 보존할 수 있다. 인공 시스템은 정확한 디지털 정보를 저장할 수 있지만, 정보를 저장하고 있다는 사실 자체가 지능적인 검색이나 이해를 보장하지 않는다. 따라서 AGI는 어떤 정보가 중요한지, 어떻게 표현해야 하는지, 언제 검색해야 하는지, 검색된 지식이 추론과 행동에 어떻게 영향을 미쳐야 하는지를 결정하는 메커니즘을 필요로 한다.

인간은 숙고적 과정(deliberate process)과 직관적 과정(intuitive process)을 혼합하여 추론한다. 익숙한 상황에서는 빠른 판단이 이루어질 수 있지만, 익숙하지 않거나 어려운 문제에서는 더 느린 분석, 정신적 시뮬레이션(mental simulation), 비교, 계획이 활성화될 수 있다. 인공지능 역시 모든 관찰에 최대 수준의 처리를 적용하기보다 적응적 계산(adaptive computation)을 활용함으로써 이점을 얻을 수 있다. 미래의 일반지능 시스템은 새로움(novelty), 불확실성, 위험, 기대가치(expected value)에 따라 추론 깊이, 기억 검색, 시뮬레이션, 계획에 필요한 계산 자원을 동적으로 할당할 수 있다.

에너지 효율(Energy Efficiency)은 또 하나의 두드러진 차이를 보여준다. 인간의 뇌는 비교적 적은 생물학적 전력 소비로 지각, 학습, 제어, 기억, 추론을 수행한다. 대규모 인공지능 모델은 학습과 추론 과정에서 상당한 계산 인프라를 요구할 수 있다. 그러나 AI는 계산을 특화하고, 분산시키고, 가속하며, 압축하거나 선택적으로 활성화할 수 있다는 공학적 장점을 가진다. 따라서 효율적인 지능은 단순한 능력뿐만 아니라 작업 요구조건에 따라 계산 자원을 어떻게 배분하는가와도 관련된다.

인간은 객체, 에이전트, 공간, 시간, 의도, 일상적인 인과관계에 대해 강력한 상식적 기대(commonsense expectation)를 가지고 있다. 이러한 지식의 상당 부분은 명시적인 공식 교육보다는 수년에 걸친 상호작용과 문화적 학습을 통해 축적된다. 인공 시스템은 대규모 데이터셋에서 방대한 통계적·사실적 지식을 획득할 수 있지만, 통계적 연관성(statistical association)이 자동으로 신뢰할 수 있는 인과적 이해(causal understanding)를 제공하는 것은 아니다. 강건한 지능(robust intelligence)은 상황이 변화할 때 상관관계, 예측, 개입(intervention), 결과를 구분할 수 있어야 한다.

언어(Language)는 인간과 인공지능 사이의 유사점과 차이점을 동시에 보여준다. 인간은 언어를 지각, 행동, 기억, 사회적 관계, 공유된 환경에 기반을 둔 더 광범위한 인지 시스템의 한 구성요소로 사용한다. 대규모 언어 모델(Large Language Model)은 방대한 텍스트 말뭉치(text corpus)에서 강력한 언어 표상을 획득하고 언어를 통해 추론과 유사한 능력을 보여줄 수 있다. 그러나 언어 능력만으로 지속적인 목표, 세계에 대한 접지된 이해, 자율학습, 장기기억, 신뢰할 수 있는 물리적 상호작용이 보장되는 것은 아니다.

인간 지능은 본질적으로 사회적이다. 사람은 다른 사람의 의도를 추론하고, 협력하고, 경쟁하고, 가르치고, 모방하며, 협상하고, 규범(norm)을 따르고, 공유 지식을 구축한다. 따라서 지능은 개별적인 뇌 내부에서만 발달하는 것이 아니라 공동체(community) 안에서도 발전한다. 인공지능 역시 인간-AI 협업(human-AI collaboration), AI 에이전트, 로봇 팀, 상호작용하는 소프트웨어 시스템을 통해 이와 유사한 다중 에이전트 맥락(multi-agent context)으로 진입하고 있다. 따라서 일반지능은 물리적 환경의 모델뿐 아니라 다른 에이전트에 대한 모델도 필요로 할 수 있다.

인공지능은 재현성(reproducibility)과 확장성(scalability) 측면에서 인간과 차이가 있다. 인간의 인지 능력은 개인마다 다르며 정확하게 복제할 수 없는 반면, 학습된 인공지능 모델은 복제하여 서로 다른 하드웨어 플랫폼에 배포할 수 있다. 여러 인공 에이전트는 데이터베이스, 모델, 도구, 검색된 정보를 거의 즉각적으로 공유할 수도 있다. 이는 생물학적 사회와는 다른 정보 공유 메커니즘을 사용하는 집단 기계지능(collective machine intelligence)의 가능성을 만들어낸다.

인간은 목표가 모호한 상황에서도 높은 능력을 발휘한다. 목표를 협상하고, 지시를 재해석하며, 명시되지 않은 의도를 추론하고, 상황이 변화하면 부적절한 계획을 포기할 수 있다. 반면 인공 시스템은 목표함수(objective function), 프롬프트, 보상 신호(reward signal), 정책 또는 시스템 제약조건의 품질에 더 크게 의존하는 경우가 많다. 따라서 AGI의 주요 과제 가운데 하나는 외부에서 주어진 고정된 목표를 단순히 최적화하는 것을 넘어 목표 자체에 대해 추론할 수 있는 에이전트를 개발하는 것이다.

또 다른 차이는 지속학습(Continual Learning)과 관련된다. 인간은 일반적으로 정적인 데이터셋을 이용해 뇌 전체를 반복적으로 재학습하지 않고도 평생 새로운 지식을 습득한다. 새로운 경험은 기존 지식을 수정하지만 과거에 획득한 대부분의 능력은 계속 유지된다. 반면 인공 신경망 시스템은 파국적 망각(catastrophic forgetting)을 겪거나 세심하게 관리된 업데이트를 필요로 할 수 있다. AGI의 지속학습은 유용한 지식을 보존하면서 새로운 정보를 통합하고, 분포 변화에 적응하며, 기존에 잘못 학습된 개념을 수정할 수 있어야 한다.

창의성(Creativity)은 지능이 과거 경험을 단순히 재생하는 것 이상의 능력임을 보여준다. 인간은 기존 개념을 새로운 제약조건 아래에서 재조합함으로써 새로운 설명, 도구, 이야기, 전략, 설계, 과학적 가설을 만들어낸다. 생성형 AI(Generative AI) 역시 텍스트, 이미지, 코드 및 다양한 표상에서 새로운 조합을 생성할 수 있다. 더 깊은 과제는 생성을 평가, 실험, 인과적 이해, 장기 목표, 현실 세계의 피드백과 연결하여 새로움이 목적을 가진 혁신(purposeful innovation)으로 이어지도록 만드는 것이다.

메타인지(Metacognition)는 또 다른 중요한 능력이다. 인간은 자신의 혼란을 인식하고, 확신 정도를 평가하며, 기존 가정을 재검토하고, 도움을 요청하고, 진행이 실패하면 전략을 변경할 수 있다. 인공지능 시스템 역시 점차 성찰(reflection), 불확실성 추정(uncertainty estimation), 검증(verification), 비평(critique), 반복적 추론(iterative reasoning) 메커니즘을 통합하고 있다. AGI에서 메타인지는 에이전트가 언제 추론을 계속하고, 지식을 검색하고, 도구를 호출하며, 대안을 시뮬레이션하고, 도움을 요청하거나 내부 모델을 수정할지를 결정하는 제어 계층(control layer)이 될 수 있다.

인간 지능과 인공지능 어느 쪽도 하나의 단일한 수치(scalar quantity)로 취급해서는 안 된다. 인간은 언어적, 공간적, 수학적, 사회적, 운동적, 창의적, 실용적 능력의 불균등한 조합을 보여준다. 인공 시스템 역시 영역마다 서로 다른 능력 프로파일(capability profile)을 나타낸다. 따라서 지능을 비교하려면 일반화, 적응성(adaptability), 표본 효율(sample efficiency), 추론, 기억, 자율성, 강건성(robustness), 체화, 사회적 상호작용, 계산 비용, 그리고 능력이 효과적으로 유지되는 환경의 범위를 함께 살펴보아야 한다.

AGI를 향한 가장 생산적인 접근은 인간의 뇌를 정확하게 복제하는 것만을 요구하지 않을 수 있다. 생물학적 지능은 지속학습, 계층적 처리(hierarchical processing), 예측 모델링(predictive modeling), 선택적 주의(selective attention), 기억 공고화(memory consolidation), 적응적 계산, 체화, 지각-행동 피드백(perception-action feedback)과 같은 중요한 원리를 제공한다. 인공 시스템은 이러한 원리를 정확한 디지털 기억, 고속 계산, 전역적 통신(global communication), 확장 가능한 시뮬레이션, 대규모 외부 지식 저장소와 같이 생물학에서는 이용하기 어려운 능력과 결합할 수 있다.

따라서 인간 지능과 인공지능은 하나의 척도에서 경쟁하는 단순한 경쟁자가 아니라 적응적 정보처리(adaptive information processing)를 구현하는 서로 다른 방식으로 이해할 수 있다. 인간은 광범위한 능력을 가진 체화 지능(embodied intelligence)의 실제 사례를 제공하며, AI는 특정 차원에서 생물학적 한계를 넘어설 수 있는 대안적인 계산 메커니즘을 탐구한다. AGI 연구는 일반적인 능력을 위해 어떤 원리가 본질적으로 필요한지, 그리고 어떤 특성이 단지 생물학적 구현(biological implementation)의 결과인지를 이해하려고 한다.

궁극적으로 이러한 비교는 일반지능이 인간의 각 구성요소를 하나씩 그대로 재현하는 것보다 다양한 능력을 하나의 일관된 적응형 에이전트(coherent adaptive agent)로 통합하는 데 더 크게 의존한다는 점을 보여준다. 이러한 시스템은 지각하고, 기억하고, 학습하고, 일반화하며, 추론하고, 계획하고, 행동하고, 의사소통하며, 불확실성을 관리하고, 경험을 통해 자신의 행동을 수정할 수 있어야 한다. 따라서 인간 지능과 인공지능의 상호보완적인 강점과 한계를 이해하는 것은 특화된 AI(specialized AI)에서 점차 일반적인 지능(general intelligence)으로 발전하는 시스템을 설계하기 위한 중요한 기반을 제공한다.

##  

## 01.02. Generalization and Transfer

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

Generalization is the ability of an intelligent system to apply knowledge learned from previous experience to situations that were not encountered during training. A system that merely memorizes examples may perform well on familiar data but fail when conditions change. General intelligence therefore requires representations that capture reusable structures, relationships, and principles rather than reproducing specific observations.

Transfer extends this idea by allowing knowledge acquired in one task, environment, or domain to improve learning or performance in another. The transferred knowledge may include perceptual features, concepts, causal relationships, skills, strategies, policies, or abstract representations. Effective transfer reduces the need to learn every new problem from the beginning and transforms accumulated experience into a reusable resource for future intelligence.

Generalization and transfer are closely related but describe different aspects of adaptive intelligence. Generalization concerns whether learned knowledge remains valid beyond the examples from which it was acquired, while transfer concerns whether knowledge developed for one problem can contribute to solving another. Together they determine how effectively an intelligent agent can expand its competence as tasks, environments, and objectives change.

Machine learning traditionally evaluates generalization by separating training data from validation and test data. A model learns patterns from training examples and is expected to perform accurately on unseen samples drawn from a similar distribution. This form of generalization is essential, but AGI requires a broader capability because real environments frequently contain situations that differ substantially from the distributions represented during training.

Distribution shift occurs when the statistical properties of the operating environment differ from those encountered during learning. Changes may appear in sensors, objects, backgrounds, behaviors, goals, physical conditions, or relationships among variables. A robust intelligent system must determine which learned structures remain reliable and which assumptions should be revised rather than blindly applying previously successful patterns to a changed world.

Out-of-distribution generalization addresses this challenge more directly. Instead of assuming that future observations resemble training examples, the agent must handle novel combinations, unfamiliar contexts, and previously unseen conditions. This requires representations that separate essential structure from incidental correlations. Learning invariant relationships can therefore be more valuable for general intelligence than simply improving accuracy within a narrowly defined dataset.

Humans demonstrate powerful forms of generalization through abstraction. After encountering several examples, people can often extract concepts that apply to many different situations. Understanding the concept of a container, obstacle, tool, ownership, or cause does not require memorizing every possible instance. Abstract concepts compress experience into reusable structures, enabling reasoning about situations that differ significantly in their superficial appearance.

Compositionality strengthens this capability by allowing previously learned components to be recombined. An agent that separately understands objects, spatial relationships, actions, goals, and consequences can potentially construct representations of situations it has never observed exactly before. Instead of storing every possible configuration, intelligence can generate new combinations from reusable components, dramatically expanding the range of situations that can be handled.

Transfer learning provides a practical implementation of knowledge reuse in artificial intelligence. A model trained on a large source dataset can provide representations that are adapted to a smaller target task through fine-tuning or related methods. The transferred representation provides a useful starting point, reducing training requirements and often improving performance when target-domain data are limited. Large pretrained models demonstrate the scalability of this principle.

Positive transfer occurs when previous knowledge improves performance on a new task, but transfer is not always beneficial. Negative transfer can occur when inappropriate assumptions from the source domain interfere with learning in the target domain. General intelligence therefore requires more than simply reusing everything previously learned. An agent must estimate the relevance of prior knowledge and selectively preserve, modify, combine, or reject it according to the new context.

Few-shot and zero-shot capabilities represent important manifestations of generalization and transfer. Few-shot learning attempts to solve new problems from a small number of examples, while zero-shot behavior relies on existing representations and instructions without task-specific examples. These abilities are important for AGI because an agent operating in an open world cannot expect extensive labeled training data for every situation it may eventually encounter.

Meta-learning approaches the problem at a higher level by attempting to learn how to learn. Instead of optimizing only for performance on one fixed task, a meta-learning system extracts strategies that allow faster adaptation across families of tasks. Previous learning episodes become information about how future learning should occur. This can improve sample efficiency and help transform repeated adaptation into increasingly effective general learning behavior.

Continual learning connects transfer with time. An intelligent agent encounters a sequence of tasks and experiences rather than one static training dataset. New knowledge should extend existing competence without unnecessarily destroying previously useful capabilities. This creates the stability-plasticity problem: the system must remain plastic enough to learn new information while remaining stable enough to preserve valuable representations, skills, and memories.

Catastrophic forgetting illustrates the difficulty of this requirement in artificial neural systems. Updating a model for new tasks can modify parameters that supported earlier capabilities, causing previously learned knowledge to degrade. Continual intelligence therefore benefits from mechanisms such as memory replay, modular representations, parameter protection, knowledge consolidation, retrieval, and selective adaptation that preserve useful competence while incorporating new experience.

Representation learning is central to both generalization and transfer because the structure of internal representations determines what can be reused. Representations tied too closely to surface details may fail when appearance changes, while representations capturing objects, relationships, dynamics, semantics, or causal structure can remain useful across broader conditions. Good representations separate information that should remain stable from information that should adapt.

Causal knowledge can support particularly strong forms of transfer. Statistical correlations may disappear when environments change, but underlying causal mechanisms can remain stable across many conditions. An agent that understands how actions influence states and how variables affect one another can reason about interventions rather than merely extrapolating observed patterns. Causal representation is therefore closely connected to robust generalization and adaptable world models.

World models provide another mechanism for transferring structured knowledge. A world model can encode entities, states, relationships, dynamics, and possible transitions independently of a single immediate task. Different goals can then reuse the same underlying model for prediction, planning, simulation, and control. Instead of learning a completely separate policy for every objective, an agent can combine shared environmental knowledge with task-specific goals.

Embodied intelligence makes transfer especially challenging because physical environments contain continuous variation. Lighting, terrain, friction, object position, sensor noise, payload, weather, human behavior, and mechanical conditions may differ from previous experience. A robot that succeeds only under conditions closely matching its training environment has limited intelligence. General robotic intelligence requires robust perception and action across meaningful variations of the physical world.

Sim-to-real transfer illustrates this problem in robotics. Policies or models can be trained efficiently in simulation, but the simulated environment never perfectly reproduces physical reality. Differences in dynamics, sensors, materials, latency, and environmental complexity create a reality gap. Domain randomization, adaptation, robust representation learning, system identification, and real-world feedback can help transfer knowledge from simulated experience to physical operation.

Multimodal learning can improve generalization by connecting information across different forms of observation. Language can describe concepts that appear visually, actions can reveal physical properties, and sensory feedback can ground symbolic descriptions in interaction. When multiple modalities share representations, knowledge acquired through one modality may support another. Such cross-modal transfer can help create more coherent and reusable internal models of the world.

Language provides an especially powerful interface for transfer because instructions can specify new tasks without requiring complete retraining. A sufficiently capable agent may reuse existing perceptual, reasoning, and action skills while language defines a new objective or constraint. This changes task learning from parameter modification toward contextual adaptation, where previously acquired capabilities are dynamically composed according to descriptions of the current problem.

Generalization must also include goals and strategies rather than only perceptual recognition. An intelligent agent should recognize that a planning principle, exploration strategy, safety constraint, or problem-solving method learned in one context may remain useful elsewhere. Transfer at this level requires abstraction over tasks themselves, allowing the agent to identify common structures among apparently different problems and reuse previously successful reasoning procedures.

Evaluation of generalization should consequently extend beyond random test splits. Systems intended for general intelligence should be examined under novel tasks, distribution shifts, new combinations, changing environments, limited examples, long-term learning, and unexpected conditions. Evaluation should measure not only whether performance decreases, but whether the system can recognize uncertainty, adapt efficiently, recover competence, and preserve previously acquired knowledge.

Generalization and transfer ultimately determine whether intelligence accumulates or repeatedly starts over. A generally intelligent agent should transform experience into increasingly reusable representations, models, skills, and strategies. It should recognize what remains invariant, adapt what has changed, combine previous knowledge in new ways, and learn efficiently when existing knowledge is insufficient. These abilities form a central bridge between specialized task performance and AGI.

일반화(Generalization)는 지능적인 시스템이 이전 경험에서 학습한 지식을 학습 과정에서 직접 접하지 않았던 상황에도 적용할 수 있는 능력이다. 단순히 사례를 암기하는 시스템은 익숙한 데이터에서는 높은 성능을 보일 수 있지만 조건이 변하면 실패할 수 있다. 따라서 일반지능(general intelligence)은 특정 관찰을 그대로 재현하는 것이 아니라 재사용 가능한 구조, 관계, 원리를 포착하는 표상(representation)을 필요로 한다.

전이(Transfer)는 한 작업, 환경 또는 영역에서 획득한 지식이 다른 작업의 학습이나 성능을 향상시키도록 함으로써 이러한 개념을 확장한다. 전이되는 지식에는 지각 특징(perceptual feature), 개념, 인과관계, 기술, 전략, 정책(policy), 추상적 표상(abstract representation) 등이 포함될 수 있다. 효과적인 전이는 새로운 문제를 매번 처음부터 학습해야 하는 필요를 줄이고, 축적된 경험을 미래 지능을 위한 재사용 가능한 자원으로 변환한다.

일반화와 전이는 서로 밀접하게 관련되지만 적응 지능(adaptive intelligence)의 서로 다른 측면을 설명한다. 일반화는 학습된 지식이 그것을 습득한 사례를 넘어 여전히 유효한지를 다루고, 전이는 한 문제를 위해 개발된 지식이 다른 문제 해결에 기여할 수 있는지를 다룬다. 두 능력은 작업, 환경, 목표가 변화할 때 지능적인 에이전트가 자신의 역량을 얼마나 효과적으로 확장할 수 있는지를 결정한다.

기계학습(Machine Learning)은 전통적으로 학습 데이터(training data), 검증 데이터(validation data), 테스트 데이터(test data)를 분리하여 일반화를 평가해 왔다. 모델은 학습 사례에서 패턴을 학습한 뒤 유사한 분포에서 추출된 보지 못한 샘플에 대해 정확한 성능을 보여야 한다. 이러한 형태의 일반화는 필수적이지만, 실제 환경에는 학습 시 표현된 분포와 크게 다른 상황이 자주 등장하기 때문에 AGI에는 더 폭넓은 능력이 요구된다.

분포 변화(Distribution Shift)는 운영 환경의 통계적 특성이 학습 과정에서 경험한 특성과 달라지는 현상을 의미한다. 이러한 변화는 센서, 객체, 배경, 행동, 목표, 물리적 조건 또는 변수들 사이의 관계에서 나타날 수 있다. 강건한 지능 시스템(robust intelligent system)은 과거에 성공했던 패턴을 변화된 세계에 무조건 적용하기보다, 어떤 학습 구조가 여전히 신뢰할 수 있고 어떤 가정은 수정되어야 하는지를 판단해야 한다.

분포 외 일반화(Out-of-Distribution Generalization)는 이러한 문제를 더욱 직접적으로 다룬다. 미래 관찰이 학습 사례와 유사하다고 가정하는 대신, 에이전트는 새로운 조합, 낯선 맥락, 이전에 보지 못한 조건을 처리해야 한다. 이를 위해서는 본질적인 구조와 우연한 상관관계(incidental correlation)를 분리하는 표상이 필요하다. 따라서 불변 관계(invariant relationship)를 학습하는 것은 좁게 정의된 데이터셋 안에서 정확도를 높이는 것보다 일반지능에 더 중요할 수 있다.

인간은 추상화(Abstraction)를 통해 강력한 일반화를 보여준다. 몇 가지 사례만 접한 뒤에도 사람은 다양한 상황에 적용 가능한 개념을 추출할 수 있다. 용기(container), 장애물(obstacle), 도구(tool), 소유(ownership), 원인(cause) 같은 개념을 이해하기 위해 가능한 모든 사례를 암기할 필요는 없다. 추상 개념은 경험을 재사용 가능한 구조로 압축하여, 겉보기에는 크게 다른 상황에 대해서도 추론할 수 있도록 한다.

조합성(Compositionality)은 이전에 학습한 구성요소를 새로운 방식으로 재결합할 수 있게 함으로써 이러한 능력을 강화한다. 객체, 공간 관계, 행동, 목표, 결과를 각각 이해하는 에이전트는 이전에 정확히 본 적이 없는 상황도 표현할 수 있다. 가능한 모든 구성을 저장하는 대신 재사용 가능한 구성요소로 새로운 조합을 생성함으로써, 지능은 처리할 수 있는 상황의 범위를 크게 확장할 수 있다.

전이학습(Transfer Learning)은 인공지능에서 지식 재사용을 구현하는 실용적인 방법을 제공한다. 대규모 원천 데이터셋(source dataset)으로 학습된 모델은 미세조정(fine-tuning)이나 관련 기법을 통해 더 작은 목표 작업(target task)에 적응될 수 있다. 전이된 표상은 유용한 출발점을 제공하여 학습 요구량을 줄이고, 목표 영역의 데이터가 제한적일 때 성능을 향상시키는 경우가 많다. 대규모 사전학습 모델은 이러한 원리의 확장 가능성을 보여준다.

긍정적 전이(Positive Transfer)는 이전 지식이 새로운 작업의 성능을 향상시키는 경우를 의미하지만, 전이가 항상 유익한 것은 아니다. 부정적 전이(Negative Transfer)는 원천 영역의 부적절한 가정이 목표 영역의 학습을 방해할 때 발생한다. 따라서 일반지능은 과거에 학습한 모든 것을 무조건 재사용하는 것 이상을 요구한다. 에이전트는 새로운 맥락에 따라 기존 지식의 관련성을 평가하고 선택적으로 유지, 수정, 결합 또는 폐기할 수 있어야 한다.

퓨샷 학습(Few-Shot Learning)과 제로샷 학습(Zero-Shot Learning)은 일반화와 전이의 중요한 형태이다. 퓨샷 학습은 소수의 사례만으로 새로운 문제를 해결하려 하고, 제로샷 행동은 작업별 사례 없이 기존 표상과 지시만을 활용한다. 개방 세계(open world)에서 작동하는 에이전트는 앞으로 마주칠 모든 상황에 대해 충분한 라벨 데이터가 제공될 것이라고 기대할 수 없기 때문에 이러한 능력은 AGI에 매우 중요하다.

메타학습(Meta-Learning)은 문제를 한 단계 더 높은 수준에서 다루며, 학습하는 방법 자체를 학습하려고 한다. 하나의 고정된 작업 성능만 최적화하는 대신, 메타학습 시스템은 여러 작업군(task family)에 걸쳐 더 빠르게 적응할 수 있는 전략을 추출한다. 과거의 학습 경험은 미래의 학습이 어떻게 이루어져야 하는지에 대한 정보가 된다. 이는 표본 효율(sample efficiency)을 높이고 반복되는 적응을 점점 더 효과적인 일반 학습 행동으로 전환하는 데 도움을 줄 수 있다.

지속학습(Continual Learning)은 전이를 시간의 흐름과 연결한다. 지능적인 에이전트는 하나의 정적인 학습 데이터셋이 아니라 연속적인 작업과 경험의 흐름을 접한다. 새로운 지식은 기존의 유용한 능력을 불필요하게 파괴하지 않으면서 기존 역량을 확장해야 한다. 이는 안정성-가소성 문제(stability-plasticity problem)를 만든다. 시스템은 새로운 정보를 학습할 수 있을 만큼 가소적이면서도 가치 있는 표상, 기술, 기억을 유지할 만큼 안정적이어야 한다.

파국적 망각(Catastrophic Forgetting)은 인공 신경망 시스템에서 이러한 요구가 얼마나 어려운지를 보여준다. 새로운 작업을 위해 모델을 업데이트하면 이전 능력을 지원하던 매개변수(parameter)가 변경되어 과거에 학습한 지식이 저하될 수 있다. 따라서 지속적인 지능은 기억 재생(memory replay), 모듈형 표상(modular representation), 매개변수 보호(parameter protection), 지식 공고화(knowledge consolidation), 검색(retrieval), 선택적 적응(selective adaptation)과 같은 메커니즘을 활용할 수 있다.

표상학습(Representation Learning)은 일반화와 전이 모두의 핵심이다. 내부 표상의 구조가 무엇을 재사용할 수 있는지를 결정하기 때문이다. 표면적인 세부사항에 지나치게 결합된 표상은 외형이 변하면 실패할 수 있지만, 객체, 관계, 동역학(dynamics), 의미(semantics), 인과 구조를 포착하는 표상은 더 넓은 조건에서도 유용성을 유지할 수 있다. 좋은 표상은 안정적으로 유지되어야 할 정보와 적응해야 할 정보를 분리한다.

인과 지식(Causal Knowledge)은 특히 강력한 전이를 지원할 수 있다. 통계적 상관관계(statistical correlation)는 환경이 변하면 사라질 수 있지만, 근본적인 인과 메커니즘(causal mechanism)은 다양한 조건에서 안정적으로 유지될 수 있다. 행동이 상태에 어떤 영향을 주고 변수들이 서로 어떻게 영향을 미치는지 이해하는 에이전트는 관찰된 패턴을 단순히 외삽하는 대신 개입(intervention)에 대해 추론할 수 있다. 따라서 인과 표상(causal representation)은 강건한 일반화와 적응 가능한 월드 모델(world model)과 밀접하게 연결된다.

월드 모델(World Model)은 구조화된 지식을 전이하는 또 다른 메커니즘을 제공한다. 월드 모델은 특정 작업 하나와 독립적으로 개체(entity), 상태(state), 관계, 동역학, 가능한 전이(transition)를 표현할 수 있다. 서로 다른 목표가 동일한 기반 모델을 예측, 계획, 시뮬레이션, 제어에 재사용할 수 있다. 모든 목표마다 완전히 새로운 정책을 학습하는 대신, 에이전트는 공유된 환경 지식과 작업별 목표를 결합할 수 있다.

체화 지능(Embodied Intelligence)에서는 물리적 환경이 지속적인 변화를 포함하기 때문에 전이가 특히 어렵다. 조명, 지형, 마찰, 객체 위치, 센서 잡음, 적재량(payload), 날씨, 인간 행동, 기계 상태는 과거 경험과 달라질 수 있다. 학습 환경과 거의 동일한 조건에서만 성공하는 로봇은 제한된 지능을 가진다. 일반적인 로봇 지능은 물리 세계에서 의미 있는 변화를 견디는 강건한 지각과 행동 능력을 필요로 한다.

시뮬레이션-현실 전이(Sim-to-Real Transfer)는 로보틱스에서 이러한 문제를 잘 보여준다. 정책이나 모델은 시뮬레이션에서 효율적으로 학습할 수 있지만, 시뮬레이션 환경은 실제 물리 세계를 완벽히 재현할 수 없다. 동역학, 센서, 재료, 지연시간(latency), 환경 복잡도의 차이는 현실 격차(reality gap)를 만든다. 도메인 랜덤화(domain randomization), 적응(adaptation), 강건한 표상학습, 시스템 식별(system identification), 현실 세계 피드백은 시뮬레이션 경험을 실제 환경으로 전이하는 데 도움을 줄 수 있다.

멀티모달 학습(Multimodal Learning)은 서로 다른 관찰 형태를 연결함으로써 일반화를 향상시킬 수 있다. 언어는 시각적으로 나타나는 개념을 설명할 수 있고, 행동은 물리적 속성을 드러내며, 감각 피드백은 기호적 설명(symbolic description)을 상호작용에 접지할 수 있다. 여러 모달리티(modality)가 표상을 공유하면 한 모달리티에서 획득한 지식이 다른 모달리티를 지원할 수 있다. 이러한 교차 모달 전이(cross-modal transfer)는 더 일관되고 재사용 가능한 세계 내부 모델을 만드는 데 기여할 수 있다.

언어(Language)는 완전한 재학습 없이 새로운 작업을 지정할 수 있기 때문에 특히 강력한 전이 인터페이스(interface)를 제공한다. 충분한 능력을 가진 에이전트는 기존의 지각, 추론, 행동 기술을 재사용하면서 언어를 통해 새로운 목표나 제약조건을 정의할 수 있다. 이는 작업 학습을 매개변수 수정(parameter modification) 중심에서 맥락적 적응(contextual adaptation) 중심으로 변화시키며, 현재 문제에 대한 설명에 따라 기존 능력을 동적으로 조합할 수 있게 한다.

일반화는 지각적 인식에만 국한되지 않고 목표와 전략에도 적용되어야 한다. 지능적인 에이전트는 한 상황에서 학습한 계획 원리(planning principle), 탐색 전략(exploration strategy), 안전 제약(safety constraint), 문제 해결 방법(problem-solving method)이 다른 상황에서도 유용할 수 있음을 인식해야 한다. 이러한 수준의 전이는 작업 자체를 추상화하여, 겉보기에는 다른 문제들 사이의 공통 구조를 식별하고 이전에 성공했던 추론 절차를 재사용할 수 있어야 한다.

따라서 일반화 평가는 무작위 테스트 분할(random test split)을 넘어 확장되어야 한다. 일반지능을 목표로 하는 시스템은 새로운 작업, 분포 변화, 새로운 조합, 변화하는 환경, 제한된 사례, 장기간 학습, 예상하지 못한 조건에서 평가되어야 한다. 평가는 단순히 성능이 얼마나 감소하는지만 측정하는 것이 아니라, 시스템이 불확실성을 인식하고, 효율적으로 적응하며, 역량을 회복하고, 기존 지식을 보존할 수 있는지도 함께 평가해야 한다.

궁극적으로 일반화와 전이는 지능이 경험을 축적하는지, 아니면 매번 처음부터 다시 시작하는지를 결정한다. 일반지능 에이전트는 경험을 점점 더 재사용 가능한 표상, 모델, 기술, 전략으로 변환해야 한다. 무엇이 불변으로 유지되는지 인식하고, 변화된 부분을 적응시키며, 기존 지식을 새로운 방식으로 결합하고, 기존 지식이 부족할 때 효율적으로 학습할 수 있어야 한다. 이러한 능력은 특화된 작업 수행(specialized task performance)에서 범용인공지능(Artificial General Intelligence, AGI)으로 이어지는 핵심적인 연결고리를 형성한다.

##  

## 01.03. Reasoning and Planning

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

Reasoning is the capacity of an intelligent agent to transform available information into conclusions, explanations, predictions, or decisions that are not directly contained in its observations. It connects perception and knowledge with purposeful action by evaluating relationships among facts, hypotheses, constraints, and possible outcomes. For AGI, reasoning must remain useful across unfamiliar tasks rather than being restricted to one predefined problem domain.

Planning extends reasoning across time by determining how a sequence of actions can transform a current state into a desired future state. An agent must represent where it is, what it wants to achieve, which actions are available, and how those actions may change the environment. Planning therefore converts knowledge about states and transitions into organized behavior directed toward goals, constraints, safety requirements, and expected consequences.

Reasoning and planning form a tightly coupled cognitive process. Reasoning helps determine what is true, what may be causing an observed situation, and what consequences different choices could produce. Planning uses those conclusions to construct action sequences. During execution, new observations may invalidate previous assumptions, requiring additional reasoning and replanning. Intelligence therefore depends on a continuous loop rather than a single reasoning or planning operation.

Deductive reasoning derives conclusions from established premises and rules. If the premises are correct and the inference procedure is valid, the conclusion follows logically. This form of reasoning is valuable when an agent operates with explicit rules, constraints, mathematical relationships, or symbolic knowledge. However, real environments rarely provide complete and perfectly reliable premises, so general intelligence cannot depend exclusively on deduction.

Inductive reasoning moves from observations toward broader patterns, hypotheses, or general rules. An agent may observe repeated events and infer a regularity that can guide future prediction. Machine learning itself can be interpreted as a large-scale form of induction because models infer structures from examples. Inductive conclusions remain uncertain, making evaluation, confidence estimation, and continued updating important when new evidence becomes available.

Abductive reasoning seeks plausible explanations for observations. When an unexpected event occurs, an intelligent agent can generate hypotheses about what may have caused it and compare them against available evidence. This capability is essential for diagnosis, troubleshooting, scientific discovery, and autonomous systems. Abduction allows intelligence to reason backward from effects toward possible causes even when several explanations remain simultaneously possible.

Analogical reasoning transfers relational structure from a familiar problem to a new one. Instead of relying only on superficial similarity, a capable agent identifies common relationships among entities, actions, and consequences. Analogies can support rapid problem solving because previously successful reasoning patterns can be reused in unfamiliar situations. This connects reasoning directly with abstraction, generalization, compositionality, and transfer.

Causal reasoning goes beyond statistical association by representing how interventions may change outcomes. An agent that understands causal relationships can distinguish observing an event from actively producing it. This distinction becomes critical for planning because actions are interventions in the world. Reliable planning therefore benefits from models that represent not merely which states are correlated, but how actions and environmental processes generate state transitions.

Reasoning under uncertainty is necessary because observations, models, and predictions are rarely complete. An intelligent system may need to compare multiple hypotheses, estimate probabilities, evaluate confidence, and make decisions despite missing information. Probabilistic reasoning provides mechanisms for updating beliefs as evidence arrives. General intelligence must also recognize when uncertainty is sufficiently important that gathering additional information is preferable to immediately taking action.

Decision-making connects reasoning to preferences and objectives. Several actions may be physically possible, but their consequences can differ in value, risk, cost, time, energy, or safety. An intelligent agent therefore evaluates alternatives according to expected outcomes and constraints. This process may involve utility, reward, priorities, uncertainty, and long-term consequences, making decision-making an important bridge between reasoning and executable planning.

Planning can be represented as search through a space of possible states and actions. Starting from the current state, an agent considers alternative actions and estimates where they may lead. Exhaustive search quickly becomes impractical as the number of possibilities grows, so effective planning requires heuristics, abstraction, pruning, hierarchical decomposition, learned value estimates, or predictive models that concentrate computation on promising possibilities.

Hierarchical planning reduces complexity by organizing behavior at multiple levels of abstraction. A high-level plan may specify objectives such as reaching a destination, obtaining an object, or completing a mission, while lower levels determine concrete movements and control commands. This decomposition allows reasoning to focus on meaningful strategic choices without representing every physical action at the same level, supporting longer and more complicated tasks.

Long-horizon planning introduces additional difficulty because uncertainty accumulates as predictions extend further into the future. Small modeling errors can produce increasingly inaccurate forecasts, while unexpected events may invalidate distant parts of a plan. Intelligent agents therefore benefit from receding-horizon strategies in which near-term actions are planned in greater detail while distant objectives remain abstract and are repeatedly revised as new observations arrive.

World models provide an internal environment in which reasoning and planning can operate. A world model represents entities, states, relationships, dynamics, and possible transitions, enabling an agent to simulate potential futures before acting physically. Instead of learning only direct stimulus-response mappings, the agent can ask what might happen under alternative actions. Internal simulation therefore provides a foundation for prediction, counterfactual reasoning, planning, and safer decision-making.

Counterfactual reasoning considers situations that did not actually occur. An agent may ask what would have happened if a different action had been selected or how an undesirable outcome could have been avoided. Such reasoning supports learning from experience because actual outcomes can be compared with hypothetical alternatives. Counterfactuals also strengthen planning by allowing multiple possible futures to be evaluated before committing to irreversible actions.

Mental simulation generalizes this process by internally constructing possible sequences of events. Humans routinely imagine routes, conversations, physical actions, or consequences before executing them. Artificial agents can perform analogous computation using learned dynamics, simulators, search procedures, or generative world models. The usefulness of simulation depends on model accuracy, computational cost, uncertainty estimation, and the ability to focus simulation on decision-relevant possibilities.

Reactive behavior and deliberate planning should not be viewed as mutually exclusive. Familiar, predictable situations may be handled efficiently by learned policies or fast control loops without extensive deliberation. Novel, uncertain, dangerous, or strategically important situations may justify deeper reasoning and simulation. General intelligence therefore benefits from adaptive computation that determines when rapid response is sufficient and when additional reasoning resources should be activated.

This distinction is particularly important for embodied agents. A robot moving through a stable corridor may require only lightweight perception and local control, while an unexpected obstacle, localization failure, human interaction, or hazardous condition may trigger more expensive reasoning and replanning. Allocating computation according to novelty, uncertainty, risk, and task importance can improve both energy efficiency and responsiveness in physical intelligent systems.

Memory supports reasoning by providing relevant facts, experiences, strategies, and previous solutions. Retrieval allows an agent to avoid reconstructing knowledge that has already been acquired. However, useful reasoning requires selective retrieval because excessive irrelevant information can increase computational cost or introduce confusion. Memory systems for AGI must therefore identify contextually relevant knowledge and integrate it with current observations and active goals.

Language can function as both an interface and a medium for reasoning. Instructions specify goals and constraints, while linguistic representations can express intermediate concepts, hypotheses, plans, and explanations. Large language models demonstrate that complex reasoning patterns can emerge from language-based learning, but reliable planning requires grounding these representations in external states, persistent memory, tools, feedback, and verifiable consequences rather than relying solely on linguistic plausibility.

Tool use expands the reasoning capacity of an intelligent agent. Calculators, search systems, databases, simulators, code execution environments, sensors, and specialized models can provide capabilities that would be inefficient to reproduce internally. Intelligent tool use requires recognizing when external assistance is useful, selecting the appropriate tool, constructing a suitable request, interpreting the result, and integrating that information into subsequent reasoning and planning.

Multi-agent environments introduce another level of complexity because other agents possess their own goals, knowledge, and strategies. Planning may require predicting cooperation, competition, negotiation, communication, or interference. An intelligent agent must therefore reason not only about physical dynamics but also about the possible decisions of others. Shared planning can additionally distribute tasks, coordinate resources, and combine specialized capabilities across multiple humans, robots, or software agents.

Metacognition can supervise the reasoning and planning process itself. An agent should estimate whether its evidence is sufficient, whether a conclusion is reliable, whether a plan is progressing, and whether additional computation is worthwhile. It may decide to verify an assumption, retrieve more information, simulate another alternative, request assistance, or abandon a failing strategy. Such monitoring turns reasoning into an adaptive process rather than an uncontrolled sequence of computations.

Evaluation of reasoning and planning should extend beyond whether a final answer or action happens to be correct. A robust system should remain effective under incomplete information, changing goals, novel tasks, long horizons, conflicting constraints, and unexpected events. Evaluation should examine adaptation, consistency, uncertainty management, recovery from failure, computational efficiency, and whether plans remain grounded in the actual environment as execution proceeds.

Ultimately, reasoning allows an intelligent agent to understand relationships and consequences, while planning transforms that understanding into organized future action. General intelligence requires both capabilities to interact continuously with perception, memory, learning, world models, decision-making, action, and feedback. The resulting agent does not merely react to the present but can interpret situations, imagine alternatives, anticipate consequences, pursue goals, and revise its plans as the world changes.

추론(Reasoning)은 지능적인 에이전트가 이용 가능한 정보를 관찰에 직접 포함되어 있지 않은 결론, 설명, 예측 또는 의사결정으로 변환하는 능력이다. 추론은 사실, 가설, 제약조건, 가능한 결과 사이의 관계를 평가함으로써 지각(perception)과 지식(knowledge)을 목적지향적 행동(purposeful action)과 연결한다. AGI에서 추론은 하나의 미리 정의된 문제 영역에 제한되지 않고 익숙하지 않은 다양한 작업에서도 유용하게 작동해야 한다.

계획(Planning)은 일련의 행동이 현재 상태(current state)를 원하는 미래 상태(desired future state)로 어떻게 변화시킬 수 있는지를 결정함으로써 추론을 시간적으로 확장한다. 에이전트는 현재 자신이 어디에 있는지, 무엇을 달성하려 하는지, 어떤 행동이 가능한지, 그리고 그러한 행동이 환경을 어떻게 변화시킬 수 있는지를 표현해야 한다. 따라서 계획은 상태와 전이에 관한 지식을 목표, 제약조건, 안전 요구사항, 예상 결과를 향한 체계적인 행동으로 변환한다.

추론과 계획은 밀접하게 결합된 인지 과정(cognitive process)을 형성한다. 추론은 무엇이 사실인지, 관찰된 상황의 원인이 무엇일 수 있는지, 서로 다른 선택이 어떤 결과를 만들어낼 수 있는지를 판단하도록 돕는다. 계획은 이러한 결론을 사용하여 행동 순서를 구성한다. 실행 과정에서 새로운 관찰이 기존 가정을 무효화할 수 있으므로 추가적인 추론과 재계획(replanning)이 필요하다. 따라서 지능은 단일한 추론이나 계획 연산이 아니라 지속적인 순환 과정에 의존한다.

연역적 추론(Deductive Reasoning)은 확립된 전제(premise)와 규칙으로부터 결론을 도출한다. 전제가 정확하고 추론 절차가 유효하다면 결론은 논리적으로 따라온다. 이러한 추론은 에이전트가 명시적인 규칙, 제약조건, 수학적 관계 또는 기호적 지식(symbolic knowledge)을 이용하는 상황에서 유용하다. 그러나 실제 환경에서는 완전하고 완벽하게 신뢰할 수 있는 전제가 거의 제공되지 않기 때문에 일반지능은 연역적 추론에만 의존할 수 없다.

귀납적 추론(Inductive Reasoning)은 관찰로부터 더 광범위한 패턴, 가설 또는 일반적인 규칙을 도출한다. 에이전트는 반복되는 사건을 관찰하고 미래 예측을 안내할 수 있는 규칙성을 추론할 수 있다. 기계학습(Machine Learning) 자체도 모델이 사례로부터 구조를 추론한다는 점에서 대규모 귀납 과정으로 해석할 수 있다. 귀납적 결론에는 불확실성이 남기 때문에 새로운 증거가 나타날 때 평가, 신뢰도 추정(confidence estimation), 지속적인 갱신이 중요하다.

가추적 추론(Abductive Reasoning)은 관찰에 대한 그럴듯한 설명을 찾는다. 예상하지 못한 사건이 발생하면 지능적인 에이전트는 무엇이 그 사건을 발생시켰을 가능성이 있는지에 대한 가설을 생성하고 이용 가능한 증거와 비교할 수 있다. 이러한 능력은 진단(diagnosis), 문제 해결(troubleshooting), 과학적 발견(scientific discovery), 자율 시스템에서 필수적이다. 가추적 추론은 여러 설명이 동시에 가능할 때에도 결과로부터 가능한 원인을 역방향으로 추론할 수 있게 한다.

유추적 추론(Analogical Reasoning)은 익숙한 문제의 관계적 구조(relational structure)를 새로운 문제로 전이한다. 유능한 에이전트는 표면적인 유사성에만 의존하지 않고 개체, 행동, 결과 사이의 공통 관계를 식별한다. 과거에 성공했던 추론 패턴을 익숙하지 않은 상황에 재사용할 수 있기 때문에 유추는 빠른 문제 해결을 지원할 수 있다. 이는 추론을 추상화(abstraction), 일반화(generalization), 조합성(compositionality), 전이(transfer)와 직접 연결한다.

인과적 추론(Causal Reasoning)은 개입(intervention)이 결과를 어떻게 변화시킬 수 있는지를 표현함으로써 통계적 연관성(statistical association)을 넘어선다. 인과관계를 이해하는 에이전트는 사건을 단순히 관찰하는 것과 사건을 능동적으로 발생시키는 것을 구분할 수 있다. 행동은 세계에 대한 개입이기 때문에 이러한 차이는 계획에서 매우 중요하다. 따라서 신뢰할 수 있는 계획은 어떤 상태들이 서로 상관되어 있는지만이 아니라 행동과 환경 과정이 상태 전이(state transition)를 어떻게 발생시키는지를 표현하는 모델의 도움을 받을 수 있다.

불확실성 하의 추론(Reasoning under Uncertainty)은 관찰, 모델, 예측이 거의 항상 불완전하기 때문에 필요하다. 지능적인 시스템은 여러 가설을 비교하고, 확률을 추정하며, 신뢰도를 평가하고, 정보가 부족한 상황에서도 의사결정을 내려야 할 수 있다. 확률적 추론(probabilistic reasoning)은 새로운 증거가 들어올 때 믿음(belief)을 갱신하는 메커니즘을 제공한다. 일반지능은 또한 불확실성이 충분히 클 경우 즉시 행동하는 것보다 추가 정보를 수집하는 것이 더 적절하다는 사실을 인식해야 한다.

의사결정(Decision-Making)은 추론을 선호와 목표에 연결한다. 여러 행동이 물리적으로 가능하더라도 그 결과는 가치, 위험, 비용, 시간, 에너지, 안전 측면에서 서로 다를 수 있다. 따라서 지능적인 에이전트는 예상 결과와 제약조건을 기준으로 대안을 평가한다. 이러한 과정에는 효용(utility), 보상(reward), 우선순위, 불확실성, 장기적인 결과가 포함될 수 있으며, 의사결정은 추론과 실행 가능한 계획을 연결하는 중요한 다리가 된다.

계획은 가능한 상태와 행동 공간을 탐색(search)하는 과정으로 표현할 수 있다. 현재 상태에서 출발하여 에이전트는 여러 대안적 행동을 고려하고 각각이 어떤 상태로 이어질 수 있는지를 추정한다. 가능한 경우의 수가 증가하면 완전 탐색(exhaustive search)은 빠르게 비현실적이 되므로 효과적인 계획에는 휴리스틱(heuristic), 추상화, 가지치기(pruning), 계층적 분해(hierarchical decomposition), 학습된 가치 추정(learned value estimate), 예측 모델 등이 필요하다.

계층적 계획(Hierarchical Planning)은 행동을 여러 추상화 수준으로 구성하여 복잡성을 감소시킨다. 상위 수준 계획은 목적지 도달, 객체 획득, 임무 완료와 같은 목표를 지정하고, 하위 수준에서는 구체적인 움직임과 제어 명령을 결정할 수 있다. 이러한 분해는 모든 물리적 행동을 동일한 수준에서 표현하지 않고도 의미 있는 전략적 선택에 추론을 집중할 수 있게 하며, 더 길고 복잡한 작업을 지원한다.

장기 계획(Long-Horizon Planning)은 예측이 먼 미래까지 확장될수록 불확실성이 누적되기 때문에 추가적인 어려움을 발생시킨다. 작은 모델링 오류도 시간이 지나면서 점점 더 부정확한 예측을 만들 수 있고, 예상하지 못한 사건이 계획의 먼 미래 부분을 무효화할 수 있다. 따라서 지능적인 에이전트는 가까운 미래의 행동은 상세하게 계획하고 먼 미래의 목표는 추상적으로 유지하면서 새로운 관찰에 따라 반복적으로 수정하는 이동 지평 전략(receding-horizon strategy)의 도움을 받을 수 있다.

월드 모델(World Model)은 추론과 계획이 작동할 수 있는 내부 환경을 제공한다. 월드 모델은 개체(entity), 상태(state), 관계, 동역학(dynamics), 가능한 전이를 표현하여 에이전트가 실제 행동을 수행하기 전에 잠재적인 미래를 시뮬레이션할 수 있도록 한다. 단순한 자극-반응 매핑(stimulus-response mapping)만 학습하는 대신, 에이전트는 대안적인 행동을 수행했을 때 어떤 일이 발생할 수 있는지를 내부적으로 검토할 수 있다. 따라서 내부 시뮬레이션은 예측, 반사실적 추론(counterfactual reasoning), 계획, 더욱 안전한 의사결정의 기반을 제공한다.

반사실적 추론(Counterfactual Reasoning)은 실제로 발생하지 않은 상황을 고려한다. 에이전트는 다른 행동을 선택했다면 어떤 일이 발생했을지 또는 바람직하지 않은 결과를 어떻게 피할 수 있었는지를 질문할 수 있다. 이러한 추론은 실제 결과와 가상의 대안을 비교할 수 있기 때문에 경험으로부터의 학습을 지원한다. 또한 반사실은 되돌릴 수 없는 행동을 실행하기 전에 여러 가능한 미래를 평가할 수 있게 하여 계획 능력을 강화한다.

정신적 시뮬레이션(Mental Simulation)은 가능한 사건의 연속을 내부적으로 구성함으로써 이러한 과정을 확장한다. 인간은 실제로 행동하기 전에 이동 경로, 대화, 물리적 행동, 결과 등을 일상적으로 상상한다. 인공 에이전트도 학습된 동역학, 시뮬레이터(simulator), 탐색 절차, 생성형 월드 모델(generative world model)을 이용해 유사한 계산을 수행할 수 있다. 시뮬레이션의 유용성은 모델 정확도, 계산 비용, 불확실성 추정, 의사결정에 중요한 가능성에 계산을 집중하는 능력에 의존한다.

반응적 행동(Reactive Behavior)과 숙고적 계획(Deliberate Planning)은 서로 배타적인 것으로 보아서는 안 된다. 익숙하고 예측 가능한 상황은 광범위한 숙고 없이 학습된 정책이나 빠른 제어 루프(control loop)를 통해 효율적으로 처리할 수 있다. 반면 새롭거나 불확실하고 위험하거나 전략적으로 중요한 상황에서는 더 깊은 추론과 시뮬레이션이 필요할 수 있다. 따라서 일반지능은 빠른 반응으로 충분한 경우와 추가적인 추론 자원을 활성화해야 하는 경우를 판단하는 적응적 계산(adaptive computation)을 통해 이점을 얻는다.

이러한 구분은 체화 에이전트(Embodied Agent)에서 특히 중요하다. 안정적인 복도를 이동하는 로봇은 가벼운 지각 처리와 로컬 제어(local control)만 필요할 수 있지만, 예상하지 못한 장애물, 위치추정 실패(localization failure), 인간과의 상호작용, 위험한 조건이 발생하면 더 많은 계산을 요구하는 추론과 재계획을 활성화할 수 있다. 새로움(novelty), 불확실성, 위험, 작업 중요도에 따라 계산 자원을 할당하면 물리적 지능 시스템의 에너지 효율과 반응성을 모두 향상시킬 수 있다.

기억(Memory)은 관련 사실, 경험, 전략, 이전 해결책을 제공함으로써 추론을 지원한다. 검색(retrieval)을 이용하면 에이전트는 이미 습득한 지식을 다시 처음부터 구성할 필요가 없다. 그러나 지나치게 많은 관련 없는 정보는 계산 비용을 증가시키거나 혼란을 발생시킬 수 있기 때문에 유용한 추론에는 선택적 검색(selective retrieval)이 필요하다. 따라서 AGI의 기억 시스템은 현재 맥락과 관련된 지식을 식별하고 이를 현재 관찰 및 활성 목표(active goal)와 통합해야 한다.

언어(Language)는 추론을 위한 인터페이스이자 매개체로 기능할 수 있다. 지시는 목표와 제약조건을 지정하며, 언어적 표상(linguistic representation)은 중간 개념, 가설, 계획, 설명을 표현할 수 있다. 대규모 언어 모델(Large Language Model)은 언어 기반 학습에서 복잡한 추론 패턴이 나타날 수 있음을 보여주지만, 신뢰할 수 있는 계획을 위해서는 단순한 언어적 개연성에 의존하기보다 이러한 표상을 외부 상태, 지속적 기억(persistent memory), 도구, 피드백, 검증 가능한 결과와 접지(grounding)해야 한다.

도구 사용(Tool Use)은 지능적인 에이전트의 추론 능력을 확장한다. 계산기, 검색 시스템, 데이터베이스, 시뮬레이터, 코드 실행 환경, 센서, 전문화된 모델은 내부적으로 구현하기 비효율적인 능력을 제공할 수 있다. 지능적인 도구 사용을 위해서는 외부 지원이 언제 유용한지 인식하고, 적절한 도구를 선택하며, 적절한 요청을 구성하고, 결과를 해석하여 이후의 추론과 계획에 통합하는 능력이 필요하다.

다중 에이전트 환경(Multi-Agent Environment)은 다른 에이전트들도 자신만의 목표, 지식, 전략을 가지고 있기 때문에 또 다른 수준의 복잡성을 발생시킨다. 계획에는 협력, 경쟁, 협상, 의사소통 또는 간섭을 예측하는 과정이 필요할 수 있다. 따라서 지능적인 에이전트는 물리적 동역학뿐만 아니라 다른 에이전트의 가능한 의사결정에 대해서도 추론해야 한다. 공유 계획(shared planning)은 여러 인간, 로봇 또는 소프트웨어 에이전트 사이에서 작업을 분배하고, 자원을 조정하며, 전문화된 능력을 결합할 수도 있다.

메타인지(Metacognition)는 추론과 계획 과정 자체를 감독할 수 있다. 에이전트는 자신이 가진 증거가 충분한지, 결론을 신뢰할 수 있는지, 계획이 제대로 진행되고 있는지, 추가적인 계산을 수행할 가치가 있는지를 평가해야 한다. 필요하다면 가정을 검증하고, 더 많은 정보를 검색하고, 다른 대안을 시뮬레이션하며, 도움을 요청하거나 실패하고 있는 전략을 포기할 수 있다. 이러한 모니터링은 추론을 통제되지 않은 계산의 연속이 아니라 적응적인 과정으로 만든다.

추론과 계획의 평가(Evaluation)는 최종 답변이나 행동이 우연히 정확했는지만을 확인하는 수준을 넘어야 한다. 강건한 시스템은 불완전한 정보, 변화하는 목표, 새로운 작업, 장기적인 계획, 상충하는 제약조건, 예상하지 못한 사건에서도 효과적으로 작동해야 한다. 평가는 적응 능력, 일관성, 불확실성 관리, 실패로부터의 회복, 계산 효율, 그리고 실행이 진행되는 동안 계획이 실제 환경에 지속적으로 접지되어 있는지를 함께 살펴보아야 한다.

궁극적으로 추론(Reasoning)은 지능적인 에이전트가 관계와 결과를 이해할 수 있도록 하고, 계획(Planning)은 이러한 이해를 체계적인 미래 행동으로 변환한다. 일반지능은 두 능력이 지각, 기억, 학습, 월드 모델, 의사결정, 행동, 피드백과 지속적으로 상호작용할 것을 요구한다. 이렇게 형성된 에이전트는 현재 상황에 단순히 반응하는 것을 넘어 상황을 해석하고, 대안을 상상하며, 결과를 예측하고, 목표를 추구하며, 세계가 변화함에 따라 자신의 계획을 지속적으로 수정할 수 있다.

##  

## 01.04. Learning Paradigms Unification

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

Learning paradigms describe the different ways an intelligent system acquires knowledge, representations, skills, and behavioral strategies from experience. Traditional artificial intelligence separates learning into supervised, unsupervised, self-supervised, reinforcement, imitation, and related approaches. General intelligence, however, requires these mechanisms to operate as complementary components of a unified learning process rather than as isolated techniques.

Supervised learning acquires mappings from inputs to desired outputs using labeled examples. It is highly effective when reliable labels are available and has supported major advances in classification, detection, recognition, prediction, and control. Its limitation for general intelligence is dependence on externally prepared targets. An autonomous agent operating continuously in the world cannot expect humans to label every object, state, action, relationship, or situation it encounters.

Unsupervised learning attempts to discover structure without explicit target labels. It can identify clusters, latent variables, statistical regularities, and lower-dimensional representations within observations. This ability is important because most information encountered by an intelligent agent is naturally unlabeled. Discovering structure independently allows experience itself to become a source of knowledge rather than requiring every learning signal to be manually specified.

Self-supervised learning constructs learning signals directly from the data. A system may predict masked information, future observations, missing components, transformations, or relationships among different views of the same environment. Because supervision is generated from the structure of experience, enormous quantities of unlabeled data can be used. Modern foundation models demonstrate how self-supervision can create broad representations before task-specific adaptation occurs.

Weakly supervised learning occupies the space between fully labeled and unlabeled learning. Training information may be incomplete, imprecise, noisy, indirect, or available only at a coarse level. Real-world intelligence frequently encounters exactly these conditions. An agent may know that an event was successful without knowing which individual action caused success, or receive approximate semantic information without precise labels for every observation.

Semi-supervised learning combines a relatively small amount of labeled data with a much larger quantity of unlabeled data. The labeled examples provide semantic anchors while the unlabeled observations reveal broader structure and variation. This paradigm is especially useful when data collection is inexpensive but expert annotation is costly. For AGI, it illustrates a broader principle: different levels of supervision should cooperate rather than define separate learning systems.

Reinforcement learning introduces action and consequence into learning. An agent interacts with an environment, receives observations and rewards, and learns policies that improve long-term outcomes. Unlike conventional supervised learning, the correct action is not necessarily provided directly. The agent must explore alternatives and connect delayed consequences with earlier decisions, making reinforcement learning particularly relevant to planning, control, autonomy, and embodied intelligence.

Imitation learning allows an agent to acquire behavior from demonstrations produced by humans or other agents. Instead of discovering every useful behavior through expensive trial and error, the learner can begin from examples of competent action. Demonstrations provide strong priors about promising regions of the behavioral space, while subsequent reinforcement, planning, or autonomous exploration can improve behavior beyond the original demonstrations.

Active learning changes the role of the learner by allowing it to influence which information should be acquired. Rather than passively accepting a fixed dataset, the system can identify uncertain or informative cases and request labels, observations, experiments, or demonstrations. This introduces information-seeking behavior into learning and connects learning with reasoning, uncertainty estimation, exploration, and decision-making.

Curriculum learning recognizes that the order of experience can affect learning efficiency. Difficult capabilities may emerge more reliably when simpler concepts or tasks establish useful foundations first. Biological learning naturally follows developmental sequences in which perception, motor skills, language, social understanding, and abstract reasoning build progressively. Artificial agents can similarly benefit from structured progression from simpler experiences toward increasingly complex tasks.

Transfer learning enables previously acquired representations and skills to support new tasks. Instead of constructing each capability independently, a unified learner should preserve reusable knowledge and adapt it when objectives or environments change. Transfer becomes especially important for AGI because the number of possible future tasks is effectively unlimited. Intelligence must therefore accumulate competence rather than repeatedly restart learning from an empty state.

Continual learning extends this principle across the lifetime of an agent. New experiences should modify existing knowledge without unnecessarily destroying previous capabilities. This creates the stability-plasticity problem: the learner must remain sufficiently plastic to adapt while sufficiently stable to preserve valuable knowledge. Memory replay, modular architectures, consolidation, retrieval, and selective parameter updates can help balance these competing requirements.

Meta-learning moves beyond acquiring individual skills toward learning how adaptation itself should occur. Experience across many tasks can reveal which representations, initialization strategies, exploration behaviors, or update mechanisms allow rapid learning. A meta-learning agent can therefore use previous learning episodes to improve future learning efficiency, potentially enabling few-shot adaptation to tasks that were not explicitly anticipated during initial training.

Multimodal learning integrates information from vision, language, audio, touch, proprioception, LiDAR, and other sensor channels. Different modalities provide complementary evidence about the same world. Language may provide semantic structure, vision may reveal appearance and geometry, and physical interaction may reveal mass, friction, or affordances. Unified intelligence should connect these signals within shared representations rather than learning each modality independently.

Predictive learning provides a common principle capable of linking several paradigms. An agent can learn by predicting missing information, future states, consequences of actions, rewards, or latent dynamics. Prediction errors then provide learning signals that refine internal representations. From this perspective, perception, self-supervised learning, world modeling, and action learning can all be understood partly as reducing errors between expected and observed outcomes.

World models offer a particularly important framework for learning unification. A world model attempts to represent entities, states, relationships, dynamics, and possible transitions within an environment. Self-supervised observation can learn perceptual structure, actions can reveal causal dynamics, reinforcement can identify valuable outcomes, and language can provide semantic knowledge. These learning signals can update different aspects of a shared internal model.

Representation learning is therefore central to unification. If every task constructs completely independent internal features, knowledge transfer becomes difficult and computationally inefficient. Shared representations allow information learned from one source to benefit another. Perception, language, action, memory, and prediction can contribute complementary constraints that produce representations containing semantic, spatial, temporal, physical, and causal information.

A unified learning architecture does not imply that every learning signal should be treated identically. Different signals provide different kinds of information and operate at different timescales. Supervision may provide precise semantic correction, self-supervision may supply continuous representation learning, reinforcement may communicate long-term value, and imitation may accelerate skill acquisition. Unification concerns coordination among these signals rather than eliminating their distinctions.

Learning can consequently be viewed as a multi-objective optimization process. An intelligent agent may simultaneously minimize prediction error, improve task performance, maximize expected reward, preserve previous knowledge, maintain safe behavior, and reduce uncertainty. These objectives can conflict, requiring mechanisms that dynamically balance them according to context. AGI therefore needs learning control as well as individual learning algorithms.

Memory provides continuity across learning paradigms. Experiences collected through interaction can later support self-supervised training, reinforcement updates, imitation, retrieval, reasoning, or planning. Episodic memory can preserve specific events, while semantic memory extracts more general knowledge and procedural memory preserves skills. Memory consolidation can transform repeated experiences into stable representations that remain available across future tasks and environments.

Exploration determines which experiences become available for learning. Random exploration may be inefficient or dangerous, especially in physical systems. Intelligent exploration can instead prioritize novelty, uncertainty, expected information gain, task relevance, or predicted value. This connects active learning and reinforcement learning with curiosity-driven behavior, world-model improvement, and autonomous experimentation, allowing the agent to participate in constructing its own training distribution.

Embodied agents make learning unification particularly important because perception and action cannot be separated cleanly. A robot observes the world, selects an action, changes the environment, receives new sensory information, and learns from the resulting transition. Demonstrations may initialize behavior, self-supervision may improve perception, reinforcement may optimize control, and world-model learning may predict consequences. All occur within the same perception-action loop.

Language can serve as an additional unifying layer. Instructions can define goals, demonstrations can be described linguistically, observations can be connected to semantic concepts, and feedback can explain success or failure. Language also enables knowledge acquired by other agents or humans to enter the learning process without direct physical experience. This creates a bridge between culturally accumulated knowledge and individually acquired sensorimotor experience.

Adaptive computation should also influence learning. Not every observation deserves the same computational effort or parameter update. Familiar and predictable situations may require little additional learning, whereas novelty, high uncertainty, failure, or unexpected state transitions may justify deeper processing and stronger updates. Such event-driven learning can improve computational efficiency while concentrating adaptation on experiences that provide substantial new information.

Safety and alignment introduce constraints on unified learning. An autonomous system should not maximize reward or exploration without considering unacceptable consequences. Learning objectives must coexist with safety boundaries, human preferences, operational constraints, and uncertainty-aware decision policies. General intelligence therefore requires mechanisms that determine not only how to learn efficiently, but also which behaviors should remain prohibited during exploration and adaptation.

Evaluation of unified learning should measure more than performance on a single static dataset. A capable system should learn from multiple forms of feedback, transfer knowledge between tasks, adapt from limited examples, retain earlier skills, integrate new modalities, recover from distribution shifts, and improve through interaction. Sample efficiency, continual adaptation, robustness, transfer, memory retention, and computational cost become important measures of learning quality.

Ultimately, learning-paradigm unification transforms learning from a collection of separate algorithms into a continuous adaptive process. A generally intelligent agent should learn from labels when available, discover structure when labels are absent, predict from experience, imitate useful behavior, explore uncertain situations, optimize consequences, transfer previous knowledge, and continually revise its world model. The objective is not one universal learning algorithm, but a coordinated architecture in which multiple learning mechanisms collectively build increasingly general intelligence.

학습 패러다임(Learning Paradigms)은 지능적인 시스템이 경험으로부터 지식, 표상(representation), 기술(skill), 행동 전략(behavioral strategy)을 획득하는 서로 다른 방식을 설명한다. 전통적인 인공지능은 학습을 지도학습(supervised learning), 비지도학습(unsupervised learning), 자기지도학습(self-supervised learning), 강화학습(reinforcement learning), 모방학습(imitation learning) 및 관련 접근법으로 구분해 왔다. 그러나 일반지능(general intelligence)은 이러한 메커니즘들이 서로 분리된 기법이 아니라 통합된 학습 과정의 상호보완적인 구성요소로 작동할 것을 요구한다.

지도학습(Supervised Learning)은 라벨이 지정된 사례(labeled example)를 이용하여 입력과 원하는 출력 사이의 매핑(mapping)을 학습한다. 신뢰할 수 있는 라벨을 확보할 수 있을 때 매우 효과적이며 분류, 탐지, 인식, 예측, 제어 분야의 주요 발전을 이끌어 왔다. 그러나 일반지능 관점에서는 외부에서 준비된 정답(target)에 의존한다는 한계가 있다. 세계에서 지속적으로 작동하는 자율 에이전트가 접하는 모든 객체, 상태, 행동, 관계, 상황에 대해 인간이 라벨을 제공할 수는 없다.

비지도학습(Unsupervised Learning)은 명시적인 목표 라벨 없이 데이터 내부의 구조를 발견하려고 한다. 관찰 데이터에서 군집(cluster), 잠재변수(latent variable), 통계적 규칙성(statistical regularity), 저차원 표상(lower-dimensional representation)을 발견할 수 있다. 지능적인 에이전트가 접하는 대부분의 정보에는 본래 라벨이 없기 때문에 이러한 능력은 중요하다. 구조를 스스로 발견할 수 있다면 모든 학습 신호를 사람이 지정하지 않더라도 경험 자체가 지식의 원천이 될 수 있다.

자기지도학습(Self-Supervised Learning)은 데이터 자체로부터 직접 학습 신호를 구성한다. 시스템은 가려진 정보(masked information), 미래 관찰, 누락된 구성요소, 변환(transformation), 동일한 환경을 바라보는 서로 다른 관점 사이의 관계 등을 예측할 수 있다. 경험의 구조 자체에서 지도 신호(supervision)가 생성되므로 방대한 양의 비라벨 데이터(unlabeled data)를 활용할 수 있다. 현대의 파운데이션 모델(foundation model)은 자기지도를 통해 광범위한 표상을 형성한 뒤 특정 작업에 적응할 수 있음을 보여준다.

약지도학습(Weakly Supervised Learning)은 완전한 라벨 학습과 비라벨 학습 사이의 영역에 위치한다. 학습 정보는 불완전하거나, 부정확하거나, 잡음이 포함되거나, 간접적이거나, 거친 수준(coarse level)에서만 제공될 수 있다. 실제 세계의 지능은 이러한 조건을 빈번하게 경험한다. 에이전트는 어떤 사건이 성공했다는 사실은 알지만 개별 행동 가운데 무엇이 성공을 발생시켰는지는 알지 못할 수 있으며, 모든 관찰에 정확한 라벨이 없어도 대략적인 의미 정보를 받을 수 있다.

준지도학습(Semi-Supervised Learning)은 비교적 적은 양의 라벨 데이터와 훨씬 많은 양의 비라벨 데이터를 결합한다. 라벨이 있는 사례는 의미적 기준점(semantic anchor)을 제공하고, 라벨이 없는 관찰은 더 광범위한 구조와 변화를 보여준다. 데이터 수집은 쉽지만 전문가의 주석(annotation) 비용이 높은 경우 특히 유용하다. AGI 관점에서 이는 서로 다른 수준의 지도 정보가 별도의 학습 시스템을 정의하기보다 서로 협력해야 한다는 더 넓은 원리를 보여준다.

강화학습(Reinforcement Learning)은 행동(action)과 결과(consequence)를 학습 과정에 도입한다. 에이전트는 환경과 상호작용하면서 관찰과 보상을 받고 장기적인 결과를 향상시키는 정책(policy)을 학습한다. 기존 지도학습과 달리 올바른 행동이 항상 직접적으로 제공되는 것은 아니다. 에이전트는 여러 대안을 탐색하고 지연된 결과(delayed consequence)를 이전의 의사결정과 연결해야 하므로 강화학습은 계획, 제어, 자율성(autonomy), 체화 지능(embodied intelligence)에 특히 중요하다.

모방학습(Imitation Learning)은 인간이나 다른 에이전트가 제공한 시범(demonstration)으로부터 행동을 획득할 수 있도록 한다. 모든 유용한 행동을 비용이 높은 시행착오(trial and error)를 통해 처음부터 발견하는 대신, 학습자는 숙련된 행동 사례에서 출발할 수 있다. 시범은 행동 공간에서 유망한 영역에 대한 강력한 사전정보(prior)를 제공하며, 이후 강화학습, 계획 또는 자율 탐색을 통해 최초 시범보다 더 발전된 행동으로 개선할 수 있다.

능동학습(Active Learning)은 학습자가 어떤 정보를 획득할지를 스스로 결정할 수 있도록 하여 학습자의 역할을 변화시킨다. 고정된 데이터셋을 수동적으로 받아들이는 대신, 시스템은 불확실하거나 정보 가치가 높은 사례를 식별하고 라벨, 관찰, 실험 또는 시범을 요청할 수 있다. 이는 정보 탐색 행동(information-seeking behavior)을 학습 과정에 도입하며 학습을 추론, 불확실성 추정(uncertainty estimation), 탐색(exploration), 의사결정과 연결한다.

커리큘럼 학습(Curriculum Learning)은 경험이 제시되는 순서가 학습 효율에 영향을 미칠 수 있다는 점을 활용한다. 어려운 능력은 더 단순한 개념이나 작업이 먼저 유용한 기반을 형성할 때 더욱 안정적으로 나타날 수 있다. 생물학적 학습은 지각, 운동 기술, 언어, 사회적 이해, 추상적 추론이 점진적으로 구축되는 발달적 순서(developmental sequence)를 자연스럽게 따른다. 인공 에이전트도 단순한 경험에서 점점 복잡한 작업으로 진행하는 구조화된 학습 과정의 도움을 받을 수 있다.

전이학습(Transfer Learning)은 이전에 획득한 표상과 기술을 새로운 작업에 활용할 수 있도록 한다. 통합 학습자는 각각의 능력을 독립적으로 구축하는 대신 재사용 가능한 지식을 보존하고 목표나 환경이 변화할 때 이를 적응시켜야 한다. 미래에 가능한 작업의 수는 사실상 무한하기 때문에 전이는 AGI에서 특히 중요하다. 따라서 지능은 새로운 작업이 등장할 때마다 빈 상태에서 다시 학습하는 것이 아니라 기존 역량을 지속적으로 축적해야 한다.

지속학습(Continual Learning)은 이러한 원리를 에이전트의 전체 생애에 걸쳐 확장한다. 새로운 경험은 기존의 유용한 능력을 불필요하게 파괴하지 않으면서 기존 지식을 수정해야 한다. 이는 안정성-가소성 문제(stability-plasticity problem)를 발생시킨다. 학습자는 새로운 정보에 적응할 수 있을 만큼 충분한 가소성(plasticity)을 유지하면서 가치 있는 지식을 보존할 만큼 안정적이어야 한다. 기억 재생(memory replay), 모듈형 아키텍처(modular architecture), 공고화(consolidation), 검색(retrieval), 선택적 매개변수 갱신(selective parameter update) 등이 이러한 균형을 지원할 수 있다.

메타학습(Meta-Learning)은 개별 기술의 습득을 넘어 적응하는 방법 자체를 학습하는 방향으로 확장된다. 다양한 작업에서 얻은 경험은 어떤 표상, 초기화 전략(initialization strategy), 탐색 행동, 갱신 메커니즘이 빠른 학습을 가능하게 하는지를 보여줄 수 있다. 따라서 메타학습 에이전트는 이전의 학습 경험을 활용하여 미래 학습의 효율을 향상시킬 수 있으며, 초기 학습 단계에서 명시적으로 예상하지 않았던 작업에도 퓨샷 적응(few-shot adaptation)을 가능하게 할 수 있다.

멀티모달 학습(Multimodal Learning)은 시각, 언어, 오디오, 촉각, 고유수용감각(proprioception), 라이다(LiDAR) 및 기타 센서 채널의 정보를 통합한다. 서로 다른 모달리티(modality)는 동일한 세계에 대한 상호보완적인 증거를 제공한다. 언어는 의미 구조를 제공하고, 시각은 외형과 기하학적 정보를 제공하며, 물리적 상호작용은 질량, 마찰, 행동유도성(affordance)을 드러낼 수 있다. 통합 지능은 각각의 모달리티를 독립적으로 학습하기보다 공유 표상(shared representation) 안에서 이러한 신호를 연결해야 한다.

예측학습(Predictive Learning)은 여러 학습 패러다임을 연결할 수 있는 공통 원리를 제공한다. 에이전트는 누락된 정보, 미래 상태, 행동의 결과, 보상 또는 잠재 동역학(latent dynamics)을 예측하면서 학습할 수 있다. 이후 예측오차(prediction error)가 내부 표상을 개선하는 학습 신호를 제공한다. 이러한 관점에서 지각, 자기지도학습, 월드 모델링(world modeling), 행동학습(action learning)은 모두 예상된 결과와 실제 관찰 사이의 오류를 감소시키는 과정으로 부분적으로 이해할 수 있다.

월드 모델(World Model)은 학습 통합을 위한 특히 중요한 프레임워크를 제공한다. 월드 모델은 환경의 개체(entity), 상태(state), 관계, 동역학(dynamics), 가능한 전이(transition)를 표현하려 한다. 자기지도 관찰은 지각 구조를 학습하고, 행동은 인과적 동역학(causal dynamics)을 드러내며, 강화학습은 가치 있는 결과를 식별하고, 언어는 의미 지식(semantic knowledge)을 제공할 수 있다. 이러한 서로 다른 학습 신호가 공유된 내부 모델의 서로 다른 측면을 함께 갱신할 수 있다.

따라서 표상학습(Representation Learning)은 통합의 핵심에 위치한다. 모든 작업이 완전히 독립적인 내부 특징을 구축한다면 지식 전이는 어렵고 계산적으로도 비효율적이다. 공유 표상을 사용하면 하나의 정보원에서 학습된 내용이 다른 영역에도 도움을 줄 수 있다. 지각, 언어, 행동, 기억, 예측은 상호보완적인 제약조건을 제공하여 의미적, 공간적, 시간적, 물리적, 인과적 정보를 포함하는 표상을 형성할 수 있다.

통합 학습 아키텍처(Unified Learning Architecture)가 모든 학습 신호를 동일하게 처리해야 한다는 의미는 아니다. 서로 다른 신호는 서로 다른 종류의 정보를 제공하며 서로 다른 시간 규모(timescale)에서 작동한다. 지도 정보는 정확한 의미적 교정을 제공하고, 자기지도는 지속적인 표상학습을 지원하며, 강화학습은 장기적인 가치를 전달하고, 모방은 기술 습득을 가속할 수 있다. 통합은 이러한 차이를 제거하는 것이 아니라 서로 다른 신호 사이의 조정을 의미한다.

따라서 학습은 다목적 최적화 과정(Multi-Objective Optimization Process)으로 볼 수 있다. 지능적인 에이전트는 동시에 예측오차를 최소화하고, 작업 성능을 향상시키며, 기대 보상을 최대화하고, 기존 지식을 보존하며, 안전한 행동을 유지하고, 불확실성을 감소시킬 수 있다. 이러한 목표는 서로 충돌할 수 있기 때문에 맥락에 따라 동적으로 균형을 조정하는 메커니즘이 필요하다. 따라서 AGI에는 개별적인 학습 알고리즘뿐만 아니라 학습 자체를 제어하는 능력도 필요하다.

기억(Memory)은 서로 다른 학습 패러다임 사이에 연속성을 제공한다. 상호작용을 통해 수집된 경험은 이후 자기지도학습, 강화학습 갱신, 모방, 검색, 추론 또는 계획에 활용될 수 있다. 일화기억(episodic memory)은 특정 사건을 보존하고, 의미기억(semantic memory)은 보다 일반적인 지식을 추출하며, 절차기억(procedural memory)은 기술을 유지한다. 기억 공고화(memory consolidation)는 반복된 경험을 미래의 작업과 환경에서도 사용할 수 있는 안정적인 표상으로 변환할 수 있다.

탐색(Exploration)은 어떤 경험이 학습에 이용될 수 있는지를 결정한다. 무작위 탐색(random exploration)은 특히 물리적 시스템에서는 비효율적이거나 위험할 수 있다. 지능적인 탐색은 새로움(novelty), 불확실성, 예상 정보이득(expected information gain), 작업 관련성, 예측된 가치 등을 우선시할 수 있다. 이는 능동학습과 강화학습을 호기심 기반 행동(curiosity-driven behavior), 월드 모델 개선, 자율 실험(autonomous experimentation)과 연결하여 에이전트가 자신의 학습 분포(training distribution)를 구성하는 과정에 직접 참여하도록 한다.

체화 에이전트(Embodied Agent)에서는 지각과 행동을 명확하게 분리할 수 없기 때문에 학습 통합이 특히 중요하다. 로봇은 세계를 관찰하고, 행동을 선택하고, 환경을 변화시키며, 새로운 감각 정보를 받고, 그 결과로 나타난 상태 전이로부터 학습한다. 시범은 초기 행동을 제공하고, 자기지도학습은 지각을 향상시키며, 강화학습은 제어를 최적화하고, 월드 모델 학습은 행동의 결과를 예측할 수 있다. 이러한 모든 과정은 동일한 지각-행동 순환(perception-action loop) 안에서 이루어진다.

언어(Language)는 추가적인 통합 계층(unifying layer)으로 기능할 수 있다. 명령은 목표를 정의하고, 시범은 언어적으로 설명될 수 있으며, 관찰은 의미적 개념과 연결되고, 피드백은 성공이나 실패의 이유를 설명할 수 있다. 또한 언어를 통해 다른 에이전트나 인간이 획득한 지식이 직접적인 물리적 경험 없이도 학습 과정에 들어올 수 있다. 이는 문화적으로 축적된 지식(culturally accumulated knowledge)과 개별적으로 획득한 감각운동 경험(sensorimotor experience) 사이에 연결고리를 형성한다.

적응적 계산(Adaptive Computation) 역시 학습에 영향을 주어야 한다. 모든 관찰에 동일한 수준의 계산 노력이나 매개변수 갱신이 필요한 것은 아니다. 익숙하고 예측 가능한 상황에서는 추가적인 학습이 거의 필요하지 않을 수 있지만, 새로움, 높은 불확실성, 실패, 예상하지 못한 상태 전이가 발생하면 더 깊은 처리와 강한 갱신이 필요할 수 있다. 이러한 사건 기반 학습(event-driven learning)은 상당한 새로운 정보를 제공하는 경험에 적응을 집중하면서 계산 효율을 향상시킬 수 있다.

안전(Safety)과 정렬(Alignment)은 통합 학습에 제약조건을 추가한다. 자율 시스템은 허용할 수 없는 결과를 고려하지 않은 채 보상이나 탐색만을 최대화해서는 안 된다. 학습 목표는 안전 경계(safety boundary), 인간의 선호, 운영 제약조건, 불확실성을 고려하는 의사결정 정책과 함께 존재해야 한다. 따라서 일반지능은 효율적으로 학습하는 방법뿐만 아니라 탐색과 적응 과정에서도 어떤 행동이 금지되어야 하는지를 판단하는 메커니즘을 필요로 한다.

통합 학습의 평가(Evaluation)는 하나의 정적인 데이터셋에서 나타나는 성능만 측정해서는 안 된다. 유능한 시스템은 여러 형태의 피드백으로부터 학습하고, 작업 사이에서 지식을 전이하며, 제한된 사례로부터 적응하고, 이전 기술을 유지하며, 새로운 모달리티를 통합하고, 분포 변화(distribution shift)에서 회복하며, 상호작용을 통해 지속적으로 개선할 수 있어야 한다. 따라서 표본 효율(sample efficiency), 지속적 적응, 강건성(robustness), 전이, 기억 유지(memory retention), 계산 비용 등이 학습 품질을 평가하는 중요한 기준이 된다.

궁극적으로 학습 패러다임 통합(Learning-Paradigm Unification)은 학습을 서로 분리된 알고리즘들의 집합에서 지속적인 적응 과정(continuous adaptive process)으로 전환한다. 일반지능 에이전트는 라벨이 존재할 때는 그것으로부터 학습하고, 라벨이 없을 때는 구조를 스스로 발견하며, 경험으로부터 미래를 예측하고, 유용한 행동을 모방하며, 불확실한 상황을 탐색하고, 행동의 결과를 최적화하며, 이전 지식을 전이하고, 자신의 월드 모델을 지속적으로 수정해야 한다. 목표는 하나의 만능 학습 알고리즘이 아니라 여러 학습 메커니즘이 협력하여 점점 더 일반적인 지능을 구축하는 조정된 아키텍처(coordinated architecture)를 만드는 것이다.

##  

## 01.05. Embodiment

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

Embodiment describes the idea that intelligence is shaped by the continuous interaction between an agent, its body, and the environment. Intelligence is therefore not only computation performed on abstract information. Perception depends on how an agent senses the world, action depends on its physical capabilities, and learning emerges from the consequences of interaction. For AGI, embodiment connects cognition with situated experience.

A body determines which aspects of the environment an agent can observe and which actions it can perform. Cameras, eyes, microphones, tactile sensors, joints, wheels, hands, and other structures create different perceptual and action spaces. Intelligence develops within these constraints. The same environment can therefore produce very different internal representations depending on the sensing, mobility, manipulation, and computational capabilities available to an agent.

Embodied intelligence operates through a perception-action loop. The agent observes its environment, interprets the current state, selects an action, changes the world through that action, and receives new observations reflecting the consequences. This cycle repeats continuously. Perception and action are therefore mutually dependent processes rather than isolated modules, because actions determine which future observations become available for subsequent learning and reasoning.

Active perception illustrates this relationship clearly. An intelligent agent does not need to passively accept whatever information happens to arrive. It can move a camera, approach an object, change its viewpoint, touch a surface, manipulate an item, or explore an uncertain region to obtain better information. Perception thus becomes a goal-directed activity in which actions are deliberately selected to reduce uncertainty and improve understanding.

Sensorimotor learning develops representations from relationships between sensory observations and physical actions. A robot may learn that certain visual patterns correspond to reachable objects, that particular motor commands produce predictable movements, or that contact forces reveal physical properties. Such knowledge grounds abstract representations in interaction, allowing concepts to become connected with what the agent can perceive, predict, manipulate, and control.

Affordances describe action possibilities provided by the relationship between an agent and its environment. An object may be graspable, movable, traversable, pushable, openable, or usable as a tool depending on both its properties and the agent\'s capabilities. Affordance learning therefore shifts perception from simply identifying what something is toward understanding what can be done with it, providing an important connection between recognition and purposeful action.

Physical interaction also provides information that passive observation cannot easily reveal. Mass, friction, compliance, stability, resistance, texture, and mechanical constraints may become apparent only when an agent acts upon an object or surface. Embodied learning can therefore use action as an experiment. The resulting state transitions provide evidence about hidden properties and help the agent refine models of physical dynamics and causal relationships.

Causality becomes especially important in embodied intelligence because actions are interventions in the environment. When an agent pushes an object and observes movement, it receives evidence about how its action influenced the resulting state. Repeated interactions can help distinguish causal relationships from passive correlations. This enables more reliable prediction when the agent must reason about what will happen if it chooses a particular action.

A world model can organize embodied experience into internal representations of entities, states, spatial relationships, dynamics, actions, and possible transitions. Rather than reacting directly to sensor inputs, an embodied agent can use such a model to predict consequences before acting. The world model therefore becomes an internal simulation environment connecting perception, physical experience, reasoning, planning, control, and learning.

Spatial intelligence is a fundamental component of embodiment. An agent must understand where objects are located, how spaces are connected, which regions are reachable, and how its own body is positioned relative to the environment. Navigation requires representations of geometry, topology, motion, obstacles, and uncertainty. Manipulation similarly requires spatial relationships among the agent, objects, tools, targets, and surrounding structures.

Proprioception provides information about the agent\'s own physical state. Biological organisms sense joint position, muscle tension, balance, and body configuration, while robots use encoders, inertial sensors, force sensors, motor feedback, and state estimators. Combining proprioception with external perception allows an agent to distinguish changes caused by its own movement from changes occurring independently in the environment.

Embodiment also introduces physical constraints that intelligence must respect. Actions consume energy, require time, encounter mechanical limits, and may create irreversible consequences. A purely digital agent can often retry computations cheaply, whereas a physical robot may damage itself, nearby objects, or people through an incorrect action. Planning in embodied systems must therefore incorporate feasibility, safety, uncertainty, energy, and recovery strategies.

Real-time operation creates another important constraint. Physical environments continue changing while an agent reasons. A robot cannot always suspend interaction while performing unlimited computation. Perception, prediction, planning, and control must operate within deadlines determined by environmental dynamics. Embodied intelligence therefore benefits from hierarchical processing in which fast reactive mechanisms coexist with slower deliberative reasoning and long-horizon planning.

Adaptive computation can help manage these requirements. Familiar and predictable situations may be handled using lightweight perception and learned policies, while unexpected obstacles, uncertain observations, failures, or hazardous conditions can activate deeper reasoning and replanning. This allows computational effort to scale with novelty, uncertainty, risk, and task importance rather than remaining uniformly high during every moment of operation.

Embodiment makes multimodal integration particularly important. A physical agent may combine cameras, depth sensors, LiDAR, radar, microphones, tactile sensors, force measurements, proprioception, and language. Each modality provides partial information about the environment. Integrating them can produce representations that are more robust than any single sensor stream, particularly when visibility, noise, occlusion, or environmental conditions reduce individual sensor reliability.

Temporal understanding is equally essential because physical intelligence concerns processes rather than isolated observations. Objects move, humans change intentions, vehicles accelerate, doors open, batteries discharge, and terrain conditions vary. An embodied agent must connect observations across time to estimate velocity, predict future states, detect changes, and understand how actions alter trajectories. Dynamic representations are therefore central to physical reasoning.

Embodied learning naturally connects self-supervised learning with interaction. Consecutive observations provide temporal relationships, actions provide information about state transitions, and multimodal sensors provide mutually constraining views of the same environment. These signals can generate learning objectives without requiring detailed human annotation. The agent\'s own experience thus becomes a continuous source of supervision for representation and world-model learning.

Reinforcement learning provides another mechanism for embodied adaptation because actions produce consequences that can be evaluated relative to goals. However, physical exploration can be expensive or unsafe. Random trial and error is therefore often inappropriate for real robots. Demonstrations, simulation, offline experience, model-based prediction, safety constraints, and carefully controlled exploration can reduce the amount of risky real-world interaction required for learning.

Simulation plays an important role because it allows embodied agents to experience large numbers of situations without the cost and danger of physical execution. Yet simulation inevitably differs from reality in dynamics, sensing, contact, materials, and environmental complexity. Sim-to-real transfer therefore requires representations and policies that remain robust when assumptions learned in simulation encounter variations and imperfections in the physical world.

Language can connect embodied experience with abstract and socially transmitted knowledge. An agent may receive instructions such as identifying an object, moving to a location, using a tool, or avoiding a hazardous region. To execute such instructions reliably, linguistic concepts must connect to perceptual entities, spatial relationships, actions, and consequences. Embodied grounding therefore links language symbols with states and interactions in the world.

Social embodiment extends this idea to environments containing humans and other agents. Physical intelligence may require interpreting gestures, personal space, intentions, cooperation, competition, and social conventions. A service robot, autonomous vehicle, or collaborative manipulator must reason not only about geometry and dynamics but also about how its actions affect people and how human behavior may respond to the agent\'s presence.

Morphology can itself contribute to intelligent behavior. The shape, compliance, joint arrangement, mechanical structure, and passive dynamics of a body can simplify control by allowing physical properties to perform part of the computation. This idea, sometimes associated with morphological computation, shows that intelligent behavior does not necessarily originate entirely in a central processor. Body design and control architecture can cooperate to produce efficient behavior.

Tool use extends the effective body of an intelligent agent. Humans dramatically expand their capabilities through tools, and robots can similarly use manipulators, external sensors, vehicles, software services, or specialized devices. Effective tool use requires understanding how an external object changes the agent\'s available actions. This transforms embodiment from a fixed physical boundary into an adaptable relationship among body, tools, environment, and goals.

Memory gives embodied experience continuity. An agent can remember locations, objects, interactions, failures, successful strategies, and environmental changes. Episodic memories preserve particular experiences, semantic memory extracts general knowledge, and procedural memory retains useful skills. Retrieval allows previous encounters to influence current action, enabling an embodied system to improve rather than treating every physical situation as entirely new.

Embodiment also changes how intelligence should be evaluated. Performance cannot be measured only through static question answering or offline prediction accuracy. Evaluation should examine whether an agent can perceive reliably, adapt to environmental variation, interact safely, recover from failures, learn from experience, transfer skills, operate under resource constraints, and achieve goals through sustained interaction with a changing physical world.

Ultimately, embodiment connects intelligence to the consequences of action. An embodied agent does not merely describe or predict the world; it participates in it. Its observations depend on previous actions, its actions generate new experience, and that experience continually modifies perception, memory, world models, reasoning, and future behavior. For AGI, embodiment provides a foundation for grounding abstract intelligence within continuous perception, interaction, adaptation, and purposeful action.

체화(Embodiment)는 지능이 에이전트(agent), 신체(body), 환경(environment) 사이의 지속적인 상호작용에 의해 형성된다는 개념을 설명한다. 따라서 지능은 추상적인 정보에 대해서만 수행되는 계산이 아니다. 지각(perception)은 에이전트가 세계를 어떻게 감지하는지에 의존하고, 행동(action)은 물리적 능력에 의해 결정되며, 학습(learning)은 상호작용의 결과로부터 발생한다. AGI에서 체화는 인지(cognition)를 상황 속 경험(situated experience)과 연결한다.

신체(Body)는 에이전트가 환경의 어떤 측면을 관찰할 수 있고 어떤 행동을 수행할 수 있는지를 결정한다. 카메라, 눈, 마이크, 촉각 센서(tactile sensor), 관절, 바퀴, 손과 같은 구조는 서로 다른 지각 공간(perceptual space)과 행동 공간(action space)을 형성한다. 지능은 이러한 제약조건 안에서 발달한다. 따라서 동일한 환경이라도 에이전트가 가진 감지, 이동, 조작, 계산 능력에 따라 매우 다른 내부 표상(internal representation)이 형성될 수 있다.

체화 지능(Embodied Intelligence)은 지각-행동 순환(perception-action loop)을 통해 작동한다. 에이전트는 환경을 관찰하고, 현재 상태를 해석하고, 행동을 선택하며, 그 행동을 통해 세계를 변화시키고, 그 결과를 반영하는 새로운 관찰을 획득한다. 이러한 순환은 지속적으로 반복된다. 따라서 행동이 이후의 학습과 추론에 사용할 수 있는 미래 관찰을 결정하기 때문에 지각과 행동은 서로 분리된 모듈이 아니라 상호의존적인 과정이다.

능동적 지각(Active Perception)은 이러한 관계를 명확하게 보여준다. 지능적인 에이전트는 우연히 들어오는 정보를 수동적으로 받아들일 필요가 없다. 더 나은 정보를 얻기 위해 카메라를 움직이고, 객체에 접근하며, 관점을 변경하고, 표면을 만지고, 물체를 조작하거나, 불확실한 영역을 탐색할 수 있다. 따라서 지각은 불확실성을 줄이고 이해를 향상시키기 위해 의도적으로 행동을 선택하는 목표지향적 활동(goal-directed activity)이 된다.

감각운동 학습(Sensorimotor Learning)은 감각 관찰과 물리적 행동 사이의 관계로부터 표상을 형성한다. 로봇은 특정한 시각적 패턴이 접근 가능한 객체와 대응한다는 것, 특정 모터 명령이 예측 가능한 움직임을 발생시킨다는 것, 접촉력이 물리적 속성을 나타낸다는 것을 학습할 수 있다. 이러한 지식은 추상적 표상을 상호작용에 접지(grounding)하여 개념을 에이전트가 지각하고, 예측하고, 조작하고, 제어할 수 있는 대상과 연결한다.

행동유도성(Affordance)은 에이전트와 환경 사이의 관계가 제공하는 행동 가능성을 의미한다. 어떤 객체는 그 속성과 에이전트의 능력에 따라 잡을 수 있고, 이동시킬 수 있으며, 통과하거나, 밀거나, 열거나, 도구로 사용할 수 있다. 따라서 행동유도성 학습(affordance learning)은 단순히 대상이 무엇인지를 식별하는 지각에서 벗어나 그것으로 무엇을 할 수 있는지를 이해하도록 하며, 인식(recognition)과 목적지향적 행동 사이의 중요한 연결을 제공한다.

물리적 상호작용(Physical Interaction)은 수동적인 관찰만으로는 쉽게 알기 어려운 정보도 제공한다. 질량, 마찰, 순응성(compliance), 안정성, 저항, 질감, 기계적 제약조건 등은 에이전트가 객체나 표면에 직접 행동을 가했을 때 드러날 수 있다. 따라서 체화 학습(embodied learning)은 행동을 하나의 실험으로 활용할 수 있다. 그 결과 발생하는 상태 전이(state transition)는 숨겨진 속성에 대한 증거를 제공하고 물리적 동역학과 인과관계에 대한 모델을 개선하도록 돕는다.

인과성(Causality)은 행동이 환경에 대한 개입(intervention)이기 때문에 체화 지능에서 특히 중요하다. 에이전트가 객체를 밀고 그 움직임을 관찰하면 자신의 행동이 결과 상태에 어떻게 영향을 미쳤는지에 대한 증거를 얻는다. 반복적인 상호작용은 수동적인 상관관계와 실제 인과관계를 구분하는 데 도움을 줄 수 있다. 이를 통해 에이전트는 특정 행동을 선택했을 때 무엇이 발생할지를 더욱 신뢰성 있게 예측할 수 있다.

월드 모델(World Model)은 체화된 경험을 개체(entity), 상태(state), 공간적 관계(spatial relationship), 동역학(dynamics), 행동, 가능한 전이의 내부 표상으로 구성할 수 있다. 체화 에이전트는 센서 입력에 직접 반응하는 대신 이러한 모델을 이용하여 실제 행동을 수행하기 전에 결과를 예측할 수 있다. 따라서 월드 모델은 지각, 물리적 경험, 추론(reasoning), 계획(planning), 제어(control), 학습을 연결하는 내부 시뮬레이션 환경(internal simulation environment)이 된다.

공간 지능(Spatial Intelligence)은 체화의 핵심적인 구성요소이다. 에이전트는 객체가 어디에 위치하는지, 공간이 어떻게 연결되는지, 어떤 영역에 도달할 수 있는지, 자신의 신체가 환경에 대해 어떤 위치와 자세를 가지는지를 이해해야 한다. 내비게이션(navigation)은 기하학, 위상(topology), 움직임, 장애물, 불확실성에 대한 표상을 필요로 한다. 조작(manipulation) 역시 에이전트, 객체, 도구, 목표물, 주변 구조 사이의 공간적 관계를 이해해야 한다.

고유수용감각(Proprioception)은 에이전트 자신의 물리적 상태에 대한 정보를 제공한다. 생물학적 유기체는 관절 위치, 근육 긴장, 균형, 신체 구성을 감지하며, 로봇은 엔코더(encoder), 관성 센서(inertial sensor), 힘 센서(force sensor), 모터 피드백, 상태 추정기(state estimator)를 사용한다. 고유수용감각과 외부 지각을 결합하면 에이전트는 자신의 움직임 때문에 발생한 변화와 환경 자체에서 독립적으로 발생한 변화를 구분할 수 있다.

체화는 지능이 반드시 고려해야 하는 물리적 제약조건(physical constraint)도 도입한다. 행동은 에너지를 소비하고, 시간을 필요로 하며, 기계적 한계에 직면하고, 되돌릴 수 없는 결과를 발생시킬 수도 있다. 순수한 디지털 에이전트는 계산을 비교적 저렴하게 다시 시도할 수 있지만 물리적 로봇은 잘못된 행동으로 자신이나 주변 객체 또는 사람에게 손상을 줄 수 있다. 따라서 체화 시스템의 계획에는 실행 가능성(feasibility), 안전, 불확실성, 에너지, 복구 전략(recovery strategy)이 포함되어야 한다.

실시간 작동(Real-Time Operation)은 또 다른 중요한 제약조건을 만든다. 물리적 환경은 에이전트가 추론하는 동안에도 계속 변화한다. 로봇은 무제한적인 계산을 수행하는 동안 항상 상호작용을 중단할 수 있는 것이 아니다. 지각, 예측, 계획, 제어는 환경 동역학에 의해 결정되는 시간 제한 내에서 수행되어야 한다. 따라서 체화 지능은 빠른 반응 메커니즘과 느린 숙고적 추론(deliberative reasoning), 장기 계획(long-horizon planning)이 공존하는 계층적 처리(hierarchical processing)의 도움을 받을 수 있다.

적응적 계산(Adaptive Computation)은 이러한 요구조건을 관리하는 데 도움을 줄 수 있다. 익숙하고 예측 가능한 상황은 가벼운 지각 처리와 학습된 정책(policy)을 사용하여 처리하고, 예상하지 못한 장애물, 불확실한 관찰, 실패 또는 위험한 조건이 발생하면 더 깊은 추론과 재계획(replanning)을 활성화할 수 있다. 이를 통해 모든 순간에 동일하게 높은 계산량을 유지하지 않고 새로움(novelty), 불확실성, 위험, 작업 중요도에 따라 계산 노력을 조절할 수 있다.

체화에서는 멀티모달 통합(Multimodal Integration)이 특히 중요하다. 물리적 에이전트는 카메라, 깊이 센서(depth sensor), 라이다(LiDAR), 레이더(radar), 마이크, 촉각 센서, 힘 측정, 고유수용감각, 언어를 결합할 수 있다. 각 모달리티(modality)는 환경에 대한 부분적인 정보를 제공한다. 이를 통합하면 특히 가시성, 잡음, 가림(occlusion), 환경 조건으로 개별 센서의 신뢰성이 감소할 때 단일 센서 스트림보다 더욱 강건한 표상을 형성할 수 있다.

시간적 이해(Temporal Understanding) 역시 필수적이다. 물리적 지능은 고립된 관찰이 아니라 변화하는 과정과 관련되기 때문이다. 객체는 움직이고, 인간은 의도를 바꾸며, 차량은 가속하고, 문은 열리고, 배터리는 방전되며, 지형 조건도 변한다. 체화 에이전트는 시간에 따른 관찰을 연결하여 속도를 추정하고, 미래 상태를 예측하고, 변화를 감지하며, 행동이 궤적(trajectory)을 어떻게 변화시키는지를 이해해야 한다. 따라서 동적 표상(dynamic representation)은 물리적 추론의 핵심이다.

체화 학습은 자기지도학습(Self-Supervised Learning)을 상호작용과 자연스럽게 연결한다. 연속된 관찰은 시간적 관계를 제공하고, 행동은 상태 전이에 대한 정보를 제공하며, 멀티모달 센서는 동일한 환경에 대한 상호 제약적인 관점을 제공한다. 이러한 신호는 상세한 인간 주석(annotation) 없이도 학습 목표를 생성할 수 있다. 따라서 에이전트 자신의 경험 자체가 표상 및 월드 모델 학습을 위한 지속적인 지도 신호(supervision)의 원천이 된다.

강화학습(Reinforcement Learning)은 행동의 결과를 목표와 비교하여 평가할 수 있기 때문에 체화 적응을 위한 또 다른 메커니즘을 제공한다. 그러나 물리적 탐색은 비용이 높거나 위험할 수 있다. 따라서 무작위 시행착오(random trial and error)는 실제 로봇에 적합하지 않은 경우가 많다. 시범(demonstration), 시뮬레이션, 오프라인 경험(offline experience), 모델 기반 예측(model-based prediction), 안전 제약조건, 세심하게 통제된 탐색은 학습에 필요한 위험한 현실 세계 상호작용을 줄일 수 있다.

시뮬레이션(Simulation)은 물리적 실행에 따른 비용과 위험 없이 체화 에이전트가 많은 상황을 경험할 수 있도록 하기 때문에 중요한 역할을 한다. 그러나 시뮬레이션은 동역학, 센싱, 접촉, 재료, 환경 복잡성 측면에서 현실과 필연적으로 차이가 있다. 따라서 시뮬레이션-현실 전이(Sim-to-Real Transfer)를 위해서는 시뮬레이션에서 학습된 가정이 현실 세계의 변화와 불완전성에 직면하더라도 강건하게 작동하는 표상과 정책이 필요하다.

언어(Language)는 체화된 경험을 추상적이고 사회적으로 전달된 지식과 연결할 수 있다. 에이전트는 객체를 식별하고, 특정 위치로 이동하며, 도구를 사용하거나, 위험 지역을 피하라는 명령을 받을 수 있다. 이러한 명령을 신뢰성 있게 실행하려면 언어적 개념이 지각된 개체, 공간적 관계, 행동, 결과와 연결되어야 한다. 따라서 체화된 접지(embodied grounding)는 언어 기호(language symbol)를 실제 세계의 상태와 상호작용에 연결한다.

사회적 체화(Social Embodiment)는 이러한 개념을 인간과 다른 에이전트가 존재하는 환경으로 확장한다. 물리적 지능은 제스처, 개인 공간(personal space), 의도, 협력, 경쟁, 사회적 관습을 해석해야 할 수 있다. 서비스 로봇, 자율주행차, 협동 매니퓰레이터(collaborative manipulator)는 기하학과 동역학뿐 아니라 자신의 행동이 사람에게 어떤 영향을 미치는지, 그리고 인간의 행동이 에이전트의 존재에 어떻게 반응할 수 있는지도 추론해야 한다.

형태학(Morphology) 자체도 지능적 행동에 기여할 수 있다. 신체의 형상, 순응성, 관절 배치, 기계 구조, 수동 동역학(passive dynamics)은 물리적 특성이 계산의 일부를 수행하도록 함으로써 제어를 단순화할 수 있다. 때때로 형태학적 계산(morphological computation)과 연결되는 이러한 개념은 지능적 행동이 반드시 중앙 프로세서에서만 발생하는 것이 아니라 신체 설계와 제어 아키텍처가 협력하여 효율적인 행동을 만들어낼 수 있음을 보여준다.

도구 사용(Tool Use)은 지능적인 에이전트의 유효한 신체 범위를 확장한다. 인간은 도구를 통해 자신의 능력을 크게 확장하며, 로봇 역시 매니퓰레이터, 외부 센서, 차량, 소프트웨어 서비스 또는 전문 장치를 사용할 수 있다. 효과적인 도구 사용을 위해서는 외부 객체가 에이전트에게 가능한 행동을 어떻게 변화시키는지를 이해해야 한다. 이를 통해 체화는 고정된 물리적 경계가 아니라 신체, 도구, 환경, 목표 사이의 적응 가능한 관계로 확장된다.

기억(Memory)은 체화된 경험에 연속성을 부여한다. 에이전트는 위치, 객체, 상호작용, 실패, 성공적인 전략, 환경 변화를 기억할 수 있다. 일화기억(episodic memory)은 특정 경험을 보존하고, 의미기억(semantic memory)은 일반적인 지식을 추출하며, 절차기억(procedural memory)은 유용한 기술을 유지한다. 검색(retrieval)을 통해 이전 경험이 현재 행동에 영향을 미치면서 체화 시스템은 모든 물리적 상황을 완전히 새로운 문제로 취급하지 않고 지속적으로 개선될 수 있다.

체화는 지능을 평가하는 방법도 변화시킨다. 성능은 정적인 질의응답(question answering)이나 오프라인 예측 정확도만으로 측정할 수 없다. 평가는 에이전트가 신뢰성 있게 지각하고, 환경 변화에 적응하며, 안전하게 상호작용하고, 실패로부터 복구하며, 경험으로부터 학습하고, 기술을 전이하며, 자원 제약조건 아래에서 작동하고, 변화하는 물리적 세계와 지속적으로 상호작용하면서 목표를 달성할 수 있는지를 살펴보아야 한다.

궁극적으로 체화(Embodiment)는 지능을 행동의 결과와 연결한다. 체화 에이전트는 세계를 단순히 설명하거나 예측하는 것이 아니라 그 세계에 직접 참여한다. 현재의 관찰은 이전 행동의 영향을 받고, 행동은 새로운 경험을 생성하며, 그 경험은 다시 지각, 기억, 월드 모델, 추론, 미래 행동을 지속적으로 수정한다. AGI에서 체화는 추상적 지능을 지속적인 지각, 상호작용, 적응, 목적지향적 행동(purposeful action)을 통해 실제 세계에 접지하기 위한 기반을 제공한다.

##  

## 01.06. World Models

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

A world model is an internal representation that allows an intelligent agent to organize knowledge about its environment and predict how that environment may change. Rather than responding only to immediate observations, the agent maintains representations of entities, states, relationships, dynamics, and possible transitions. This internal structure enables intelligence to connect past experience with present interpretation and possible future situations.

The central purpose of a world model is prediction. Given a representation of the current state and a possible action, the model estimates what state may follow. Prediction can occur at many levels, from low-level sensory changes to object motion, semantic events, human behavior, or task outcomes. By anticipating future states before acting, an agent can compare alternatives and select actions according to their expected consequences.

World models differ from simple predictive models because they attempt to represent reusable structure rather than only predict a single target variable. A useful world model may contain objects, agents, spatial relationships, physical properties, goals, uncertainties, and transition rules. These representations can support multiple downstream functions such as perception, planning, control, reasoning, simulation, exploration, and learning instead of serving only one predefined task.

State representation is therefore a fundamental design problem. Raw sensor observations contain enormous amounts of information, much of which may be irrelevant to future decisions. A world model must compress observations into states that preserve information necessary for prediction and action. Learned latent states can provide compact representations while semantic or structured states can explicitly represent entities, properties, relationships, and task-relevant concepts.

An observation and a world state are not necessarily the same thing. Sensors provide partial and noisy measurements of reality, while the internal state represents what the agent believes about the underlying environment. An object may temporarily disappear behind an obstacle but remain represented in the world model. This distinction allows an intelligent system to maintain object permanence, track hidden variables, and reason under partial observability.

Temporal modeling connects states across time. Instead of treating individual observations independently, a world model estimates how states evolve and which variables remain stable or change. Motion, velocity, interaction, object transformation, environmental processes, and agent behavior all require temporal representations. Learning these transitions allows the system to move from static recognition toward understanding processes unfolding within the environment.

Dynamics models describe how states change over time, either naturally or because of actions. In an embodied agent, the model may estimate how steering affects vehicle motion, how force changes an object\'s position, or how terrain influences locomotion. More abstract models may predict how actions alter task progress or other agents\' behavior. Dynamics therefore provide the connection between world representation and purposeful intervention.

Actions are especially important because they distinguish passive prediction from interactive intelligence. A model that predicts what usually happens may rely heavily on observed correlations. A model that predicts what will happen when the agent performs a particular action must represent intervention. Learning action-conditioned transitions helps the agent understand controllability and provides a foundation for causal reasoning, planning, and model-based decision-making.

Causal structure can make world models more robust when environments change. Surface correlations may vary across locations, tasks, or operating conditions, while underlying causal mechanisms can remain more stable. An agent that represents how variables influence one another can reason about interventions and unfamiliar combinations more effectively than one relying only on statistical similarity. Causal world models therefore support generalization and transfer.

Uncertainty must also be represented because the future is rarely deterministic or completely observable. Several future states may be possible from the same current state, especially when other agents or unknown environmental factors are involved. A world model should therefore represent distributions, alternative hypotheses, or confidence estimates rather than producing only one certain prediction. Planning can then account for both expected outcomes and associated risks.

Multimodal world models integrate complementary information from different sensors and information sources. Vision may provide appearance and semantics, LiDAR may provide geometry, radar may provide motion information, proprioception may describe the agent\'s own state, and language may provide goals or conceptual knowledge. Combining these modalities can create a richer state representation while increasing robustness when individual information sources become unreliable.

Object-centric representations provide one approach to organizing world knowledge. Instead of representing an entire scene as an undifferentiated feature vector, the model identifies entities and their attributes, relationships, and interactions. This structure can support compositional generalization because familiar objects and relations can appear in previously unseen combinations. Object-centric models also connect naturally with reasoning about persistence, motion, ownership, interaction, and affordances.

Spatial representations describe where entities exist and how they relate geometrically or topologically. For embodied systems, this may include metric maps, occupancy structures, semantic maps, three-dimensional geometry, or bird\'s-eye-view representations. Spatial world models support localization, navigation, collision avoidance, manipulation, and route planning while connecting sensor observations to a persistent representation of the surrounding environment.

Semantic representations add meaning beyond geometry. A region may be recognized not merely as free space but as a road, corridor, doorway, workspace, restricted area, or hazardous zone. Objects can similarly be represented according to category, function, state, or affordance. Combining geometric and semantic information allows planning to consider not only where an agent can move but also what actions are appropriate within different contexts.

Hierarchical world models can represent the environment at several levels of abstraction. Low levels may describe sensory features, geometry, motion, and short-term dynamics, while higher levels represent objects, events, goals, tasks, and longer-term relationships. Hierarchical structure reduces computational complexity because not every decision requires detailed simulation of every variable. Different levels can be activated according to the reasoning and planning requirements of the current situation.

Prediction horizon introduces an important tradeoff. Short-term prediction can retain substantial physical detail and often achieve higher accuracy, while long-term prediction becomes increasingly uncertain. A useful world model may therefore predict near-term states precisely while representing distant futures more abstractly. Receding-horizon operation repeatedly updates predictions as new observations arrive, preventing the agent from depending excessively on increasingly uncertain long-range forecasts.

Generative models provide powerful mechanisms for representing multiple possible futures. Rather than predicting only a single next state, a generative world model can produce alternative future trajectories consistent with the current situation and candidate actions. Techniques based on autoregressive modeling, latent-variable models, diffusion, or related generative methods can support multimodal prediction when several plausible outcomes exist.

Simulation transforms a world model from a predictive representation into a reasoning environment. An agent can internally test candidate actions, estimate resulting states, compare alternative trajectories, and reject undesirable outcomes before acting physically. This process resembles mental simulation in biological intelligence. The ability to simulate possible futures connects world models directly with counterfactual reasoning, planning, risk assessment, and model-based control.

Model-based reinforcement learning uses this capability to reduce dependence on direct trial and error. Instead of learning only from actions executed in the real environment, an agent can use a learned model to generate imagined transitions and evaluate possible policies. If the model is sufficiently accurate, simulated experience can improve sample efficiency. However, planning must account for model error because repeated imagined transitions can accumulate prediction inaccuracies.

World models can also guide exploration. When the model encounters unfamiliar states or produces uncertain predictions, the agent can identify gaps in its knowledge. It may then seek observations or interactions expected to reduce uncertainty and improve the model. Exploration becomes purposeful information gathering rather than random behavior, connecting world-model learning with curiosity, active perception, active learning, and autonomous experimentation.

Memory and world models serve complementary roles. Episodic memory can preserve specific experiences, while a world model extracts reusable regularities from many experiences. Retrieved memories may provide evidence when the model encounters a similar situation, while model predictions can determine which memories are relevant. Over time, repeated experiences can be consolidated into increasingly stable representations of entities, dynamics, relationships, and environmental structure.

Language can extend a world model beyond directly observed experience. Descriptions, instructions, documentation, and communication with other agents can provide information about entities, relationships, rules, hazards, and goals before physical interaction occurs. For general intelligence, linguistic knowledge should connect with perceptual and action-based representations so that statements about the world influence prediction, planning, and behavior rather than remaining isolated symbolic information.

World models are particularly important for embodied intelligence because physical actions have costs and consequences. A robot cannot safely explore every possible action through unrestricted trial and error. Predicting outcomes internally allows it to reject dangerous or inefficient actions before execution. The world model therefore functions as a bridge between perception and safe action, supporting navigation, manipulation, autonomous driving, and other physical tasks.

Real-world environments require continual world-model updating. Objects move, maps change, machines degrade, weather varies, people behave unpredictably, and previously learned relationships may become invalid. A static model eventually becomes inaccurate. Continual learning must therefore update states and dynamics while preserving useful prior knowledge, distinguishing temporary changes from persistent changes and avoiding unnecessary destruction of previously reliable representations.

Adaptive computation can make world-model operation more efficient. Predictable observations may require only lightweight state updates, whereas unexpected events, high uncertainty, or dangerous situations can trigger deeper prediction and simulation. Rather than using maximum computation continuously, the system can allocate resources according to novelty, uncertainty, risk, and planning importance. This is especially valuable for edge and embodied systems with limited energy and compute.

Evaluating world models requires more than measuring one-step prediction accuracy. A useful model should preserve task-relevant information, support long-horizon reasoning, represent uncertainty, generalize to unfamiliar conditions, remain consistent across modalities, and improve downstream planning and control. Evaluation should also examine whether model errors are detected and corrected rather than silently propagated into increasingly unreliable decisions.

Ultimately, a world model gives an intelligent agent an internal arena in which experience can be organized and possible futures can be explored before actions are committed to the external world. By connecting perception, memory, causality, prediction, simulation, reasoning, planning, and learning, it transforms intelligence from reactive pattern matching into anticipatory behavior. For AGI and embodied AI, world models provide a central mechanism for understanding how the world changes and how purposeful action can change it.

월드 모델(World Model)은 지능적인 에이전트(agent)가 자신의 환경에 관한 지식을 구성하고 그 환경이 어떻게 변화할 수 있는지를 예측할 수 있도록 하는 내부 표상(internal representation)이다. 에이전트는 즉각적인 관찰에만 반응하는 대신 개체(entity), 상태(state), 관계(relationship), 동역학(dynamics), 가능한 전이(transition)를 표현한다. 이러한 내부 구조는 지능이 과거의 경험을 현재 상황의 해석 및 가능한 미래 상황과 연결할 수 있도록 한다.

월드 모델의 핵심 목적은 예측(Prediction)이다. 현재 상태에 대한 표상과 가능한 행동이 주어지면 모델은 다음에 어떤 상태가 나타날 수 있는지를 추정한다. 예측은 저수준의 감각 변화에서부터 객체의 움직임, 의미적 사건(semantic event), 인간 행동, 작업 결과에 이르기까지 다양한 수준에서 이루어질 수 있다. 행동하기 전에 미래 상태를 예상함으로써 에이전트는 여러 대안을 비교하고 예상되는 결과에 따라 행동을 선택할 수 있다.

월드 모델은 하나의 목표 변수만을 예측하는 것이 아니라 재사용 가능한 구조를 표현하려 한다는 점에서 단순한 예측 모델(predictive model)과 차이가 있다. 유용한 월드 모델은 객체, 에이전트, 공간 관계, 물리적 속성, 목표, 불확실성, 전이 규칙 등을 포함할 수 있다. 이러한 표상은 하나의 미리 정의된 작업에만 사용되는 것이 아니라 지각, 계획, 제어, 추론, 시뮬레이션, 탐색, 학습과 같은 여러 후속 기능을 지원할 수 있다.

따라서 상태 표상(State Representation)은 근본적인 설계 문제이다. 원시 센서 관찰(raw sensor observation)은 방대한 정보를 포함하지만 그중 상당 부분은 미래의 의사결정과 관련이 없을 수 있다. 월드 모델은 관찰을 압축하면서 예측과 행동에 필요한 정보는 보존하는 상태를 만들어야 한다. 학습된 잠재 상태(latent state)는 압축된 표상을 제공할 수 있으며, 의미적 또는 구조화된 상태는 개체, 속성, 관계, 작업 관련 개념을 명시적으로 표현할 수 있다.

관찰(Observation)과 세계 상태(World State)는 반드시 동일한 것이 아니다. 센서는 현실에 대한 부분적이고 잡음이 포함된 측정값을 제공하지만 내부 상태는 에이전트가 기반 환경에 대해 무엇을 믿고 있는지를 표현한다. 객체가 일시적으로 장애물 뒤로 사라지더라도 월드 모델에는 계속 존재하는 것으로 표현될 수 있다. 이러한 구분을 통해 지능 시스템은 객체 영속성(object permanence)을 유지하고, 숨겨진 변수(hidden variable)를 추적하며, 부분 관측(partial observability) 상황에서 추론할 수 있다.

시간 모델링(Temporal Modeling)은 시간에 따라 상태들을 서로 연결한다. 월드 모델은 개별적인 관찰을 독립적으로 처리하는 대신 상태가 어떻게 변화하고 어떤 변수가 안정적으로 유지되거나 변화하는지를 추정한다. 움직임, 속도, 상호작용, 객체 변환, 환경 과정, 에이전트 행동은 모두 시간적 표상(temporal representation)을 필요로 한다. 이러한 전이를 학습하면 시스템은 정적인 인식에서 벗어나 환경 안에서 전개되는 과정을 이해할 수 있다.

동역학 모델(Dynamics Model)은 상태가 자연적으로 또는 행동에 의해 시간에 따라 어떻게 변화하는지를 설명한다. 체화 에이전트(embodied agent)에서는 조향이 차량 움직임에 어떤 영향을 주는지, 힘이 객체 위치를 어떻게 변화시키는지, 지형이 이동에 어떤 영향을 주는지를 추정할 수 있다. 더 추상적인 모델은 행동이 작업 진행이나 다른 에이전트의 행동을 어떻게 변화시키는지를 예측할 수 있다. 따라서 동역학은 세계 표상과 목적지향적 개입(purposeful intervention)을 연결한다.

행동(Action)은 수동적인 예측과 상호작용 지능(interactive intelligence)을 구분한다는 점에서 특히 중요하다. 일반적으로 어떤 일이 발생하는지를 예측하는 모델은 관찰된 상관관계에 크게 의존할 수 있다. 그러나 에이전트가 특정 행동을 수행했을 때 무엇이 발생할지를 예측하는 모델은 개입(intervention)을 표현해야 한다. 행동 조건부 전이(action-conditioned transition)를 학습하면 에이전트는 제어 가능성(controllability)을 이해할 수 있으며, 인과적 추론, 계획, 모델 기반 의사결정(model-based decision-making)의 기반을 형성할 수 있다.

인과 구조(Causal Structure)는 환경이 변화할 때 월드 모델을 더욱 강건하게 만들 수 있다. 표면적인 상관관계는 위치, 작업, 운영 조건에 따라 달라질 수 있지만 근본적인 인과 메커니즘(causal mechanism)은 더 안정적으로 유지될 수 있다. 변수들이 서로 어떻게 영향을 미치는지를 표현하는 에이전트는 통계적 유사성에만 의존하는 시스템보다 개입과 익숙하지 않은 조합을 더욱 효과적으로 추론할 수 있다. 따라서 인과적 월드 모델(causal world model)은 일반화(generalization)와 전이(transfer)를 지원한다.

미래는 거의 항상 비결정적이거나 완전히 관측되지 않기 때문에 불확실성(Uncertainty) 역시 표현되어야 한다. 특히 다른 에이전트나 알려지지 않은 환경 요인이 존재하는 경우 동일한 현재 상태에서도 여러 미래 상태가 가능할 수 있다. 따라서 월드 모델은 하나의 확정적인 예측만 생성하기보다 분포(distribution), 대안적 가설(alternative hypothesis), 신뢰도 추정(confidence estimate)을 표현해야 한다. 이를 통해 계획은 예상 결과뿐 아니라 그에 수반되는 위험까지 고려할 수 있다.

멀티모달 월드 모델(Multimodal World Model)은 서로 다른 센서와 정보원으로부터 얻은 상호보완적인 정보를 통합한다. 시각은 외형과 의미 정보를 제공하고, 라이다(LiDAR)는 기하학적 정보를 제공하며, 레이더(radar)는 움직임 정보를 제공하고, 고유수용감각(proprioception)은 에이전트 자신의 상태를 설명하며, 언어는 목표나 개념적 지식을 제공할 수 있다. 이러한 모달리티(modality)를 결합하면 개별 정보원의 신뢰성이 떨어지는 상황에서도 더욱 풍부하고 강건한 상태 표상을 만들 수 있다.

객체 중심 표상(Object-Centric Representation)은 세계 지식을 구성하는 하나의 접근법을 제공한다. 전체 장면을 구분되지 않은 하나의 특징 벡터(feature vector)로 표현하는 대신, 모델은 개체와 각각의 속성, 관계, 상호작용을 식별한다. 이러한 구조에서는 익숙한 객체와 관계가 이전에 보지 못한 조합으로 나타날 수 있기 때문에 조합적 일반화(compositional generalization)를 지원할 수 있다. 또한 객체 중심 모델은 영속성, 움직임, 소유, 상호작용, 행동유도성(affordance)에 관한 추론과 자연스럽게 연결된다.

공간 표상(Spatial Representation)은 개체가 어디에 존재하고 기하학적 또는 위상적으로 어떻게 연결되는지를 설명한다. 체화 시스템에서는 메트릭 맵(metric map), 점유 구조(occupancy structure), 의미 지도(semantic map), 3차원 기하학, 조감도 표상(Bird\'s-Eye-View representation) 등이 포함될 수 있다. 공간 월드 모델은 센서 관찰을 주변 환경의 지속적인 표상과 연결하면서 위치추정(localization), 내비게이션, 충돌 회피, 조작, 경로 계획을 지원한다.

의미 표상(Semantic Representation)은 기하학적 정보를 넘어 의미를 추가한다. 어떤 영역은 단순한 빈 공간이 아니라 도로, 복도, 출입구, 작업 공간, 제한 구역 또는 위험 지역으로 인식될 수 있다. 객체 역시 범주(category), 기능, 상태 또는 행동유도성에 따라 표현할 수 있다. 기하학적 정보와 의미적 정보를 결합하면 계획 과정에서 에이전트가 어디로 이동할 수 있는지만이 아니라 서로 다른 맥락에서 어떤 행동이 적절한지도 고려할 수 있다.

계층적 월드 모델(Hierarchical World Model)은 환경을 여러 추상화 수준(level of abstraction)에서 표현할 수 있다. 하위 수준에서는 감각 특징, 기하학, 움직임, 단기 동역학을 표현하고, 상위 수준에서는 객체, 사건, 목표, 작업, 장기적인 관계를 표현할 수 있다. 모든 의사결정에서 모든 변수를 세밀하게 시뮬레이션할 필요가 없기 때문에 계층적 구조는 계산 복잡성을 줄인다. 현재 상황의 추론과 계획 요구조건에 따라 서로 다른 수준을 활성화할 수 있다.

예측 지평(Prediction Horizon)은 중요한 절충관계(tradeoff)를 발생시킨다. 단기 예측은 상당한 물리적 세부 정보를 유지하면서 일반적으로 더 높은 정확도를 달성할 수 있지만, 장기 예측은 미래로 갈수록 불확실성이 증가한다. 따라서 유용한 월드 모델은 가까운 미래 상태를 정밀하게 예측하고 먼 미래는 더욱 추상적으로 표현할 수 있다. 이동 지평 방식(receding-horizon operation)은 새로운 관찰이 들어올 때마다 예측을 반복적으로 갱신하여 점점 불확실해지는 장거리 예측에 지나치게 의존하는 것을 방지한다.

생성 모델(Generative Model)은 여러 가능한 미래를 표현하는 강력한 메커니즘을 제공한다. 생성형 월드 모델(generative world model)은 하나의 다음 상태만 예측하는 대신 현재 상황과 후보 행동에 부합하는 여러 대안적인 미래 궤적(future trajectory)을 생성할 수 있다. 자기회귀 모델링(autoregressive modeling), 잠재변수 모델(latent-variable model), 확산 모델(diffusion model) 및 관련 생성 기법은 여러 개의 그럴듯한 결과가 존재하는 다중양식 예측(multimodal prediction)을 지원할 수 있다.

시뮬레이션(Simulation)은 월드 모델을 단순한 예측 표상에서 추론 환경(reasoning environment)으로 변화시킨다. 에이전트는 실제 물리적 행동을 수행하기 전에 내부적으로 후보 행동을 시험하고, 그 결과 상태를 추정하며, 대안적인 궤적을 비교하고, 바람직하지 않은 결과를 제거할 수 있다. 이러한 과정은 생물학적 지능의 정신적 시뮬레이션(mental simulation)과 유사하다. 가능한 미래를 시뮬레이션하는 능력은 월드 모델을 반사실적 추론(counterfactual reasoning), 계획, 위험 평가, 모델 기반 제어와 직접 연결한다.

모델 기반 강화학습(Model-Based Reinforcement Learning)은 이러한 능력을 활용하여 직접적인 시행착오에 대한 의존도를 줄인다. 실제 환경에서 실행한 행동만으로 학습하는 대신 에이전트는 학습된 모델을 사용하여 상상된 전이(imagined transition)를 생성하고 가능한 정책(policy)을 평가할 수 있다. 모델이 충분히 정확하다면 시뮬레이션 경험은 표본 효율(sample efficiency)을 향상시킬 수 있다. 그러나 상상된 전이가 반복되면 예측 오류가 누적될 수 있으므로 계획 과정에서 모델 오류(model error)를 고려해야 한다.

월드 모델은 탐색(Exploration)을 안내할 수도 있다. 모델이 익숙하지 않은 상태를 만나거나 불확실한 예측을 생성하면 에이전트는 자신의 지식에 존재하는 공백을 식별할 수 있다. 이후 불확실성을 감소시키고 모델을 개선할 것으로 예상되는 관찰이나 상호작용을 선택할 수 있다. 따라서 탐색은 무작위 행동이 아니라 목적을 가진 정보 수집으로 변화하며, 월드 모델 학습을 호기심(curiosity), 능동적 지각(active perception), 능동학습(active learning), 자율 실험(autonomous experimentation)과 연결한다.

기억(Memory)과 월드 모델은 서로 상호보완적인 역할을 수행한다. 일화기억(episodic memory)은 구체적인 경험을 보존할 수 있고, 월드 모델은 여러 경험으로부터 재사용 가능한 규칙성을 추출한다. 모델이 유사한 상황을 만났을 때 검색된 기억이 추가적인 증거를 제공할 수 있으며, 반대로 모델의 예측은 어떤 기억이 관련되어 있는지를 결정할 수 있다. 시간이 지나면서 반복되는 경험은 개체, 동역학, 관계, 환경 구조에 대한 더욱 안정적인 표상으로 공고화(consolidation)될 수 있다.

언어(Language)는 월드 모델을 직접 관찰된 경험의 범위를 넘어 확장할 수 있다. 설명, 명령, 문서, 다른 에이전트와의 의사소통은 실제 물리적 상호작용이 발생하기 전에 개체, 관계, 규칙, 위험, 목표에 대한 정보를 제공할 수 있다. 일반지능에서는 언어적 지식이 고립된 기호 정보(symbolic information)로 남는 것이 아니라 지각 및 행동 기반 표상과 연결되어 세계에 관한 설명이 예측, 계획, 행동에 영향을 미칠 수 있어야 한다.

월드 모델은 물리적 행동에 비용과 결과가 수반되기 때문에 체화 지능(Embodied Intelligence)에서 특히 중요하다. 로봇은 가능한 모든 행동을 제한 없는 시행착오를 통해 안전하게 탐색할 수 없다. 결과를 내부적으로 예측하면 실행 전에 위험하거나 비효율적인 행동을 제거할 수 있다. 따라서 월드 모델은 지각과 안전한 행동 사이의 다리로 기능하며 내비게이션, 조작(manipulation), 자율주행(autonomous driving) 및 다양한 물리적 작업을 지원한다.

실제 환경에서는 월드 모델의 지속적인 갱신이 필요하다. 객체는 움직이고, 지도는 변하며, 기계는 열화되고, 날씨는 달라지고, 사람은 예측하기 어렵게 행동하며, 과거에 학습한 관계가 더 이상 유효하지 않을 수 있다. 정적인 모델은 결국 현실과 맞지 않게 된다. 따라서 지속학습(continual learning)은 유용한 기존 지식을 보존하면서 상태와 동역학을 갱신하고, 일시적인 변화와 지속적인 변화를 구분하며, 이전의 신뢰할 수 있는 표상을 불필요하게 파괴하지 않아야 한다.

적응적 계산(Adaptive Computation)은 월드 모델의 작동을 더욱 효율적으로 만들 수 있다. 예측 가능한 관찰은 가벼운 상태 갱신만 필요할 수 있지만 예상하지 못한 사건, 높은 불확실성 또는 위험한 상황은 더 깊은 예측과 시뮬레이션을 활성화할 수 있다. 시스템은 항상 최대 계산량을 사용하는 대신 새로움(novelty), 불확실성, 위험, 계획 중요도에 따라 계산 자원을 배분할 수 있다. 이는 에너지와 계산 자원이 제한된 엣지 시스템(edge system)과 체화 시스템에서 특히 중요하다.

월드 모델의 평가(Evaluation)는 단순한 1단계 예측 정확도(one-step prediction accuracy)를 측정하는 것 이상이어야 한다. 유용한 모델은 작업에 관련된 정보를 보존하고, 장기 추론을 지원하며, 불확실성을 표현하고, 익숙하지 않은 조건으로 일반화하며, 여러 모달리티 사이에서 일관성을 유지하고, 후속 계획과 제어의 성능을 향상시켜야 한다. 또한 모델 오류가 점점 더 신뢰할 수 없는 의사결정으로 조용히 전파되는 것이 아니라 탐지되고 수정될 수 있는지도 평가해야 한다.

궁극적으로 월드 모델(World Model)은 지능적인 에이전트에게 경험을 조직하고 외부 세계에서 실제 행동을 실행하기 전에 가능한 미래를 탐색할 수 있는 내부 공간을 제공한다. 지각, 기억, 인과성, 예측, 시뮬레이션, 추론, 계획, 학습을 서로 연결함으로써 지능을 반응적인 패턴 매칭(reactive pattern matching)에서 미래를 예상하는 행동(anticipatory behavior)으로 변화시킨다. AGI와 체화 인공지능(Embodied AI)에서 월드 모델은 세계가 어떻게 변화하며 목적지향적 행동이 그 세계를 어떻게 변화시킬 수 있는지를 이해하기 위한 핵심 메커니즘을 제공한다.

##  

## 01.07. Information and Knowledge

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

Information is the reduction of uncertainty through observations, signals, measurements, or communication. An intelligent system continuously receives information from its environment, internal states, memory, and other agents. Yet information alone does not constitute intelligence. The system must determine what signals mean, which are relevant, how they relate to existing experience, and whether they should influence beliefs, predictions, decisions, or actions.

Data, information, and knowledge represent related but distinct levels of organization. Data consists of recorded observations or symbols, while information emerges when those data are interpreted within a context. Knowledge develops when information becomes connected with concepts, relationships, rules, experience, and expectations that can support reasoning or action. Intelligence depends on transforming raw observations progressively into representations that can guide behavior.

The value of information depends strongly on context. The same observation may be critical in one situation and irrelevant in another. A temperature measurement, object location, spoken instruction, or sensor anomaly acquires significance according to the agent\'s goals, current state, uncertainty, and prior knowledge. Intelligent information processing therefore requires selective attention and relevance estimation rather than treating every available signal with equal importance.

Knowledge can be understood as structured information that supports prediction, explanation, reasoning, and action. Knowing an isolated fact is useful, but intelligence becomes more powerful when facts are connected through relationships. Knowledge that a surface is wet, for example, becomes more actionable when connected with concepts such as reduced friction, increased stopping distance, instability, risk, and appropriate changes in movement or control.

Declarative knowledge represents facts, concepts, and relationships that can often be explicitly described. It includes knowledge about objects, categories, properties, locations, events, and rules. An artificial agent may know that batteries store energy, obstacles restrict motion, or certain regions are hazardous. Such knowledge supports explanation and reasoning, but effective intelligence also requires knowing how to perform actions rather than merely describing the world.

Procedural knowledge represents skills and methods for accomplishing tasks. It may describe how to navigate, manipulate an object, operate a tool, solve a problem, or execute a control strategy. Procedural knowledge is often encoded implicitly in policies, programs, motor patterns, or learned parameters rather than explicit propositions. General intelligence requires interaction between declarative understanding and procedural competence so that knowing and doing reinforce one another.

Episodic knowledge preserves information about particular experiences situated in time and context. An agent may remember where an event occurred, which actions were attempted, what outcome followed, and which environmental conditions were present. Such experiences can later provide evidence for reasoning and planning. Episodic information also enables learning from rare events that might disappear if experience were reduced immediately to general statistical patterns.

Semantic knowledge abstracts reusable concepts and relationships from individual experiences. Repeated observations of particular objects, actions, and outcomes can gradually produce general knowledge that applies beyond the original episodes. Semantic knowledge therefore supports generalization by separating stable regularities from incidental details. An intelligent memory system must continually balance preservation of specific experiences with consolidation into broader conceptual structures.

Knowledge representation determines how information becomes accessible to intelligence. Symbolic systems may represent explicit entities, predicates, relations, and rules, while neural systems encode distributed patterns within learned representations. Vector embeddings capture similarity and contextual structure, graphs express relationships, and probabilistic models represent uncertainty. General intelligence may benefit from combining multiple forms rather than assuming that one representation is universally optimal.

Distributed representations allow concepts to be encoded across many interacting dimensions rather than assigning each concept a single isolated symbol. This enables similarity, analogy, and statistical generalization to emerge naturally from representation geometry. Modern neural networks and foundation models rely heavily on such representations. Their strength lies in flexible pattern learning, although their internal knowledge may be difficult to interpret or verify explicitly.

Structured representations provide complementary advantages by making entities and relationships more explicit. Knowledge graphs, relational structures, scene graphs, semantic maps, and symbolic models can preserve information about how concepts are connected. This structure supports compositional reasoning, constraint checking, and interpretable relationships. Combining distributed and structured representations can therefore connect flexible learning with more explicit reasoning.

Uncertainty is an essential property of knowledge because intelligent systems rarely possess complete or perfectly reliable information. A system may be uncertain whether an object exists, whether a sensor reading is accurate, or whether a prediction will occur. Knowledge should therefore include confidence, probability, alternative hypotheses, or evidence quality. Recognizing uncertainty prevents incomplete information from being incorrectly treated as unquestionable fact.

Belief represents an agent\'s current estimate of what is likely to be true given available evidence. New observations can strengthen, weaken, or replace existing beliefs. Probabilistic inference provides formal mechanisms for updating beliefs when evidence arrives, but intelligent systems may also use learned confidence estimates and competing hypotheses. Knowledge is therefore not always static storage; it can be an evolving state continually revised through interaction.

Information fusion combines evidence from multiple sources into more reliable representations. A robot may integrate cameras, LiDAR, radar, proprioception, maps, language, and prior experience when estimating its environment. Different sources may have different resolutions, uncertainties, failure modes, and update rates. Effective fusion must determine not only how signals agree but also which source should be trusted when observations conflict.

Multimodal knowledge extends beyond sensor fusion by connecting different forms of meaning. The concept of an object can include its visual appearance, spoken or written name, physical shape, sound, function, affordances, and interaction history. Connecting these modalities enables knowledge acquired through one channel to influence another. Language can identify an unfamiliar object, while physical interaction can later enrich the linguistic concept with grounded properties.

Grounding connects abstract information with entities, states, actions, and consequences in the world. A symbol such as "door" becomes more meaningful when connected with visual appearances, spatial structures, opening actions, accessibility, and expected state transitions. For embodied intelligence, grounding prevents knowledge from remaining purely symbolic. Concepts become useful because they participate directly in perception, prediction, planning, and physical interaction.

Information is also organized across time. Some knowledge describes stable properties, while other information represents rapidly changing states. An object\'s identity may remain persistent while its position changes continuously. Intelligent systems therefore need temporal representations that distinguish enduring knowledge from transient observations. This distinction is essential for tracking objects, updating maps, detecting changes, predicting events, and maintaining coherent beliefs about a dynamic world.

A world model provides a framework for organizing information and knowledge into an operational representation of the environment. Perceptual information updates estimates of current states, memory contributes previous experience, semantic knowledge provides concepts and relationships, and dynamics describe possible transitions. The resulting model enables knowledge to participate directly in prediction and simulation rather than remaining a passive database of stored facts.

Prediction provides an important test of whether information has been transformed into useful knowledge. If an agent understands relationships among states, actions, and outcomes, it should be able to anticipate at least some consequences of future events. Prediction errors reveal where knowledge is incomplete or incorrect. Learning can then modify representations, allowing knowledge to become progressively better aligned with observed environmental structure and dynamics.

Causal knowledge goes beyond recognizing statistical regularities by describing how changes in one variable can influence another. This distinction becomes essential when an agent must intervene in the world. Correlation may support prediction under familiar conditions, but planning requires understanding how actions produce consequences. Causal knowledge therefore provides a stronger basis for counterfactual reasoning, transfer, diagnosis, and purposeful action.

Knowledge acquisition can occur through many learning paradigms. Supervised learning provides explicit associations, self-supervised learning extracts structure from observations, reinforcement learning connects actions with consequences, imitation provides behavioral examples, and language transfers knowledge accumulated by others. A general intelligence system should integrate these sources so that information obtained through one learning mechanism can improve representations used by others.

Memory retrieval determines which stored knowledge becomes available at a particular moment. An intelligent system cannot efficiently process everything it has ever learned for every decision. Retrieval must therefore identify information relevant to the current observation, question, goal, or uncertainty. Effective retrieval transforms large memory stores into context-sensitive working knowledge and is central to retrieval-augmented systems, agents, and long-term autonomous operation.

Forgetting and compression are also necessary components of intelligent knowledge management. Preserving every observation indefinitely at equal priority would create enormous storage and retrieval costs. Repeated information can be consolidated, irrelevant details can lose priority, and important or unusual experiences can be preserved. Intelligent forgetting is therefore not simply loss; it can be a mechanism for maintaining efficient, useful, and adaptable knowledge.

Knowledge must also be evaluated for provenance and reliability. Information may originate from direct observation, human instruction, documents, other agents, simulations, or model-generated predictions. These sources do not necessarily deserve equal trust. Recording where knowledge came from, when it was acquired, how strongly it is supported, and whether contradictory evidence exists can improve verification and reduce propagation of incorrect assumptions.

Contradictory information creates a further challenge. An intelligent agent may receive evidence that conflicts with stored knowledge or with another source. Simply retaining both claims without evaluation can produce inconsistent reasoning, while immediately replacing old knowledge can destroy useful information. Resolution may require considering recency, source reliability, contextual differences, uncertainty, and additional observations before beliefs are revised.

Knowledge becomes most valuable when it can transfer to unfamiliar situations. Memorizing individual observations may provide high performance within familiar conditions but weak generalization. Abstract concepts, causal relationships, compositional structures, and reusable skills allow an agent to interpret new combinations of entities and events. General intelligence therefore requires knowledge that supports adaptation rather than merely reproducing previously observed patterns.

Metacognition adds knowledge about the system\'s own knowledge state. An intelligent agent should distinguish what it knows, what it believes with uncertainty, what it has forgotten, and what information it still needs. This awareness can trigger retrieval, observation, experimentation, tool use, or requests for assistance. Knowing the limits of available knowledge is therefore itself an important component of intelligent reasoning and safe decision-making.

Ultimately, information becomes valuable to intelligence when it is transformed into organized, grounded, retrievable, and revisable knowledge. An intelligent agent must continuously acquire signals, interpret context, construct representations, integrate evidence, preserve useful experience, estimate uncertainty, and update beliefs. Through memory, learning, world models, reasoning, and action, knowledge becomes not merely stored information but an active structure for understanding the world and deciding what to do next.

정보(Information)는 관찰, 신호, 측정 또는 의사소통을 통해 불확실성(uncertainty)이 감소하는 것을 의미한다. 지능적인 시스템은 환경, 내부 상태, 기억(memory), 다른 에이전트로부터 지속적으로 정보를 받아들인다. 그러나 정보 자체만으로 지능이 형성되는 것은 아니다. 시스템은 신호가 무엇을 의미하는지, 어떤 정보가 관련성이 있는지, 기존 경험과 어떻게 연결되는지, 그리고 그것이 믿음(belief), 예측, 의사결정 또는 행동에 영향을 주어야 하는지를 판단해야 한다.

데이터(Data), 정보(Information), 지식(Knowledge)은 서로 관련되어 있지만 서로 다른 조직화 수준을 나타낸다. 데이터는 기록된 관찰이나 기호(symbol)로 구성되며, 정보는 이러한 데이터가 특정 맥락(context) 안에서 해석될 때 형성된다. 지식은 정보가 개념, 관계, 규칙, 경험, 기대와 연결되어 추론이나 행동을 지원할 수 있을 때 발전한다. 지능은 원시 관찰(raw observation)을 점진적으로 행동을 안내할 수 있는 표상(representation)으로 변환하는 과정에 의존한다.

정보의 가치(Value of Information)는 맥락에 크게 의존한다. 동일한 관찰도 어떤 상황에서는 매우 중요하지만 다른 상황에서는 거의 의미가 없을 수 있다. 온도 측정값, 객체의 위치, 음성 명령, 센서 이상(sensor anomaly)은 에이전트의 목표, 현재 상태, 불확실성, 사전 지식(prior knowledge)에 따라 서로 다른 중요성을 가진다. 따라서 지능적인 정보 처리는 모든 신호를 동일하게 취급하기보다 선택적 주의(selective attention)와 관련성 평가(relevance estimation)를 필요로 한다.

지식(Knowledge)은 예측, 설명, 추론, 행동을 지원하는 구조화된 정보(structured information)로 이해할 수 있다. 하나의 고립된 사실을 아는 것도 유용하지만, 사실들이 관계를 통해 연결될 때 지능은 더욱 강력해진다. 예를 들어 표면이 젖어 있다는 지식은 마찰 감소, 제동거리 증가, 불안정성, 위험, 적절한 이동이나 제어의 변화와 연결될 때 실제 행동에 더욱 유용하게 활용될 수 있다.

선언적 지식(Declarative Knowledge)은 명시적으로 설명할 수 있는 사실, 개념, 관계를 표현한다. 여기에는 객체, 범주(category), 속성, 위치, 사건, 규칙에 대한 지식이 포함된다. 인공 에이전트는 배터리가 에너지를 저장한다는 것, 장애물이 이동을 제한한다는 것, 특정 영역이 위험하다는 것을 알 수 있다. 이러한 지식은 설명과 추론을 지원하지만, 효과적인 지능을 위해서는 세계를 설명하는 것뿐 아니라 실제로 행동하는 방법도 알아야 한다.

절차적 지식(Procedural Knowledge)은 작업을 수행하기 위한 기술과 방법을 표현한다. 여기에는 내비게이션, 객체 조작, 도구 사용, 문제 해결, 제어 전략 실행 방법 등이 포함될 수 있다. 절차적 지식은 명시적인 명제(proposition)보다 정책(policy), 프로그램, 운동 패턴(motor pattern), 학습된 매개변수에 암묵적으로 인코딩되는 경우가 많다. 일반지능은 앎(knowing)과 실행(doing)이 서로 강화되도록 선언적 이해와 절차적 능력 사이의 상호작용을 필요로 한다.

일화적 지식(Episodic Knowledge)은 시간과 맥락 속에서 발생한 특정 경험에 관한 정보를 보존한다. 에이전트는 사건이 어디에서 발생했는지, 어떤 행동을 시도했는지, 어떤 결과가 뒤따랐는지, 당시 어떤 환경 조건이 존재했는지를 기억할 수 있다. 이러한 경험은 이후 추론과 계획에 증거를 제공할 수 있다. 또한 일화 정보는 경험이 즉시 일반적인 통계 패턴으로 축약될 경우 사라질 수 있는 희귀한 사건으로부터 학습할 수 있게 한다.

의미적 지식(Semantic Knowledge)은 개별 경험으로부터 재사용 가능한 개념과 관계를 추상화한다. 특정 객체, 행동, 결과에 대한 반복적인 관찰은 점차 원래 경험을 넘어 적용할 수 있는 일반적인 지식으로 발전할 수 있다. 따라서 의미적 지식은 안정적인 규칙성과 우연한 세부사항을 분리함으로써 일반화(generalization)를 지원한다. 지능적인 기억 시스템은 구체적인 경험의 보존과 더 광범위한 개념 구조로의 공고화(consolidation) 사이에서 지속적으로 균형을 유지해야 한다.

지식 표상(Knowledge Representation)은 정보가 지능에 어떻게 접근 가능한 형태가 되는지를 결정한다. 기호 시스템(symbolic system)은 명시적인 개체, 술어(predicate), 관계, 규칙을 표현할 수 있고, 신경망 시스템은 학습된 표상 내부의 분산된 패턴으로 정보를 인코딩한다. 벡터 임베딩(vector embedding)은 유사성과 맥락 구조를 포착하고, 그래프(graph)는 관계를 표현하며, 확률 모델(probabilistic model)은 불확실성을 표현한다. 일반지능은 하나의 표상 방식이 모든 문제에 최적이라고 가정하기보다 여러 형태를 결합함으로써 이점을 얻을 수 있다.

분산 표상(Distributed Representation)은 각 개념에 하나의 고립된 기호를 할당하는 대신 여러 상호작용하는 차원에 걸쳐 개념을 인코딩한다. 이를 통해 표상 공간의 기하학적 구조에서 유사성, 유추(analogy), 통계적 일반화가 자연스럽게 나타날 수 있다. 현대 신경망과 파운데이션 모델(foundation model)은 이러한 표상에 크게 의존한다. 장점은 유연한 패턴 학습에 있지만 내부 지식을 명시적으로 해석하거나 검증하기 어려울 수 있다는 한계도 존재한다.

구조화된 표상(Structured Representation)은 개체와 관계를 더욱 명시적으로 표현함으로써 상호보완적인 장점을 제공한다. 지식 그래프(knowledge graph), 관계 구조(relational structure), 장면 그래프(scene graph), 의미 지도(semantic map), 기호 모델(symbolic model)은 개념들이 서로 어떻게 연결되는지를 보존할 수 있다. 이러한 구조는 조합적 추론(compositional reasoning), 제약조건 검증, 해석 가능한 관계를 지원한다. 따라서 분산 표상과 구조화된 표상을 결합하면 유연한 학습과 보다 명시적인 추론을 연결할 수 있다.

지능적인 시스템은 완전하거나 완벽하게 신뢰할 수 있는 정보를 거의 보유하지 못하기 때문에 불확실성(Uncertainty)은 지식의 필수적인 속성이다. 시스템은 객체가 실제로 존재하는지, 센서 측정값이 정확한지, 특정 예측이 실제로 발생할지 확신하지 못할 수 있다. 따라서 지식에는 신뢰도(confidence), 확률, 대안적 가설(alternative hypothesis), 증거 품질(evidence quality)이 포함되어야 한다. 불확실성을 인식하면 불완전한 정보가 의심할 수 없는 사실로 잘못 취급되는 것을 방지할 수 있다.

믿음(Belief)은 이용 가능한 증거를 바탕으로 무엇이 사실일 가능성이 높은지에 대한 에이전트의 현재 추정을 나타낸다. 새로운 관찰은 기존 믿음을 강화하거나 약화시키거나 대체할 수 있다. 확률적 추론(probabilistic inference)은 증거가 들어올 때 믿음을 갱신하는 공식적인 메커니즘을 제공하지만, 지능 시스템은 학습된 신뢰도 추정과 경쟁하는 가설을 사용할 수도 있다. 따라서 지식은 항상 정적인 저장물이 아니라 상호작용을 통해 지속적으로 수정되는 상태가 될 수 있다.

정보 융합(Information Fusion)은 여러 정보원으로부터 얻은 증거를 결합하여 더욱 신뢰할 수 있는 표상을 형성한다. 로봇은 환경을 추정할 때 카메라, 라이다(LiDAR), 레이더(radar), 고유수용감각(proprioception), 지도, 언어, 사전 경험을 통합할 수 있다. 서로 다른 정보원은 해상도, 불확실성, 고장 형태(failure mode), 갱신 주기가 다를 수 있다. 효과적인 융합은 신호들이 어떻게 일치하는지만이 아니라 관찰이 충돌할 때 어떤 정보원을 신뢰해야 하는지도 판단해야 한다.

멀티모달 지식(Multimodal Knowledge)은 서로 다른 형태의 의미를 연결함으로써 단순한 센서 융합을 넘어선다. 객체에 대한 하나의 개념에는 시각적 외형, 말하거나 기록된 이름, 물리적 형상, 소리, 기능, 행동유도성(affordance), 상호작용 이력이 포함될 수 있다. 이러한 모달리티(modality)를 연결하면 한 채널을 통해 획득한 지식이 다른 채널에도 영향을 줄 수 있다. 언어는 익숙하지 않은 객체를 식별할 수 있고, 이후 물리적 상호작용은 접지된 속성(grounded property)을 통해 언어적 개념을 더욱 풍부하게 만들 수 있다.

접지(Grounding)는 추상적인 정보를 실제 세계의 개체, 상태, 행동, 결과와 연결한다. 예를 들어 '문(door)'이라는 기호는 시각적 외형, 공간 구조, 문을 여는 행동, 접근 가능성, 예상되는 상태 전이와 연결될 때 더욱 의미 있는 개념이 된다. 체화 지능(embodied intelligence)에서 접지는 지식이 순수한 기호 수준에 머무르는 것을 방지한다. 개념은 지각, 예측, 계획, 물리적 상호작용에 직접 참여함으로써 실질적인 가치를 가지게 된다.

정보는 시간에 따라서도 조직된다. 일부 지식은 안정적인 속성을 설명하지만 다른 정보는 빠르게 변화하는 상태를 나타낸다. 객체의 정체성(identity)은 지속적으로 유지될 수 있지만 위치는 계속 변할 수 있다. 따라서 지능 시스템에는 지속적인 지식과 일시적인 관찰을 구분하는 시간적 표상(temporal representation)이 필요하다. 이러한 구분은 객체 추적, 지도 갱신, 변화 감지, 사건 예측, 동적인 세계에 대한 일관된 믿음을 유지하는 데 필수적이다.

월드 모델(World Model)은 정보와 지식을 환경에 대한 작동 가능한 표상(operational representation)으로 구성하기 위한 프레임워크를 제공한다. 지각 정보는 현재 상태에 대한 추정을 갱신하고, 기억은 이전 경험을 제공하며, 의미적 지식은 개념과 관계를 제공하고, 동역학(dynamics)은 가능한 전이를 설명한다. 이렇게 형성된 모델을 통해 지식은 저장된 사실들의 수동적인 데이터베이스에 머무르지 않고 예측과 시뮬레이션에 직접 참여할 수 있다.

예측(Prediction)은 정보가 유용한 지식으로 변환되었는지를 확인하는 중요한 방법을 제공한다. 에이전트가 상태, 행동, 결과 사이의 관계를 이해하고 있다면 미래 사건의 결과 중 적어도 일부를 예상할 수 있어야 한다. 예측오차(prediction error)는 지식이 불완전하거나 잘못된 부분을 드러낸다. 이후 학습은 표상을 수정하여 지식이 관찰된 환경의 구조와 동역학에 점차 더 정확하게 일치하도록 만들 수 있다.

인과 지식(Causal Knowledge)은 하나의 변수가 다른 변수에 어떤 영향을 미칠 수 있는지를 설명함으로써 통계적 규칙성을 인식하는 수준을 넘어선다. 이러한 차이는 에이전트가 세계에 개입해야 할 때 필수적이다. 상관관계(correlation)는 익숙한 조건에서 예측을 지원할 수 있지만 계획에는 행동이 어떻게 결과를 발생시키는지에 대한 이해가 필요하다. 따라서 인과 지식은 반사실적 추론(counterfactual reasoning), 전이(transfer), 진단(diagnosis), 목적지향적 행동을 위한 더욱 강력한 기반을 제공한다.

지식 획득(Knowledge Acquisition)은 다양한 학습 패러다임을 통해 이루어질 수 있다. 지도학습(supervised learning)은 명시적인 연관성을 제공하고, 자기지도학습(self-supervised learning)은 관찰에서 구조를 추출하며, 강화학습(reinforcement learning)은 행동과 결과를 연결하고, 모방학습(imitation learning)은 행동 사례를 제공하며, 언어는 다른 주체들이 축적한 지식을 전달한다. 일반지능 시스템은 하나의 학습 메커니즘에서 획득한 정보가 다른 메커니즘이 사용하는 표상을 향상시킬 수 있도록 이러한 정보원을 통합해야 한다.

기억 검색(Memory Retrieval)은 특정 순간에 어떤 저장된 지식을 사용할 수 있게 할지를 결정한다. 지능 시스템은 모든 의사결정마다 지금까지 학습한 모든 내용을 효율적으로 처리할 수 없다. 따라서 검색은 현재 관찰, 질문, 목표 또는 불확실성과 관련된 정보를 식별해야 한다. 효과적인 검색은 대규모 기억 저장소를 맥락 민감형 작업 지식(context-sensitive working knowledge)으로 변환하며, 검색 증강 시스템(retrieval-augmented system), 에이전트, 장기간 자율 운영의 핵심 요소가 된다.

망각(Forgetting)과 압축(Compression) 역시 지능적인 지식 관리에 필요한 구성요소이다. 모든 관찰을 동일한 우선순위로 영구히 보존한다면 막대한 저장 및 검색 비용이 발생한다. 반복되는 정보는 공고화할 수 있고, 관련성이 낮은 세부사항은 우선순위를 낮추며, 중요하거나 특이한 경험은 보존할 수 있다. 따라서 지능적인 망각(intelligent forgetting)은 단순한 정보 손실이 아니라 효율적이고 유용하며 적응 가능한 지식을 유지하기 위한 메커니즘이 될 수 있다.

지식은 또한 출처(Provenance)와 신뢰성(Reliability)에 따라 평가되어야 한다. 정보는 직접적인 관찰, 인간의 지시, 문서, 다른 에이전트, 시뮬레이션 또는 모델이 생성한 예측에서 비롯될 수 있다. 이러한 정보원이 반드시 동일한 수준의 신뢰를 받아야 하는 것은 아니다. 지식이 어디에서 왔는지, 언제 획득되었는지, 어느 정도의 증거로 뒷받침되는지, 상충하는 증거가 존재하는지를 기록하면 검증 능력을 향상시키고 잘못된 가정이 전파되는 것을 줄일 수 있다.

상충하는 정보(Contradictory Information)는 또 다른 문제를 발생시킨다. 지능적인 에이전트는 저장된 지식이나 다른 정보원과 충돌하는 증거를 받을 수 있다. 평가 없이 두 주장을 모두 유지하면 일관되지 않은 추론이 발생할 수 있지만, 기존 지식을 즉시 교체하면 유용한 정보가 손실될 수 있다. 이러한 충돌을 해결하려면 믿음을 수정하기 전에 최신성(recency), 정보원의 신뢰성, 맥락의 차이, 불확실성, 추가적인 관찰 등을 고려해야 할 수 있다.

지식은 익숙하지 않은 상황으로 전이될 수 있을 때 가장 큰 가치를 가진다. 개별적인 관찰을 암기하는 것은 익숙한 조건에서 높은 성능을 제공할 수 있지만 일반화 능력은 제한될 수 있다. 추상적 개념(abstract concept), 인과관계, 조합적 구조(compositional structure), 재사용 가능한 기술은 에이전트가 개체와 사건의 새로운 조합을 해석할 수 있도록 한다. 따라서 일반지능은 이전에 관찰한 패턴을 단순히 재현하는 지식이 아니라 새로운 상황에 적응할 수 있는 지식을 필요로 한다.

메타인지(Metacognition)는 시스템 자신의 지식 상태에 대한 지식을 추가한다. 지능적인 에이전트는 자신이 무엇을 알고 있는지, 무엇을 불확실하게 믿고 있는지, 무엇을 잊었는지, 어떤 정보가 추가로 필요한지를 구분해야 한다. 이러한 인식은 검색, 관찰, 실험, 도구 사용(tool use), 도움 요청을 활성화할 수 있다. 따라서 이용 가능한 지식의 한계를 아는 것 자체가 지능적 추론과 안전한 의사결정의 중요한 구성요소가 된다.

궁극적으로 정보(Information)는 조직화되고, 접지되며, 검색 가능하고, 수정 가능한 지식(Knowledge)으로 변환될 때 지능에 실질적인 가치를 제공한다. 지능적인 에이전트는 지속적으로 신호를 획득하고, 맥락을 해석하며, 표상을 구성하고, 증거를 통합하고, 유용한 경험을 보존하며, 불확실성을 추정하고, 믿음을 갱신해야 한다. 기억, 학습, 월드 모델, 추론, 행동을 통해 지식은 단순히 저장된 정보가 아니라 세계를 이해하고 다음에 무엇을 해야 하는지를 결정하기 위한 능동적인 구조(active structure)가 된다.

##  

## 01.08. Representation Learning Revisited

![](images/image10.png){width="7.268055555555556in" height="7.268055555555556in"}

Representation learning is the process by which an intelligent system transforms raw observations into internal forms that make important structure easier to recognize, predict, reason about, and use for action. Instead of relying entirely on manually designed features, the system learns which properties of experience should be preserved. The quality of these representations strongly determines what the system can generalize, transfer, remember, and understand.

Raw observations are usually too detailed and unstable to serve directly as useful knowledge. Images contain millions of pixel values, audio contains rapidly changing waveforms, and robotic sensors continuously produce high-dimensional measurements. Representation learning compresses these signals while attempting to retain information relevant to objects, relationships, dynamics, semantics, goals, and possible actions. Effective compression removes redundancy without discarding structure required for intelligence.

Early machine learning often depended heavily on handcrafted features designed by domain experts. Computer vision used edges, corners, textures, and geometric descriptors, while speech and control systems relied on carefully selected signal characteristics. Deep learning changed this approach by allowing hierarchical features to emerge from data. Representations could increasingly be optimized together with the task rather than being completely specified before learning began.

Hierarchical representation is important because intelligent understanding occurs at multiple levels of abstraction. Low-level features may describe color, texture, motion, sound, or local geometry, while intermediate representations capture parts, objects, spatial configurations, and events. Higher levels can represent concepts, goals, intentions, causal relationships, or task structure. Intelligence requires connections across these levels rather than treating perception and abstract reasoning as independent processes.

Distributed representations encode information across patterns of many interacting dimensions. A concept does not necessarily correspond to one dedicated unit but may emerge from relationships among many features. This provides flexibility because similar concepts can occupy nearby regions of representation space and share useful structure. Distributed representations support statistical generalization, analogy, and transfer, although their internal meaning may be difficult to interpret explicitly.

Latent representations provide compact descriptions of underlying factors that may explain observations. A latent state can summarize information about objects, motion, geometry, context, or hidden environmental conditions without reproducing every sensor measurement. For intelligent agents, the objective is not simply dimensionality reduction. The latent space should preserve variables that support prediction, planning, control, reasoning, and adaptation across changing situations.

Self-supervised learning has become a major mechanism for constructing such representations. Instead of requiring explicit labels, the learner derives objectives from the structure of data itself. Predicting masked components, future observations, transformations, or relationships between different views encourages the model to discover reusable regularities. Large quantities of unlabeled experience can therefore build general representations before specialized tasks provide additional supervision.

Contrastive learning develops representations by encouraging related observations to become closer while separating unrelated examples. Different views of the same object, scene, event, or temporal sequence can provide positive relationships, while other observations provide comparisons. This teaches the model which variations should be ignored and which distinctions should remain meaningful. The resulting invariances can improve robustness and transfer when carefully aligned with downstream requirements.

Predictive representation learning instead emphasizes information that helps anticipate future observations or states. Features useful only for reconstructing irrelevant details may be less valuable than features capturing variables that determine how the environment evolves. Prediction therefore encourages representations of dynamics, persistence, interaction, and temporal structure. This becomes especially important for autonomous agents that must reason about what may happen after their actions.

Generative representation learning attempts to capture enough structure to explain or produce observations. Autoencoders, latent-variable models, autoregressive systems, diffusion approaches, and other generative methods can learn rich latent spaces by modeling data distributions. Generative objectives can preserve detailed information and represent multiple plausible outcomes, making them useful when an intelligent system must imagine alternatives or model uncertainty about possible futures.

Multimodal representation learning connects information from vision, language, audio, touch, proprioception, LiDAR, radar, and other channels. Different modalities describe overlapping aspects of the same world, allowing one source to constrain another. A shared representation can connect the appearance of an object with its name, geometry, sound, physical properties, and possible uses. This creates richer concepts than representations learned independently from isolated modalities.

Grounded representation learning extends multimodal learning by connecting internal concepts with physical states, actions, and consequences. Understanding a "container," for example, should involve more than linguistic similarity or visual appearance. It may include expectations about containment, opening, manipulation, capacity, and possible state transitions. Grounding therefore transforms representations from statistical patterns into structures connected with what an embodied agent can perceive and do.

Object-centric representation learning attempts to decompose scenes into persistent entities rather than representing an entire observation as one undifferentiated vector. Objects can have identities, attributes, positions, relationships, and changing states. Such structure supports tracking, compositionality, reasoning, and prediction because familiar entities can participate in new combinations. Object persistence also helps maintain coherent world states when objects become temporarily unobservable.

Relational representations complement object-centric structure by encoding how entities interact. Intelligence often depends less on recognizing isolated objects than on understanding relationships such as inside, behind, attached, approaching, supporting, owning, or causing. Graph-based and relational architectures can represent these dependencies explicitly. Relational knowledge is especially important for reasoning because many concepts are defined by connections among entities rather than intrinsic properties alone.

Spatial representations organize information about geometry, location, orientation, distance, connectivity, and reachability. For embodied agents, spatial understanding may involve local coordinates, maps, three-dimensional geometry, occupancy structures, semantic maps, or bird\'s-eye-view representations. These representations allow observations from different positions and times to be integrated into a persistent model that supports navigation, manipulation, planning, and environmental understanding.

Temporal representations capture how states evolve rather than describing only static observations. Motion, actions, events, intentions, and physical processes become meaningful through sequences. Recurrent models, temporal attention, state-space models, and predictive architectures can encode dependencies across time. A useful temporal representation should distinguish persistent properties from changing states while preserving information required to anticipate future transitions.

Causal representations seek variables and relationships that remain meaningful under intervention and environmental change. Statistical features can provide excellent prediction within familiar distributions while failing when correlations shift. Representations that capture causal mechanisms may transfer more reliably because they describe how states influence one another. For agents that act in the world, causal structure is particularly valuable because actions deliberately modify variables and create consequences.

Invariance is a central objective of representation learning, but excessive invariance can be harmful. A recognition system may appropriately ignore small changes in lighting or viewpoint, yet a navigation system cannot ignore changes in obstacle position. Intelligent representations must therefore preserve task-relevant variation while discarding irrelevant variation. What should remain invariant depends on the agent\'s goals, actions, environment, and level of abstraction.

Equivariance provides another useful principle. Instead of ignoring a transformation, an equivariant representation changes in a predictable way when the input changes. If an object moves, for example, its internal spatial representation should reflect that movement consistently. Equivariance is valuable for geometry, robotics, physical reasoning, and manipulation because transformations of the world should correspond systematically to transformations within the internal model.

Compositional representations allow familiar components to be combined into unfamiliar configurations. Rather than memorizing every possible scene or task, an agent can represent objects, properties, relations, actions, and goals as reusable components. New situations can then be constructed from known elements. Compositionality is therefore closely connected with systematic generalization and provides a mechanism for expanding competence beyond combinations explicitly encountered during training.

Representation learning must also separate state from observation. Sensors provide incomplete and noisy measurements, while intelligent behavior requires estimates of underlying environmental conditions. A representation may therefore maintain beliefs about hidden objects, intentions, physical properties, or other latent variables that are not directly observable. This distinction becomes fundamental under partial observability and forms an important foundation for persistent world models.

World models place representation learning inside a larger predictive architecture. Encoders transform observations into states, dynamics models predict how those states evolve, and decoders or task heads translate internal states into useful predictions or actions. Representation quality determines whether the learned state contains sufficient information for future prediction. World-model learning can therefore shape representations according to their usefulness for simulation, planning, and control.

Memory extends representations across longer timescales than immediate perception. Episodic memory preserves particular experiences, semantic memory extracts reusable concepts, and procedural memory retains skills. Retrieval can reintroduce information that is not present in the current observation. Representation learning and memory must therefore cooperate so that stored experiences can be efficiently indexed, compared, retrieved, consolidated, and integrated with the agent\'s current internal state.

Language provides an additional representational layer capable of expressing abstract concepts, relationships, instructions, and explanations. Language representations can transfer knowledge across tasks and agents, but linguistic structure alone does not guarantee grounded understanding. General intelligence benefits when language connects with perception, action, memory, and world models, allowing abstract descriptions to influence predictions and behavior while physical experience refines linguistic concepts.

Continual representation learning is required because the environment and the agent\'s capabilities change over time. New objects, tasks, sensors, behaviors, and operating conditions may require existing representations to adapt. Yet uncontrolled adaptation can destroy previously useful structure. A general system therefore needs mechanisms for preserving stable concepts while extending its representational space, balancing plasticity with long-term consistency and avoiding catastrophic forgetting.

Adaptive computation can make representation learning more efficient. Familiar and highly predictable observations may require only small state updates, while novelty, uncertainty, prediction error, or unexpected transitions can trigger deeper processing and stronger learning. This event-sensitive strategy concentrates computation on informative experiences. For embodied and edge systems, such selective processing can reduce energy consumption while preserving responsiveness to important environmental changes.

Evaluating representations requires more than measuring reconstruction accuracy or performance on one downstream benchmark. Useful representations should support generalization, transfer, prediction, reasoning, planning, robustness, compositionality, and adaptation. They should preserve information relevant to action while rejecting irrelevant variation. Evaluation must therefore examine whether learned structure remains useful across tasks, environments, modalities, timescales, and distribution shifts.

Ultimately, representation learning determines how experience becomes internal structure. Intelligence cannot reason effectively about a world represented only as unorganized sensory measurements, nor can it generalize well from representations tied too closely to individual observations. By learning abstractions that preserve entities, relationships, dynamics, semantics, uncertainty, causality, and action possibilities, an intelligent agent builds the internal language through which perception becomes knowledge and knowledge becomes purposeful behavior.

표상학습(Representation Learning)은 지능적인 시스템이 원시 관찰(raw observation)을 중요한 구조를 더 쉽게 인식하고, 예측하고, 추론하며, 행동에 활용할 수 있는 내부 형태로 변환하는 과정이다. 시스템은 사람이 설계한 특징(feature)에 전적으로 의존하는 대신 경험의 어떤 속성을 보존해야 하는지를 스스로 학습한다. 이러한 표상의 품질은 시스템이 무엇을 일반화하고, 전이하며, 기억하고, 이해할 수 있는지를 크게 결정한다.

원시 관찰(Raw Observation)은 일반적으로 유용한 지식으로 직접 사용하기에는 지나치게 상세하고 불안정하다. 이미지는 수백만 개의 픽셀 값을 포함하고, 오디오는 빠르게 변화하는 파형을 포함하며, 로봇 센서는 지속적으로 고차원 측정값을 생성한다. 표상학습은 이러한 신호를 압축하면서 객체, 관계, 동역학, 의미, 목표, 가능한 행동에 관련된 정보를 보존하려 한다. 효과적인 압축은 지능에 필요한 구조를 버리지 않으면서 중복성을 제거한다.

초기의 기계학습(Machine Learning)은 도메인 전문가가 설계한 수작업 특징(handcrafted feature)에 크게 의존했다. 컴퓨터 비전(computer vision)은 에지(edge), 코너(corner), 텍스처(texture), 기하학적 기술자(geometric descriptor)를 사용했고, 음성 및 제어 시스템은 신중하게 선택된 신호 특성에 의존했다. 딥러닝(Deep Learning)은 데이터로부터 계층적 특징이 나타날 수 있도록 함으로써 이러한 접근법을 변화시켰다. 표상은 학습 전에 완전히 지정되는 대신 작업과 함께 최적화될 수 있게 되었다.

계층적 표상(Hierarchical Representation)은 지능적인 이해가 여러 추상화 수준(level of abstraction)에서 이루어지기 때문에 중요하다. 저수준 특징은 색상, 질감, 움직임, 소리, 국소적 기하학을 설명하고, 중간 수준 표상은 부분, 객체, 공간적 구성, 사건을 포착할 수 있다. 상위 수준에서는 개념, 목표, 의도, 인과관계 또는 작업 구조를 표현할 수 있다. 지능은 지각과 추상적 추론을 독립적인 과정으로 취급하기보다 이러한 여러 수준을 서로 연결해야 한다.

분산 표상(Distributed Representation)은 많은 상호작용하는 차원의 패턴에 걸쳐 정보를 인코딩한다. 하나의 개념이 반드시 하나의 전용 단위에 대응하는 것이 아니라 여러 특징 사이의 관계를 통해 나타날 수 있다. 이러한 방식은 유사한 개념들이 표상 공간(representation space)의 가까운 영역에 위치하면서 유용한 구조를 공유할 수 있기 때문에 유연성을 제공한다. 분산 표상은 통계적 일반화, 유추(analogy), 전이를 지원하지만 내부 의미를 명시적으로 해석하기 어려울 수 있다.

잠재 표상(Latent Representation)은 관찰을 설명할 수 있는 근본적인 요인에 대한 압축된 표현을 제공한다. 잠재 상태(latent state)는 모든 센서 측정값을 그대로 재현하지 않으면서 객체, 움직임, 기하학, 맥락 또는 숨겨진 환경 조건에 관한 정보를 요약할 수 있다. 지능적인 에이전트에게 목적은 단순한 차원 축소(dimensionality reduction)가 아니다. 잠재 공간(latent space)은 변화하는 상황에서 예측, 계획, 제어, 추론, 적응을 지원하는 변수를 보존해야 한다.

자기지도학습(Self-Supervised Learning)은 이러한 표상을 구축하기 위한 주요 메커니즘으로 발전하였다. 명시적인 라벨(label)을 요구하는 대신 학습자는 데이터 자체의 구조에서 학습 목표를 생성한다. 가려진 구성요소(masked component), 미래 관찰, 변환 또는 서로 다른 관점 사이의 관계를 예측함으로써 모델은 재사용 가능한 규칙성을 발견하도록 학습한다. 따라서 방대한 양의 비라벨 경험(unlabeled experience)을 통해 일반적인 표상을 구축한 후 특정 작업을 위한 추가적인 지도학습을 수행할 수 있다.

대조학습(Contrastive Learning)은 관련된 관찰의 표상을 서로 가깝게 만들고 관련되지 않은 사례는 서로 분리하도록 학습함으로써 표상을 형성한다. 동일한 객체, 장면, 사건 또는 시간적 연속에 대한 서로 다른 관점은 긍정적 관계(positive relationship)를 제공하며 다른 관찰들은 비교 대상으로 활용될 수 있다. 이를 통해 모델은 어떤 변화는 무시해야 하고 어떤 차이는 의미 있게 유지해야 하는지를 학습한다. 적절한 불변성(invariance)은 강건성과 전이 성능을 향상시킬 수 있다.

예측적 표상학습(Predictive Representation Learning)은 미래의 관찰이나 상태를 예상하는 데 도움이 되는 정보를 강조한다. 관련 없는 세부사항을 재구성하는 데만 유용한 특징보다 환경이 어떻게 변화하는지를 결정하는 변수를 포착하는 특징이 더 중요할 수 있다. 따라서 예측은 동역학, 지속성(persistence), 상호작용, 시간 구조를 표현하도록 유도한다. 이는 자신의 행동 이후 무엇이 발생할지를 추론해야 하는 자율 에이전트에게 특히 중요하다.

생성형 표상학습(Generative Representation Learning)은 관찰을 설명하거나 생성할 수 있을 만큼 충분한 구조를 포착하려 한다. 오토인코더(autoencoder), 잠재변수 모델(latent-variable model), 자기회귀 시스템(autoregressive system), 확산 접근법(diffusion approach) 및 기타 생성 기법은 데이터 분포를 모델링하면서 풍부한 잠재 공간을 학습할 수 있다. 생성 목적함수는 세부 정보를 보존하고 여러 가능한 결과를 표현할 수 있기 때문에 지능 시스템이 대안을 상상하거나 가능한 미래의 불확실성을 모델링해야 할 때 유용하다.

멀티모달 표상학습(Multimodal Representation Learning)은 시각, 언어, 오디오, 촉각, 고유수용감각(proprioception), 라이다(LiDAR), 레이더(radar) 및 기타 채널의 정보를 연결한다. 서로 다른 모달리티(modality)는 동일한 세계의 중첩되는 측면을 설명하므로 하나의 정보원이 다른 정보원을 제약할 수 있다. 공유 표상(shared representation)은 객체의 외형을 이름, 기하학, 소리, 물리적 특성, 가능한 용도와 연결할 수 있으며, 독립적으로 학습된 표상보다 풍부한 개념을 형성할 수 있다.

접지된 표상학습(Grounded Representation Learning)은 내부 개념을 물리적 상태, 행동, 결과와 연결함으로써 멀티모달 학습을 확장한다. 예를 들어 '용기(container)'를 이해한다는 것은 언어적 유사성이나 시각적 외형만을 의미하지 않는다. 여기에는 물체를 담는 기능, 열기, 조작, 용량, 가능한 상태 전이에 대한 기대가 포함될 수 있다. 따라서 접지(grounding)는 표상을 통계적 패턴에서 체화 에이전트가 실제로 지각하고 행동할 수 있는 구조로 변화시킨다.

객체 중심 표상학습(Object-Centric Representation Learning)은 전체 관찰을 하나의 구분되지 않은 벡터로 표현하는 대신 장면을 지속적으로 존재하는 개체(entity)로 분해하려 한다. 객체는 정체성(identity), 속성, 위치, 관계, 변화하는 상태를 가질 수 있다. 이러한 구조는 익숙한 개체들이 새로운 조합으로 등장할 수 있기 때문에 추적, 조합성(compositionality), 추론, 예측을 지원한다. 객체 지속성(object persistence)은 객체가 일시적으로 관측되지 않더라도 일관된 세계 상태를 유지하는 데 도움을 준다.

관계적 표상(Relational Representation)은 개체들이 서로 어떻게 상호작용하는지를 인코딩함으로써 객체 중심 구조를 보완한다. 지능은 고립된 객체를 인식하는 것보다 내부, 뒤쪽, 부착, 접근, 지지, 소유, 인과와 같은 관계를 이해하는 데 더 크게 의존하는 경우가 많다. 그래프 기반 및 관계형 아키텍처(graph-based and relational architecture)는 이러한 의존성을 명시적으로 표현할 수 있다. 많은 개념이 개체 자체의 속성보다 개체 사이의 연결을 통해 정의되기 때문에 관계 지식은 추론에서 특히 중요하다.

공간 표상(Spatial Representation)은 기하학, 위치, 방향, 거리, 연결성, 도달 가능성(reachability)에 관한 정보를 조직한다. 체화 에이전트에서는 로컬 좌표계, 지도, 3차원 기하학, 점유 구조(occupancy structure), 의미 지도(semantic map), 조감도 표상(Bird\'s-Eye-View representation) 등이 사용될 수 있다. 이러한 표상은 서로 다른 위치와 시간에서 획득한 관찰을 지속적인 모델로 통합하여 내비게이션, 조작, 계획, 환경 이해를 지원한다.

시간 표상(Temporal Representation)은 정적인 관찰만 설명하는 대신 상태가 어떻게 변화하는지를 포착한다. 움직임, 행동, 사건, 의도, 물리적 과정은 시간적 연속을 통해 의미를 가진다. 순환 모델(recurrent model), 시간적 어텐션(temporal attention), 상태공간 모델(state-space model), 예측 아키텍처는 시간에 걸친 의존성을 인코딩할 수 있다. 유용한 시간 표상은 지속적인 속성과 변화하는 상태를 구분하면서 미래 전이를 예측하는 데 필요한 정보를 보존해야 한다.

인과 표상(Causal Representation)은 개입(intervention)과 환경 변화에서도 의미를 유지하는 변수와 관계를 찾으려 한다. 통계적 특징은 익숙한 분포에서는 뛰어난 예측을 제공하면서도 상관관계가 변화하면 실패할 수 있다. 인과 메커니즘을 포착하는 표상은 상태들이 서로 어떤 영향을 미치는지를 설명하기 때문에 더욱 안정적으로 전이될 수 있다. 세계에서 직접 행동하는 에이전트에게 인과 구조는 행동이 의도적으로 변수를 변화시키고 결과를 발생시키므로 특히 중요하다.

불변성(Invariance)은 표상학습의 핵심 목표이지만 지나친 불변성은 오히려 해로울 수 있다. 인식 시스템은 작은 조명이나 시점 변화를 무시하는 것이 적절할 수 있지만 내비게이션 시스템은 장애물 위치의 변화를 무시해서는 안 된다. 따라서 지능적인 표상은 관련 없는 변화는 제거하면서 작업에 필요한 변화는 보존해야 한다. 무엇이 불변으로 유지되어야 하는지는 에이전트의 목표, 행동, 환경, 추상화 수준에 따라 달라진다.

등변성(Equivariance)은 또 다른 유용한 원리를 제공한다. 변환을 무시하는 대신 입력이 변화할 때 표상도 예측 가능한 방식으로 변화한다. 예를 들어 객체가 이동하면 내부 공간 표상 역시 그 움직임을 일관되게 반영해야 한다. 등변성은 실제 세계의 변환이 내부 모델의 변환과 체계적으로 대응하도록 하기 때문에 기하학, 로보틱스, 물리적 추론, 조작에서 중요한 가치를 가진다.

조합적 표상(Compositional Representation)은 익숙한 구성요소를 이전에 경험하지 못한 새로운 구성으로 결합할 수 있도록 한다. 에이전트는 가능한 모든 장면이나 작업을 암기하는 대신 객체, 속성, 관계, 행동, 목표를 재사용 가능한 구성요소로 표현할 수 있다. 새로운 상황은 이미 알고 있는 요소들의 새로운 조합으로 구성될 수 있다. 따라서 조합성은 체계적 일반화(systematic generalization)와 밀접하게 연결되며 훈련 중 명시적으로 경험하지 못한 조합까지 역량을 확장하는 메커니즘을 제공한다.

표상학습은 또한 상태(State)와 관찰(Observation)을 구분해야 한다. 센서는 불완전하고 잡음이 포함된 측정값을 제공하지만 지능적인 행동을 위해서는 실제 환경 상태에 대한 추정이 필요하다. 따라서 표상은 직접 관찰할 수 없는 숨겨진 객체, 의도, 물리적 속성 또는 기타 잠재변수에 대한 믿음(belief)을 유지할 수 있다. 이러한 구분은 부분 관측(partial observability) 환경에서 필수적이며 지속적인 월드 모델(World Model)을 구축하는 중요한 기반이 된다.

월드 모델(World Model)은 표상학습을 더 큰 예측 아키텍처(predictive architecture) 안에 배치한다. 인코더(encoder)는 관찰을 상태로 변환하고, 동역학 모델(dynamics model)은 이러한 상태가 어떻게 변화하는지를 예측하며, 디코더(decoder) 또는 작업 헤드(task head)는 내부 상태를 유용한 예측이나 행동으로 변환한다. 표상의 품질은 학습된 상태가 미래 예측에 충분한 정보를 포함하는지를 결정한다. 따라서 월드 모델 학습은 시뮬레이션, 계획, 제어에 얼마나 유용한지를 기준으로 표상을 형성할 수 있다.

기억(Memory)은 표상을 즉각적인 지각보다 더 긴 시간 범위로 확장한다. 일화기억(episodic memory)은 특정 경험을 보존하고, 의미기억(semantic memory)은 재사용 가능한 개념을 추출하며, 절차기억(procedural memory)은 기술을 유지한다. 검색(retrieval)은 현재 관찰에 존재하지 않는 정보를 다시 가져올 수 있다. 따라서 저장된 경험을 효율적으로 색인하고, 비교하고, 검색하고, 공고화하며 현재 내부 상태와 통합할 수 있도록 표상학습과 기억이 협력해야 한다.

언어(Language)는 추상적 개념, 관계, 명령, 설명을 표현할 수 있는 추가적인 표상 계층을 제공한다. 언어 표상은 작업과 에이전트 사이에서 지식을 전이할 수 있지만 언어적 구조만으로 접지된 이해가 보장되는 것은 아니다. 일반지능은 언어가 지각, 행동, 기억, 월드 모델과 연결될 때 이점을 얻는다. 이를 통해 추상적인 설명이 예측과 행동에 영향을 미치고 물리적 경험이 다시 언어적 개념을 개선할 수 있다.

지속적 표상학습(Continual Representation Learning)은 환경과 에이전트의 능력이 시간에 따라 변화하기 때문에 필요하다. 새로운 객체, 작업, 센서, 행동, 운영 조건에 적응하려면 기존 표상이 변화해야 할 수 있다. 그러나 통제되지 않은 적응은 이전에 유용했던 구조를 파괴할 수 있다. 따라서 일반적인 시스템은 안정적인 개념을 보존하면서 표상 공간을 확장하고, 가소성(plasticity)과 장기적인 일관성 사이의 균형을 유지하며, 파국적 망각(catastrophic forgetting)을 방지하는 메커니즘을 필요로 한다.

적응적 계산(Adaptive Computation)은 표상학습을 더욱 효율적으로 만들 수 있다. 익숙하고 예측 가능성이 높은 관찰은 작은 상태 갱신만 필요할 수 있지만 새로움(novelty), 불확실성, 예측오차(prediction error), 예상하지 못한 전이는 더 깊은 처리와 강한 학습을 활성화할 수 있다. 이러한 사건 민감형 전략(event-sensitive strategy)은 정보 가치가 높은 경험에 계산을 집중한다. 체화 시스템과 엣지 시스템(edge system)에서는 중요한 환경 변화에 대한 반응성을 유지하면서 에너지 소비를 줄일 수 있다.

표상의 평가(Evaluation)는 재구성 정확도(reconstruction accuracy)나 하나의 후속 벤치마크 성능만 측정해서는 충분하지 않다. 유용한 표상은 일반화, 전이, 예측, 추론, 계획, 강건성(robustness), 조합성, 적응을 지원해야 한다. 또한 행동에 필요한 정보는 보존하면서 관련 없는 변화는 제거해야 한다. 따라서 학습된 구조가 여러 작업, 환경, 모달리티, 시간 규모, 분포 변화(distribution shift)에서도 계속 유용한지를 평가해야 한다.

궁극적으로 표상학습(Representation Learning)은 경험이 어떻게 내부 구조로 변환되는지를 결정한다. 지능은 조직되지 않은 감각 측정값만으로 표현된 세계에 대해 효과적으로 추론할 수 없으며, 개별 관찰에 지나치게 종속된 표상으로는 충분히 일반화할 수 없다. 개체, 관계, 동역학, 의미, 불확실성, 인과성, 행동 가능성을 보존하는 추상화(abstraction)를 학습함으로써 지능적인 에이전트는 지각을 지식으로, 지식을 목적지향적 행동(purposeful behavior)으로 변환하기 위한 내부 언어를 구축한다.

##  

## 01.09. Unified Intelligence Framework

![](images/image11.png){width="7.268055555555556in" height="7.268055555555556in"}

A unified intelligence framework views intelligence not as a collection of independent abilities but as a coordinated system in which perception, representation, memory, learning, reasoning, prediction, planning, and action continuously influence one another. Intelligence emerges from their integration. No single component is sufficient by itself; adaptive behavior depends on information flowing across multiple cognitive functions while the agent interacts with its environment.

Perception provides the framework with observations about the external world and the agent\'s internal condition. Vision, language, sound, touch, proprioception, and other sensory channels deliver partial and uncertain evidence rather than complete descriptions of reality. Intelligent perception must therefore select relevant information, integrate multiple modalities, estimate uncertainty, and transform raw signals into representations that can support higher-level cognition and action.

Representation learning converts observations into internal states that preserve useful structure while removing unnecessary detail. Effective representations capture entities, properties, relationships, spatial organization, temporal dynamics, semantics, uncertainty, and action possibilities. They provide a shared internal language through which perception can communicate with memory, prediction, reasoning, and planning, making representation a central integration layer within the intelligence architecture.

Memory extends intelligence beyond the immediate present. Working memory maintains information required for current reasoning, episodic memory preserves specific experiences, semantic memory stores generalized concepts and relationships, and procedural memory retains skills and policies. Memory is not simply passive storage. Retrieval reconstructs relevant context, while consolidation transforms repeated experiences into reusable knowledge that can guide future interpretation, prediction, and behavior.

Learning continually modifies the framework using experience. Supervised signals can provide explicit correction, self-supervised learning can discover structure from observation, reinforcement learning can connect actions with consequences, and imitation can transfer useful behavior from demonstrations. Rather than operating as isolated paradigms, these learning mechanisms can contribute complementary signals to shared representations, memories, policies, and world models.

A world model provides a persistent internal representation of how the environment is organized and how it may change. It connects entities, states, relationships, dynamics, actions, and possible transitions. Observations update the estimated current state, while learned dynamics predict future states. This enables an intelligent agent to move beyond immediate reaction and internally examine possible consequences before committing to actions in the external world.

Prediction is a fundamental operation within this framework because intelligence must anticipate rather than merely recognize. Predictions can concern sensory inputs, object motion, environmental changes, human behavior, task outcomes, rewards, or the consequences of actions. Differences between predicted and observed outcomes generate prediction errors that reveal weaknesses in current knowledge and provide signals for updating representations, beliefs, and world models.

Reasoning operates over representations, memories, beliefs, and world-model states to derive conclusions that are not directly present in current observations. It may involve logical, probabilistic, causal, analogical, spatial, or commonsense processes. Reasoning allows an agent to connect evidence, evaluate hypotheses, resolve inconsistencies, infer hidden conditions, and determine which knowledge is relevant to a problem rather than merely matching familiar patterns.

Causal reasoning is especially important when intelligence must act. Statistical associations may predict what commonly occurs, but an autonomous agent needs to estimate what will happen if it deliberately changes the environment. Actions are interventions that alter future states. Representing causal relationships therefore supports counterfactual reasoning, diagnosis, planning, transfer, and robust decision-making when familiar correlations no longer hold.

Planning transforms goals into sequences of possible actions. Using current state estimates, predicted transitions, constraints, and expected outcomes, the agent can compare alternative trajectories before execution. Short-horizon planning may focus on immediate motion or control, while long-horizon planning considers tasks, resources, dependencies, and future objectives. Hierarchical planning allows these timescales to cooperate without requiring every decision to operate at identical levels of detail.

Decision-making selects actions under uncertainty, limited resources, and competing objectives. The most likely outcome is not always the most desirable, and the highest expected reward may not always be sufficiently safe. Intelligent decisions may therefore balance utility, risk, information gain, energy, time, social constraints, and future flexibility. Decision-making becomes the interface through which internal cognition is converted into commitments that affect the world.

Action closes the perception-action loop. Once an action is executed, the environment changes and new observations become available. The resulting consequences provide evidence about whether the agent\'s predictions, causal assumptions, and plans were correct. Action therefore serves both as task execution and as an information-generating process. Intelligence develops through repeated cycles in which acting changes what can subsequently be perceived and learned.

Embodiment gives this loop physical meaning. A body determines what an agent can sense, where it can move, which objects it can manipulate, how much energy it consumes, and which actions are feasible or dangerous. Physical constraints transform abstract reasoning into situated intelligence. For embodied AI, cognition must remain connected to geometry, dynamics, time, safety, resources, and the irreversible consequences that may follow physical actions.

Attention regulates which information receives computational priority. Environments contain more information than an intelligent system can process equally at every moment. Attention can emphasize observations, memories, objects, goals, uncertainties, or predicted hazards that are currently relevant. This selective allocation of processing resources allows intelligence to remain responsive while avoiding unnecessary computation on information that has little influence on current decisions.

Adaptive computation extends this principle across the entire architecture. Familiar and predictable situations may require only lightweight perception, state estimation, and reactive control. Novelty, uncertainty, conflict, prediction error, or risk can activate deeper reasoning, broader memory retrieval, simulation, and replanning. Intelligence can therefore dynamically allocate computational effort according to the complexity and importance of the current situation.

Hierarchical organization provides another mechanism for managing complexity. Low-level processes can handle fast sensory processing and control, intermediate processes can maintain objects, spatial relationships, and short-term predictions, while higher levels represent goals, tasks, abstract concepts, and long-term strategies. Information can move both upward and downward, allowing sensory evidence to modify high-level beliefs while goals influence attention and lower-level action.

Fast and slow processing can coexist within such a hierarchy. Frequently encountered situations may be handled through learned policies and rapid pattern recognition, whereas unfamiliar or consequential problems may require deliberate simulation and reasoning. These modes should not be interpreted as completely separate systems. Instead, they represent different operating regimes within a shared architecture, with uncertainty and task demands determining how much computation is required.

Knowledge provides stable structure across these processes. Declarative knowledge represents facts and relationships, procedural knowledge supports skills, episodic knowledge preserves experiences, and semantic knowledge captures generalized concepts. Knowledge can originate from observation, interaction, language, demonstration, or external information sources. A unified framework must connect these forms so that what is learned in one context can influence prediction, reasoning, planning, and action elsewhere.

Language provides a powerful interface between internal intelligence and culturally accumulated knowledge. Instructions can specify goals, descriptions can update world knowledge, explanations can communicate causal relationships, and dialogue can provide feedback. Language also enables reasoning about situations that have not been directly experienced. Its greatest value emerges when linguistic representations connect with perception, memory, world models, and actions rather than remaining isolated symbolic patterns.

Metacognition allows the system to reason about its own cognitive state. An intelligent agent should estimate what it knows, where uncertainty remains, whether a memory is reliable, whether a prediction is outside familiar conditions, and whether additional information is required. These judgments can trigger deeper computation, retrieval, observation, experimentation, tool use, or assistance, enabling the system to regulate its own reasoning rather than treating every conclusion as equally reliable.

Exploration follows naturally from metacognition and uncertainty. When important knowledge is missing, an agent can actively seek information instead of waiting passively for new observations. It may change viewpoint, investigate an unfamiliar region, test an object, ask a question, or perform a controlled experiment. Exploration therefore connects learning with planning and action, allowing the agent to improve both its task performance and its internal model of the world.

Continual learning keeps the framework synchronized with changing environments and expanding experience. New observations may introduce unfamiliar entities, altered dynamics, new tasks, or exceptions to previous knowledge. The system must incorporate these changes without unnecessarily destroying established capabilities. Memory consolidation, selective updating, modularity, replay, and retrieval can help balance plasticity with stability across the lifetime of an intelligent agent.

Transfer and generalization determine whether the integrated framework produces reusable intelligence rather than task-specific competence. Representations, causal models, skills, concepts, and strategies learned in one situation should support adaptation to related but unfamiliar situations. Compositional knowledge is especially valuable because known entities, relationships, actions, and goals can be reorganized into new combinations without requiring the agent to learn every possible configuration independently.

Safety must constrain every stage of the framework rather than appearing only after an action has been selected. Perception should detect hazards, world models should represent uncertainty, planning should reject unsafe trajectories, learning should respect operational boundaries, and decision-making should account for risk. For embodied intelligence, safety becomes an architectural property connecting sensing, prediction, reasoning, planning, control, monitoring, and recovery.

The unified framework can therefore be understood as a continuous closed loop rather than a linear pipeline. Perception updates representations, representations update memory and world models, prediction anticipates transitions, reasoning interprets possibilities, planning constructs candidate actions, decision-making selects among them, and action changes the environment. New observations then begin another cycle, while learning modifies every component from accumulated experience.

Ultimately, unified intelligence emerges when these mechanisms become mutually supportive rather than independently optimized modules. Perception supplies evidence, representation creates structure, memory provides continuity, learning enables adaptation, world models provide predictive understanding, reasoning derives implications, planning explores possible futures, and action tests those expectations against reality. Their integration creates an adaptive system capable not merely of processing information, but of understanding situations, anticipating consequences, pursuing goals, and continually improving through experience.

통합 지능 프레임워크(Unified Intelligence Framework)는 지능을 서로 독립적인 능력들의 집합이 아니라 지각(perception), 표상(representation), 기억(memory), 학습(learning), 추론(reasoning), 예측(prediction), 계획(planning), 행동(action)이 지속적으로 서로 영향을 주고받는 조정된 시스템으로 바라본다. 지능은 이러한 요소들의 통합을 통해 출현한다. 어느 하나의 구성요소만으로는 충분하지 않으며, 적응적 행동은 에이전트가 환경과 상호작용하는 동안 여러 인지 기능 사이에서 정보가 지속적으로 흐를 때 가능해진다.

지각(Perception)은 외부 세계와 에이전트 자신의 내부 상태에 대한 관찰을 프레임워크에 제공한다. 시각, 언어, 소리, 촉각, 고유수용감각(proprioception) 및 기타 감각 채널은 현실에 대한 완전한 설명이 아니라 부분적이고 불확실한 증거를 제공한다. 따라서 지능적 지각은 관련 정보를 선택하고, 여러 모달리티(modality)를 통합하며, 불확실성을 추정하고, 원시 신호를 상위 수준의 인지와 행동을 지원할 수 있는 표상으로 변환해야 한다.

표상학습(Representation Learning)은 관찰을 유용한 구조는 보존하면서 불필요한 세부사항은 제거한 내부 상태로 변환한다. 효과적인 표상은 개체(entity), 속성, 관계, 공간적 조직, 시간적 동역학(temporal dynamics), 의미, 불확실성, 행동 가능성을 포착한다. 이러한 표상은 지각이 기억, 예측, 추론, 계획과 소통할 수 있도록 하는 공유 내부 언어(shared internal language)를 제공하며, 지능 아키텍처에서 핵심적인 통합 계층으로 기능한다.

기억(Memory)은 지능을 즉각적인 현재를 넘어 확장한다. 작업기억(working memory)은 현재의 추론에 필요한 정보를 유지하고, 일화기억(episodic memory)은 구체적인 경험을 보존하며, 의미기억(semantic memory)은 일반화된 개념과 관계를 저장하고, 절차기억(procedural memory)은 기술과 정책(policy)을 유지한다. 기억은 단순한 수동적 저장소가 아니다. 검색(retrieval)은 관련 맥락을 재구성하고, 공고화(consolidation)는 반복된 경험을 미래의 해석, 예측, 행동을 안내할 수 있는 재사용 가능한 지식으로 변환한다.

학습(Learning)은 경험을 이용하여 프레임워크를 지속적으로 수정한다. 지도 신호(supervised signal)는 명시적인 교정을 제공할 수 있고, 자기지도학습(self-supervised learning)은 관찰에서 구조를 발견하며, 강화학습(reinforcement learning)은 행동과 결과를 연결하고, 모방학습(imitation learning)은 시범(demonstration)으로부터 유용한 행동을 전달할 수 있다. 이러한 학습 메커니즘은 서로 고립된 패러다임으로 작동하기보다 공유 표상, 기억, 정책, 월드 모델에 상호보완적인 신호를 제공할 수 있다.

월드 모델(World Model)은 환경이 어떻게 구성되어 있으며 어떻게 변화할 수 있는지에 대한 지속적인 내부 표상을 제공한다. 월드 모델은 개체, 상태, 관계, 동역학, 행동, 가능한 전이를 서로 연결한다. 관찰은 추정된 현재 상태를 갱신하고, 학습된 동역학은 미래 상태를 예측한다. 이를 통해 지능적인 에이전트는 즉각적인 반응을 넘어 외부 세계에서 행동을 실행하기 전에 가능한 결과를 내부적으로 검토할 수 있다.

예측(Prediction)은 지능이 단순히 인식하는 것을 넘어 미래를 예상해야 하기 때문에 이 프레임워크의 근본적인 연산이다. 예측 대상에는 감각 입력, 객체의 움직임, 환경 변화, 인간 행동, 작업 결과, 보상 또는 행동의 결과가 포함될 수 있다. 예측 결과와 실제 관찰 결과 사이의 차이는 예측오차(prediction error)를 생성하며, 이는 현재 지식의 약점을 드러내고 표상, 믿음(belief), 월드 모델을 갱신하기 위한 신호를 제공한다.

추론(Reasoning)은 표상, 기억, 믿음, 월드 모델의 상태를 바탕으로 현재 관찰에 직접 존재하지 않는 결론을 도출한다. 여기에는 논리적, 확률적, 인과적, 유추적(analogical), 공간적 또는 상식적 추론이 포함될 수 있다. 추론을 통해 에이전트는 단순히 익숙한 패턴을 일치시키는 것을 넘어 증거를 연결하고, 가설을 평가하며, 모순을 해결하고, 숨겨진 조건을 추론하며, 어떤 지식이 현재 문제와 관련되어 있는지를 결정할 수 있다.

인과적 추론(Causal Reasoning)은 지능이 실제로 행동해야 할 때 특히 중요하다. 통계적 연관성은 일반적으로 무엇이 발생하는지를 예측할 수 있지만 자율 에이전트는 자신이 의도적으로 환경을 변화시켰을 때 어떤 일이 발생할지를 추정해야 한다. 행동은 미래 상태를 변화시키는 개입(intervention)이다. 따라서 인과관계의 표현은 익숙한 상관관계가 더 이상 유지되지 않는 상황에서도 반사실적 추론(counterfactual reasoning), 진단, 계획, 전이, 강건한 의사결정을 지원한다.

계획(Planning)은 목표를 가능한 행동들의 연속으로 변환한다. 에이전트는 현재 상태 추정, 예측된 전이, 제약조건, 예상 결과를 이용하여 실행 전에 여러 대안적인 궤적(trajectory)을 비교할 수 있다. 단기 계획(short-horizon planning)은 즉각적인 움직임이나 제어에 집중할 수 있고, 장기 계획(long-horizon planning)은 작업, 자원, 의존관계, 미래 목표를 고려한다. 계층적 계획(hierarchical planning)은 모든 의사결정이 동일한 세부 수준에서 작동할 필요 없이 이러한 서로 다른 시간 규모가 협력하도록 한다.

의사결정(Decision-Making)은 불확실성, 제한된 자원, 서로 경쟁하는 목표 아래에서 행동을 선택한다. 가장 가능성이 높은 결과가 항상 가장 바람직한 것은 아니며, 기대 보상이 가장 높은 행동도 항상 충분히 안전한 것은 아니다. 따라서 지능적인 의사결정은 효용(utility), 위험, 정보이득(information gain), 에너지, 시간, 사회적 제약조건, 미래의 유연성 등을 균형 있게 고려할 수 있다. 의사결정은 내부의 인지 과정이 실제 세계에 영향을 주는 선택으로 변환되는 인터페이스가 된다.

행동(Action)은 지각-행동 순환(perception-action loop)을 완성한다. 행동이 실행되면 환경이 변화하고 새로운 관찰이 가능해진다. 그 결과는 에이전트의 예측, 인과적 가정, 계획이 올바른지에 대한 증거를 제공한다. 따라서 행동은 작업을 실행하는 수단이면서 동시에 정보를 생성하는 과정이다. 지능은 행동이 이후에 무엇을 지각하고 학습할 수 있는지를 변화시키는 반복적인 순환을 통해 발전한다.

체화(Embodiment)는 이러한 순환에 물리적인 의미를 부여한다. 신체는 에이전트가 무엇을 감지할 수 있는지, 어디로 이동할 수 있는지, 어떤 객체를 조작할 수 있는지, 얼마나 많은 에너지를 소비하는지, 어떤 행동이 가능하거나 위험한지를 결정한다. 물리적 제약조건은 추상적인 추론을 상황적 지능(situated intelligence)으로 변화시킨다. 체화 인공지능(Embodied AI)에서 인지는 기하학, 동역학, 시간, 안전, 자원, 물리적 행동에서 발생할 수 있는 비가역적 결과와 연결되어야 한다.

주의(Attention)는 어떤 정보에 계산상의 우선순위를 부여할지를 조절한다. 환경에는 지능 시스템이 매 순간 동일한 수준으로 처리할 수 있는 것보다 훨씬 많은 정보가 존재한다. 주의는 현재 관련성이 높은 관찰, 기억, 객체, 목표, 불확실성 또는 예측된 위험을 강조할 수 있다. 이러한 선택적인 처리 자원 배분을 통해 지능은 현재 의사결정에 거의 영향을 주지 않는 정보에 불필요한 계산을 사용하지 않으면서 중요한 변화에 반응할 수 있다.

적응적 계산(Adaptive Computation)은 이러한 원리를 전체 아키텍처로 확장한다. 익숙하고 예측 가능한 상황에서는 가벼운 지각, 상태 추정(state estimation), 반응적 제어(reactive control)만으로 충분할 수 있다. 반면 새로움(novelty), 불확실성, 충돌, 예측오차 또는 위험이 발생하면 더 깊은 추론, 광범위한 기억 검색, 시뮬레이션, 재계획(replanning)을 활성화할 수 있다. 따라서 지능은 현재 상황의 복잡성과 중요도에 따라 계산 자원을 동적으로 배분할 수 있다.

계층적 조직(Hierarchical Organization)은 복잡성을 관리하기 위한 또 다른 메커니즘을 제공한다. 저수준 과정은 빠른 감각 처리와 제어를 담당하고, 중간 수준 과정은 객체, 공간 관계, 단기 예측을 유지하며, 상위 수준에서는 목표, 작업, 추상적 개념, 장기 전략을 표현할 수 있다. 정보는 상향식과 하향식으로 모두 이동할 수 있어 감각적 증거가 상위 수준의 믿음을 수정하고 목표가 주의와 저수준 행동에 영향을 줄 수 있다.

빠른 처리와 느린 처리(Fast and Slow Processing)는 이러한 계층 구조 안에서 공존할 수 있다. 자주 경험하는 상황은 학습된 정책과 빠른 패턴 인식을 통해 처리할 수 있지만 익숙하지 않거나 결과가 중요한 문제에서는 의도적인 시뮬레이션과 추론이 필요할 수 있다. 이러한 방식들은 완전히 분리된 시스템이라기보다 공유된 아키텍처 내부의 서로 다른 작동 체계(operating regime)로 이해할 수 있으며, 불확실성과 작업 요구조건이 필요한 계산량을 결정한다.

지식(Knowledge)은 이러한 과정 전반에 걸쳐 안정적인 구조를 제공한다. 선언적 지식(declarative knowledge)은 사실과 관계를 표현하고, 절차적 지식(procedural knowledge)은 기술을 지원하며, 일화적 지식(episodic knowledge)은 경험을 보존하고, 의미적 지식(semantic knowledge)은 일반화된 개념을 포착한다. 지식은 관찰, 상호작용, 언어, 시범 또는 외부 정보원에서 획득될 수 있다. 통합 프레임워크는 한 맥락에서 학습한 것이 다른 영역의 예측, 추론, 계획, 행동에 영향을 줄 수 있도록 이러한 지식 형태를 연결해야 한다.

언어(Language)는 내부 지능과 문화적으로 축적된 지식(culturally accumulated knowledge)을 연결하는 강력한 인터페이스를 제공한다. 명령은 목표를 지정하고, 설명은 세계 지식을 갱신하며, 해설은 인과관계를 전달하고, 대화는 피드백을 제공할 수 있다. 또한 언어는 직접 경험하지 않은 상황에 대해서도 추론할 수 있게 한다. 언어의 가장 큰 가치는 언어 표상이 고립된 기호 패턴으로 남지 않고 지각, 기억, 월드 모델, 행동과 연결될 때 나타난다.

메타인지(Metacognition)는 시스템이 자신의 인지 상태에 대해 추론할 수 있도록 한다. 지능적인 에이전트는 자신이 무엇을 알고 있는지, 어디에 불확실성이 존재하는지, 특정 기억이 신뢰할 수 있는지, 예측이 익숙한 조건을 벗어났는지, 추가 정보가 필요한지를 추정해야 한다. 이러한 판단은 더 깊은 계산, 검색, 관찰, 실험, 도구 사용(tool use), 도움 요청을 활성화할 수 있으며, 모든 결론을 동일하게 신뢰하는 대신 시스템이 자신의 추론 과정을 스스로 조절하도록 한다.

탐색(Exploration)은 메타인지와 불확실성으로부터 자연스럽게 이어진다. 중요한 지식이 부족한 경우 에이전트는 새로운 관찰을 수동적으로 기다리는 대신 능동적으로 정보를 찾을 수 있다. 관점을 변경하고, 익숙하지 않은 영역을 조사하며, 객체를 시험하고, 질문하거나, 통제된 실험을 수행할 수 있다. 따라서 탐색은 학습을 계획 및 행동과 연결하여 에이전트가 작업 성능뿐 아니라 자신의 내부 월드 모델도 개선하도록 한다.

지속학습(Continual Learning)은 변화하는 환경과 축적되는 경험에 프레임워크를 지속적으로 동기화한다. 새로운 관찰은 익숙하지 않은 개체, 변화된 동역학, 새로운 작업 또는 기존 지식의 예외를 도입할 수 있다. 시스템은 기존에 확립된 능력을 불필요하게 파괴하지 않으면서 이러한 변화를 통합해야 한다. 기억 공고화(memory consolidation), 선택적 갱신, 모듈성(modularity), 재생(replay), 검색은 지능적인 에이전트의 전체 수명에 걸쳐 가소성(plasticity)과 안정성 사이의 균형을 유지하도록 도울 수 있다.

전이(Transfer)와 일반화(Generalization)는 통합 프레임워크가 작업별 능력에 머무르지 않고 재사용 가능한 지능을 생성하는지를 결정한다. 하나의 상황에서 학습된 표상, 인과 모델, 기술, 개념, 전략은 관련성이 있지만 익숙하지 않은 상황에 적응하는 데 활용될 수 있어야 한다. 조합적 지식(compositional knowledge)은 이미 알려진 개체, 관계, 행동, 목표를 새로운 조합으로 재구성할 수 있기 때문에 특히 중요하며, 가능한 모든 구성을 독립적으로 학습할 필요를 줄여준다.

안전(Safety)은 행동이 선택된 이후에만 적용되는 요소가 아니라 프레임워크의 모든 단계에 제약조건으로 포함되어야 한다. 지각은 위험을 감지해야 하고, 월드 모델은 불확실성을 표현해야 하며, 계획은 안전하지 않은 궤적을 제거해야 하고, 학습은 운영상의 경계조건을 준수해야 하며, 의사결정은 위험을 고려해야 한다. 체화 지능에서는 안전이 감지, 예측, 추론, 계획, 제어, 모니터링, 복구를 연결하는 아키텍처적 속성(architectural property)이 된다.

따라서 통합 프레임워크(Unified Framework)는 선형적인 파이프라인(linear pipeline)이 아니라 지속적인 폐루프(continuous closed loop)로 이해할 수 있다. 지각은 표상을 갱신하고, 표상은 기억과 월드 모델을 갱신하며, 예측은 상태 전이를 예상하고, 추론은 가능한 상황을 해석하며, 계획은 후보 행동을 구성하고, 의사결정은 그중 하나를 선택하며, 행동은 환경을 변화시킨다. 이후 새로운 관찰이 또 다른 순환을 시작하고, 학습은 축적된 경험을 바탕으로 모든 구성요소를 수정한다.

궁극적으로 통합 지능(Unified Intelligence)은 이러한 메커니즘들이 독립적으로 최적화된 모듈에 머무르지 않고 서로를 지원할 때 출현한다. 지각은 증거를 제공하고, 표상은 구조를 형성하며, 기억은 연속성을 제공하고, 학습은 적응을 가능하게 하며, 월드 모델은 예측적 이해를 제공하고, 추론은 함의를 도출하며, 계획은 가능한 미래를 탐색하고, 행동은 이러한 예상이 현실에서 올바른지를 검증한다. 이들의 통합은 단순히 정보를 처리하는 것을 넘어 상황을 이해하고, 결과를 예상하고, 목표를 추구하며, 경험을 통해 지속적으로 향상되는 적응적 시스템(adaptive system)을 만들어낸다.
