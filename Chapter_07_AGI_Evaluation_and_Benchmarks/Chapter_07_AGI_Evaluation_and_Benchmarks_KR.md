**Volume 47. Artificial General Intelligence**

# Chapter 07. AGI Evaluation and Benchmarks

## 07.00. What is AGI Evaluation

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

인공일반지능 평가(Artificial General Intelligence Evaluation)는 인공지능 시스템이 개별적인 특정 과제(Isolated Task)의 수행 능력을 넘어서는 지능(Intelligence)을 보유하고 있는지를 체계적으로 판단하는 과정이다. 기존의 모델 평가(Model Evaluation)가 미리 정의된 데이터셋(Dataset)이나 제한된 목표에 대한 성능을 측정한다면, AGI 평가는 시스템이 낯선 상황을 이해하고 새로운 능력을 습득하며 영역 간 지식을 전이하고 불확실한 상황에서 추론하며 학습 과정에서 명시적으로 경험하지 않은 환경에서도 목표를 달성할 수 있는지를 평가한다.

핵심적인 어려움은 일반지능(General Intelligence)을 하나의 정확도 점수(Accuracy Score)만으로 적절하게 표현할 수 없다는 점이다. 어떤 시스템이 수학, 프로그래밍, 언어 또는 시각 인식에서 인간보다 뛰어난 성능을 보이더라도 이러한 능력을 새롭게 조합해야 하는 상황에서는 취약할 수 있다. 따라서 AGI 평가는 지능을 하나의 벤치마크(Benchmark)에 대한 숙련도가 아니라 지각(Perception), 기억(Memory), 추론(Reasoning), 학습(Learning), 계획(Planning), 적응(Adaptation), 의사소통(Communication), 행동(Action), 메타인지(Metacognition)를 포함하는 다차원적 능력으로 다룬다.

일반화(Generalization)는 특히 중요하다. 겉으로는 지능적으로 보이는 시스템도 실제로는 학습 분포(Training Distribution)에 포함된 패턴을 활용하는 것에 불과할 수 있기 때문이다. 보다 강력한 평가는 과제, 규칙, 환경, 표현 또는 목표가 변경되었을 때의 성능을 조사한다. 핵심 질문은 시스템이 이전에 경험한 문제 유형을 해결할 수 있는가에 그치지 않고, 새로운 문제의 구조를 파악하고 기존 지식과 연결하며 적절한 전략을 구성하고 초기 가정이 잘못되었을 때 이를 수정할 수 있는가에 있다.

전이(Transfer)는 AGI 평가의 또 다른 핵심 차원이다. 한 영역에서 습득한 지식은 완전한 재학습(Retraining) 없이도 관련되거나 구조적으로 유사한 다른 영역의 성능을 향상시킬 수 있어야 한다. 예를 들어 일반지능 에이전트(Generally Intelligent Agent)는 내비게이션(Navigation)에서 공간 추론(Spatial Reasoning)의 원리를 학습한 뒤 이를 조작(Manipulation)이나 계획(Planning)에 다시 활용할 수 있다. 따라서 평가는 내부 표현(Internal Representation)이 개별 데이터셋이나 과제에 특화된 표면적 상관관계가 아니라 재사용 가능한 개념과 관계를 포착하는지를 살펴보아야 한다.

추론 평가(Reasoning Evaluation)는 에이전트가 이용 가능한 정보를 얼마나 효과적으로 결론, 설명, 예측 및 의사결정으로 변환하는지를 조사한다. 여기에는 논리적 추론(Logical Reasoning), 수학적 추론(Mathematical Reasoning), 확률적 추론(Probabilistic Reasoning), 인과적 추론(Causal Reasoning), 상식 추론(Commonsense Reasoning), 반사실적 추론(Counterfactual Reasoning)이 포함된다. 현실의 문제는 어떤 추론 방법을 사용해야 하는지 미리 알려주지 않으므로 어려운 평가에서는 이러한 능력들을 독립적으로 시험하기보다 서로 결합하여 요구해야 한다. AGI 후보 시스템은 무엇을 추론해야 하는지뿐 아니라 어떻게 추론해야 하는지도 스스로 결정해야 한다.

학습 능력(Learning Ability)은 학습이 완료된 모델에 고정된 능력만을 대상으로 하는 것이 아니라 동적으로 평가되어야 한다. 일반지능은 시연(Demonstration), 지시(Instruction), 상호작용(Interaction), 피드백(Feedback), 관찰(Observation), 경험(Experience)을 통해 유용한 지식을 새롭게 획득할 수 있는 능력을 의미한다. 따라서 평가는 학습 효율성(Learning Efficiency), 적응에 필요한 경험의 양, 치명적 망각(Catastrophic Forgetting)에 대한 저항성, 그리고 기존 능력을 손상시키지 않으면서 새로운 지식을 통합하는 능력을 측정해야 한다.

에이전트 평가(Agent Evaluation)는 올바른 답을 생성하는 문제에서 벗어나 연속적인 의사결정을 통해 목표를 달성하는 문제로 평가 범위를 확장한다. 지능형 에이전트(Intelligent Agent)는 목표를 해석하고 이를 하위 목표(Subgoal)로 분해하며 도구(Tool)를 선택하고 부족한 정보를 수집하며 진행 상황을 감시하고 오류에서 회복하며 계획을 수정해야 할 수 있다. 이러한 능력은 단순한 질의응답 벤치마크에서 행동이 미래 상태를 변화시키고 오류가 장기간 누적될 수 있는 상호작용 환경(Interactive Environment)으로 평가가 확장될수록 중요해진다.

장기 지평 평가(Long-Horizon Evaluation)는 짧은 과제에서 드러나지 않는 약점을 발견한다. 각각의 상호작용이 독립적일 때는 뛰어나 보이는 시스템도 수백 번의 행동에 걸쳐 목표, 기억, 제약조건 및 인과적 의존성을 유지해야 하는 상황에서는 실패할 수 있다. 따라서 AGI 평가에는 에이전트가 시간에 걸쳐 일관성을 유지하고, 변화된 상황이 이전 계획을 무효화했음을 인식하며, 자원을 배분하고, 즉각적인 보상과 지연된 결과 사이에서 균형을 유지해야 하는 과제가 포함되어야 한다.

다중양식 평가(Multimodal Evaluation)는 언어(Language), 시각(Vision), 오디오(Audio), 공간 정보(Spatial Information), 센서 관측(Sensor Observation), 행동(Action) 전반에서 지능이 일관되게 유지되는지를 조사한다. 일반지능은 서로 독립적인 양식별 모듈(Modality-Specific Module)이 단절된 결과를 생성하는 것에 그쳐서는 안 된다. 시스템은 서로 다른 양식의 증거를 통합하고 동일한 세계를 나타내는 서로 다른 표현 사이의 대응 관계를 형성하며, 충돌하는 관측을 해결하고, 특정 양식의 정보가 불완전하거나 불확실할 때 다른 양식을 이용해 이를 보완할 수 있어야 한다.

강건성(Robustness) 역시 중요하다. 세심하게 통제된 벤치마크 조건에서만 나타나는 지능은 실제 환경(Real-World Environment)에 배치되었을 때 유지되지 않을 수 있기 때문이다. 평가는 모호성(Ambiguity), 잡음이 포함된 관측(Noisy Observation), 불완전한 지시(Incomplete Instruction), 오해를 유발하는 정보(Misleading Information), 분포 변화(Distribution Shift), 예상하지 못한 사건(Unexpected Event), 적대적 조건(Adversarial Condition)을 포함해야 한다. 목표는 완벽한 성능을 요구하는 것이 아니라 시스템이 불확실성을 인식하고 근거 없는 확신을 피하며 실패를 감지하고 통제되지 않은 행동 대신 점진적으로 성능이 저하되는지를 판단하는 것이다.

메타인지(Metacognition)는 시스템이 자신의 인지 상태(Cognitive State)를 얼마나 이해하고 있는지를 평가 대상으로 추가한다. 능력 있는 에이전트는 자신의 확신도(Confidence)를 추정하고 지식의 공백(Knowledge Gap)을 인식하며 추론 과정의 충돌을 찾아내고 실패한 전략을 감지하며 추가 정보나 외부 지원이 필요한 시점을 판단할 수 있어야 한다. 이러한 자기 감시(Self-Monitoring)는 자율 시스템(Autonomous System)에서 특히 중요하다. 자신의 한계를 신뢰성 있게 인식하지 못한 높은 문제 해결 능력은 오히려 확신에 찬 위험한 의사결정으로 이어질 수 있기 때문이다.

AGI 평가는 능력(Capability)과 신뢰성(Reliability)을 구분해야 한다. 시스템이 매우 어려운 문제를 간헐적으로 해결할 수 있다는 사실만으로 그 능력이 필요할 때 일관되게 발휘된다고 판단할 수는 없다. 따라서 반복 시험(Repeated Trial), 문맥 변화(Context Variation), 대체 표현(Alternative Formulation), 섭동(Perturbation), 통제된 난이도(Controlled Difficulty)가 필요하다. 평가는 최고 성능뿐 아니라 성능 편차(Variance), 실패 유형(Failure Mode), 보정(Calibration), 복구 행동(Recovery Behavior), 특정 능력이 나타나거나 사라지는 조건까지 특성화해야 한다.

인간 비교(Human Comparison)는 유용한 기준점을 제공할 수 있지만 인간 수준의 성능(Human-Level Performance)을 자동적으로 AGI의 정의로 간주해서는 안 된다. 인간 역시 지식, 기억, 추론, 지각 및 전문성에서 상당한 개인차를 나타내며 인공지능 시스템은 인간과 근본적으로 다른 능력 프로파일(Capability Profile)을 가질 수 있다. 따라서 인간 기준선(Human Baseline)은 유용한 참조점으로 사용하되 일반지능을 평균적인 인간 점수의 모방으로 축소하지 않고 능력의 폭(Breadth), 적응성(Adaptability), 효율성(Efficiency), 자율성(Autonomy), 강건성(Robustness), 전이(Transfer)를 별도로 측정해야 한다.

벤치마크 오염(Benchmark Contamination)은 중요한 방법론적 문제를 발생시킨다. 평가 문제 또는 이와 매우 유사한 사례가 학습 데이터(Training Data)에 포함되어 있다면 높은 성능은 일반지능이 아니라 암기(Memorization)의 결과일 수 있다. 따라서 강력한 AGI 평가는 새롭게 생성된 과제, 절차적으로 생성된 환경(Procedurally Generated Environment), 비공개 시험 분포(Hidden Test Distribution), 동적으로 변경되는 규칙, 모델 학습 이후에 만들어진 평가 세트를 활용하는 것이 바람직하다. 평가 조건의 새로움이 커질수록 성공적인 적응은 일반지능을 보여주는 더욱 의미 있는 증거가 된다.

시스템이 자율적이고 광범위한 능력을 갖추게 되면 안전성(Safety)과 정렬(Alignment)은 평가와 분리할 수 없는 요소가 된다. 제약조건을 위반하면서 목표를 효율적으로 달성하는 에이전트는 단순히 과제 완료율이 높다는 이유만으로 성공적으로 평가되었다고 볼 수 없다. 따라서 평가는 지시 준수(Instruction Following), 제약조건 유지(Constraint Preservation), 유해한 조작에 대한 저항성, 불확실성 처리, 수정 가능성(Corrigibility), 인간 감독과의 호환성(Oversight Compatibility), 목표가 충돌하거나 요청된 행동이 허가된 범위를 초과했을 때의 행동까지 조사해야 한다.

어떠한 단일 벤치마크(Single Benchmark)도 AGI의 존재를 확정할 수 없다. 따라서 신뢰할 수 있는 평가 프레임워크(Evaluation Framework)는 일반화 시험(Generalization Test), 추론 벤치마크(Reasoning Benchmark), 에이전트 환경(Agent Environment), 다중양식 과제(Multimodal Task), 장기 지평 과제(Long-Horizon Challenge), 학습 실험(Learning Experiment), 강건성 시험(Robustness Test), 안전성 평가(Safety Assessment)를 결합해야 한다. 이러한 구성요소는 일반화, 추론, 에이전트성(Agency), 다중양식 지능, 시간적 지속성(Temporal Persistence), 통합 평가(Integrated Evaluation)를 동일한 일반지능 문제를 바라보는 상호보완적 관점으로 다루는 전체 평가 구조와 연결된다.

궁극적으로 AGI 평가(AGI Evaluation)는 벤치마크 승리의 누적이 아니라 지능의 구조(Structure of Intelligence)와 적응성(Adaptability)을 측정해야 한다. 일반지능을 뒷받침하는 가장 강력한 증거는 낯선 영역에서도 지속되는 능력, 새로운 기술을 효율적으로 습득하는 능력, 일관된 추론과 계획, 변화하는 환경과의 효과적인 상호작용, 신뢰할 수 있는 자기 수정(Self-Correction), 불확실한 상황에서의 안전한 행동이다. 따라서 AGI 평가는 지능형 시스템이 무엇을 이해하고 학습하며 전이하고 성취할 수 있는지, 그리고 그러한 능력을 얼마나 신뢰성 있게 통제할 수 있는지를 지속적으로 규명하는 과학적 과정(Scientific Process)이라고 할 수 있다.

## 07.01. Generalization Tests

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

일반화 테스트(Generalization Tests)는 인공지능 시스템이 학습 과정에서 경험한 정확한 조건을 넘어 지식과 능력을 적용할 수 있는지를 평가한다. AGI에서 이러한 능력은 핵심적이다. 과제(Task), 환경(Environment), 표현(Representation), 목표(Goal), 규칙(Rule)이 변경되더라도 지능은 계속 유용하게 작동해야 하기 때문이다. 익숙한 사례에서만 성공하는 시스템은 뛰어난 패턴 인식(Pattern Recognition)을 보여줄 수는 있지만 진정한 일반지능(General Intelligence)을 입증했다고 보기는 어렵다.

가장 단순한 형태의 일반화(Generalization)는 학습 데이터와 대략 동일한 분포에서 추출되었지만 이전에는 보지 못했던 사례에 대한 성능을 평가한다. 이는 시스템이 개별 사례를 암기(Memorization)한 것이 아니라 재사용 가능한 패턴을 학습했는지를 확인한다. 이러한 분포 내 평가(In-Distribution Evaluation)도 중요하지만 실제 환경에서는 학습 중 경험했던 것과 상당히 다른 상황, 조합, 문맥 및 제약조건이 지속적으로 발생하기 때문에 AGI 평가만으로는 충분하지 않다.

분포 외 일반화(Out-of-Distribution Generalization)는 평가 환경의 중요한 특성을 변화시켜 난이도를 높인다. 입력에는 익숙하지 않은 객체, 서로 다른 언어 표현 방식, 변화된 시각적 조건, 새로운 과제 구조 또는 기존 개념의 예상하지 못한 조합이 포함될 수 있다. 이러한 상황에서도 성공적인 성능을 보인다면 시스템이 익숙한 상관관계에 전적으로 의존하는 대신 표면적인 통계적 규칙성이 변화해도 유용하게 유지되는 추상화(Abstraction)를 학습했음을 의미한다.

조합적 일반화(Compositional Generalization)는 이전에 학습한 개념을 새로운 방식으로 결합할 수 있는지를 시험한다. 시스템이 객체, 행동, 공간적 관계, 수치 연산 또는 논리 규칙과 같은 개별 개념을 이해하면서도 학습 중 등장하지 않았던 조합에서는 실패할 수 있다. 현실 세계에서 가능한 조합의 수는 사실상 무한하기 때문에 AGI는 재사용 가능한 구성요소(Reusable Component)를 이용하여 새로운 해결책을 구성할 수 있어야 한다.

체계적 일반화(Systematic Generalization)는 학습한 규칙이 동등한 상황에 일관되게 적용되는지를 평가한다. 시스템이 특정 문맥에서 어떤 관계를 학습했다면 구조적으로 유사한 관계에서도 동일한 기본 원리를 활용할 수 있어야 한다. 이러한 시험은 표면적인 유사성을 의도적으로 줄이면서 더 깊은 구조적 관계를 유지할 수 있기 때문에 진정한 규칙 기반 이해(Rule-Like Understanding)와 단순한 패턴 매칭(Pattern Matching)을 구별하는 데 특히 유용하다.

영역 간 전이(Cross-Domain Transfer)는 하나의 과제에서 발생하는 변형을 넘어 일반화 범위를 확장한다. 언어(Language), 시각(Vision), 수학(Mathematics), 내비게이션(Navigation), 상호작용(Interaction)에서 획득한 지식에는 다른 영역에서도 활용할 수 있는 원리가 포함될 수 있다. 따라서 테스트는 에이전트가 서로 다른 영역 사이의 공통 구조를 인식하고 이를 효과적으로 재사용하는지를 평가할 수 있다. 강력한 전이는 내부 표현(Internal Representation)이 더 광범위한 지능을 지원할 만큼 충분히 추상적인 수준에서 개념을 표현하고 있음을 시사한다.

퓨샷 평가(Few-Shot Evaluation)와 제로샷 평가(Zero-Shot Evaluation)는 직접적인 학습 사례가 거의 없거나 전혀 없는 상황에서 시스템이 얼마나 효율적으로 작동할 수 있는지를 측정한다. 제로샷 과제(Zero-Shot Task)는 과제별 사례 없이 지시를 해석하고 기존 지식을 적용하도록 요구하며, 퓨샷 과제(Few-Shot Task)는 제한된 수의 시범 사례만 제공한다. 일반지능 시스템은 새로운 목표나 익숙하지 않은 환경을 만날 때마다 대규모 재학습(Retraining)을 필요로 해서는 안 되므로 이러한 평가 방식은 AGI에서 중요하다.

과제 적응 테스트(Task Adaptation Tests)는 평가 과정에서 시스템이 학습할 수 있도록 함으로써 상호작용적 요소를 추가한다. 이미 학습된 고정 능력만을 측정하는 대신 평가자는 시스템이 새로운 규칙을 얼마나 빠르게 파악하고 전략을 갱신하며 피드백(Feedback)을 통해 성능을 개선하는지를 관찰한다. 지능은 이미 학습한 내용뿐 아니라 앞으로 얼마나 효과적으로 학습할 수 있는지도 포함하므로 적응 속도(Adaptation Speed), 표본 효율성(Sample Efficiency), 안정성(Stability), 유지 능력(Retention)이 중요한 평가 지표가 된다.

분포 변화(Distribution Shift)는 점진적으로 또는 갑작스럽게 도입할 수 있다. 점진적 변화는 시스템이 변화하는 조건을 감지하고 내부 모델(Internal Model)을 지속적으로 조정할 수 있는지를 평가하며, 갑작스러운 변화는 예상하지 못한 전환으로부터 회복하는 능력을 시험한다. 센서 특성의 변화, 새로운 환경 동역학(Environmental Dynamics), 사용자 행동 변화 또는 보상 구조(Reward Structure)의 변경 등이 이에 해당한다. 강건한 AGI는 기존 가정이 더 이상 신뢰할 수 없음을 인식하고 그에 따라 이를 수정해야 한다.

일반화는 표현 방식의 변화(Representation Change)에 대해서도 평가되어야 한다. 동일한 기본 문제가 서로 다른 단어, 기호, 시각적 배치, 좌표계(Coordinate System), 단위(Unit) 또는 양식(Modality)을 사용하여 표현될 수 있다. 문제의 구조를 진정으로 이해하는 시스템이라면 이러한 변환에도 상당한 수준의 능력을 유지해야 한다. 표면적인 문제 표현의 변화만으로 성능이 크게 저하된다면 안정적인 개념적 이해(Conceptual Understanding)보다 표현 방식에 특화된 단서에 의존하고 있음을 보여줄 수 있다.

반사실적 일반화(Counterfactual Generalization)와 인과적 일반화(Causal Generalization)는 서로 다른 개입(Intervention)이 이루어졌을 때 결과가 어떻게 변화하는지를 추론해야 하기 때문에 더욱 강력한 시험을 제공한다. 환경이 익숙한 사례와 다르게 작동한다면 통계적 유사성만으로는 충분하지 않을 수 있다. 지능형 시스템은 상관관계(Correlation)와 인과관계(Causation)를 구별하고 개입의 결과를 예측하며 관련 없는 배경 특성은 유지되더라도 인과 메커니즘이 변화하면 추론 방식을 적절하게 조정할 수 있어야 한다.

일반화 테스트는 벤치마크 오염(Benchmark Contamination)을 세심하게 통제해야 한다. 평가 과제, 정답 또는 매우 유사한 변형이 학습 과정에서 이미 사용되었다면 인상적인 제로샷 성능도 부분적으로 암기에서 비롯되었을 수 있다. 비공개 평가 세트(Hidden Evaluation Set), 절차적으로 생성된 문제(Procedurally Generated Problem), 새롭게 만들어진 환경, 무작위화된 규칙(Randomized Rule), 학습 이후 생성된 과제(Post-Training Task)를 활용하면 이러한 위험을 줄일 수 있다. 목표는 성공이 이전 노출이 아니라 전이 가능한 능력(Transferable Capability)을 반영할 가능성을 최대화하는 것이다.

난이도(Difficulty)는 하나의 통과 또는 실패 기준으로 표현하기보다 체계적으로 변화시켜야 한다. 평가자는 새로움(Novelty), 상호작용하는 변수의 수, 필요한 추론 깊이(Reasoning Depth), 지평 길이(Horizon Length), 불확실성(Uncertainty), 환경 변화의 정도를 점진적으로 증가시킬 수 있다. 이를 통해 어느 지점에서 성능이 저하되기 시작하는지를 보여주는 능력 프로파일(Capability Profile)을 구성할 수 있다. 비슷한 평균 점수를 가진 두 시스템도 서로 매우 다른 일반화 경계(Generalization Boundary)를 보일 수 있으므로 이러한 프로파일은 단순한 종합 점수보다 많은 정보를 제공한다.

따라서 실패 분석(Failure Analysis)은 일반화 테스트에서 필수적인 요소이다. 평가자는 오류가 지식 부족, 약한 추론, 부족한 추상화, 기억 한계(Memory Limitation), 잘못된 불확실성 추정, 취약한 계획(Brittle Planning), 적응 능력 부족 중 어디에서 발생했는지를 파악해야 한다. 통제된 섭동(Controlled Perturbation)을 이용한 반복 시험은 실패가 일시적인 것인지 체계적인 것인지를 확인하고, 시스템이 실패를 스스로 인식하여 추가적인 추론이나 학습을 통해 회복할 수 있는지를 평가하는 데 도움을 준다.

궁극적으로 AGI 일반화 테스트(AGI Generalization Tests)는 익숙한 가정들이 점진적으로 제거되는 상황에서도 지능이 계속 기능할 수 있는지를 측정해야 한다. 강력한 일반화의 증거에는 새로운 과제에 대한 능력, 재사용 가능한 추상화(Reusable Abstraction), 조합적 추론(Compositional Reasoning), 영역 간 전이, 효율적인 적응, 표현 변화에 대한 강건성, 분포 변화로부터의 회복 능력이 포함된다. 따라서 일반화는 하나의 벤치마크 특성이 아니라 학습된 지능이 자신의 학습 이력(Training History)을 넘어 얼마나 확장될 수 있는지를 판단하는 AGI의 핵심 시험이라고 할 수 있다.

## 07.02. Reasoning Benchmarks

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

추론 벤치마크(Reasoning Benchmarks)는 인공지능 시스템이 단순히 익숙한 답을 검색하거나 통계적 패턴을 재현하는 것을 넘어, 정보를 정당화된 결론으로 변환할 수 있는지를 평가한다. AGI 평가에서 추론은 특히 중요하다. 익숙하지 않은 문제에서는 시스템이 관계를 파악하고 중간 결론을 구성하며 대안을 비교하고, 학습 경험에서 직접적으로 일치하는 사례가 존재하지 않더라도 적절한 해결책을 결정해야 하는 경우가 많기 때문이다.

포괄적인 추론 벤치마크(Reasoning Benchmark)는 지능을 하나의 동질적인 능력으로 취급하기보다 여러 형태의 추론을 측정해야 한다. 논리적 추론(Logical Reasoning), 수학적 추론(Mathematical Reasoning), 확률적 추론(Probabilistic Reasoning), 인과적 추론(Causal Reasoning), 공간적 추론(Spatial Reasoning), 시간적 추론(Temporal Reasoning), 유추적 추론(Analogical Reasoning), 상식 추론(Commonsense Reasoning), 반사실적 추론(Counterfactual Reasoning)은 서로 다른 구조와 가정을 가진다. AGI 후보는 이러한 능력을 개별적으로 잘 수행할 뿐 아니라 특정 문제에 어떤 추론 방식 또는 추론 방식의 조합이 적절한지도 판단할 수 있어야 한다.

논리적 추론(Logical Reasoning)은 시스템이 명제(Proposition), 규칙(Rule), 제약조건(Constraint), 관계(Relationship)를 일관되게 처리할 수 있는지를 시험한다. 과제에서는 알려진 전제로부터의 연역(Deduction), 관찰로부터의 귀납(Induction), 가장 가능성 높은 설명을 찾는 가추(Abduction)가 요구될 수 있다. 강력한 성능은 단순히 최종 정답을 생성하는 것을 넘어 관련 제약조건을 유지하고 모순을 피하며, 타당한 함의와 근거 없는 결론을 구분하고, 동일한 문제가 다르게 표현되더라도 일관성을 유지하는 능력을 요구한다.

수학적 추론 벤치마크(Mathematical Reasoning Benchmarks)는 여러 단계에 걸쳐 정확성을 유지하면서 수량, 기호, 방정식, 구조 및 변환을 이해하는 능력을 평가한다. 어려운 과제는 산술(Arithmetic), 대수(Algebra), 기하학(Geometry), 확률(Probability), 최적화(Optimization), 추상적 수학 개념을 결합할 수 있다. AGI 평가에서 중요한 것은 알려진 해답의 암기가 아니라 익숙하지 않은 문제를 정식화하고 적절한 연산을 선택하며 중간 상태를 추적하고 결과가 원래 조건을 만족하는지 검증하는 능력이다.

확률적 추론(Probabilistic Reasoning)은 정보가 불완전하거나 불확실한 상황에서의 의사결정과 결론을 평가한다. 지능형 시스템은 가능성(Possibility)과 확률(Probability)을 구별하고 새로운 증거가 제공될 때 믿음(Belief)을 갱신하며 조건부 의존성(Conditional Dependency)을 추론할 수 있어야 한다. 현실 환경에서는 완전한 정보가 제공되는 경우가 드물기 때문에 보정된 불확실성(Calibrated Uncertainty)과 합리적인 믿음 수정(Belief Revision)은 결정론적 문제 해결에 부가되는 선택적 기능이 아니라 신뢰할 수 있는 추론의 핵심 요소이다.

인과적 추론(Causal Reasoning)은 통계적 연관성(Statistical Association)을 넘어 한 변수의 변화가 기본적인 메커니즘을 통해 다른 변수에 어떤 영향을 주는지를 시스템이 이해하는지 평가한다. 벤치마크에서는 관찰(Observation)과 개입(Intervention)을 구분하거나 변화된 조건에서 결과를 예측하도록 요구할 수 있다. 이러한 과제는 모델이 사건이 발생하는 이유를 추론하고 행동의 결과를 예상하며, 표면적인 상관관계가 유사하게 유지되더라도 인과 메커니즘이 변화했을 때 예측을 수정할 수 있는지를 보여준다.

반사실적 추론(Counterfactual Reasoning)은 어떤 사건, 조건 또는 행동이 달랐다면 무엇이 발생했을지를 질문함으로써 인과적 이해를 확장한다. 시스템은 알려진 상황의 관련 요소를 유지하면서 특정 가정만 변경하고 그 변화에 따른 결과를 추론해야 한다. 이러한 능력은 계획(Planning), 진단(Diagnosis), 과학적 추론(Scientific Reasoning), 의사결정 지원(Decision Support), 실수로부터의 학습에서 중요하다. 지능형 에이전트는 실제 결과와 가능한 대안적 결과를 자주 비교해야 하기 때문이다.

상식 추론(Commonsense Reasoning)은 일상적인 물리적, 사회적, 실용적 상황에 관한 지식과 추론 능력을 평가한다. 겉으로는 단순해 보이는 문제도 객체 영속성(Object Permanence), 일반적인 인간의 의도, 일상적인 인과관계 또는 기본적인 물리적 제약처럼 명시적으로 표현되지 않는 가정을 요구하는 경우가 많다. 따라서 AGI 추론 벤치마크는 시스템이 명시되지 않았지만 관련성이 높은 정보를 추론하면서 학습 데이터에서 자주 등장한 패턴과 유사하다는 이유만으로 근거 없는 가정을 만들어내지 않는지를 평가해야 한다.

유추적 추론(Analogical Reasoning)은 표면적 특징이 서로 다른 상황 사이에서 구조적 유사성(Structural Similarity)을 식별할 수 있는지를 측정한다. 단순히 단어나 외형을 일치시키는 것이 아니라 시스템은 대응되는 관계를 파악하고 한 문제에서 얻은 유용한 해결 원리를 다른 문제로 전이해야 한다. 이러한 능력은 추상적인 관계 지식(Abstract Relational Knowledge)이 이전에 습득한 추론 전략을 익숙하지 않은 영역과 문맥에서도 활용할 수 있게 한다는 점에서 추론 벤치마크를 일반화(Generalization)와 직접 연결한다.

공간적 추론(Spatial Reasoning)과 시간적 추론(Temporal Reasoning)은 위치, 방향, 이동, 순서, 지속시간 및 변화와 관련된 관계를 평가한다. 시스템은 상대적인 위치를 추론하고 구성 상태가 어떻게 변화하는지 예측하며 사건의 순서를 재구성하거나 시간에 따른 의존성을 추론해야 할 수 있다. 이러한 능력은 추론이 고립된 텍스트 설명이 아니라 동적으로 변화하는 상태에 기반해야 하는 체화형 AGI(Embodied AGI), 로보틱스(Robotics), 자율 에이전트(Autonomous Agent), 월드 모델(World Model)에서 특히 중요해진다.

다단계 추론 벤치마크(Multi-Step Reasoning Benchmarks)는 시스템이 확장된 추론 연쇄(Inference Chain)에 걸쳐 일관된 중간 상태를 유지할 수 있는지를 시험한다. 초기 가정이 잘못되거나 관련 정보를 잊거나 중간 결론이 불일치하면 오류가 연속적으로 누적될 수 있다. 따라서 평가는 추론 깊이와 의존 구조를 체계적으로 변화시키면서 더 긴 추론 연쇄, 분기되는 대안, 중첩된 제약조건 또는 여러 추론 과정의 상호작용이 요구될 때 성능이 어떻게 변화하는지를 확인해야 한다.

불완전한 정보에서의 추론(Reasoning under Incomplete Information)도 일반지능을 평가하는 중요한 시험이다. 일부 문제는 처음 제공된 증거만으로 신뢰성 있게 해결할 수 없으며, 올바른 행동은 불확실성을 인정하거나 추가 정보를 요청하거나 증거를 탐색하거나 판단을 보류하는 것일 수 있다. 항상 명확한 정답이 존재하도록 설계된 벤치마크는 의도하지 않게 과도한 확신(Overconfidence)을 보상할 수 있으므로 현실적인 평가는 정당화된 결론과 근거 없는 확신으로 제시된 추측을 구분해야 한다.

상호작용적 추론(Interactive Reasoning)은 정적인 질의응답(Question Answering)을 넘어 평가 범위를 확장한다. 에이전트는 실험을 수행하거나 도구(Tool)를 사용하고 외부 정보를 조사하며 가설(Hypothesis)을 검증하거나 이전에는 이용할 수 없었던 증거를 발견하기 위한 행동을 선택해야 할 수 있다. 이때 추론은 가설 형성(Hypothesis Formation), 정보 획득(Information Acquisition), 추론(Inference), 행동(Action), 관찰(Observation), 수정(Revision)이 반복되는 폐쇄 루프(Closed Loop)가 된다. 이러한 구조는 복잡한 환경에서 작동하는 자율 AGI의 추론 요구사항을 더욱 현실적으로 반영한다.

벤치마크 설계(Benchmark Design)는 암기(Memorization)와 벤치마크 오염(Benchmark Contamination)에 대해서도 방어할 수 있어야 한다. 널리 공개된 추론 문제는 학습 말뭉치(Training Corpus)에 직접적 또는 간접적으로 포함되었을 수 있기 때문에 높은 점수를 해석하기 어렵게 만든다. 새로운 문제 생성, 비공개 테스트 세트(Hidden Test Set), 무작위 변수(Randomized Variable), 절차적으로 구성된 과제(Procedurally Constructed Task), 변화된 표면 표현, 학습 이후 평가(Post-Training Evaluation)는 이러한 위험을 줄일 수 있다. 동일한 문제를 여러 동등한 형태로 표현하는 방법도 성능이 실제 이해에 기반하는지 우연한 프롬프트 단서에 의존하는지를 확인하는 데 유용하다.

평가는 최대 추론 능력(Maximum Capability)뿐 아니라 추론 신뢰성(Reasoning Reliability)도 측정해야 한다. 어려운 문제를 한 번 해결하지만 사소한 표현 변경, 정보 순서 변화, 관련 없는 방해 정보(Irrelevant Distractor) 또는 반복 시험에서 실패하는 시스템은 취약한 추론(Fragile Reasoning)을 보여준 것이다. 따라서 유용한 평가 지표에는 일관성(Consistency), 보정(Calibration), 섭동 민감도(Sensitivity to Perturbation), 오류 전파(Error Propagation), 잘못된 중간 단계로부터의 복구 능력, 모순을 감지하거나 제안된 해결책을 다시 검토해야 하는 시점을 인식하는 능력이 포함된다.

궁극적으로 AGI 추론 벤치마크(AGI Reasoning Benchmarks)는 시스템이 다양하고 익숙하지 않은 문제에 대해 추론 연쇄를 구성하고 평가하며 수정할 수 있는지를 판단해야 한다. 강력한 증거에는 논리적 일관성(Logical Consistency), 수학적 능력(Mathematical Competence), 불확실성을 고려한 추론(Uncertainty-Aware Inference), 인과적·반사실적 이해, 유추적 전이(Analogical Transfer), 상식적 판단, 장기 추론 연쇄의 안정성(Long-Chain Stability), 적응적 정보 탐색(Adaptive Information Seeking)이 포함된다. 따라서 추론 평가는 단순히 지능이 전이되는지를 확인하는 것을 넘어 전이된 지식이 일관된 의사결정과 해결책으로 변환될 수 있는지를 평가함으로써 일반화 테스트(Generalization Tests)를 보완한다.

## 07.03. Agent Benchmarks

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

에이전트 벤치마크(Agent Benchmarks)는 인공지능 시스템이 단순히 독립적인 질문에 답하는 것을 넘어 자율적인 목표 지향 에이전트(Autonomous Goal-Directed Agent)로 작동할 수 있는지를 평가한다. AGI 평가에서 이러한 구분은 매우 중요하다. 실제 지능은 연속적인 상호작용 과정에서 지각(Perception), 추론(Reasoning), 기억(Memory), 계획(Planning), 도구 사용(Tool Use), 행동(Action)을 서로 연결해야 하기 때문이다. 핵심 질문은 시스템이 하나의 목표(Objective)를 변화하는 환경에서 효과적인 행동으로 변환할 수 있는가이다.

일반적으로 에이전트 벤치마크는 행동이 결과를 발생시키고 미래의 관측이 이전의 의사결정에 따라 달라지는 환경(Environment) 안에 시스템을 배치한다. 정적인 추론 테스트와 달리 에이전트는 각 단계를 서로 독립적으로 처리할 수 없다. 현재 상태(Current State)를 표현하고 관련된 과거 정보를 기억하며 가능한 결과를 예측하고 새로운 정보가 들어올 때마다 전략을 지속적으로 갱신해야 한다. 따라서 평가는 단발성 예측(One-Shot Prediction)이 아니라 폐쇄 루프 지능(Closed-Loop Intelligence)을 시험하는 과정이 된다.

목표 이해(Goal Understanding)는 에이전트 벤치마크가 측정해야 하는 첫 번째 능력 중 하나이다. 실제 지시는 불완전하거나 모호하고 계층적일 수 있으며, 명시적인 절차 대신 원하는 결과의 형태로 주어질 수도 있다. 능력 있는 에이전트는 기본 목표를 파악하고 합리적인 제약조건을 추론하며 필수적인 결과와 선택적인 선호를 구별하고 추가적인 확인이 필요한 시점을 인식해야 한다. 목표를 잘못 해석하면 기술적으로 뛰어난 계획과 실행도 결국 무의미해질 수 있다.

과제 분해(Task Decomposition)는 에이전트가 복잡한 목표를 관리 가능한 하위 목표(Subgoal)로 변환할 수 있는지를 평가한다. 많은 실용적인 과제는 하나의 행동으로 해결되지 않으며 정보 수집, 준비, 실행, 검증, 수정 사이의 의존관계를 필요로 한다. 강력한 에이전트는 이러한 의존관계를 파악하고 적절한 순서로 구성하며 가정이 변경되면 과제 분해 구조를 수정하고, 목표 달성에 실질적으로 기여하지 않으면서 시간이나 자원을 소비하는 불필요한 행동을 피해야 한다.

계획 벤치마크(Planning Benchmarks)는 에이전트가 제약조건, 불확실성, 비용 및 미래 결과를 고려하면서 일련의 행동을 어떻게 선택하는지를 평가한다. 짧은 계획은 기본적인 능력을 보여줄 수 있지만 AGI 중심의 평가에는 분기 전략(Branching Strategy), 비상 계획(Contingency Planning), 자원 할당(Resource Allocation), 지연된 결과(Delayed Outcome)를 요구하는 상황도 포함되어야 한다. 에이전트는 즉시 행동할 것인지, 추가 정보를 수집할 것인지, 또는 불확실성이 감소할 때까지 선택 가능성을 유지할 것인지를 판단해야 하는 경우가 많다.

도구 사용 평가(Tool-Use Evaluation)는 에이전트가 외부 자원(External Resource)을 활용하여 자신의 내부 능력을 확장할 수 있는지를 시험한다. 도구에는 검색 시스템, 데이터베이스(Database), 계산기, 소프트웨어 환경, 응용 프로그램 인터페이스(API), 시뮬레이터(Simulator), 센서(Sensor), 로봇 액추에이터(Robotic Actuator) 등이 포함될 수 있다. 효과적인 도구 사용을 위해서는 도구가 필요한 시점을 인식하고 적절한 도구를 선택하며 올바른 입력을 구성하고 반환된 정보를 해석하여 이후의 추론 과정에 통합할 수 있어야 한다.

정보 탐색 행동(Information-Seeking Behavior)은 환경이 성공에 필요한 모든 정보를 처음부터 제공하지 않을 때 특히 중요하다. 능력 있는 에이전트는 부족한 지식을 인식하고 추측하는 대신 필요한 증거를 적극적으로 확보해야 한다. 벤치마크는 에이전트가 유용한 질문을 하고 전략적으로 정보를 검색하며 진단 행동(Diagnostic Action)을 수행하거나 불확실성을 감소시키는 실험을 수행하는지를 평가할 수 있다. 효율적인 정보 획득(Information Acquisition)은 이미 보유한 정보를 대상으로 추론하는 능력만큼 중요할 수 있다.

에이전트 과제가 긴 상호작용 과정으로 확장되면 기억(Memory)이 필수적이 된다. 에이전트는 목표, 중간 결과, 사용자 선호, 환경 변화, 실패한 접근 방식, 해결되지 않은 제약조건을 유지해야 할 수 있다. 에이전트 벤치마크는 오래되거나 관련성이 낮은 정보가 의사결정을 지배하지 않으면서 필요한 정보가 적절한 시점에 접근 가능한지를 평가해야 한다. 따라서 기억 평가는 유지(Retention), 검색(Retrieval), 갱신(Updating), 우선순위화(Prioritization), 통제된 망각(Controlled Forgetting)을 포함한다.

모니터링(Monitoring)과 자기 수정(Self-Correction)은 단순히 초기 계획을 실행하는 시스템과 강건한 에이전트를 구별한다. 실행 과정에서 지능형 에이전트는 실제 진행 상황과 예상 진행 상황을 비교하고 편차를 감지하며 가능한 원인을 파악하고 부분적인 수정 또는 전체 재계획(Replanning)이 필요한지를 판단해야 한다. 따라서 평가에는 예상하지 못한 실패, 잘못된 가정, 사용할 수 없는 도구, 변화된 환경, 오해를 유발하는 관측을 포함하여 에이전트가 이전의 의사결정을 다시 검토하도록 만들어야 한다.

장기 지평 에이전트 벤치마크(Long-Horizon Agent Benchmarks)는 여러 단계에 걸쳐 일관된 행동을 지속할 수 있는지를 시험한다. 기억, 계획, 추론 또는 도구 사용에서 발생하는 작은 오류가 누적되면 원래의 목표 자체를 잃어버릴 수 있다. 시스템은 개별적인 계획은 변화시키면서도 과제 정체성(Task Identity)을 유지해야 한다. 따라서 성능은 최종적인 과제 완료 여부뿐 아니라 장기간에 걸친 의사결정 과정의 효율성(Efficiency), 일관성(Consistency), 복구 가능성(Recoverability), 안정성(Stability)을 함께 측정해야 한다.

환경 상호작용(Environmental Interaction)은 지능적인 행동 자체가 추론 대상이 되는 상태를 변화시키기 때문에 또 다른 난이도를 추가한다. 로보틱스(Robotics), 게임(Game), 시뮬레이션(Simulation), 소프트웨어 시스템 또는 디지털 작업공간(Digital Workspace)에서 하나의 행동은 새로운 기회를 만드는 동시에 기존의 다른 가능성을 제거할 수도 있다. 따라서 AGI 에이전트는 상태 전이(State Transition)를 추론하고 행동을 단순한 출력이 아니라 이후의 가능성, 위험, 관측 및 계획 요구사항을 변화시키는 개입(Intervention)으로 이해해야 한다.

부분 관측 가능성(Partial Observability)은 에이전트 평가를 더욱 현실적으로 만든다. 에이전트는 환경의 제한된 일부만 관찰하는 경우가 많으며 관측과 과거 기록을 이용하여 숨겨진 상태(Hidden State)를 추론해야 한다. 보이지 않는 조건에 대한 가설을 유지하고 새로운 증거에 따라 이를 갱신하며, 목표 달성과 정보 획득 모두에 유용한 행동을 선택해야 할 수 있다. 모든 관련 상태 변수를 에이전트에게 제공하는 벤치마크는 실제 자율 동작의 난이도를 크게 과소평가할 수 있다.

다중 에이전트 환경(Multi-Agent Environment)은 에이전트가 세계를 수동적인 대상으로 취급하지 않고 다른 지능형 행위자(Intelligent Actor)를 고려하여 추론할 수 있는지를 시험한다. 다른 에이전트는 협력하거나 경쟁하고 의사소통하며 협상하고 자원을 공유하거나 서로 충돌하는 목표를 추구할 수 있다. 평가는 협업(Coordination), 역할 할당(Role Assignment), 의사소통 효율성, 다른 에이전트의 행동 예측, 갈등 해결(Conflict Resolution), 변화하는 집단 행동에 대한 적응 능력을 조사할 수 있다. 이러한 능력은 AGI 시스템이 인간과 기계로 구성된 조직에 참여하면서 더욱 중요해진다.

신뢰성(Reliability)은 간헐적인 과제 성공과 구별되어야 한다. 어려운 목표를 한 번 달성하지만 작은 변화만 발생해도 자주 실패하는 에이전트는 강건한 자율성(Robust Autonomy)을 갖추었다고 보기 어렵다. 반복 시험에서는 초기 조건, 지시 표현, 환경 배치, 도구 가용성, 외부 교란, 과제 순서를 변화시켜야 한다. 유용한 측정 지표에는 성공률(Success Rate), 완료 시간, 자원 소비량, 불필요한 행동, 복구율(Recovery Rate), 일관성 및 복구 불가능한 실패의 발생 빈도가 포함된다.

안전성(Safety)과 제약조건 유지(Constraint Preservation)는 자율 시스템이 행동을 통해 실제 결과를 발생시킬 수 있기 때문에 에이전트 벤치마크와 분리할 수 없다. 에이전트가 명시적인 제한을 위반하거나 권한 경계(Authorization Boundary)를 무시하고 자원을 손상시키거나 위험한 지름길을 선택한다면 목표를 완료했다는 사실만으로 충분하지 않다. 따라서 벤치마크에는 운영 제약조건(Operational Constraint)이 포함되어야 하며 에이전트가 계획, 도구 사용, 실행, 재계획 및 예상하지 못한 상황에서의 복구 과정 전체에서 이를 유지하는지를 평가해야 한다.

벤치마크 오염(Benchmark Contamination) 역시 중요한 문제이다. 고정된 에이전트 과제가 학습 데이터 또는 반복적인 최적화 과정에서 익숙해질 수 있기 때문이다. 절차적으로 생성된 환경(Procedurally Generated Environment), 비공개 목표(Hidden Objective), 무작위화된 배치(Randomized Layout), 변화하는 도구 인터페이스, 새로운 하위 과제 조합, 학습 이후 생성된 시나리오(Post-Training Scenario)는 진정한 에이전트 능력을 보여주는 더욱 강력한 증거를 제공할 수 있다. 평가자는 특정 벤치마크의 행동 경로를 암기했는지가 아니라 학습된 전략을 새로운 상황으로 전이할 수 있는지를 측정해야 한다.

궁극적으로 AGI 에이전트 벤치마크(AGI Agent Benchmarks)는 시스템이 목표를 이해하고 환경을 관찰하며 관련 지식을 기억하고 대안을 추론하며 행동을 계획하고 도구를 사용하며 결과를 모니터링하고 피드백으로부터 학습하여 목표를 완료하거나 책임 있게 중단할 때까지 적응하는 통합 인지 루프(Integrated Cognitive Loop)를 측정해야 한다. 이러한 평가는 더 넓은 AGI 평가 구조에서 일반화(Generalization) 및 추론 벤치마크(Reasoning Benchmarks)를 보완하며, 지속적인 자율 행동(Sustained Autonomous Behavior)을 통해 지능이 실제로 통합되어 작동하는지를 검증한다.

## 07.04. Multimodal Evaluation

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

다중양식 평가(Multimodal Evaluation)는 인공지능 시스템이 하나의 양식(Modality)에서만 효과적으로 작동하는 것을 넘어, 여러 형태의 정보를 이해하고 통합하며 추론할 수 있는지를 평가한다. AGI에서는 언어(Language), 이미지(Image), 비디오(Video), 오디오(Audio), 공간 정보(Spatial Information), 센서 신호(Sensor Signal), 행동(Action)을 함께 처리해야 할 수 있다. 핵심 질문은 이러한 입력들이 서로 분리된 능력으로 남는 것이 아니라 하나의 일관된 상황 표현(Coherent Representation)에 기여하는가이다.

기본적인 다중양식 벤치마크(Multimodal Benchmark)는 여러 양식을 통합하기 전에 각각의 개별 양식에서의 능력을 먼저 측정한다. 시스템이 뛰어난 언어 이해(Language Understanding)를 보이면서 시각 지각(Visual Perception)은 약할 수 있고, 정확한 이미지 인식(Image Recognition)을 수행하면서도 비디오의 시간적 흐름을 제대로 해석하지 못할 수도 있다. 이러한 비대칭성은 하나의 채널에서 높은 성능이 다른 채널의 약점을 가릴 수 있기 때문에 중요하다. 따라서 AGI 평가는 양식별 강점과 양식 간 통합 능력을 함께 보여주는 능력 프로파일(Capability Profile)을 필요로 한다.

교차양식 그라운딩(Cross-Modal Grounding)은 한 양식에서 표현된 개념을 다른 양식의 대응 정보와 정확하게 연결할 수 있는지를 평가한다. 언어가 이미지 속 객체를 지칭할 수 있고, 소리가 시야 밖에서 발생한 사건을 나타낼 수 있으며, 센서 측정값이 장면에 대한 물리적 증거를 제공할 수도 있다. 일반지능 시스템은 이러한 대응 관계를 형성하고, 서로 다른 양식이 동일한 세계 상태(World State)의 상호보완적인 측면을 표현한다는 점을 이해해야 한다.

다중양식 융합(Multimodal Fusion)은 여러 정보원을 결합했을 때 개별 정보원만 사용할 때보다 더 유용한 표현을 만들 수 있는지를 시험한다. 효과적인 융합을 위해서는 어떤 관측이 관련성이 높은지, 공간과 시간에서 서로 어떻게 대응하는지, 각 정보원에 어느 정도의 신뢰도(Confidence)를 부여해야 하는지를 판단해야 한다. 시스템은 상호보완적 정보를 활용하면서 모든 양식이 모든 조건에서 동일하게 신뢰할 수 있다고 가정해서는 안 된다.

시각-언어 추론(Visual-Language Reasoning)은 지각(Perception)과 기호적 해석(Symbolic Interpretation)이 함께 작동해야 하므로 다중양식 평가에서 흔히 사용되는 요소이다. 과제에는 장면 설명, 이미지 질의응답, 시각적으로 근거화된 지시 수행, 객체 비교, 다이어그램 해석, 텍스트에 명시되지 않은 관계 추론 등이 포함될 수 있다. 강력한 성능을 위해서는 익숙한 언어 응답과 이미지 패턴을 단순히 연결하는 것이 아니라 실제 시각적 증거(Visual Evidence)를 바탕으로 추론할 수 있어야 한다.

오디오-언어 평가(Audio-Language Evaluation)는 이러한 통합을 음성(Speech), 환경음(Environmental Sound), 음향 사건(Acoustic Event), 시간적 신호(Temporal Signal)로 확장한다. 능력 있는 시스템은 무엇이 말해졌는지뿐 아니라 어떻게 말해졌는지를 구별하고, 소리를 시각적으로 관찰된 사건과 연결하거나 시각적으로 보이지 않는 중요한 사건을 인식해야 할 수 있다. 이러한 벤치마크는 청각 정보가 독립적인 전사(Transcription)나 분류 채널로만 작동하는 것이 아니라 실제 추론에 의미 있게 기여하는지를 평가한다.

비디오 평가(Video Evaluation)는 시간적 연속성(Temporal Continuity)을 추가한다. 하나의 영상 시퀀스를 이해하려면 개별 프레임을 인식하는 것만으로는 충분하지 않다. 시스템은 객체와 에이전트를 추적하고 사건을 식별하며 움직임과 상태 전이(State Transition)를 추론하고 시간에 걸쳐 동일성을 유지하며 인과적 또는 시간적 관계를 파악해야 한다. AGI 관점에서 비디오는 행동과 외부 사건에 따라 환경이 어떻게 변화하는지를 보여주므로 정적인 지각과 월드 모델링(World Modeling)을 연결하는 중요한 역할을 한다.

공간적 다중양식 평가(Spatial Multimodal Evaluation)는 이미지, 깊이 정보(Depth), 지도(Map), 좌표(Coordinate), 언어, 센서 정보를 하나의 일관된 공간 표현(Spatial Representation)으로 구성할 수 있는지를 평가한다. 이는 에이전트가 객체의 위치, 기하학적 관계, 접근 가능한 영역, 이동에 따른 관점 변화 등을 이해해야 하는 체화 지능(Embodied Intelligence)에서 특히 중요하다. 평가는 공간을 이해하는 능력뿐 아니라 그 이해를 계획(Planning)과 행동(Action)에 활용하는 능력도 시험해야 한다.

시간 정렬(Temporal Alignment) 역시 중요하다. 서로 다른 양식은 서로 다른 주기, 지연, 정밀도로 도착할 수 있기 때문이다. 음성 지시, 카메라 프레임, 라이다 스캔(LiDAR Scan), 고유수용성 측정(Proprioceptive Measurement), 행동 명령(Action Command)은 서로 관련된 사건을 나타내면서도 서로 다른 시점에 발생할 수 있다. 따라서 다중양식 평가는 시스템이 비동기 관측(Asynchronous Observation)을 정렬하고 시간 순서를 유지하며 서로 다른 환경 상태에 속하는 정보를 잘못 결합하지 않는지를 시험해야 한다.

교차양식 추론(Cross-Modal Inference)은 하나의 양식에서 부족하거나 모호한 정보를 다른 양식이 보완할 수 있는지를 평가한다. 가려진 객체를 소리로 추론하거나, 언어가 제스처(Gesture)의 의도를 명확하게 해주거나, 깊이 정보가 2차원 이미지의 모호성을 해결할 수 있다. 강력한 다중양식 지능은 선호하는 정보 채널이 불완전하거나 잡음이 있거나 사용할 수 없을 때 실패하는 대신, 상호보완적인 증거를 유연하게 활용할 수 있어야 한다.

서로 충돌하는 증거(Conflicting Evidence)는 더욱 강력한 평가 조건을 제공한다. 센서 잡음, 가림(Occlusion), 오해를 유발하는 언어, 측정 오류, 환경 변화 때문에 서로 다른 양식이 서로 다른 정보를 제공할 수 있다. 시스템은 이러한 신호를 기계적으로 결합해서는 안 된다. 대신 각 정보원의 신뢰성을 평가하고 모순을 식별하며 불확실성(Uncertainty)을 추정하고 추가적인 관측이 필요한지를 판단해야 한다. 불일치를 관리하는 능력은 통제되지 않은 현실 환경에서 강건한 지능(Robust Intelligence)을 구현하는 데 필수적이다.

양식 누락 테스트(Missing-Modality Tests)는 하나 이상의 정보 채널이 사라졌을 때 시스템이 점진적으로 성능을 저하시키며 작동할 수 있는지를 평가한다. 풍부한 시각, 언어, 센서 입력을 이용해 학습된 시스템도 하나의 정보원이 제거되면 예상보다 취약해질 수 있다. AGI 중심의 벤치마크는 양식을 체계적으로 제거하거나 손상시키고 남아 있는 증거를 중심으로 시스템이 추론 구조를 재구성할 수 있는지를 관찰해야 한다. 강건한 성능은 다중양식 지능이 특정 채널에 불필요하게 의존하지 않으면서 통합되어 있음을 의미한다.

상호작용적 다중양식 평가(Interactive Multimodal Evaluation)는 지각을 행동과 직접 연결한다. 에이전트는 소프트웨어 또는 물리적 액추에이터(Actuator)를 제어하면서 시각 관측, 음성 지시, 센서 측정, 텍스트 목표를 동시에 받을 수 있다. 행동은 다시 환경을 변화시키고 새로운 관측을 생성한다. 이 과정은 다중양식 이해가 하나의 정적인 답을 생성하는 데 그치지 않고 계획, 실행, 모니터링, 수정, 학습을 지속적으로 지원해야 하는 폐쇄형 지각-추론-행동 루프(Closed Perception-Reasoning-Action Loop)를 형성한다.

체화 평가(Embodied Evaluation)는 이러한 요구사항을 더욱 구체적으로 만든다. 로봇 또는 시뮬레이션 에이전트는 객체를 시각적으로 식별하고 언어 명령을 이해하며 공간적 관계를 추정하고 해당 객체로 이동하며 이를 조작하고 여러 센서를 통해 결과를 검증해야 할 수 있다. 성공 여부는 양식과 시간 전반에서 공유 표현(Shared Representation)을 유지할 수 있는지에 달려 있다. 이러한 과제는 다중양식 지능이 실제 또는 시뮬레이션 세계와 목적 지향적으로 상호작용할 수 있는지를 보여준다.

벤치마크 설계(Benchmark Design)는 하나의 지배적인 양식(Dominant Modality)을 이용한 지름길로 시스템이 성공하는 것을 방지해야 한다. 예를 들어 이미지가 포함되어 있더라도 질문에 텍스트만으로 답할 수 있다면 실제로 시각 추론을 평가하고 있다고 보기 어렵다. 평가자는 균형 조정 사례(Counterbalanced Example), 양식 제거(Modality Ablation), 모순되는 입력, 숨겨진 정보, 새로운 조합, 통제된 섭동(Controlled Perturbation)을 활용하여 각각의 양식이 최종 의사결정에 실제로 기여하는지를 확인할 수 있다.

따라서 평가 지표(Evaluation Metrics)는 최종 답변 정확도만을 넘어야 한다. 유용한 측정 항목에는 교차양식 일관성(Cross-Modal Consistency), 그라운딩 정확도(Grounding Accuracy), 시간 정렬 정확도, 입력 누락에 대한 강건성, 불확실성 보정(Uncertainty Calibration), 충돌 해결(Conflict Resolution), 센서 성능 저하에 대한 적응, 상호작용 중의 과제 성공률이 포함된다. 실패 분석(Failure Analysis)은 오류가 지각, 정렬, 융합, 기억, 추론, 그라운딩, 행동 중 어디에서 발생했는지를 구분해야 하며, 이를 통해 겉으로 비슷한 실패를 메커니즘 수준에서 구별할 수 있다.

궁극적으로 AGI 다중양식 평가(AGI Multimodal Evaluation)는 서로 다른 정보 채널이 하나의 일관되고 행동 가능한 세계 모델(Actionable Model of the World)로 통합되는지를 판단해야 한다. 강력한 증거에는 신뢰할 수 있는 교차양식 그라운딩, 상호보완적 융합, 공간적·시간적 일관성, 정보 누락 상황에서의 추론, 충돌하는 증거의 해결, 성공적인 지각-행동 루프가 포함된다. 따라서 다중양식 평가는 현실이 다양한 형태의 관측으로 표현되더라도 일반지능(General Intelligence)이 하나로 통합된 상태를 유지할 수 있는지를 시험한다.

## 07.05. Long Horizon Tasks

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

장기 범위 작업(Long-Horizon Tasks)은 단일 상호작용에서 고립된 문제를 해결하는 것이 아니라, 장기간에 걸쳐 서로 의존하는 많은 의사결정(Decisions)을 수행하면서 인공지능 시스템(Artificial Intelligence System)이 목표를 지속적으로 추구할 수 있는지를 평가합니다. AGI 평가(AGI Evaluation)에서 이 능력은 특히 중요합니다. 현실 세계의 목표는 흔히 인식(Perception), 추론(Reasoning), 계획(Planning), 행동(Action), 모니터링(Monitoring), 수정(Correction)이 연속적으로 이어지는 과정으로 전개되기 때문입니다.

장기 범위 작업(Long-Horizon Task)은 일반적인 벤치마크(Conventional Benchmark)와 달리 하나의 정확한 예측이나 응답만으로 성공하기 어렵습니다. 시스템은 상위 수준 목표(High-Level Objective)를 중간 목표(Intermediate Goals)로 변환하고, 이들 사이의 의존관계(Dependencies)를 파악하며, 적절한 행동을 선택하고, 여러 단계에 걸쳐 진행 상태를 유지해야 합니다. 초기 단계의 오류가 이후 단계로 전파될 수 있기 때문에 개별 단계의 능력만큼 시간에 따른 행동의 일관성(Coherent Behavior)이 중요합니다.

따라서 목표 분해(Goal Decomposition)는 장기 범위 평가(Long-Horizon Evaluation)에서 시험해야 하는 핵심 능력입니다. AGI 시스템은 광범위한 목표를 관리 가능한 하위 목표(Subgoals)로 변환하면서 원래 의도와의 관계를 유지해야 합니다. 목표 분해는 단순히 그럴듯한 작업 목록을 생성하는 것이 아니라 선행 조건 관계(Prerequisite Relationships), 자원 제약(Resource Constraints), 수행 순서(Ordering Requirements), 완료 조건(Completion Conditions)을 포착해야 합니다. 효과적인 분해는 전략적 일관성(Strategic Coherence)을 잃지 않으면서 복잡한 목표를 실행 가능한 구조로 변환합니다.

계획 품질(Planning Quality)은 여러 시간적 규모(Temporal Scales)에서 평가되어야 합니다. 단기 계획(Short-Term Planning)은 다음에 수행할 유용한 행동을 결정하고, 중기 계획(Medium-Term Planning)은 여러 행동의 집합을 조정하며, 장기 계획(Long-Term Planning)은 최종 목표를 향한 방향을 유지합니다. 유능한 시스템은 처음에 하나의 경직된 계획을 생성하는 데 그치지 않고 이러한 수준 사이를 유연하게 이동해야 합니다. 이는 계획, 기억, 추론, 인식, 행동이 서로 구별되면서도 통합되는 광범위한 AGI 아키텍처(AGI Architecture)와 연결됩니다.

작업의 시간 범위(Task Horizon)가 길어질수록 기억(Memory)은 핵심적인 역할을 합니다. 에이전트(Agent)는 완료한 행동, 해결되지 않은 문제, 중간 단계에서 발견한 정보, 이전 실패, 환경 변화, 그리고 훨씬 나중에 중요해질 수 있는 약속이나 결정 사항을 기억해야 합니다. 작업이 수백 또는 수천 번의 상호작용으로 확장되면 작업 기억(Working Memory)만으로는 충분하지 않습니다. 따라서 장기 범위 평가는 정보가 선택적으로 유지되고, 필요할 때 검색되며, 상황 변화에 따라 갱신되고, 불필요하거나 잘못된 문맥으로 누적되지 않는지를 평가해야 합니다.

상태 추적(State Tracking)은 현재 진행 상황에 대한 정확한 표현(Representation)을 유지하도록 요구함으로써 기억을 보완합니다. 에이전트는 계획한 것, 실제로 시도한 것, 실제로 발생한 것, 아직 완료되지 않은 것을 구분해야 합니다. 이러한 구분은 행동이 명확한 오류 없이 실패하거나 예상하지 못한 결과를 만들 때 특히 중요합니다. 실제로 관찰된 상태(Observed State)가 아니라 가정된 상태(Assumed State)를 기반으로 계속 추론하는 시스템은 개별 판단이 합리적으로 보이더라도 점차 현실에서 벗어날 수 있습니다.

장기 범위 능력(Long-Horizon Competence)은 목표를 향한 진행 상황을 지속적으로 모니터링(Progress Monitoring)하는 능력도 요구합니다. 에이전트는 계획을 맹목적으로 실행하는 대신 관찰된 결과(Observed Outcomes)를 예상 결과(Expected Outcomes)와 비교하고 현재 전략이 여전히 적절한지 판단해야 합니다. 진행 상황 모니터링은 편차가 치명적인 문제로 확대되기 전에 이를 발견할 수 있게 합니다. 벤치마크는 지연된 결과(Delayed Consequences), 불완전한 피드백(Incomplete Feedback), 오해를 유발하는 중간 성공, 변화하는 조건 등을 도입하여 시스템이 실제로 실행 과정을 모니터링하는지 시험할 수 있습니다.

재계획(Replanning)은 기존 계획이 더 이상 유효하지 않을 때 행동을 수정하는 능력을 측정합니다. 자원이 사라지거나, 도구가 고장 나거나, 환경이 변화하거나, 새롭게 발견된 정보로 인해 이전의 가정이 잘못된 것으로 드러날 수 있습니다. 일반 지능형 에이전트(Generally Intelligent Agent)는 기존 계획 전체를 폐기하는 대신 유용한 부분은 유지하면서 새로운 증거에 영향을 받은 부분만 수정할 수 있어야 합니다. 불필요하게 전체 작업을 처음부터 다시 시작하는 것은 계획 변경을 전혀 하지 않는 것만큼 문제가 될 수 있습니다.

오류 복구(Error Recovery)는 장시간 작업에서 실패가 발생할 가능성이 필연적으로 증가하기 때문에 특히 중요한 평가 요소입니다. 평가는 일반적인 벤치마크 오류를 단순히 회피하는 시스템과 예상하지 못한 실패를 진단하고 복구할 수 있는 시스템을 구별해야 합니다. 복구에는 실패한 단계의 식별, 실패 결과의 영향 추정, 유효한 상태 복원, 대체 방법 선택, 그리고 관련 없는 기존 진행 상황을 잃지 않은 상태에서 작업을 계속하는 과정이 포함될 수 있습니다. 이를 통해 강건성(Robustness)은 수동적인 오류 저항 능력에서 능동적인 인지 능력(Active Cognitive Capability)으로 확장됩니다.

신용 할당(Credit Assignment)은 결과가 해당 결과를 발생시킨 의사결정보다 훨씬 나중에 나타날 때 어려워집니다. 작업 마지막 부분에서 발생한 좋지 않은 결과의 원인이 여러 단계 이전에 만들어진 가정이나 행동일 수 있습니다. 장기 범위 평가는 시스템이 의사결정 이력(Decision History)을 역으로 추적하여 결과에 영향을 준 원인을 식별할 수 있는지를 평가해야 합니다. 이러한 능력이 없다면 에이전트는 어떤 결정을 강화하고 어떤 결정을 수정해야 하는지 판단하기 어렵기 때문에 장기간의 경험으로부터 효율적으로 학습하기 어렵습니다.

계획이 길어질수록 불확실성(Uncertainty)은 사라지는 것이 아니라 명시적으로 누적되고 관리되어야 합니다. 모든 인식, 추론, 검색된 기억, 외부 도구 결과, 예측된 결과에는 불확실성이 포함될 수 있습니다. 에이전트가 불확실한 중간 결론을 반복적으로 확정된 사실처럼 취급하면 시스템의 신뢰도(Confidence)가 현실과 분리될 수 있습니다. 따라서 장기 범위 벤치마크는 불확실성 추적(Uncertainty Tracking), 검증 행동(Verification Behavior), 정보 수집(Information Gathering), 그리고 누적된 불확실성이 운영상 중요해졌을 때 기존 가정을 다시 검토하는 능력을 시험해야 합니다.

도구 사용(Tool Use)은 장기 범위 평가의 또 다른 중요한 차원을 형성합니다. 복잡한 목표에는 검색 시스템(Search Systems), 데이터베이스(Databases), 소프트웨어 애플리케이션(Software Applications), 계산기(Calculators), 외부 서비스(External Services), 로봇 액추에이터(Robotic Actuators), 특수 모델(Specialized Models)이 필요할 수 있습니다. 에이전트는 개별 도구를 사용하는 방법뿐만 아니라 언제 해당 도구가 필요한지, 도구 사이에서 어떤 정보를 전달해야 하는지, 도구의 결과가 이후 의사결정에 어떤 영향을 주는지를 판단해야 합니다.

장기 범위 작업은 자원 관리(Resource Management) 능력도 평가할 수 있습니다. 지능형 시스템은 제한된 시간, 계산 능력(Computational Capacity), 에너지(Energy), 메모리(Memory), 통신 대역폭(Communication Bandwidth), 비용 등의 제약 속에서 작동할 수 있습니다. 시스템은 모든 판단에 최대의 자원을 사용하는 대신 작업의 중요성과 불확실성에 따라 자원을 배분해야 합니다. 효율적인 지능은 어떤 상황에서 더 깊은 추론, 추가 관찰, 외부 도구 사용, 비상 계획(Contingency Planning)이 필요한지와 어떤 상황을 저비용의 일상적인 행동으로 처리할 수 있는지를 구분해야 합니다.

환경 지속성(Environmental Persistence)은 현실적인 장기 범위 평가를 정적인 질의응답(Static Question Answering)과 구별하는 또 하나의 특징입니다. 행동은 세계를 변화시키며 이러한 변화는 이후 선택을 제한할 수 있습니다. 물체를 이동하거나, 파일을 변경하거나, 자원을 소비하거나, 정보를 전달하거나, 다른 위치로 이동하는 행동은 지속적인 결과를 생성합니다. 평가는 에이전트가 이러한 상태 전이(State Transitions)를 추론하고 이후의 의사결정이 자신의 이전 행동으로 부분적으로 변화된 세계에서 이루어진다는 사실을 이해하는지 시험해야 합니다.

다중 에이전트(Multi-Agent) 및 인간 상호작용(Human Interaction)은 작업의 시간 범위를 더욱 확장할 수 있습니다. 목표는 다른 에이전트와의 약속, 위임된 작업, 협상, 공유 자원, 장기간에 걸쳐 제공되는 정보에 의존할 수 있습니다. 평가 대상 시스템은 책임을 기억하고, 의존관계를 파악하며, 협력자가 예상과 다르게 행동할 경우 계획을 갱신하고, 서로 모순되는 행동을 방지해야 합니다. 따라서 장기 범위 지능(Long-Horizon Intelligence)은 내부적인 추론 순서뿐만 아니라 사회적·운영적 연속성(Social and Operational Continuity)을 유지하는 능력까지 포함합니다.

체화된 장기 범위 작업(Embodied Long-Horizon Tasks)은 계획이 지속적인 물리적 상호작용(Physical Interaction)에 기반해야 하므로 특히 까다로운 평가를 제공합니다. 로봇은 여러 위치를 탐색하고, 물체를 찾고, 장비를 조작하고, 충전하고, 장애물에 대응하며, 사람과 협력하면서 수 시간 또는 수일에 걸친 임무를 완수해야 할 수 있습니다. 각각의 행동은 이후 가능한 선택을 변화시킵니다. 성공하려면 하나의 지속적인 인식-행동 루프(Perception-Action Loop) 안에서 인식, 기억, 계획, 제어(Control), 월드 모델링(World Modeling), 복구(Recovery)를 통합해야 합니다.

벤치마크 설계(Benchmark Design)는 최종 목표가 결국 달성되었는지만 측정해서는 안 됩니다. 유용한 평가 지표(Evaluation Metrics)에는 작업 완료율(Completion Rate), 성공한 중간 목표 수, 불필요한 행동 수, 복구 효율(Recovery Efficiency), 자원 소비(Resource Consumption), 기억 일관성(Memory Consistency), 계획 안정성(Planning Stability), 적응 속도(Adaptation Speed), 안전 위반(Safety Violations), 누적 오류(Accumulated Error) 등이 포함됩니다. 동일한 최종 상태에 도달한 두 에이전트도 효율성, 신뢰성, 자율성, 강건성 측면에서는 크게 다를 수 있으므로 전체 수행 궤적(Trajectory)도 함께 평가해야 합니다.

난이도(Difficulty)는 작업 길이를 증가시키거나, 피드백을 지연하거나, 숨겨진 의존관계를 도입하거나, 환경 조건을 변화시키거나, 자원을 제한하거나, 관측 정보를 손상시키거나, 여러 도구 사이의 전환을 요구하거나, 복구 가능한 실패를 의도적으로 삽입하는 방식으로 체계적으로 높일 수 있습니다. 가장 유용한 벤치마크는 암기된 행동 시퀀스(Memorized Action Sequences)에 기반한 해결을 방지해야 합니다. 새로운 작업 조합과 동적인 환경은 에이전트가 학습된 궤적을 단순 재현하는 것이 아니라 실제로 계획을 구성하고 유지할 수 있는지를 보여줍니다.

궁극적으로 장기 범위 평가(Long-Horizon Evaluation)는 의사결정이 시간에 따라 누적되더라도 지능이 일관성(Coherence)을 유지할 수 있는지를 묻습니다. 강력한 AGI 성능에는 지속적인 목표(Persistent Goals), 계층적 계획(Hierarchical Planning), 신뢰할 수 있는 기억(Reliable Memory), 정확한 상태 추적(Accurate State Tracking), 불확실성 관리(Uncertainty Management), 진행 상황 모니터링, 적응적 재계획(Adaptive Replanning), 오류 복구, 지연된 결과로부터의 학습이 필요합니다. 몇 단계 동안 뛰어난 성능을 보이지만 시간이 지나면서 목표를 잃거나 현실과의 일관성을 상실하는 시스템은 근본적으로 제한적입니다. 일반 지능(General Intelligence)은 장기간의 상호작용에서도 목적 지향적 행동(Purposeful Behavior)을 지속적으로 유지할 수 있어야 합니다.

## 07.06. Evaluation Framework [w/Code]

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

AGI 평가 프레임워크(AGI Evaluation Framework)는 인공지능 시스템(Artificial Intelligence System)이 개별 벤치마크(Benchmark)에서 제한된 능력만을 보이는 것이 아니라 광범위하고 전이 가능하며 신뢰할 수 있는 지능을 나타내는지를 체계적으로 판단하기 위한 구조를 제공합니다. 일반 지능(General Intelligence)은 인식(Perception), 추론(Reasoning), 학습(Learning), 기억(Memory), 계획(Planning), 행동(Action), 적응(Adaptation)을 포함하므로 평가는 지능을 하나의 정확도 점수로 축소하기보다 여러 능력 차원의 증거를 통합해야 합니다.

평가 프레임워크(Evaluation Framework)는 먼저 목표로 하는 일반 지능의 개념을 구성하는 능력을 정의해야 합니다. 여기에는 일반화(Generalization), 전이(Transfer), 추론, 계획, 멀티모달 이해(Multimodal Understanding), 자율 에이전시(Autonomous Agency), 장기 범위 행동(Long-Horizon Behavior), 학습, 기억, 도구 사용(Tool Use), 적응 등이 포함될 수 있습니다. 각각의 능력은 관찰 가능한 행동(Observable Behaviors)을 통해 구체화되어야 하며, 이를 통해 지능이라는 추상적인 개념을 측정 가능한 실험 조건으로 변환할 수 있습니다.

평가는 능력(Capability)과 벤치마크 성능(Benchmark Performance)을 구분해야 합니다. 벤치마크는 특정 조건에서 행동을 관찰하기 위한 측정 도구이며, 능력은 벤치마크가 측정하려는 근본적인 역량입니다. 하나의 데이터셋(Dataset)에서 높은 성능을 달성했다고 해서 반드시 일반적인 추론이나 일반화 능력을 입증하는 것은 아닙니다. 따라서 하나의 능력에 대한 더 강력한 증거를 확보하려면 여러 작업, 환경, 교란(Perturbations), 평가 방법을 사용해야 합니다.

유용한 프레임워크는 평가를 계층적(Hierarchical)으로 구성합니다. 가장 낮은 수준에서는 객체 인식(Object Recognition), 검색(Retrieval), 논리적 추론(Logical Inference), 내비게이션(Navigation), 도구 호출(Tool Invocation)과 같은 개별 기술을 직접 측정할 수 있습니다. 상위 수준에서는 이러한 기술의 조합을 추론 문제, 멀티모달 작업, 에이전트 환경(Agent Environments), 장기 임무(Extended Missions)에서 평가합니다. 최상위 수준에서는 통합 지능(Integrated Intelligence)이 요구되는 복잡한 목표를 만났을 때 여러 능력이 지속적으로 조정되는지를 평가합니다.

일반화 평가(Generalization Evaluation)는 시스템의 성능이 익숙한 학습 분포(Training Distribution)를 넘어 전이되는지를 판단해야 합니다. 테스트에서는 시스템이 발견해야 하는 기본 구조 일부를 유지하면서 새로운 예제, 조합, 환경, 작업, 규칙 또는 도메인(Domain)을 도입할 수 있습니다. 분포적 거리(Distributional Distance)를 점진적으로 증가시키면 시스템의 능력이 암기된 패턴에 의존하는지, 아니면 실제로 낯선 조건에서도 행동을 지원할 수 있는 재사용 가능한 표현(Reusable Representations)과 전략을 갖추고 있는지를 확인할 수 있습니다.

추론 평가(Reasoning Evaluation)는 최종 답변이 정확한지만 확인해서는 안 됩니다. 시스템은 관계를 추론하고, 여러 증거를 결합하고, 인과적으로 추론하며, 불확실성(Uncertainty)을 관리하고, 중간 결론을 구성하고, 새로운 정보가 나타났을 때 기존 믿음(Beliefs)을 수정해야 할 수 있습니다. 평가에서는 문제 구조와 표면적 표현(Surface Representation)을 변화시켜 시스템이 익숙한 벤치마크 템플릿을 인식하거나 우연한 통계적 상관관계를 활용하는 방식만으로 성공하지 못하도록 해야 합니다.

에이전트 평가(Agent Evaluation)는 응답 중심 평가를 행동 중심 평가로 확장합니다. 에이전트(Agent)는 목표를 해석하고, 계획을 수립하고, 도구나 환경과 상호작용하며, 결과를 관찰하고, 상태를 유지하고, 이후의 행동을 결정해야 합니다. 따라서 성능은 고립된 개별 의사결정이 아니라 전체 수행 궤적(Complete Trajectories)을 대상으로 측정되어야 합니다. 작업 완료(Task Completion), 행동 효율(Action Efficiency), 복구 행동(Recovery Behavior), 자원 소비(Resource Consumption), 제약조건 준수(Constraint Satisfaction), 불필요한 개입(Unnecessary Interventions)은 자율적 능력에 대한 상호 보완적인 증거를 제공할 수 있습니다.

멀티모달 평가(Multimodal Evaluation)는 서로 다른 정보 채널이 하나의 일관된 상황 이해(Coherent Understanding)에 기여하는지를 판단합니다. 언어(Language), 이미지(Images), 비디오(Video), 오디오(Audio), 공간 정보(Spatial Information), 센서 측정값(Sensor Measurements), 행동은 서로 보완적이거나 충돌하는 증거를 제공할 수 있습니다. 평가는 그라운딩(Grounding), 융합(Fusion), 시간 정렬(Temporal Alignment), 공간 일관성(Spatial Consistency), 결손 모달리티 강건성(Missing-Modality Robustness), 충돌 해결(Conflict Resolution), 그리고 추론과 행동 과정에서 멀티모달 표현을 활용하는 능력을 측정해야 합니다.

장기 범위 평가(Long-Horizon Evaluation)는 의사결정이 시간에 따라 누적될 때도 능력이 안정적으로 유지되는지를 평가합니다. 장기간의 작업에는 지속적인 목표(Persistent Goals), 계층적 계획(Hierarchical Planning), 기억, 상태 추적(State Tracking), 진행 상황 모니터링(Progress Monitoring), 불확실성 관리(Uncertainty Management), 재계획(Replanning), 오류 복구(Error Recovery)가 필요합니다. 시스템이 개별 단계를 정확하게 수행하더라도 수백 개의 상호 의존적인 행동을 조정해야 하는 상황에서는 실패할 수 있습니다. 따라서 최종 성공뿐 아니라 그 결과에 도달하는 전체 수행 과정의 품질도 평가해야 합니다.

강건성(Robustness)은 지능이 작동하는 조건을 의도적으로 교란함으로써 시험해야 합니다. 입력은 노이즈가 있거나, 불완전하거나, 지연되거나, 서로 모순되거나, 적대적(Adversarial)이거나, 정상적인 운영 분포(Operating Distribution)를 벗어날 수 있습니다. 도구를 사용할 수 없게 되거나 환경이 예기치 않게 변화할 수도 있습니다. 강건한 시스템은 성능이 점진적으로 저하되어야 하며, 불확실성을 인식하고, 필요한 경우 추가 증거를 수집하며, 작은 교란이 통제되지 않는 연쇄적 실패로 확대되는 것을 방지해야 합니다.

적응(Adaptation)은 일반 지능이 새로운 상황을 단순히 견디는 데 그치지 않고 건설적으로 대응해야 한다는 점에서 또 다른 핵심 평가 차원을 제공합니다. 평가 환경에서는 배포(Deployment) 이후 새로운 규칙, 목표, 인터페이스(Interfaces), 도구 또는 제약조건을 도입할 수 있습니다. 시스템은 무엇이 변화했는지를 추론하고, 전략을 갱신하며, 적절한 경우 기존 지식을 활용하고, 이전에 학습한 능력을 불필요하게 파괴하지 않으면서 새로운 역량을 습득해야 합니다.

효율성(Efficiency)은 원시적인 능력(Raw Capability)과 함께 고려되어야 합니다. 두 시스템이 동일한 목표를 달성하더라도 계산량(Computation), 메모리, 에너지, 시간, 외부 도구 호출(External Tool Calls), 인간 지원(Human Assistance)의 사용량은 크게 다를 수 있습니다. 따라서 평가 프레임워크는 일정한 성능을 달성하는 데 필요한 자원을 측정해야 합니다. 효율적인 지능은 모든 상황에 최대 계산 자원을 투입하는 대신 비용이 높은 추론과 정보 수집을 필요한 상황에 선택적으로 할당합니다.

신뢰성(Reliability)을 평가하려면 단일 시연이 아니라 반복적인 평가가 필요합니다. 어려운 작업을 한 번 해결했지만 동일한 조건에서 자주 실패하는 시스템은 신뢰할 수 있다고 보기 어렵습니다. 반복 시행(Repeated Trials), 대체 작업 표현(Alternative Task Formulations), 무작위 시드(Random Seeds), 환경 변화(Environmental Variations), 독립적인 평가 세트(Independent Evaluation Sets)를 활용하면 성능의 변동성을 파악할 수 있습니다. 평균 또는 최고 성능만 제시하는 것보다 성능 분포와 실패율(Failure Rates)을 함께 보고하는 것이 더욱 현실적인 평가를 제공합니다.

보정(Calibration)은 시스템의 신뢰도(Confidence)가 판단이나 행동이 정확할 실제 확률과 일치하는지를 평가해야 합니다. 이는 AGI 시스템이 자율적으로 진행할지, 추가 정보를 수집할지, 도움을 요청할지, 또는 판단을 보류(Abstain)할지를 결정해야 하는 상황에서 특히 중요합니다. 자신의 지식 한계를 인식하는 에이전트는 약간 더 높은 정확도를 보이지만 정당화되지 않은 높은 확신을 표현하는 시스템보다 실제 운영 환경에서 더 뛰어난 능력을 가질 수 있습니다.

안전성(Safety)과 제약조건 준수(Constraint Satisfaction)는 능력 평가와 완전히 분리된 문제로 취급하기보다 평가 체계 내부에 통합해야 합니다. 에이전트가 목표를 달성하더라도 운영 한계를 위반하거나, 지시를 무시하거나, 허용할 수 없는 자원을 소비하거나, 위험한 중간 상태(Hazardous Intermediate States)를 만들 수 있습니다. 따라서 평가는 목표 달성 여부뿐 아니라 지정된 경계 안에서 목표를 달성했는지, 그리고 전체 실행 궤적이 허용 가능한 상태를 유지했는지도 판단해야 합니다.

인간 개입(Human Intervention)은 실질적인 자율성(Practical Autonomy)을 측정하는 유용한 지표를 제공합니다. 일부 시스템은 자율적으로 보이지만 실제로는 인간 운영자의 반복적인 명확화(Clarification), 수정(Correction), 작업 분해(Task Decomposition), 복구 지원(Recovery Assistance)에 의존할 수 있습니다. 평가는 인간 개입이 언제 발생했고, 왜 필요했으며, 이후 에이전트가 효과적으로 작업을 재개할 수 있었는지를 기록해야 합니다. 점점 어려워지는 작업에서 인간 개입에 대한 의존도가 감소하는 것은 더 강한 자율적 능력을 보여주는 증거가 됩니다.

벤치마크 오염(Benchmark Contamination)과 지름길 학습(Shortcut Learning)은 AGI 평가를 심각하게 왜곡할 수 있습니다. 테스트 항목이 학습 데이터와 유사하거나, 의도하지 않은 단서를 포함하거나, 실제로 측정하려는 능력을 우회하는 해결 방법을 허용할 수 있습니다. 따라서 평가 프레임워크는 새로운 작업 생성(Novel Task Generation), 비공개 테스트 세트(Hidden Test Sets), 균형화된 예제(Counterbalanced Examples), 통제된 교란(Controlled Perturbations), 모달리티 제거(Modality Ablations), 대체 표현, 절차적으로 생성되는 환경(Procedural Environments)을 포함하여 표면적인 암기의 효과를 줄여야 합니다.

평가 지표(Metrics)는 하나의 범용적인 숫자로 성급하게 통합하기보다 다차원 능력 프로파일(Multidimensional Capability Profile)로 구성해야 합니다. 유용한 차원에는 작업 성공(Task Success), 일반화, 추론 정확도(Reasoning Accuracy), 계획 품질(Planning Quality), 그라운딩, 적응, 강건성, 효율성, 보정, 자율성(Autonomy), 안전성, 기억 일관성(Memory Consistency), 복구 성능(Recovery Performance)이 포함될 수 있습니다. 종합 점수(Composite Score)는 시스템 비교에 도움이 될 수 있지만 서로 다른 시스템이 근본적으로 다른 강점과 약점을 통해 비슷한 점수를 얻을 수 있으므로 기본 능력 프로파일도 함께 제시되어야 합니다.

실패 분석(Failure Analysis)은 정량적 점수(Quantitative Scoring)와 함께 수행되어야 합니다. 오류는 인식, 검색, 기억, 그라운딩, 추론, 계획, 도구 선택(Tool Selection), 실행(Execution), 상태 추정(State Estimation), 적응 등에서 발생할 수 있습니다. 실패 메커니즘(Failure Mechanism)을 식별하면 동일한 잘못된 결과를 서로 다른 이유로 생성한 시스템을 구별할 수 있습니다. 따라서 평가는 단순히 시스템의 순위를 정하는 수단이 아니라 어떤 아키텍처 개선과 추가 학습이 필요한지를 보여주는 진단 과정(Diagnostic Process)이 됩니다.

평가에서는 일반 지능이 여러 구성요소 사이의 조정에서 나타나기 때문에 능력 간 상호작용(Capability Interactions)도 고려해야 합니다. 강력한 인식 능력이 있더라도 관련 관찰 정보가 기억되지 않는다면 유용하지 않을 수 있으며, 정확한 추론도 계획 시스템이 결론을 행동으로 변환하지 못한다면 실제 운영에서 실패할 수 있습니다. 따라서 통합 작업(Integrated Tasks)은 인식, 기억, 추론, 계획, 학습, 제어(Control)가 목표와 환경 상태에 대한 공유 표현(Shared Representation)을 유지하면서 정보를 일관되게 교환할 수 있는지를 시험해야 합니다.

성숙한 AGI 평가 프레임워크는 작업의 다양성(Task Diversity), 신규성(Novelty), 지속 시간(Duration), 불확실성, 상호작용(Interaction), 환경 복잡성(Environmental Complexity)을 점진적으로 증가시켜야 합니다. 초기 단계에서는 통제된 조건에서 기본적인 역량을 확인하고, 이후 단계에서는 불완전한 정보와 지연된 결과가 존재하는 동적 환경에서 여러 능력을 결합할 수 있습니다. 이러한 단계적 접근은 AGI와 비AGI를 임의적인 이분법으로 구분하는 대신 어느 수준에서 시스템 성능이 저하되기 시작하는지를 식별할 수 있게 합니다.

궁극적으로 AGI 평가(AGI Evaluation)는 변화하는 조건에서도 지능이 일반적(General), 통합적(Integrated), 적응적(Adaptive), 강건하며(Robust), 효율적(Efficient)이고 신뢰할 수 있음(Reliable)을 입증하는 증거 프로파일(Evidence Profile)을 구축해야 합니다. 단 하나의 벤치마크만으로 일반 지능을 입증할 수는 없습니다. 시스템이 새로운 상황으로 일반화하고, 여러 모달리티에 걸쳐 추론하며, 장기 범위에서 자율적으로 행동하고, 실패에서 복구하며, 불확실성을 관리하고, 제약조건을 준수하면서 작업 복잡성이 증가해도 일관된 성능을 유지할 때 일반 지능에 대한 더욱 강력한 증거가 형성됩니다.
