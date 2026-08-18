**Volume 47. Artificial General Intelligence**

# Chapter 06. Self Evolving Intelligence

## 06.00. Self Improvement

![](images/image1.png){width="7.268055555555556in" height="7.268055555555556in"}

자기 개선(Self-Improvement)은 인공 일반 지능(Artificial General Intelligence)이 경험, 평가, 적응(adaptation), 수정을 통해 자신의 성능을 향상시키는 능력을 의미한다. 주로 사전에 정의된 훈련 단계(training phase)에서 최적화되는 기존 머신러닝(machine learning) 시스템과 달리, 자기 개선 시스템(self-improving system)은 배포 이후에도 자신의 약점을 식별하고 더 나은 전략을 지속적으로 발견한다. 이러한 능력은 자기 진화 지능(self-evolving intelligence)의 개념적 기반을 형성한다.

핵심 개념은 단순히 인공지능(AI) 시스템이 더 많은 정보를 학습하는 것이 아니다. 자기 개선(Self-Improvement)은 시스템이 인지적 작업(cognitive work)을 수행하는 방식 자체의 변화를 포함한다. 지능형 에이전트(intelligent agent)는 자신의 표현(representation), 추론 절차(reasoning procedure), 계획 전략(planning strategy), 메모리 구성(memory organization), 도구 선택 정책(tool-selection policy), 학습 메커니즘(learning mechanism)을 개선할 수 있다. 따라서 개선은 새로운 지식의 습득부터 그 지식을 획득하고 활용하는 과정 자체의 수정까지 여러 수준에서 이루어진다.

매개변수 적응(parameter adaptation)과 구조적 개선(structural improvement)을 구분하는 것이 유용하다. 매개변수 적응은 기존 모델의 기본 아키텍처(architecture)를 유지하면서 내부의 수치 값을 변경한다. 반면 구조적 개선은 모듈(module), 워크플로(workflow), 메모리 구조(memory structure), 추론 절차 또는 구성 요소 간 상호작용을 변경할 수 있다. 더욱 발전된 AGI 시스템은 두 방식을 결합하여 점진적 최적화를 수행하면서 기존 구조가 충분하지 않을 때 더 큰 아키텍처 변화를 도입할 수 있다.

자기 개선(Self-Improvement)이 가능하려면 개선이 필요하다는 사실을 인식하는 메커니즘이 필요하다. 따라서 지능형 시스템은 목표(objective), 제약 조건(constraint), 기대 결과 또는 이전 성능을 기준으로 자신의 행동을 평가해야 한다. 오류(error), 예측 실패(prediction failure), 비효율적인 계획, 실패한 행동, 과도한 계산 비용(computational cost), 불확실성(uncertainty)은 모두 적응을 위한 신호가 될 수 있다. 신뢰할 수 있는 평가가 없다면 시스템은 변화가 실제로 더 나은 행동을 만들어냈는지 판단할 수 없으므로 단순한 수정만으로는 의미 있는 개선이라고 할 수 없다.

이러한 과정은 중요한 피드백 순환(feedback cycle)을 형성한다. 에이전트(agent)는 상황을 관찰하고, 예측이나 계획을 생성하며, 행동을 수행한 후 그 결과를 측정하고 예상 결과와 비교한다. 이후 차이를 발생시킨 메커니즘을 업데이트하고, 수정된 시스템으로 새로운 상황을 경험하면서 동일한 과정을 반복한다. 따라서 자기 개선(Self-Improvement)은 지능형 에이전트의 일반적인 인지(perception), 추론(reasoning), 계획(planning), 행동(action) 순환을 둘러싼 상위 수준의 학습 순환(higher-order learning loop)으로 이해할 수 있다.

메모리(memory)는 이전의 성공과 실패에 관한 유용한 정보를 보존해야 한다는 점에서 특히 중요한 역할을 한다. 일화 기억(episodic memory)은 개별 경험을 저장하고, 의미 기억(semantic memory)은 일반화된 지식을 통합하며, 절차 기억(procedural memory)은 효과적인 전략이나 기술을 표현할 수 있다. 자기 개선 에이전트는 이러한 서로 다른 형태의 메모리를 분석하여 반복적으로 발생하는 오류, 재사용 가능한 해결책, 특정 전략이 성공할 가능성을 나타내는 패턴을 식별할 수 있다.

성찰(reflection)은 이러한 과정을 직접적인 오류 수정(error correction)보다 더 높은 수준으로 확장한다. 단순히 답변이나 행동이 실패했다는 사실만 확인하는 것이 아니라, 시스템은 왜 실패했는지, 어떤 가정이 잘못되었는지, 어떤 중간 의사결정이 취약했는지, 어떤 대안적인 추론 경로(reasoning path)가 더 나은 결과를 만들 수 있었는지를 분석할 수 있다. 성찰은 경험을 에이전트 자신의 인지적 행동에 관한 구조화된 정보로 변환하며, 일반적인 학습과 이후의 명시적인 자기 성찰(self-reflection) 메커니즘을 연결한다.

자기 개선(Self-Improvement)은 실험(experimentation)을 통해서도 이루어질 수 있다. 에이전트는 대안적인 프롬프트(prompt), 계획, 알고리즘(algorithm), 도구 사용 순서(tool sequence), 표현 또는 정책(policy)을 생성하고 통제된 평가를 통해 성능을 비교할 수 있다. 이를 통해 개선 과정은 가능한 수정안들을 탐색하는 검색 문제(search problem)가 된다. 따라서 강화학습(reinforcement learning), 진화 최적화(evolutionary optimization), 자동화 머신러닝(Automated Machine Learning), 프로그램 합성(program synthesis), 개체군 기반 탐색(population-based search)과 관련된 기법들이 더 나은 내부 구성을 스스로 발견하는 시스템에 기여할 수 있다.

아키텍처 수준에서 모듈성(modularity)은 통제된 개선을 더욱 쉽게 만든다. 인지, 메모리, 추론, 계획, 도구 사용, 제어가 서로 구별되는 구성 요소로 표현된다면 시스템 전체를 다시 구축하지 않고도 개별 능력을 평가하고 수정할 수 있다. 메모리를 유지하면서 추론 모듈(reasoning module)을 교체하거나, 인지 기능과 독립적으로 검색 전략(retrieval strategy)을 최적화할 수 있다. 따라서 모듈형 아키텍처(modular architecture)는 실험과 검증(validation)을 수행할 수 있는 실질적인 경계를 제공한다.

AGI 시스템은 계산 자원(computational resource)을 할당하는 방식 자체도 개선할 수 있다. 어려운 문제에는 더 깊은 추론, 광범위한 검색(retrieval), 더 긴 계획 지평(planning horizon), 추가적인 검증이 필요하지만 익숙한 상황에는 가벼운 처리만으로 충분할 수 있다. 비용이 높은 인지 메커니즘(cognitive mechanism)을 언제 활성화해야 하는지를 학습하는 것 자체가 자기 개선의 한 형태가 된다. 이러한 적응형 계산(adaptive computation)은 더 나은 답변뿐 아니라 시간, 메모리, 에너지, 하드웨어를 더욱 효율적으로 사용함으로써 지능을 향상시킨다.

또 다른 중요한 차원은 커리큘럼 생성(curriculum generation)이다. 고급 에이전트는 외부에서 선택된 훈련 예제(training example)에 전적으로 의존하는 대신 자신의 능력이 부족한 영역을 식별하고 해당 약점을 집중적으로 개선하는 경험을 생성하거나 탐색할 수 있다. 스스로 질문을 만들고, 시뮬레이션된 과제(simulated task)를 생성하고, 익숙하지 않은 환경을 탐색하거나 외부 정보를 요청할 수 있다. 따라서 시스템은 단순히 훈련 데이터를 수동적으로 받아들이는 것이 아니라 다음에 무엇을 학습해야 하는지 결정하는 과정에 직접 참여한다.

자기 개선(Self-Improvement)은 월드 모델(world model)과 연결될 때 특히 강력해진다. 환경에 대한 내부 예측 표현(internal predictive representation)을 가진 에이전트는 실제 세계에서 행동하기 전에 상상되거나 시뮬레이션된 미래를 통해 가능한 전략을 시험할 수 있다. 예측 결과와 실제 관찰 결과 사이의 차이는 월드 모델 자체의 약점을 드러낸다. 에이전트는 환경에 대한 이해와 그 이해에 의존하는 정책을 함께 개선함으로써 상호 강화되는 개선(mutually reinforcing improvement)을 만들어낼 수 있다.

체화된 AGI(Embodied AGI)의 경우 개선은 인지와 행동 사이의 상호작용에서도 발생한다. 로봇(robot)은 특정 시점(viewpoint)이 객체 인식(object recognition)을 향상시키거나, 특정 이동 경로가 위치 추정 불확실성(localization uncertainty)을 줄이며, 물리적 조건에 따라 서로 다른 조작 전략(manipulation strategy)이 더 효과적이라는 사실을 발견할 수 있다. 따라서 지능은 고립된 데이터 처리만으로 발전하는 것이 아니라 능동적 경험(active experience)을 통해 발달하며, 환경은 운영 영역인 동시에 지속적인 학습 신호의 원천이 된다.

사회적 환경(social environment)과 다중 에이전트 환경(multi-agent environment)은 또 다른 개선 경로를 제공한다. 지능형 시스템은 다른 에이전트나 인간이 제공하는 시연(demonstration), 비평(critique), 토론(debate), 공유 메모리(shared memory), 성공적인 전략으로부터 학습할 수 있다. 모든 능력을 독립적으로 다시 발견하는 대신 외부에서 생성된 지식을 자신의 시스템에 통합하고 그것이 실제 행동을 개선하는지 평가할 수 있다. 따라서 자기 개선은 분산 지능(distributed intelligence)과 축적된 경험으로 구성된 더 큰 생태계 안에서도 이루어질 수 있다.

그러나 하나의 평가 지표(metric)를 개선했다고 해서 전체적인 지능이 향상되었다고 볼 수는 없다. 과제 정확도(task accuracy)를 높이는 과정에서 계산 비용이 증가하거나, 강건성(robustness)이 감소하거나, 이전에 학습한 과제의 성능이 저하되거나, 다른 영역에서 바람직하지 않은 행동이 발생할 수 있다. 따라서 자기 개선에는 능력(capability), 일반화(generalization), 효율성(efficiency), 신뢰성(reliability), 안전성(safety), 일관성(consistency)을 포함하는 다차원적 평가(multidimensional evaluation)가 필요하다. 수정 사항은 좁은 벤치마크(benchmark)의 향상만으로 채택해서는 안 되며 대표적인 다양한 상황에서 검증해야 한다.

지속적인 수정은 파국적 망각(catastrophic forgetting)이라는 문제도 발생시킨다. 새로운 학습이 기존에 습득한 능력을 방해하여 최근 과제에서는 성능이 향상되지만 이전 과제에서는 성능이 저하될 수 있다. 메모리 재생(memory replay), 매개변수 격리(parameter isolation), 정규화(regularization), 모듈형 적응(modular adaptation), 선택적 통합(selective consolidation) 등의 접근법은 유용한 능력을 보존하는 데 도움을 줄 수 있다. 진정한 자기 개선은 기존 기술을 새로운 기술과 계속 교환하는 것이 아니라 시간이 지남에 따라 능력을 누적해야 한다.

가역적 변화(reversible change)와 비가역적 변화(irreversible change)의 구분도 중요하다. 실험적인 수정은 실제 운영 시스템에 통합되기 전에 격리된 환경에서 평가되는 것이 바람직하다. 버전 관리된 모델(versioned model), 체크포인트(checkpoint), 샌드박스 실행(sandboxed execution), 회귀 테스트(regression test), 롤백 메커니즘(rollback mechanism)은 이러한 과정에 공학적 안전장치를 제공한다. 자기 개선 아키텍처는 신뢰할 수 있는 안정적인 구성을 유지하면서 별도로 후보 개선안을 생성하고 시험한 뒤 통제된 절차를 통해 적용할 수 있다.

개선이 중요한 능력이나 행동을 변경할 수 있는 경우에는 인간 감독(human oversight)이 여전히 중요하다. 제한된 매개변수나 저위험 전략에는 자율 최적화(autonomous optimization)를 적용할 수 있지만, 아키텍처 변경, 목표 수정 또는 안전 핵심 정책(safety-critical policy)의 변경에는 외부 승인이 필요할 수 있다. 이를 통해 시스템이 일부 구성 요소는 자유롭게 수정하고, 다른 부분은 제한적으로 실험하며, 보호된 목표나 제약 조건은 독립적으로 변경하지 못하도록 하는 적응 권한의 계층 구조(hierarchy of adaptation rights)를 구성할 수 있다.

따라서 무엇을 최적화하는지를 정의하는 목표(objective)가 근본적으로 중요하다. 잘못 정의된 목표를 점점 더 효과적으로 추구하는 시스템은 능력이 향상되더라도 실질적인 의미에서는 오히려 유용성이 감소할 수 있다. 자기 개선은 안정적인 상위 수준 목표(higher-level objective), 안전 제약 조건(safety constraint), 평가 절차 안에서 이루어져야 한다. 모든 개선 메커니즘은 무엇을 바람직한 변화로 간주할 것인지를 암묵적으로 정의하기 때문에 능력 향상(capability growth)과 정렬(alignment)을 서로 독립적인 과정으로 다룰 수 없다.

이는 제한된 자기 개선(bounded self-improvement)이라는 개념으로 이어진다. AGI 아키텍처는 시스템 전체를 제한 없이 수정할 권한을 부여하는 대신 명시적인 개선 범위(improvement envelope)를 정의할 수 있다. 여기에는 수정 가능한 매개변수, 허용된 도구, 계산 예산(computational budget), 배포 환경(deployment environment), 허용 가능한 아키텍처 변경 유형 등이 포함될 수 있다. 이러한 경계는 신뢰성, 통제 가능성(controllability), 시스템 정체성(system identity)을 보호하면서 실험과 적응을 가능하게 한다.

자기 개선(Self-Improvement)은 재귀적 자기 개선(recursive self-improvement)과도 구별된다. 시스템은 자기 개선 메커니즘 자체를 향상시키지 않으면서도 특정 과제의 성능을 개선할 수 있다. 재귀적 자기 개선은 시스템이 자신의 학습, 평가, 최적화 또는 재설계 능력 자체를 수정하면서 시작되며, 이후의 개선을 더욱 쉽고 빠르게 만들 가능성이 있다. 이러한 구분은 재귀적 개선이 훨씬 강력한 피드백 역학(feedback dynamics)을 발생시키므로 기본적인 적응 지능(adaptive intelligence)과 구분하여 다룰 필요가 있다는 점에서 중요하다.

공학적 관점에서 실용적인 자기 개선 파이프라인(self-improvement pipeline)은 지속적인 관찰(observation), 진단(diagnosis), 개선안 생성(proposal generation), 시뮬레이션 또는 샌드박스 시험, 평가(evaluation), 검증(validation), 배포(deployment), 모니터링(monitoring)의 과정으로 이해할 수 있다. 각 단계는 제안된 수정 사항이 다음 단계로 진행되어야 하는지를 판단하기 위한 증거를 생성한다. 이는 현대 머신러닝 수명주기 관리(machine-learning lifecycle management)와 유사하지만, 더 발전된 에이전트가 문제 진단과 후보 해결책 생성 과정에 직접 참여한다는 중요한 차이가 있다.

평가(evaluation)는 즉각적인 결과뿐 아니라 지연된 결과(delayed consequence)까지 포함해야 한다. 짧은 시험에서 우수한 성능을 보인 수정 사항도 장기적인 운영, 다른 모듈과의 상호작용, 익숙하지 않은 환경에 노출될 경우 미묘한 실패를 발생시킬 수 있다. 따라서 자기 개선 AGI에는 시간의 흐름에 따른 지속적인 모니터링과 회귀 테스트가 필요하다. 일반 지능은 장기간 이어지는 추론, 계획, 행동, 학습 과정에서 일관된 행동을 유지해야 하므로 장기 지평 평가(long-horizon evaluation)가 특히 중요하다.

자기 개선(Self-Improvement)이 발전할수록 학습(learning)과 시스템 설계(system design) 사이의 경계는 점차 흐려진다. 전통적인 공학에서는 아키텍처를 만드는 설계자와 그 내부에서 작동하는 모델을 구분한다. 충분한 적응 능력을 가진 AGI는 두 역할 모두에 참여할 수 있다. 즉, 과제를 수행하는 동시에 자신의 아키텍처가 해당 과제를 더 잘 수행할 수 있도록 개선하는 방법에 관한 증거를 수집한다. 지능은 더 이상 고정된 계산 구조만을 의미하지 않고 자신의 일부를 재설계할 수 있는 진화하는 과정(evolving process)이 된다.

궁극적으로 자기 개선(Self-Improvement)의 목적은 제한 없는 최적화(unlimited optimization)가 아니라 지속 가능한 적응 능력(sustained adaptive competence)에 있다. 일반 지능 시스템은 새로운 문제를 인식하고, 자신의 한계를 진단하며, 적절한 지식을 획득하고, 효과적이지 않은 전략을 수정하며, 가치 있는 기존 능력을 보존하고, 수정된 결과가 실제로 자신의 행동을 개선했는지 검증할 수 있어야 한다. 이러한 메커니즘은 메타 학습(meta-learning), 자동화 에이전트 설계(automated agent design), 자기 성찰(self-reflection), 지속 학습(continual learning), 그리고 궁극적으로 더욱 발전된 자기 진화 지능(self-evolving intelligence)을 위한 기반을 형성한다.

## 06.01. Meta Learning

![](images/image2.png){width="7.268055555555556in" height="7.268055555555556in"}

![](images/image3.png){width="7.268055555555556in" height="7.268055555555556in"}

메타 학습(Meta-Learning)은 흔히 "학습하는 방법을 학습하기(learning to learn)"라고 표현되며, 지능형 시스템(intelligent system)이 새로운 능력을 획득하는 과정 자체를 개선하는 능력을 의미한다. 특정 과제(task)의 성능만 최적화하는 대신, 메타 학습은 다양한 과제에서 계속 활용할 수 있는 학습 전략(learning strategy)을 발견하려 한다. 자기 진화 지능(self-evolving intelligence)에서 이 능력은 에이전트(agent)가 적응(adaptation)하는 능력 자체를 점진적으로 향상시킬 수 있도록 한다.

기존 머신러닝(machine learning)은 일반적으로 모델(model)이 데이터셋(dataset)을 입력받고, 미리 정의된 최적화 절차(optimization procedure)를 수행하면서 목표 문제를 해결하는 매개변수(parameter)를 점진적으로 학습한다고 가정한다. 메타 학습(Meta-Learning)은 이러한 과정의 상위에 또 하나의 학습 수준을 도입한다. 시스템은 여러 학습 에피소드(learning episode)를 관찰하고 학습이 어떻게 이루어져야 하는지에 관한 지식을 추출하여, 이전 학습 경험이 이후 적응의 속도와 방향 및 효과에 영향을 미치도록 한다.

이러한 구조는 내부 학습 순환(inner learning loop)과 외부 메타 학습 순환(outer meta-learning loop)을 구분하게 한다. 내부 순환은 이용 가능한 관찰이나 피드백을 사용하여 특정 과제에 모델을 적응시킨다. 외부 순환은 여러 과제에 걸친 성능을 평가하고 적응을 지배하는 메커니즘을 수정한다. 두 순환의 반복적인 상호작용을 통해 시스템은 더 빠른 학습을 가능하게 하는 초기 상태(initialization state), 표현(representation), 업데이트 규칙(update rule), 메모리 구조(memory structure), 전략(strategy)을 발견할 수 있다.

메타 학습 문제(meta-learning problem)는 일반적으로 하나의 데이터셋이 아니라 과제 분포(task distribution)를 중심으로 구성된다. 훈련 과정에서 학습자는 서로 관련되어 있지만 구별되는 여러 문제를 경험하며, 각각의 문제는 고유한 경험과 평가 신호(evaluation signal)를 제공한다. 목표는 이러한 과제의 해결책을 단순히 암기하는 것이 아니라 과제 사이에서 전이 가능한 규칙성(transferable regularity)을 발견하는 것이다. 새로운 과제가 나타나면 시스템은 이러한 규칙성을 활용하여 비교적 적은 추가 경험만으로 적응할 수 있다.

퓨샷 학습(Few-Shot Learning)은 이러한 원리를 명확하게 보여준다. 기존 모델은 새로운 범주(category)를 학습하기 위해 수천 개의 라벨된 예제(labeled example)를 필요로 할 수 있지만, 메타 학습된 시스템(meta-learned system)은 단지 몇 개의 시연(demonstration)만으로 유용한 행동을 추론하려 한다. 여기서 중요한 능력은 단순히 제한된 데이터로 분류하는 것이 아니라, 이전 과제에 관한 지식을 재사용하여 이전에 경험하지 못한 문제에 적절한 해결책을 빠르게 구성하는 것이다.

메타 학습(Meta-Learning)은 지능형 아키텍처(intelligent architecture)의 여러 수준에서 작동할 수 있다. 좋은 출발점을 제공하는 모델 매개변수(model parameter), 여러 도메인(domain)에 전이 가능한 표현, 매개변수가 어떻게 변화해야 하는지를 결정하는 최적화 규칙(optimization rule), 적절한 학습 전략을 선택하는 정책(policy)을 학습할 수 있다. 더욱 발전된 에이전트는 언제 메모리를 검색하고, 정보를 요청하고, 실험을 수행하고, 도구를 호출하며, 추가적인 계산 자원을 할당할 것인지까지 학습할 수 있다.

최적화 기반 메타 학습(optimization-based meta-learning)은 빠른 적응을 하나의 최적화 문제(optimization problem)로 취급한다. 시스템은 소수의 학습 단계만으로 새로운 과제에서 높은 성능을 얻을 수 있는 매개변수나 업데이트 절차를 탐색한다. 하나의 문제에 특화된 매개변수를 찾는 대신, 메타 목표(meta-objective)는 쉽게 적응할 수 있는 구성을 선호한다. 따라서 학습은 모델이 현재 무엇을 알고 있는지만 결정하는 것이 아니라 그 지식을 얼마나 쉽게 재구성할 수 있는지도 결정한다.

거리 기반 접근법(metric-based approach)은 예제 사이의 유사성(similarity)이 빠른 추론에 유용하도록 표현을 학습한다. 새로운 관찰은 이전에 인코딩된 예제(encoded example), 프로토타입(prototype), 학습된 참조 구조(reference structure)와 비교될 수 있다. 표현이 전이 가능한 관계를 포착하고 있다면 단지 몇 개의 예제만으로 새로운 개념을 인식할 수 있다. 이러한 접근법은 적절한 표현 공간의 기하학(representational geometry)을 학습하는 것 자체가 학습하는 방법을 학습하는 하나의 형태가 될 수 있음을 보여준다.

메모리 기반 메타 학습(memory-based meta-learning)은 저장된 경험을 적응 자원(adaptive resource)으로 활용한다. 이전의 모든 지식을 고정된 모델 매개변수에 저장하도록 강제하는 대신, 시스템은 새로운 문제를 만났을 때 관련된 에피소드, 전략, 해결책 또는 맥락 패턴(contextual pattern)을 검색할 수 있다. 어텐션(attention)과 검색 메커니즘(retrieval mechanism)은 현재 상황에서 어떤 메모리가 유용한지를 결정하며, 이를 통해 매개변수 업데이트뿐 아니라 경험에 대한 동적인 접근을 통해서도 적응이 이루어질 수 있다.

문맥 내 학습(In-Context Learning)은 빠른 적응에 대한 또 다른 관점을 제공한다. 충분한 능력을 가진 모델은 자신의 매개변수를 영구적으로 변경하지 않더라도 현재 문맥(context) 안에서 제공되는 지시(instruction), 시연, 예제 또는 중간 피드백(intermediate feedback)을 통해 행동을 변화시킬 수 있다. AGI 관점에서 이것은 모델이 상호작용 과정에서 이용 가능한 정보를 기반으로 과제의 구조를 추론하고 적절한 전략을 구성하는 일시적인 학습 과정(temporary learning process)과 유사하다.

메타 강화학습(meta-reinforcement learning)은 이러한 개념을 순차적 의사결정(sequential decision making)으로 확장한다. 하나의 환경에 대한 고정 정책(fixed policy)을 학습하는 대신, 에이전트는 여러 환경군(environment family)을 경험하면서 보상(reward), 관찰(observation), 이전 행동으로부터 자신의 행동을 적응시키는 방법을 학습한다. 내부 상태(internal state) 또는 메모리는 현재 에피소드에서 발견된 내용을 인코딩하여, 에이전트가 효율적으로 탐색하고 어떤 전략이 적절한지를 빠르게 추론하도록 할 수 있다.

월드 모델(world model)은 메타 학습(Meta-Learning)을 크게 강화할 수 있다. 에이전트가 객체(object), 행동(action), 동역학(dynamics), 인과관계(causality), 시간적 상태 전이(temporal transition)를 설명하는 재사용 가능한 구조를 학습한다면 새로운 과제를 원시 관찰(raw observation)로부터 완전히 다시 학습할 필요가 없다. 시스템은 새로운 목표와 제약 조건 아래에서 기존의 세계 지식을 재해석할 수 있다. 적응은 처음부터 지능을 다시 구성하는 것이 아니라 이전에 학습된 개념과 예측 구조를 재조합하는 과정이 된다.

체화된 에이전트(embodied agent)의 경우 메타 학습은 서로 다른 로봇, 환경, 객체, 지형 조건, 센서(sensor), 물리 동역학(physical dynamics)에 대한 적응을 지원할 수 있다. 하나의 환경을 탐색하면서 획득한 경험은 다른 환경에서 탐색 방법을 학습하는 데 도움을 줄 수 있다. 이전 객체에 대한 조작 경험(manipulation experience)은 익숙하지 않은 객체에 대한 사전 지식(prior)을 제공할 수 있다. 따라서 시스템은 운동 정책(motor policy)뿐 아니라 새로운 물리적 상황의 특성을 효율적으로 발견하는 방법까지 학습한다.

중요한 메타 학습 능력 중 하나는 능동적 정보 획득(active information acquisition)이다. 불확실성에 직면했을 때 지능형 에이전트는 어떤 관찰, 실험, 질문 또는 행동이 적응에 가장 유용한 정보를 제공하는지를 판단해야 한다. 무엇을 관찰해야 하는지를 학습하는 것은 관찰 결과로부터 학습하는 것만큼 중요할 수 있다. 이는 메타 학습을 능동 학습(active learning), 탐색(exploration), 실험 설계(experiment design), 도구 사용(tool use), 자율 과학 추론(autonomous scientific reasoning)과 연결한다.

메타 학습(Meta-Learning)은 시스템이 서로 다른 종류의 문제에 서로 다른 전략을 학습하도록 할 수도 있다. 일부 과제에는 검색(retrieval)이 효과적이고, 다른 과제에는 기호 추론(symbolic reasoning), 시뮬레이션(simulation), 최적화, 모방 학습(imitation learning), 강화학습(reinforcement learning)이 더 적합할 수 있다. 하나의 학습 알고리즘을 모든 문제에 동일하게 적용하는 대신, 더욱 일반적인 에이전트는 문제의 구조를 추정하고 그에 따라 학습 메커니즘을 선택하거나 결합할 수 있다. 따라서 전략 선택(strategy selection) 자체가 또 하나의 학습 대상이 된다.

전이(transfer)와 일반화(generalization)는 핵심적인 요구사항이다. 훈련 경험과 매우 유사한 과제에만 빠르게 적응하는 메타 학습자는 광범위하게 유용한 학습 능력이 아니라 제한된 적응 절차를 학습한 것이다. 효과적인 메타 학습에는 다양한 훈련 경험과 그 이면의 공통 규칙을 포착하는 표현이 필요하다. 따라서 평가는 익숙한 예제의 반복적인 변형보다 실제로 새로운 조건에 대한 적응 능력을 중요하게 평가해야 한다.

과제 다양성(task diversity)은 어려운 균형 문제를 발생시킨다. 훈련 과제가 지나치게 유사하면 시스템이 제한된 과제군(task family)에 과적합(overfitting)될 수 있다. 반대로 과제들이 서로 관련성이 없다면 전이 가능한 구조를 발견하기 어려울 수 있다. 유용한 메타 학습 환경은 의미 있는 잠재 원리(latent principle)를 공유하면서도 서로 다른 해결책을 요구하는 변화를 에이전트에게 제공한다. 이를 통해 학습자는 과제 전반에서 무엇이 안정적으로 유지되고 무엇을 맥락에 따라 적응해야 하는지를 발견할 수 있다.

메타 학습(Meta-Learning)은 부정적 전이(negative transfer)의 문제도 해결해야 한다. 하나의 도메인에서 학습 속도를 높였던 지식이 다른 도메인의 적응을 방해할 수 있기 때문이다. 따라서 지능형 시스템은 이전 경험을 적용하기 전에 그것이 현재 문제와 관련이 있는지를 추정하는 메커니즘을 필요로 한다. 불확실성 추정(uncertainty estimation), 모듈형 표현(modular representation), 과제 추론(task inference), 선택적 검색(selective retrieval), 맥락 게이팅(contextual gating)은 부적절한 기존 전략의 재사용을 방지하면서 유용한 전이 지식을 유지하는 데 도움을 줄 수 있다.

메타 학습(Meta-Learning)과 지속 학습(continual learning)의 관계는 자기 진화 지능(self-evolving intelligence)에서 특히 중요하다. 지속 학습은 파국적 망각(catastrophic forgetting)을 방지하면서 장기간 이어지는 경험으로부터 능력을 축적하는 데 초점을 맞추는 반면, 메타 학습은 적응 메커니즘 자체를 개선하는 데 초점을 둔다. 두 가지를 결합하면 에이전트는 이전 지식을 보존하면서 미래 경험으로부터 새로운 지식을 획득하는 효율성을 지속적으로 향상시킬 수 있다.

메타 학습(Meta-Learning)은 자기 성찰(self-reflection)과도 직접적으로 연결된다. 에이전트는 이전 학습 에피소드(learning episode)를 분석하여 어떤 전략이 성공적인 적응을 만들어냈으며 어떤 전략이 오류, 과도한 계산 또는 낮은 일반화를 발생시켰는지를 식별할 수 있다. 성찰(reflection)은 이러한 관찰을 문제 해결에 관한 상위 수준의 규칙(higher-level rule)으로 변환할 수 있다. 이후 이러한 규칙은 계획, 검색, 실험, 학습을 안내하면서 경험으로부터 개선된 학습 전략으로 이어지는 피드백 경로(feedback pathway)를 형성한다.

따라서 실용적인 메타 학습 시스템(meta-learning system)은 여러 시간 척도(timescale)에 걸친 세심한 평가를 필요로 한다. 즉각적인 적응 속도도 중요하지만 최종 성능, 샘플 효율성(sample efficiency), 계산 비용, 강건성(robustness), 전이, 장기 기억 유지(long-term retention) 역시 중요하다. 빠르게 학습하지만 불안정한 행동을 생성하는 전략은 더 느리게 적응하더라도 신뢰할 수 있고 전이 가능한 지식을 만들어내는 전략보다 열등할 수 있다. 따라서 메타 학습 목표는 이러한 보다 광범위한 적응 역량(adaptive competence)을 반영해야 한다.

시스템이 자신의 학습 행동 자체를 수정하는 방법을 학습할수록 안전성(safety)은 더욱 중요해진다. 메타 학습자는 모든 성능 향상을 자동적으로 바람직한 것으로 간주해서는 안 된다. 보호된 목표(protected objective), 제약된 최적화(constrained optimization), 검증 환경(validation environment), 권한 경계(permission boundary), 모니터링(monitoring), 롤백 메커니즘(rollback mechanism)은 학습된 적응 전략이 실제 운영 행동에 영향을 미치는 범위를 제한할 수 있다. 따라서 학습하는 방법을 학습하는 과정은 상위 수준의 안전성과 정렬(alignment) 요구사항을 준수해야 한다.

공학적 수준에서 메타 학습(Meta-Learning)은 과제 경험(task experience), 메모리(memory), 적응(adaptation), 평가(evaluation), 전략 최적화(strategy optimization)를 연결하는 아키텍처로 이해할 수 있다. 개별 과제는 학습 에피소드를 생성하고, 에피소드는 저장되고 비교되며, 반복적으로 나타나는 패턴이 추출된다. 이후 적응 메커니즘이 업데이트되고 수정된 학습자는 새로운 과제에서 시험된다. 이러한 과정의 반복은 축적된 경험을 미래의 능력을 더욱 효과적으로 획득하기 위한 절차로 점진적으로 변환한다.

AGI에서 메타 학습(Meta-Learning)이 중요한 이유는 대규모 재훈련(retraining)과 사람이 직접 설계한 학습 절차에 대한 의존성을 줄일 수 있기 때문이다. 일반 지능 시스템(generally intelligent system)은 설계자가 사전에 모두 열거할 수 없는 상황을 계속해서 만나게 된다. 따라서 익숙하지 않은 문제를 어떻게 학습해야 하는지를 스스로 발견할 수 있는 메커니즘이 필요하다. 메타 학습은 이전 경험을 세계에 관한 지식뿐 아니라 지식을 획득하는 과정 자체에 관한 지식으로 전환하는 프레임워크(framework)를 제공한다.

자기 진화 지능(self-evolving intelligence)에서 메타 학습(Meta-Learning)은 단순히 학습을 통해 변화하는 시스템에서 자신이 변화하는 방법 자체를 개선하는 시스템으로의 전환을 의미한다. 이러한 상위 수준의 적응(higher-order adaptation)은 빠른 일반화, 자율 기술 습득(autonomous skill acquisition), 지속 학습(continual learning), 자기 성찰(self-reflection), 자동화 에이전트 설계(automated agent design), 그리고 궁극적으로 재귀적 개선(recursive improvement)을 위한 기반을 제공한다. 장기적인 목표는 축적된 경험이 다음에 무엇을 만나더라도 그것을 학습할 수 있는 능력을 지속적으로 향상시키는 지능을 구현하는 것이다.

## 06.02. AutoML and AutoAgents [w/Code]

![](images/image4.png){width="7.268055555555556in" height="7.268055555555556in"}

자동화 머신러닝(AutoML, Automated Machine Learning)은 전통적으로 인간 전문가가 수행하던 모델 개발의 중요한 부분을 계산 시스템이 자동화할 수 있도록 함으로써 머신러닝(machine learning)을 확장한다. 이러한 과정에는 데이터 전처리(data preprocessing), 특징 선택(feature selection), 모델 선택(model selection), 하이퍼파라미터 최적화(hyperparameter optimization), 아키텍처 탐색(architecture search), 훈련 구성(training configuration), 평가(evaluation) 등이 포함될 수 있다. 자기 진화 지능(self-evolving intelligence)에서 AutoML은 AI 시스템이 인간의 개입을 점차 줄이면서 더 나은 학습 구성을 탐색할 수 있도록 하는 메커니즘을 제공한다.

AGI에서 AutoML이 갖는 의미는 단순히 엔지니어링 작업량을 줄이는 것보다 훨씬 넓다. 일반 지능 시스템(generally intelligent system)은 새로운 문제를 만날 때마다 인간 개발자가 학습 파이프라인(learning pipeline)을 수동으로 다시 설계하는 방식에 의존할 수 없다. 시스템 스스로 대안적인 모델과 구성을 자율적으로 탐색할 수 있는 메커니즘이 필요하다. 따라서 AutoML은 AI 시스템이 자신의 계산 구조 일부를 직접 설계하고 개선하는 데 참여하는 시스템으로 발전하기 위한 초기 공학적 경로를 나타낸다.

일반적인 AutoML 과정은 가능한 모델, 매개변수(parameter), 전처리 연산(preprocessing operation), 아키텍처 또는 훈련 전략을 포함하는 탐색 공간(search space)을 정의하는 것으로 시작한다. 이후 탐색 알고리즘(search algorithm)이 후보 구성을 제안하고 성능을 평가하며, 그 결과를 이용하여 다음에 어떤 후보를 탐색할 것인지 결정한다. 이 과정은 모델 엔지니어링(model engineering)을 체계적인 실험을 통해 점점 더 효과적인 해결책을 발견하는 최적화 문제(optimization problem)로 변환한다.

하이퍼파라미터 최적화(hyperparameter optimization)는 자동화된 모델 개선의 가장 확립된 형태 중 하나이다. 학습률(learning rate), 정규화 강도(regularization strength), 배치 크기(batch size), 옵티마이저 설정(optimizer setting), 모델 차원(model dimension) 등의 매개변수는 성능에 큰 영향을 줄 수 있다. 이러한 값을 수동으로 선택하는 대신 자동화 시스템은 무작위 탐색(random search), 베이지안 최적화(Bayesian optimization), 진화 알고리즘(evolutionary algorithm), 개체군 기반 방법(population-based method) 등을 사용하여 유망한 영역에 계산 자원을 집중할 수 있다.

신경망 아키텍처 탐색(Neural Architecture Search, NAS)은 자동화 최적화를 신경망(neural network)의 구조 자체로 확장한다. 탐색 공간에는 계층(layer), 연결(connection), 연산(operation), 어텐션 메커니즘(attention mechanism), 은닉 차원(hidden dimension), 재사용 가능한 모듈의 조합 등이 포함될 수 있다. 후보 아키텍처를 훈련하거나 근사적으로 평가하고 목표에 따라 비교함으로써, 과거 사람이 직접 설계했던 모델 아키텍처의 일부를 계산 기반 탐색과 최적화의 대상으로 만들 수 있다.

그러나 AutoML은 예측 정확도(predictive accuracy)만 최적화해서는 안 된다. 실제 시스템은 지연 시간(latency), 메모리(memory), 에너지 소비(energy consumption), 하드웨어 가용성(hardware availability), 강건성(robustness), 훈련 비용(training cost), 배포 요구사항(deployment requirement) 등의 제약 조건 아래에서 작동한다. 따라서 다목적 AutoML(multi-objective AutoML)은 여러 경쟁 목표 사이의 균형을 만족하는 구성을 탐색할 수 있다. 클라우드(cloud), 엣지(edge), 체화 플랫폼(embodied platform)을 넘나드는 AGI에서는 지능의 품질과 제한된 계산 자원 사이의 균형이 특히 중요하다.

자동 에이전트(AutoAgents)는 이와 유사한 원리를 모델 개발에서 자율 에이전트(autonomous agent)의 구성과 운영으로 확장한다. 단순히 더 나은 신경망 모델을 탐색하는 것이 아니라 에이전트가 어떻게 추론하고, 계획하고, 정보를 검색하고, 메모리를 사용하고, 도구를 호출하고, 다른 에이전트와 통신하며, 결과를 평가할 것인지를 구성할 수 있다. 따라서 탐색 공간은 모델 매개변수와 아키텍처에서 완전한 인지 워크플로(cognitive workflow)와 상호작용 패턴(interaction pattern)으로 확장된다.

자동 에이전트(AutoAgent)는 특정 목표를 위해 일련의 연산을 동적으로 구성할 수 있다. 과제가 검색(retrieval), 추론(reasoning), 시뮬레이션(simulation), 코드 실행(code execution), 외부 도구(external tool), 계획(planning), 검증(verification), 전문화된 에이전트와의 협업 중 무엇을 필요로 하는지 판단할 수 있다. 모든 문제에 하나의 고정된 파이프라인을 적용하는 대신 이용 가능한 능력으로 적절한 워크플로를 구성할 수 있으며, 이에 따라 에이전트 아키텍처는 완전히 사전 결정된 구조가 아니라 과제에 따라 적응하는 구조가 된다.

도구 선택(tool selection)은 이러한 프레임워크에서 특히 중요하다. 능력 있는 에이전트는 검색 시스템, 데이터베이스(database), 계산기, 시뮬레이터(simulator), 소프트웨어 환경, 로봇 제어기(robotic controller), 센서(sensor), 외부 서비스에 접근할 수 있다. 에이전트는 어떤 도구가 적절한지, 어떤 정보를 입력해야 하는지, 결과를 어떻게 해석해야 하는지, 추가 검증이 필요한지를 학습해야 한다. 이러한 의사결정을 개선하는 것만으로도 기반 모델(foundation model)을 변경하지 않고 전체 시스템의 능력을 크게 향상시킬 수 있다.

메모리 구성(memory configuration) 역시 자동화할 수 있다. 서로 다른 과제에는 작업 기억(working memory), 일화 기억(episodic memory), 의미 지식(semantic knowledge), 검색된 문서(retrieved document), 절차적 경험(procedural experience)의 서로 다른 조합이 필요할 수 있다. 자동 에이전트는 정보를 언제 저장하고, 압축하고, 검색하고, 삭제하거나 더 지속적인 지식으로 승격시킬지를 학습할 수 있다. 이를 통해 메모리 관리는 정적인 엔지니어링 선택에서 지능적 행동의 적응형 구성 요소(adaptive component)로 변화한다.

계획(planning)은 자동화의 또 다른 중요한 영역이다. 일부 문제는 짧은 행동 순서로 해결할 수 있지만 다른 문제는 계층적 분해(hierarchical decomposition), 장기 지평 계획(long-horizon planning), 재계획(replanning), 여러 대안 전략의 병렬 탐색(parallel exploration)이 필요하다. 자동 에이전트는 과제 복잡도를 추정하고 적절한 계획 깊이(planning depth), 추론 예산(reasoning budget), 분해 전략(decomposition strategy)을 선택할 수 있다. 따라서 에이전트는 무엇을 생각할 것인지뿐 아니라 생각하는 데 얼마나 많은 계산을 투입할 것인지도 적응시킨다.

다중 에이전트(multiple agents)는 설계 공간을 더욱 확장할 수 있다. 복잡한 문제는 계획자(planner), 연구자(researcher), 비평자(critic), 검증자(verifier), 시뮬레이터, 실행자(executor), 메모리 관리자(memory manager) 등의 전문화된 역할로 분해될 수 있다. 자동화된 에이전트 시스템은 과제 요구사항에 따라 이러한 역할을 생성하고, 선택하고, 조정하거나 제거할 수 있다. 따라서 다중 에이전트 조직 자체가 더 나은 협업 패턴을 학습하면서 변화할 수 있는 구성 가능한 아키텍처(configurable architecture)가 된다.

평가(evaluation)는 AutoML과 자동 에이전트(AutoAgents)를 실제 자기 개선(self-improvement)과 연결하는 메커니즘이다. 후보 모델, 워크플로, 도구, 프롬프트(prompt), 정책(policy), 에이전트 구조를 측정 가능한 증거를 사용하여 비교해야 한다. 평가는 정확성(correctness), 일반화(generalization), 과제 완료(task completion), 계산 비용(computational cost), 지연 시간, 신뢰성(reliability), 안전성(safety), 장기적 결과(long-term consequence)를 고려할 수 있다. 엄격한 평가가 없다면 자동화된 생성은 단순히 여러 대안을 만들어낼 뿐 그것이 의미 있는 개선인지는 판단할 수 없다.

이를 통해 생성-평가-선택 순환(generate-evaluate-select cycle)이 형성된다. 시스템은 후보 구성을 제안하고, 통제된 환경에서 실행하고, 결과를 측정하고, 유망한 대안을 선택한 후 축적된 결과를 이용하여 이후 탐색을 안내한다. 많은 반복을 거치면서 탐색 과정은 이전 실험에서 얻은 정보에 의해 점점 더 정교해질 수 있다. 따라서 AutoML과 자동 에이전트는 개선을 한 번의 수동 설계 훈련 과정이 아니라 지속적인 실험 과정(continuous experimental process)으로 변화시킨다.

시뮬레이션(simulation)과 샌드박스 환경(sandbox environment)은 자율적인 실험이 예상하지 못한 행동을 만들어낼 수 있기 때문에 특히 중요하다. 후보 에이전트는 실제 배포 전에 합성 과제(synthetic task), 시뮬레이션 세계(simulated world), 벤치마크 모음(benchmark suite), 적대적 상황(adversarial situation), 회귀 테스트(regression test)를 통해 시험할 수 있다. 성능이 좋지 않은 구성은 운영 시스템에 영향을 주지 않고 제거할 수 있다. 자동화 시스템이 자신의 행동에서 점점 더 중요한 부분을 수정할 수 있게 될수록 실험과 실제 실행을 분리하는 것은 필수적이다.

월드 모델(world model)은 자동화된 탐색을 훨씬 효율적으로 만들 수 있다. 모든 후보를 비용이 높은 실제 환경과의 상호작용을 통해 평가하는 대신, 에이전트는 예측 모델(predictive model)을 사용하여 아키텍처, 계획, 행동, 도구 사용 순서의 예상 결과를 추정할 수 있다. 이후 유망한 대안에 더욱 상세한 평가를 수행할 수 있다. 월드 모델이 개선될수록 실제 자원을 투입하거나 물리적 행동을 실행하기 전에 가능한 변화를 시험하는 더욱 유용한 내부 환경을 제공할 수 있다.

AutoML과 자동 에이전트(AutoAgents)는 메타 학습(meta-learning)과도 자연스럽게 상호작용한다. AutoML은 효과적인 모델과 구성을 탐색하고, 메타 학습은 특정 종류의 문제에서 어떤 탐색 전략이 효과적일 가능성이 높은지를 학습할 수 있다. 마찬가지로 자동 에이전트는 다양한 워크플로를 생성하고 메타 학습은 어떤 에이전트 구조가 가장 효과적으로 적응하는지를 보여주는 패턴을 식별할 수 있다. 시스템은 점차 더 좋은 해결책뿐 아니라 그러한 해결책을 발견하는 더 좋은 절차까지 학습하게 된다.

과거 경험(historical experience)은 탐색 비용을 더욱 줄일 수 있다. 이전 실험은 특정 조건에서 어떤 아키텍처, 도구, 프롬프트, 계획 전략, 에이전트 조직이 성공했는지에 관한 정보를 제공한다. 메모리 시스템(memory system)은 새로운 탐색을 시작하기 전에 관련 사례를 검색하여 에이전트가 무작위로 탐색하는 대신 이미 정보를 가진 후보에서 출발하도록 할 수 있다. 따라서 자동화된 설계는 시스템이 재사용 가능한 엔지니어링 및 운영 지식을 축적함에 따라 점점 더 효율적으로 발전한다.

체화된 AGI(Embodied AGI)에서 자동화 에이전트는 환경 조건에 따라 인지(perception), 위치 추정(localization), 계획, 제어(control), 계산 자원 할당(computational allocation)을 구성할 수 있다. 단순한 환경에서 작동하는 로봇은 가벼운 인지와 계획을 사용할 수 있지만 불확실하거나 위험한 상황에서는 추가적인 센싱(sensing), 예측(prediction), 검증, 추론을 활성화할 수 있다. 따라서 자동 에이전트 메커니즘은 운영 요구에 따라 계산 강도(computational intensity)가 변화하는 적응형 인지 아키텍처(adaptive cognitive architecture)를 지원할 수 있다.

이러한 유연성은 동시에 중요한 안전 문제(safety concern)를 발생시킨다. 모델, 프롬프트, 도구, 워크플로 또는 에이전트 구조를 수정할 수 있는 자율 시스템은 중요한 안전장치를 실수로 제거하거나 좁은 평가 지표에서는 높은 성능을 보이지만 다른 영역에서는 바람직하지 않은 행동을 나타내는 구성을 발견할 수 있다. 보호된 구성 요소(protected component), 권한 경계(permission boundary), 제한된 탐색 공간(constrained search space), 변경 불가능한 안전 정책(immutable safety policy), 검증 게이트(validation gate), 감사 로그(audit log), 인간 승인(human authorization)을 통해 허용되는 수정과 배포 방식을 제한할 수 있다.

따라서 버전 관리(versioning)와 롤백(rollback)은 기본적인 공학 메커니즘이다. 모든 후보 구성에는 식별 가능한 상태, 평가 이력(evaluation history), 의존성 기록(dependency record), 재현 가능한 실행 환경(reproducible execution environment)이 있어야 한다. 새롭게 배포된 구성이 예상하지 못한 성능 저하를 발생시키면 시스템은 이전에 검증된 상태로 돌아갈 수 있어야 한다. 자기 진화 시스템은 앞으로 나아가는 메커니즘뿐 아니라 실패한 변경을 신뢰성 있게 되돌리는 메커니즘도 필요하다.

또 다른 문제는 잘못된 벤치마크(misleading benchmark)를 향한 최적화를 피하는 것이다. 자동화 시스템은 평가 절차의 약점을 이용하여 의도한 능력을 실제로 획득하지 않고도 높은 점수를 만들어낼 수 있다. 따라서 평가에는 다양한 과제, 숨겨진 시험(hidden test), 강건성 검사(robustness check), 장기 지평 시나리오(long-horizon scenario), 독립적인 검증(independent validation)이 필요하다. 최적화 과정이 자율화될수록 평가 체계가 시스템에 요구되는 실제 목표를 정확하게 표현하는 것이 더욱 중요해진다.

공학적 관점에서 AutoML과 자동 에이전트(AutoAgents)는 문제 식별(problem identification), 후보 생성(candidate generation), 자동화된 실험(automated experimentation), 평가, 선택(selection), 검증(validation), 배포(deployment), 모니터링(monitoring), 피드백(feedback)으로 구성된 통제된 수명주기(controlled lifecycle)에 통합될 수 있다. 운영 결과는 새로운 증거로 탐색 시스템에 다시 전달된다. 이를 통해 시스템 운영과 시스템 설계 사이의 순환이 닫히며, 실제로 배포된 지능이 자신의 미래 개선을 위한 정보를 제공할 수 있다.

AutoML과 자동 에이전트(AutoAgents)의 더 깊은 의미는 AI 엔지니어링의 일부를 인간이 직접 설계하는 구성 방식에서 기계 지원 발견(machine-assisted discovery)으로 전환한다는 데 있다. 모델, 학습 절차, 인지 워크플로, 도구 조합, 메모리 전략, 에이전트 조직은 점차 탐색 가능한 설계 변수(searchable design variable)가 된다. 인간 엔지니어는 목표, 제약 조건, 인터페이스(interface), 안전 경계를 정의하고 자동화 시스템은 그 경계 내부에서 방대한 구현 가능성을 탐색할 수 있다.

자기 진화 지능(self-evolving intelligence)에서 AutoML과 자동 에이전트(AutoAgents)는 메타 학습(meta-learning)과 더욱 발전된 자기 개선(self-improvement)을 연결하는 실용적인 다리를 제공한다. 메타 학습은 시스템이 학습하는 방법을 개선하고, 자동화된 모델 및 에이전트 설계는 학습과 추론을 수행하는 구조 자체를 변경할 수 있는 메커니즘을 제공한다. 메모리, 성찰(reflection), 지속 학습(continual learning), 평가, 통제된 실험(controlled experimentation)과 결합될 때 이러한 메커니즘은 AGI가 자신의 운영 구조 일부를 점진적으로 재설계할 수 있는 아키텍처로 발전하도록 한다.

## 06.03. Self Reflection

![](images/image5.png){width="7.268055555555556in" height="7.268055555555556in"}

인공 일반 지능(Artificial General Intelligence)에서 자기 성찰(Self-Reflection)은 지능형 시스템이 자신의 추론(reasoning), 의사결정(decision), 행동(action), 내부 상태(internal state), 결과(outcome)를 검토하여 약점을 식별하고 향후 행동을 개선하는 능력을 의미한다. 성찰형 에이전트(reflective agent)는 외부 피드백에만 반응하는 것이 아니라 자신이 어떻게 특정 결과에 도달했는지를 분석한다. 이를 통해 일반적인 경험을 시스템 자신의 인지적 작동(cognitive operation)에 관한 정보로 변환하는 내부 평가 과정(internal evaluation process)이 형성된다.

성찰(reflection)은 성공이나 실패의 원인을 조사한다는 점에서 기본적인 오류 수정(error correction)과 다르다. 시스템은 어떤 답변이 잘못되었다는 사실을 인식할 수 있지만, 자기 성찰(Self-Reflection)은 어떤 가정(assumption), 검색된 메모리(retrieved memory), 추론 단계, 계획, 도구 또는 관찰이 오류에 영향을 미쳤는지를 분석한다. 최종 결과뿐 아니라 중간 과정(intermediate process)을 검토함으로써 에이전트는 그렇지 않았다면 발견되지 않았을 반복적인 약점을 식별할 수 있다.

유용한 성찰 순환(reflective cycle)은 에이전트가 과제를 수행하고 자신의 활동과 관련된 추적 정보(trace)를 기록하는 것에서 시작한다. 이러한 기록에는 관찰, 검색된 정보, 중간 추론 상태(intermediate reasoning state), 의사결정, 도구 호출(tool call), 행동, 신뢰도 추정(confidence estimate), 결과 등이 포함될 수 있다. 실행 이후 시스템은 실제 발생한 결과와 예상 결과를 비교하고 중요한 차이, 불확실성, 성공과 실패에 대한 설명을 구성한다.

따라서 자기 성찰(Self-Reflection)은 메모리(memory)에 크게 의존한다. 일화 기억(episodic memory)은 이전 시도와 결과를 보존하고, 의미 기억(semantic memory)은 일반화된 교훈을 표현하며, 절차 기억(procedural memory)은 개선된 전략을 저장할 수 있다. 이후 유사한 상황이 발생하면 에이전트는 같은 실수를 반복하는 대신 이전 경험에서 도출된 성찰 결과를 검색할 수 있다. 성찰은 원시 경험(raw experience)을 효과적이거나 비효과적인 인지 행동에 관한 재사용 가능한 지식으로 변환한다.

메타인지(Metacognition)는 이러한 과정의 중요한 개념적 기반을 제공한다. 메타인지는 자신의 인지 과정에 관한 지식과 이를 조절하는 능력을 의미한다. 인공 시스템에서는 신뢰도 추정, 불확실성 탐지, 지식 부족의 인식, 추론 진행 상황의 모니터링, 추가적인 계산이 필요한 시점의 판단 등이 포함될 수 있다. 메타인지 에이전트(metacognitive agent)는 단순히 문제를 해결하는 데 그치지 않고 자신의 문제 해결 과정이 얼마나 잘 작동하고 있는지도 추정한다.

불확실성 인식(uncertainty awareness)은 특히 중요하다. 성찰 과정에서는 내부적으로 생성된 모든 결론이 신뢰할 수 있다고 가정해서는 안 되기 때문이다. 지능형 시스템은 증거가 불완전하거나, 서로 충돌하거나, 익숙하지 않거나, 자신의 능력 범위를 벗어나는 상황을 인식할 수 있는 메커니즘을 필요로 한다. 이러한 인식은 추가 검색, 시뮬레이션, 검증, 실험 또는 인간의 지원을 유발할 수 있다. 따라서 초기 답변을 언제 신뢰하지 않아야 하는지를 아는 것은 성찰 지능(reflective intelligence)의 중요한 구성 요소이다.

성찰(reflection)은 서로 다른 수준에서 이루어질 수 있다. 과제 수준(task level)에서는 특정 답변이나 행동이 성공적이었는지를 검토한다. 전략 수준(strategy level)에서는 선택한 추론, 계획 또는 도구 사용 방식이 적절했는지를 평가한다. 아키텍처 수준(architectural level)에서는 메모리, 검색, 인지(perception), 계획 또는 학습 메커니즘에서 반복적으로 나타나는 한계를 식별할 수 있다. 이러한 여러 수준은 즉각적인 오류 수정과 장기적인 자기 개선(self-improvement)을 연결한다.

실용적인 형태 중 하나는 결과 기반 성찰(outcome-based reflection)이며, 시스템은 예상된 결과와 실제 관찰된 결과 사이의 차이를 분석한다. 예측 오류(prediction error), 실패한 행동, 낮은 보상(reward), 실패한 계획 또는 외부 비평(external critique)은 진단을 위한 증거가 된다. 에이전트는 실패가 잘못된 인지, 불완전한 지식, 잘못된 추론, 부적절한 계획, 잘못된 도구 선택, 실행 오류 또는 부정확한 환경 모델 중 어디에서 발생했는지를 판단하려 한다.

과정 기반 성찰(process-based reflection)은 결과 자체만 평가하는 대신 결과가 어떻게 만들어졌는지를 검토한다. 두 해결책이 동일한 결과를 얻더라도 신뢰성(reliability), 효율성(efficiency), 일반화 가능성(generalizability)에서는 크게 다를 수 있다. 중간 의사결정을 검토하면 시스템은 불필요한 계산, 근거 없는 가정, 취약한 추론 경로, 중복된 도구 호출 또는 우연한 성공을 발견할 수 있다. 이를 통해 최종 답변이 우연히 정확했던 경우에도 개선이 가능하다.

자기 비평(self-critique)은 에이전트가 명시적인 기준에 따라 자신이 생성한 결과를 의도적으로 평가하는 관련 메커니즘이다. 이러한 기준에는 정확성(correctness), 완전성(completeness), 일관성(consistency), 안전성(safety), 관련성(relevance), 효율성, 제약 조건 준수(compliance with constraints) 등이 포함될 수 있다. 이후 비평 결과를 이용하여 답변이나 행동을 확정하기 전에 수정할 수 있다. 이를 통해 외부의 수정 없이도 성능을 개선할 수 있는 내부 생성-평가-수정 순환(generate-evaluate-revise loop)이 형성된다.

성찰(reflection)은 여러 관점(multiple perspectives)을 활용할 수도 있다. 하나의 추론 과정이 즉시 자기 자신을 평가하도록 하는 대신, 아키텍처는 생성(generation)과 비평 또는 검증(verification)을 분리할 수 있다. 하나의 구성 요소가 해결책을 제안하면 다른 구성 요소가 모순, 누락된 증거, 안전하지 않은 가정 또는 대안적 설명을 탐색할 수 있다. 전문화된 비평 에이전트(critic agent)나 검증 에이전트(verifier agent)는 다중 에이전트 시스템(multi-agent system)의 복잡한 의사결정을 평가할 때 추가적인 독립성을 제공할 수 있다.

외부 피드백(external feedback)은 자기 성찰만으로 잘못된 믿음을 강화할 수 있기 때문에 여전히 중요하다. 인간의 수정, 환경에서 발생한 결과, 신뢰할 수 있는 도구, 형식 검증(formal verification), 시뮬레이션, 다른 에이전트는 시스템 내부 해석에 도전하는 증거를 제공할 수 있다. 따라서 효과적인 성찰 지능은 자기 내부에 대한 검토(introspection)와 외부에 근거한 신호(externally grounded signal)를 결합한다. 목적은 내부 추론을 자동으로 신뢰하는 것이 아니라 독립적인 증거를 통해 성찰 결과를 시험하는 것이다.

월드 모델(world model)은 성찰을 위한 또 다른 기반을 제공한다. 에이전트는 행동 이후 실제로 발생한 상태 전이(state transition)를 자신이 예측했던 상태 전이와 비교할 수 있다. 큰 차이는 인지, 인과적 이해(causal understanding), 동역학 예측(dynamics prediction), 계획 가정(planning assumption)의 오류를 의미할 수 있다. 성찰은 이러한 차이를 이용하여 월드 모델을 개선하고, 이후 유사한 환경과 상호작용할 때 더욱 정확한 예측과 더 나은 의사결정을 가능하게 한다.

체화된 AGI(Embodied AGI)에서는 성찰 처리가 물리적 경험과 인지적 개선을 연결할 수 있다. 로봇은 위치 추정(localization)이 왜 악화되었는지, 이동 경로가 왜 비효율적이었는지, 객체 조작(object manipulation)이 왜 실패했는지 또는 인지 시스템이 왜 높은 불확실성을 생성했는지를 검토할 수 있다. 이러한 실패를 센서 조건(sensor condition), 환경 특성, 제어 의사결정(control decision), 이전 경험과 연관시킴으로써 운영상의 실패를 구조화된 학습 기회로 변환할 수 있다.

성찰(reflection)은 메타 학습(meta-learning)과도 밀접하게 상호작용한다. 개별 성찰 에피소드(reflective episode)는 특정 조건에서 어떤 학습 전략이 효과적으로 작동했는지를 보여준다. 여러 에피소드에 걸쳐 메타 학습은 반복되는 패턴을 식별하고 향후 적응에 사용되는 메커니즘을 개선할 수 있다. 성찰은 이전 학습 과정의 품질에 관한 정보를 제공하고, 메타 학습은 그 정보를 새로운 지식과 기술을 획득하기 위한 보다 일반적인 전략으로 변환한다.

자동화 머신러닝(AutoML)과 자동 에이전트(AutoAgents)는 성찰 정보를 자동화된 재설계(automated redesign)의 입력으로 사용할 수 있다. 성찰이 검색, 계획 깊이(planning depth), 메모리 구성, 모델 선택 또는 도구 조정(tool coordination)의 약점을 반복적으로 식별한다면 자동 최적화 메커니즘(automated optimization mechanism)은 대안적인 구성을 제안할 수 있다. 이후 후보 변경 사항을 통제된 환경에서 평가할 수 있다. 따라서 성찰은 진단(diagnosis)을 제공하고 자동화된 설계 메커니즘은 가능한 구조적 대응을 제공한다.

지속 학습(continual learning)은 모든 경험이 장기 지식에 동일한 영향을 줄 필요는 없다는 점에서 성찰의 도움을 받을 수 있다. 성찰 메커니즘은 특정 사건이 새로운 교훈을 포함하는지, 드문 예외인지, 체계적인 실패(systematic failure)를 드러내는지 또는 기존 전략을 확인하는지를 추정할 수 있다. 이를 통해 메모리 통합(memory consolidation)과 학습 우선순위를 결정하고, 중요한 경험은 보존하면서 잡음(noise)이나 잘못된 관찰로 인한 불필요한 업데이트를 방지할 수 있다.

성찰형 에이전트(reflective agent)는 자원 사용(resource usage)도 검토할 수 있다. 일부 과제는 난이도에 비해 과도한 추론 시간, 메모리, 에너지 또는 도구 호출을 소비할 수 있다. 시스템은 계산 노력(computational effort)과 실제 성능을 비교함으로써 언제 깊은 추론이 가치가 있고 언제 단순한 처리만으로 충분한지를 학습할 수 있다. 따라서 성찰은 정확성뿐 아니라 적응형 계산(adaptive computation)과 인지 자원(cognitive resource)의 효율적인 할당에도 기여한다.

그러나 성찰(reflection)에는 중요한 한계가 있다. 시스템은 자신의 행동에 대해 그럴듯한 설명을 생성할 수 있지만, 그 설명이 실제 인과적 원인(causal cause)을 정확하게 나타낸다고 보장할 수는 없다. 내부적으로 일관된 비평도 불완전한 정보나 부정확한 표현에 기반하면 잘못될 수 있다. 따라서 성찰적 설명(reflective statement)은 시스템의 실제 계산 원인을 보장하는 설명이 아니라 증거를 통해 검증해야 하는 가설(hypothesis)로 취급해야 한다.

반복적인 성찰은 계산 비용을 증가시키거나 오히려 역효과를 낼 수도 있다. 모든 의사결정을 계속해서 재검토하는 에이전트는 의미 있는 성능 향상 없이 지연 시간만 증가시킬 수 있다. 따라서 실용적인 시스템에는 추가적인 성찰이 언제 가치가 있는지를 결정하는 종료 기준(stopping criteria)이 필요하다. 신뢰도, 과제 중요도(task importance), 불확실성, 위험(risk), 평가자 간 의견 차이, 예상되는 개선 효과 등을 이용하여 적절한 성찰 깊이(reflection depth)를 결정할 수 있다.

안전 핵심 상황(safety-critical situation)에서는 특히 신중한 성찰 설계가 필요하다. 성찰 과정에서 과제 성능이 향상된다는 이유만으로 에이전트가 보호된 목표(protected objective)를 재해석하거나 제약 조건을 제거하도록 허용해서는 안 된다. 안전 정책(safety policy), 권한 경계(permission boundary), 변경 불가능한 규칙(immutable rule), 검증 게이트(validation gate), 모니터링(monitoring), 인간 감독(human oversight)을 통해 적응 가능한 구성 요소와 성찰이 독립적으로 재정의할 수 없는 구성 요소를 분리할 수 있다.

따라서 성찰(reflection)은 통제된 개선 아키텍처(controlled improvement architecture) 안에서 작동해야 한다. 관찰과 결과를 기록하고, 중요한 차이를 탐지하며, 후보 설명(candidate explanation)을 생성하고, 증거를 수집하고, 교훈을 제안한 뒤 실제 운영 행동에 통합하기 전에 변경 사항을 시험한다. 버전 관리(versioning)와 롤백 메커니즘(rollback mechanism)은 성찰에 따른 업데이트가 예상치 못하게 신뢰성을 낮추거나 바람직하지 않은 행동을 도입했을 경우 이전에 검증된 상태를 보존할 수 있도록 한다.

성찰의 품질 자체도 평가할 수 있다. 시스템은 성찰을 통해 도출된 결론이 미래의 실패를 실제로 예측하는지, 제안된 수정 사항이 성능을 향상시키는지, 교훈을 반영한 이후 유사한 실수가 감소하는지를 측정할 수 있다. 이를 통해 성찰은 제한 없는 내부 논평이 아니라 경험적으로 검증되는 과정(empirical process)이 된다. 유용한 성찰 메커니즘은 반복되는 과제와 변화하는 환경에서 측정 가능한 개선을 보여줄 수 있어야 한다.

시간이 지나면서 축적된 성찰은 시스템의 능력(capability), 한계(limitation), 성공적인 전략, 반복적인 실패 유형(failure mode), 불확실성 패턴, 자원 요구사항을 설명하는 구조화된 자기 모델(self-model)을 형성할 수 있다. 이러한 모델이 인간과 같은 의식(consciousness)이나 주관적 자각(subjective awareness)을 의미하는 것은 아니다. 이는 시스템이 자신의 성능을 예측하고 현재 능력과 상황에 적합한 전략을 선택하도록 돕는 운영적 표현(operational representation)으로 기능한다.

자기 진화 지능(self-evolving intelligence)에서 자기 성찰(Self-Reflection)은 경험과 의도적인 개선(deliberate improvement)을 연결하는 진단적 다리(diagnostic bridge)를 제공한다. 경험은 무엇이 발생했는지를 보여주고, 성찰은 그것이 왜 발생했는지를 분석하며, 메모리는 그 결과로 얻은 교훈을 보존하고, 메타 학습(meta-learning)은 이를 일반화하며, 자동화된 최적화(automated optimization)는 이를 수정된 전략이나 아키텍처로 변환할 수 있다. 이러한 메커니즘이 결합되면 지능형 시스템은 단순히 데이터를 축적하는 수준을 넘어 자신의 작동 과정 자체로부터 체계적으로 학습하며 지속적으로 개선될 수 있다.

## 06.04. Recursive Self Improvement

![](images/image6.png){width="7.268055555555556in" height="7.268055555555556in"}

재귀적 자기 개선(Recursive Self-Improvement)은 지능형 시스템이 과제 수행 능력뿐만 아니라 이후의 개선을 만들어내는 메커니즘 자체까지 개선하는 과정을 의미한다. 일반적인 적응형 시스템(adaptive system)은 더 나은 정책(policy)을 학습하거나 추가적인 지식을 획득할 수 있지만, 재귀적으로 개선되는 시스템은 자신의 학습(learning), 추론(reasoning), 평가(evaluation), 최적화(optimization), 재설계(redesign) 과정 자체를 수정할 수 있다. 따라서 성공적인 각각의 개선은 이후의 개선을 발견하는 능력까지 향상시킬 수 있다.

핵심적인 특징은 여러 적응 수준(adaptation level)에 걸쳐 재귀(recursion)가 발생한다는 것이다. 한 수준에서는 시스템이 특정 과제를 수행하는 방법을 개선한다. 더 높은 수준에서는 과제를 학습하는 방법, 자신의 성능을 평가하는 방법, 대안을 탐색하는 방법 또는 아키텍처(architecture)를 수정하는 방법을 개선한다. 이러한 상위 수준의 개선이 미래의 최적화를 더욱 효과적으로 만든다면 그 능력이 다시 개선 과정으로 피드백되어, 개선을 수행하는 메커니즘 자체가 개선 대상이 되는 반복적인 순환이 형성된다.

이러한 특성은 재귀적 자기 개선(Recursive Self-Improvement)을 일반적인 자기 개선(self-improvement)과 구별한다. 새로운 정보를 받아 지식을 업데이트하는 에이전트(agent)는 개선되고 있지만 반드시 재귀적으로 개선되고 있는 것은 아니다. 재귀는 변화가 미래의 변화를 생성하는 메커니즘 자체에 영향을 미칠 때 시작된다. 예를 들어 최적화 알고리즘을 개선하거나, 더 나은 평가 절차를 개발하거나, 메모리 구성을 재설계하거나, 실험 효율성을 높이거나, 내부 구성 요소를 수정하는 더욱 효과적인 전략을 학습하는 것이 이에 해당한다.

유용한 개념적 모델(conceptual model)은 운영 시스템(operational system)과 개선 시스템(improvement system)을 구분한다. 운영 시스템은 인지(perception), 추론, 계획(planning), 학습, 행동(action)을 수행하고, 개선 시스템은 이러한 과정을 모니터링하고 한계를 식별하며 수정안을 제안하고 후보를 평가하여 검증된 변경 사항을 적용할 것인지를 결정한다. 개선 시스템 자체도 고정된 상태로 남아 있지 않고 유사한 메커니즘을 통해 평가되고 수정될 수 있을 때 재귀적 개선이 발생한다.

따라서 평가(evaluation)는 근본적으로 중요하다. 시스템은 단순히 수정 사항을 생성하는 것만으로는 자신을 신뢰성 있게 개선할 수 없으며, 그러한 수정이 실제적인 이점을 만들어내는지를 판단해야 한다. 평가는 정확성(accuracy), 일반화(generalization), 학습 속도, 샘플 효율성(sample efficiency), 추론 품질, 계산 비용(computational cost), 강건성(robustness), 안전성(safety), 장기적 성능 등을 측정할 수 있다. 특히 재귀적 개선에서는 평가자의 오류가 이후 여러 세대의 수정에 영향을 미칠 수 있으므로 매우 강력한 평가 체계가 필요하다.

자기 성찰(self-reflection)은 이러한 과정에 필요한 진단 정보(diagnostic information)를 제공할 수 있다. 에이전트는 이전의 추론, 의사결정, 실패, 성공적인 전략을 검토하여 자신의 작동 과정에서 반복적으로 발생하는 약점을 식별할 수 있다. 성찰을 통해 비효율적인 검색(retrieval), 얕은 계획, 부족한 불확실성 추정(uncertainty estimation), 비효율적인 학습 전략이 반복적으로 발견된다면 이러한 문제는 재설계의 대상이 될 수 있다. 따라서 성찰은 자동화된 메커니즘이 어떻게 개선할 것인지를 탐색하기 전에 무엇을 개선해야 하는지를 결정하는 데 도움을 준다.

메타 학습(meta-learning)은 적응 과정 자체를 명시적으로 개선한다는 점에서 또 하나의 중요한 계층을 제공한다. 메타 학습자는 새로운 과제를 더욱 효율적으로 학습할 수 있도록 표현(representation), 초기 상태(initialization state), 메모리 전략(memory strategy), 업데이트 절차(update procedure), 학습 정책(learning policy)을 발견할 수 있다. 메타 학습 자체의 개선이 미래의 더 나은 학습 절차를 개발하는 시스템의 능력까지 향상시킨다면 메타 학습은 재귀적 자기 개선 아키텍처의 한 구성 요소가 될 수 있다.

자동화 머신러닝(AutoML)과 자동화 에이전트 설계(automated agent design)는 가능한 수정 사항을 탐색하기 위한 실용적인 메커니즘을 제공한다. 자동화 시스템은 모델 아키텍처(model architecture), 하이퍼파라미터(hyperparameter), 훈련 절차, 프롬프트(prompt), 메모리 구성, 추론 워크플로(reasoning workflow), 도구 조합(tool combination), 다중 에이전트 구조(multi-agent structure)를 탐색할 수 있다. 개선된 탐색 또는 평가 절차가 이후 더욱 우수한 구성을 발견하게 한다면 자동화 설계는 일회성 엔지니어링 과정이 아니라 재귀적 최적화 순환(recursive optimization loop)의 일부가 된다.

메모리(memory)는 재귀적 개선이 이전 실험에 관한 누적 지식(cumulative knowledge)에 의존하기 때문에 필수적이다. 시스템은 어떤 수정이 시도되었는지, 어떤 조건에서 시험되었는지, 어떤 결과가 발생했는지, 그리고 후보가 왜 채택되거나 거부되었는지를 보존해야 한다. 이러한 과거 정보는 동일한 실패의 반복을 방지하고, 재사용 가능한 패턴을 식별하며, 미래 탐색에 사전 정보(prior)를 제공할 수 있다. 이를 통해 개선 과정은 매번 빈 탐색 공간에서 시작하는 것이 아니라 점차 축적된 정보를 활용하게 된다.

월드 모델(world model)은 재귀적 실험(recursive experimentation)의 비용을 줄일 수 있다. 충분히 정확한 예측 모델(predictive model)은 후보 변경 사항이 미래 행동에 어떤 영향을 미칠지를 실제 환경에 배포하기 전에 추정할 수 있다. 대안적인 전략, 아키텍처 또는 정책을 먼저 시뮬레이션(simulation)이나 내부 예측을 통해 검토할 수 있다. 유망한 후보에는 더 많은 비용이 드는 검증을 수행하고, 명백히 좋지 않은 후보는 개선 파이프라인의 초기 단계에서 제거할 수 있다.

재귀적 개선이 반드시 모든 구성 요소의 수정을 의미하는 것은 아니다. 실용적인 아키텍처에서는 시스템을 수정 가능 영역(mutable region), 조건부 수정 가능 영역(conditionally mutable region), 보호 영역(protected region)으로 구분할 수 있다. 학습 전략이나 검색 매개변수는 자동으로 수정할 수 있지만 안전 제약 조건(safety constraint), 승인 메커니즘(authorization mechanism), 근본적인 목표(fundamental objective)는 보호할 수 있다. 이러한 분리는 시스템 전체에 무제한적인 수정 권한을 부여하지 않으면서 상당한 수준의 적응을 가능하게 한다.

모듈성(modularity)은 이러한 과정을 더욱 관리하기 쉽게 만든다. 인지, 메모리, 추론, 계획, 평가, 학습, 도구 사용(tool use)이 구별 가능한 모듈(module)로 표현되면 개선 사항을 국소적으로 적용하고 독립적으로 시험할 수 있다. 새로운 계획 메커니즘을 평가하면서 인지 또는 안전 제어(safety control)를 동시에 수정하지 않을 수 있다. 모듈형 설계(modular design)는 서로 상호작용하는 변수의 수를 줄이고 개별 수정의 영향을 측정하고 되돌리기 쉽게 만든다.

재귀적 자기 개선(Recursive Self-Improvement)은 서로 다른 속도로 작동할 수 있다. 일부 변화는 매개변수 업데이트(parameter update)나 메모리 통합(memory consolidation)을 통해 지속적으로 발생할 수 있지만, 아키텍처 수정은 더 긴 실험과 검증 주기를 필요로 할 수 있다. 시스템 전체에 더 큰 영향을 주는 변화에는 더욱 엄격한 검토를 적용할 수 있다. 따라서 다중 시간 척도 아키텍처(multi-timescale architecture)는 위험이 낮은 적응을 빠르게 수행하면서 더 큰 시스템적 영향을 갖는 수정에 대해서는 신중한 통제를 유지할 수 있도록 한다.

중요한 가능성 중 하나는 탐색 효율성(search efficiency)의 개선이다. 초기 버전의 시스템은 후보 해결책을 광범위하고 비효율적으로 탐색할 수 있다. 경험이 축적되면 설계 공간(design space)의 어떤 영역이 유망한지, 어떤 평가 방법이 유용한 정보를 제공하는지, 어떤 실험의 가치가 낮은지를 발견할 수 있다. 이후 시스템은 후보를 생성하는 과정을 개선하여 다음 개선 사항을 발견하는 데 필요한 자원을 줄이고 미래 실험의 효율성을 높일 수 있다.

또 다른 가능성은 평가 자체의 개선이다. 시스템은 초기에는 제한적인 벤치마크(benchmark)에 의존할 수 있지만 이후 이러한 벤치마크가 실제 환경의 성능을 제대로 예측하지 못한다는 사실을 발견할 수 있다. 개선된 평가에는 숨겨진 시험(hidden test), 적대적 사례(adversarial case), 장기 지평 시나리오(long-horizon scenario), 불확실성 측정, 안전성 검사, 다양한 환경 등이 포함될 수 있다. 미래의 수정 사항은 평가 결과에 따라 선택되기 때문에 평가자의 개선은 재귀적 발전의 방향에 특히 큰 영향을 줄 수 있다.

그러나 재귀적 개선이 지속적으로 가속되는 능력 향상을 보장하는 것은 아니다. 명백한 약점이 제거될수록 추가적인 개선은 점차 어려워질 수 있다. 하드웨어 한계(hardware limitation), 데이터 가용성(data availability), 계산 비용, 제거할 수 없는 불확실성(irreducible uncertainty), 아키텍처 제약, 수익 체감(diminishing returns)은 발전을 제한할 수 있다. 또한 어떤 수정은 하나의 능력을 개선하면서 다른 능력을 저하시킬 수 있다. 따라서 재귀적 자기 개선은 무제한적이거나 필연적인 가속을 의미하는 것이 아니라 하나의 피드백 구조(feedback structure)로 이해해야 한다.

부정적 피드백(negative feedback)은 긍정적 피드백(positive feedback)만큼 중요하다. 신뢰성을 낮추거나 자원 소비를 증가시키거나 이전에 학습된 능력을 손상시키거나 안전하지 않은 행동을 발생시키는 수정은 거부되거나 되돌려져야 한다. 회귀 테스트(regression testing), 비교 평가(comparative evaluation), 체크포인트(checkpoint), 버전 관리(version control), 롤백 메커니즘(rollback mechanism)을 통해 검증된 능력을 보존할 수 있다. 안정적인 재귀적 개선은 새롭게 생성된 모든 구성을 자동으로 채택하는 것이 아니라 선택적으로 유지하는 과정에 의존한다.

분포 변화(distribution shift)는 또 다른 문제를 발생시킨다. 특정 평가 환경에서 우수하게 보이는 수정 사항이 익숙하지 않은 조건에서는 실패할 수 있다. 따라서 재귀적 시스템은 다양한 과제, 환경, 시간 지평(time horizon), 운영 맥락(operational context)에 걸친 폭넓은 검증이 필요하다. 개선 사항은 현재의 시험 분포를 이용하는 데 그치지 않고 전이(transfer)와 강건성을 보여야 한다. 그렇지 않으면 반복적인 최적화 과정에서 일반적인 개선처럼 보이면서 실제로는 시스템이 점점 더 특수화될 수 있다.

목표 보존(goal preservation)은 최적화 능력의 향상이 잘못 정의된 목표의 오류까지 증폭시킬 수 있기 때문에 특히 중요하다. 불완전하거나 왜곡된 목표를 더욱 효과적으로 추구하는 시스템은 의도된 행동에서 오히려 더 멀어질 수 있다. 따라서 재귀적 자기 개선은 제한된 성능 향상과 독립적으로 어떤 변화가 허용 가능한지를 정의하는 보호된 상위 수준 목표(protected higher-level objective), 제약 조건, 거버넌스 메커니즘(governance mechanism) 안에서 이루어져야 한다.

능력 개선(capability improvement)과 안전성 개선(safety improvement)은 이상적으로 함께 발전해야 한다. 계획, 학습, 도구 사용 능력이 향상되는 시스템은 불확실성 추정, 이상 탐지(anomaly detection), 검증(verification), 모니터링(monitoring), 위험 평가(risk assessment) 능력도 함께 향상시켜야 한다. 운영 능력이 증가하는 동안 안전 메커니즘이 고정된 상태로 남아서는 안 된다. 재귀적 아키텍처는 자율적으로 제거할 수 없는 근본적인 제한을 보존하면서 강건성과 안전 메커니즘 자체도 개선 대상으로 다룰 수 있다.

샌드박스화(sandboxing)는 제안된 개선과 실제 운영 배포 사이에 중요한 경계를 제공한다. 후보 수정 사항은 먼저 제한된 권한, 통제된 자원, 광범위한 모니터링을 갖춘 격리된 환경에서 작동할 수 있다. 실제 적용 전에 검증된 기준 시스템(validated baseline)과 행동을 비교할 수 있다. 시스템에 더 큰 영향을 주는 수정에는 더 강력한 증거나 인간 승인(human authorization)을 요구함으로써 실험에서 신뢰할 수 있는 배포까지 단계적인 경로를 구성할 수 있다.

따라서 탐색 과정의 상당 부분이 자동화되더라도 인간 감독(human oversight)은 재귀적 개선의 일부로 유지될 수 있다. 인간은 보호된 목표를 정의하고, 주요 아키텍처 변경을 승인하고, 예상하지 못한 행동을 검토하며, 배포 기준(deployment criteria)을 설정하고, 허용 가능한 위험 수준을 결정할 수 있다. 자동화의 목적이 반드시 인간 거버넌스를 제거하는 것은 아니며, 명시적으로 정의된 경계 안에서 기계가 점점 더 복잡한 개선 사항을 탐색하고 평가하도록 하는 데 있을 수 있다.

체화된 AGI(Embodied AGI)에서 재귀적 개선은 인지 모델(perception model), 센서 융합(sensor fusion), 월드 모델링(world modeling), 내비게이션(navigation), 조작(manipulation), 계획, 계산 스케줄링(computational scheduling)을 포함할 수 있다. 운영 경험이 약점을 드러내고, 성찰 메커니즘이 이를 진단하며, 자동화된 설계가 대안을 생성하고, 시뮬레이션이 이를 평가하며, 검증된 개선 사항을 다시 로봇에 배포할 수 있다. 이후 물리적 상호작용이 다음 개선 주기를 위한 새로운 증거를 제공한다.

다중 에이전트 시스템(multi-agent system)은 전문화(specialization)와 독립적인 평가를 통해 재귀적 개선을 확장할 수 있다. 서로 다른 에이전트가 후보 설계를 생성하고, 시험하고, 가정을 비평하고, 결과를 검증하거나 안전성을 모니터링할 수 있다. 이러한 에이전트의 조직 자체도 최적화 대상이 될 수 있다. 그러나 동일한 가정을 사용하는 여러 에이전트는 의미 있는 검증을 제공하기보다 동일한 오류를 반복할 수 있으므로 다양성과 독립적인 검사가 중요하다.

따라서 실용적인 재귀적 개선 수명주기(recursive improvement lifecycle)는 운영(operation), 관찰(observation), 성찰(reflection), 진단(diagnosis), 후보 생성(candidate generation), 실험(experimentation), 평가, 검증(validation), 배포(deployment), 모니터링을 연결한다. 배포 결과는 이후 개선 주기를 위한 증거로 다시 전달된다. 더 높은 수준에서는 시스템이 자신의 진단, 탐색, 실험, 평가 메커니즘 자체가 효과적인지도 평가하여 개선 파이프라인(improvement pipeline) 자체를 점진적으로 정교화할 수 있다.

재귀적 자기 개선(Recursive Self-Improvement)의 장기적인 중요성은 지능의 발전 과정이 대부분 설계자에 의해 고정된 시스템에서 자신의 발전 과정 자체를 개선하는 데 참여할 수 있는 시스템으로 전환한다는 데 있다. 이를 위해 무제한적인 자기 수정(unrestricted self-modification)이 필요한 것은 아니다. 통제된 아키텍처는 적응 가능한 구성 요소, 보호된 불변 요소(protected invariant), 엄격한 평가, 과거 메모리, 시뮬레이션, 롤백, 거버넌스를 결합하여 운영 안정성을 유지하면서 누적적인 개선을 지원할 수 있다.

자기 진화 지능(self-evolving intelligence)에서 재귀적 자기 개선(Recursive Self-Improvement)은 자기 성찰(self-reflection), 메타 학습(meta-learning), 자동화 머신러닝(AutoML), 자동화 에이전트(automated agents), 지속 학습(continual learning), 메모리(memory), 월드 모델(world model), 평가(evaluation)를 상위 수준에서 통합한다. 이러한 메커니즘은 지능이 과제를 수행하고, 결과로부터 학습하고, 전략을 개선하며, 궁극적으로 그 개선을 담당하는 선택된 메커니즘 자체까지 개선하는 폐쇄 순환(closed loop)을 형성한다. 핵심 과제는 이러한 재귀 과정을 누적 가능하고(cumulative), 검증 가능하며(verifiable), 제한되고(bounded), 강건하며(robust), 의도된 목표에 정렬된(aligned) 형태로 구현하는 것이다.

## 06.05. Continual Learning

![](images/image7.png){width="7.268055555555556in" height="7.268055555555556in"}

지속 학습(Continual Learning)은 지능형 시스템이 고정된 훈련 단계(training phase)에서만 학습하는 것이 아니라 장기간에 걸쳐 이어지는 경험을 통해 지식을 획득하고, 통합하며, 지속적으로 정교화하는 능력을 의미한다. AGI에서 이러한 능력은 필수적이다. 실제 환경에서는 새로운 과제, 개념, 상황, 제약 조건이 계속 등장하기 때문이다. 따라서 지능은 배포(deployment) 이후에도 적응할 수 있어야 하며, 동시에 계속 유용한 기존 지식을 보존해야 한다.

전통적인 머신러닝(machine learning)은 일반적으로 훈련 데이터가 사전에 수집되고 비교적 안정적인 분포(distribution)에서 샘플링된다고 가정한다. 지속 학습(Continual Learning)은 이러한 가정을 제거한다. 데이터는 순차적으로 도착하고 환경은 변화할 수 있으며 이전에 경험했던 예제에 더 이상 접근할 수 없을 수도 있다. 시스템은 변화하는 조건에서 학습하면서 새로운 정보가 기존 지식을 어떻게 수정하고, 확장하고, 또는 기존 지식과 공존해야 하는지를 결정해야 한다.

핵심적인 어려움은 안정성-가소성 딜레마(stability-plasticity dilemma)이다. 가소성(plasticity)은 시스템이 새로운 정보를 학습하고 빠르게 적응하도록 하며, 안정성(stability)은 유용한 기존 지식이 파괴적으로 변경되지 않도록 보호한다. 지나친 가소성은 이전 능력을 사라지게 하고, 지나친 안정성은 의미 있는 적응을 방해한다. 따라서 지속 학습은 변화할 수 있는 능력과 이미 학습한 것을 보존하는 능력 사이의 균형을 유지하는 메커니즘을 필요로 한다.

파국적 망각(catastrophic forgetting)은 이러한 문제의 가장 중요한 형태 중 하나이다. 신경망 모델(neural model)이 새로운 과제나 데이터 분포를 순차적으로 학습할 때 최근 경험을 위한 매개변수 업데이트(parameter update)가 이전 과제에 필요한 표현(representation)을 덮어쓸 수 있다. 현재 데이터의 성능은 향상되지만 이전에 획득했던 능력이 조용히 저하될 수 있다. 이러한 파괴적 간섭(destructive interference)을 방지하는 것은 지속 학습의 근본적인 목표이다.

재생(Replay)은 이전 지식을 보존하기 위한 하나의 접근법을 제공한다. 학습자는 대표적인 경험을 유지하고 이를 새로운 훈련 데이터와 주기적으로 결합한다. 이전 예제를 다시 학습하면 모델이 새로운 경험에 적응하는 동안 과거 과제를 기억하도록 할 수 있다. 재생 버퍼(replay buffer)는 메모리 용량과 학습 시스템의 요구사항에 따라 실제 관찰, 압축된 표현, 궤적(trajectory) 또는 전략적으로 선택된 경험을 저장할 수 있다.

생성적 재생(generative replay)은 원래 경험을 직접 저장해야 하는 필요성을 줄인다. 이전의 모든 예제를 보존하는 대신 생성 모델(generative model)이 과거 데이터 분포를 근사하는 합성 샘플(synthetic sample)을 생성하도록 학습할 수 있다. 이렇게 생성된 경험을 새로운 관찰과 함께 학습에 사용한다. 이 접근법은 저장 공간 요구사항을 줄이고 개인정보 보호 제약을 지원할 수 있지만, 생성기가 이전 지식의 중요한 특성을 얼마나 정확하게 보존하는지에 따라 효과가 달라진다.

정규화 기반 방법(regularization-based method)은 이전 과제에 중요하다고 판단되는 매개변수의 변화를 제한함으로써 기존 능력을 보호한다. 시스템은 확립된 지식에 크게 기여하는 매개변수를 추정하고 이를 손상시키는 변경에 페널티(penalty)를 부여한다. 상대적으로 중요하지 않은 매개변수는 새로운 학습을 위해 더 유연하게 유지된다. 이를 통해 지속 학습은 새로운 경험에 대한 적응과 기존 능력의 보존 사이에서 균형을 찾는 최적화 문제(optimization problem)가 된다.

매개변수 격리(parameter isolation)는 보다 구조적인 접근법을 사용한다. 서로 다른 과제, 도메인(domain), 능력이 부분적으로 분리된 매개변수, 어댑터(adapter), 모듈(module), 서브네트워크(subnetwork)를 사용할 수 있다. 동일한 표현을 반복적으로 수정하는 대신 새로운 지식을 추가되거나 선택적으로 활성화되는 구성 요소에 할당한다. 모듈형 아키텍처(modular architecture)는 간섭을 줄일 수 있지만 통제되지 않은 확장은 메모리, 계산량, 라우팅(routing), 장기적인 아키텍처 복잡성이라는 문제를 발생시킨다.

동적 아키텍처(dynamic architecture)는 경험이 축적됨에 따라 시스템이 자신의 구조를 수정하도록 함으로써 이러한 원리를 확장한다. 기존 구성 요소가 새로운 능력을 효과적으로 표현하지 못하면 새로운 모듈을 생성할 수 있으며, 이후 중복되는 모듈은 병합, 압축 또는 제거할 수 있다. 따라서 지속 학습은 단순히 매개변수를 계속 적응시키는 과정이 아니라 증가하는 지식을 표현하는 아키텍처 자체를 통제된 방식으로 진화시키는 과정이 된다.

지식 통합(knowledge consolidation)은 어떤 경험을 장기적으로 보존해야 하는지를 결정한다. 많은 사건은 중복되거나 잡음(noise)을 포함하거나 예외적이므로 모든 관찰이 영구적인 업데이트를 발생시켜서는 안 된다. 지속 학습 시스템은 무엇을 통합할지 결정하기 전에 새로움(novelty), 중요성, 불확실성(uncertainty), 반복성, 미래의 유용성을 추정할 수 있다. 이는 일시적인 경험이 점차 안정적인 의미적 또는 절차적 지식으로 전환되는 선택적인 과정과 유사하다.

서로 다른 메모리 시스템(memory system)은 서로 다른 시간 척도(timescale)의 학습을 지원할 수 있다. 작업 기억(working memory)은 현재 과제에 필요한 정보를 유지하고, 일화 기억(episodic memory)은 특정 경험을 보존하며, 의미 기억(semantic memory)은 일반화된 지식을 표현하고, 절차 기억(procedural memory)은 학습된 전략이나 기술을 유지한다. 지속 지능(continual intelligence)은 이러한 메모리 시스템을 조정하여 충분한 증거가 확보되면 정보가 일시적인 저장소에서 더욱 지속적인 표현으로 점진적으로 이동하도록 할 수 있다.

과제 경계(task boundary)가 항상 명시적으로 제공되는 것은 아니다. 실제 환경에서 AGI 시스템은 하나의 과제가 종료되고 다른 과제가 시작되었다는 신호를 받지 못할 수 있다. 시스템은 관찰, 예측 오류(prediction error), 맥락(context), 보상 구조(reward structure), 불확실성으로부터 변화를 감지해야 한다. 따라서 과제 비의존 지속 학습(task-free continual learning)은 근본적인 상황이 언제 변화했는지를 추론하고 기존 지식을 적응시킬 것인지 새로운 표현을 형성할 것인지 결정해야 한다.

분포 변화(distribution shift)는 이러한 능력을 특히 중요하게 만든다. 센서 특성, 사용자 행동, 물리적 환경, 언어 패턴, 운영 목표 또는 환경 동역학(environmental dynamics)은 시간이 지나면서 변화할 수 있다. 지속 학습자는 일반적인 변동과 의미 있는 변화를 구별해야 한다. 이러한 변화를 감지하면 성능이 크게 저하되기 전에 모델과 정책(policy)을 조정할 수 있으며, 중요하지 않은 변동 때문에 불필요하게 재훈련(retraining)하는 것도 방지할 수 있다.

지속 학습(Continual Learning)은 경험이 지식뿐 아니라 미래의 지식을 획득하는 과정 자체도 개선할 수 있다는 점에서 메타 학습(meta-learning)과 밀접하게 연결된다. 시스템은 어떤 매개변수를 안정적으로 유지해야 하는지, 어떤 모듈이 효과적으로 전이되는지, 어떤 메모리를 재생해야 하는지, 서로 다른 조건에서 어떤 학습률(learning rate)이 적절한지를 발견할 수 있다. 따라서 메타 학습은 지속적인 적응을 점차 더 빠르고 선택적이며 덜 파괴적인 과정으로 만들 수 있다.

자기 성찰(self-reflection)은 경험으로부터 무엇을 학습해야 하는지를 결정하는 데 도움을 줄 수 있다. 에이전트(agent)는 실패, 예상하지 못한 결과, 불확실성, 비효율적인 추론, 성공적인 전략을 분석하여 가치 있는 교훈을 포함하는 사건을 식별할 수 있다. 성찰(reflection)은 체계적인 약점과 우연한 사고를 구별하고 학습 우선순위를 결정할 수 있다. 따라서 지속 학습은 새로운 관찰이 들어올 때마다 단순히 매개변수를 업데이트하는 것보다 더욱 의도적인 과정이 된다.

월드 모델(world model)은 지속적인 적응을 위한 또 하나의 강력한 메커니즘을 제공한다. 예측된 상태 전이(state transition)와 실제 관찰된 상태 전이 사이의 차이는 환경에 대한 에이전트의 이해가 어디에서 부정확해졌는지를 보여준다. 이러한 예측 오류는 새로운 동역학, 익숙하지 않은 객체, 변화된 관계 또는 이전에 알려지지 않았던 인과 구조(causal structure)를 식별할 수 있다. 월드 모델을 업데이트하면 이후의 추론과 계획에 새롭게 발견된 환경 특성을 반영할 수 있다.

체화된 AGI(Embodied AGI)에서는 물리적 환경을 고정된 훈련 데이터셋으로 완전히 표현할 수 없기 때문에 지속 학습이 불가피하다. 로봇은 새로운 지형, 객체, 조명 조건, 센서 성능 저하(sensor degradation), 페이로드(payload), 상호작용 패턴, 기계적 변화를 경험한다. 새로운 적응 과정이 이전의 신뢰할 수 있는 행동을 파괴하지 않는다면 운영 경험을 통해 인지(perception), 내비게이션(navigation), 조작(manipulation), 제어(control), 예측 능력을 점진적으로 향상시킬 수 있다.

로봇은 자신의 신체(body) 변화에도 적응해야 할 수 있다. 타이어 마모(tire wear), 액추에이터 노화(actuator aging), 페이로드 변화, 보정 드리프트(calibration drift), 센서 교체, 기계적 손상은 명령과 실제 물리적 결과 사이의 관계를 변화시킬 수 있다. 지속 학습은 로봇 자신의 내부 모델(internal model)을 업데이트하여 물리적 플랫폼이 영구적으로 동일하다고 가정하는 대신 계획 및 제어 시스템이 변화하는 동역학을 보상하도록 할 수 있다.

다중 에이전트 시스템(multi-agent system)은 여러 에이전트에 걸쳐 지식을 축적할 수 있다는 또 다른 차원을 제공한다. 하나의 로봇이 다른 로봇들이 경험하지 못한 환경이나 실패를 경험할 수 있다. 공유 메모리(shared memory), 모델 또는 학습된 정책을 통해 유용한 정보를 전체 플릿(fleet)에 전달할 수 있다. 그러나 하드웨어, 환경, 구성 또는 지역적 맥락의 차이로 인해 다른 에이전트의 경험이 적절하지 않을 수도 있으므로 전이된 지식을 평가해야 한다.

지속 학습(Continual Learning)은 부정적 전이(negative transfer)를 탐지하는 메커니즘도 필요로 한다. 이전 지식은 현재 상황에 적용될 수 있을 때만 유용하다. 에이전트는 검색된 경험이나 기존 표현이 적응에 도움을 주는지 또는 방해하는지를 추정해야 한다. 맥락적 라우팅(contextual routing), 불확실성 추정, 모듈형 모델(modular model), 선택적 검색(selective retrieval), 과제 추론(task inference)은 기존 지식을 언제 재사용하고, 수정하고, 격리하거나 무시해야 하는지를 결정하는 데 도움을 줄 수 있다.

평가(evaluation)는 현재 과제의 성능만 측정해서는 안 된다. 지속 학습자는 이전 능력의 유지(retention), 새로운 능력의 획득, 과제 사이의 전이(transfer), 적응 속도, 메모리 사용량, 계산 비용, 강건성(robustness), 장기적인 성능을 평가해야 한다. 시스템이 특정 순간에는 성공적으로 보이면서도 이전 단계에서 축적한 중요한 능력을 점차 잃어버릴 수 있기 때문에 시간에 따른 평가가 필수적이다.

후방 전이(backward transfer)는 새로운 학습이 이전에 습득한 과제에 어떤 영향을 미치는지를 설명한다. 긍정적 후방 전이(positive backward transfer)는 이후의 경험이 이전 능력까지 향상시키는 경우이며, 부정적 후방 전이(negative backward transfer)는 망각이나 간섭을 의미한다. 전방 전이(forward transfer)는 이전 학습이 미래 과제의 습득에 미치는 영향을 설명한다. 강력한 지속 지능은 과거 능력을 보존하면서 축적된 경험을 이용하여 익숙하지 않은 상황에서의 학습을 점차 가속할 수 있어야 한다.

안전성(safety)은 지속적인 적응에 추가적인 제약 조건을 부여한다. 운영 시스템은 새로운 모든 관찰을 중요한 행동에 자동으로 반영해서는 안 된다. 손상된 데이터(corrupted data), 적대적 입력(adversarial input), 비정상적인 사건 또는 일시적인 환경 이상(environmental anomaly)이 위험한 업데이트를 발생시킬 수 있기 때문이다. 검증 게이트(validation gate), 신뢰할 수 있는 데이터 소스, 제한된 업데이트 권한(bounded update permission), 샌드박스 시험(sandbox testing), 모니터링, 체크포인트(checkpoint), 롤백 메커니즘(rollback mechanism)을 통해 검증되지 않은 학습이 안전 핵심 기능(safety-critical function)에 즉시 영향을 주는 것을 방지할 수 있다.

따라서 서로 다른 구성 요소는 서로 다른 학습 권한(learning permission)과 시간 척도로 작동할 수 있다. 위험이 낮은 메모리 업데이트는 빈번하게 수행할 수 있지만 인지 모델, 계획 정책 또는 제어 시스템의 수정에는 더욱 강력한 증거가 필요할 수 있다. 보호된 목표(protected objective)나 안전 제약 조건에 영향을 주는 변화는 외부 승인(external authorization)을 요구할 수 있다. 이러한 계층적 접근법(layered approach)은 AGI 아키텍처의 모든 부분을 동일하게 수정 가능한 것으로 취급하지 않으면서 지속적인 적응을 가능하게 한다.

지속 학습(Continual Learning)은 재귀적 자기 개선(recursive self-improvement)을 위한 시간적 기반(temporal foundation)을 제공한다. 재귀적 개선에는 여러 개선 주기에 걸쳐 축적된 증거가 필요하며, 지속 학습은 이러한 주기에서 생성된 지식을 보존한다. 성찰은 교훈을 식별하고, 메타 학습은 적응 전략을 일반화하며, 자동화된 최적화(automated optimization)는 변경 사항을 제안하고, 지속 학습은 이전 능력을 불필요하게 파괴하지 않으면서 검증된 개선 사항을 통합한다.

장기적인 목표는 단순히 영원히 훈련을 계속하는 모델이 아니라 축적된 능력에 대한 일관된 발전의 역사(coherent history of accumulated competence)를 형성할 수 있는 지능이다. 새로운 경험은 기존 지식을 정교화하고, 필요한 경우 새로운 표현을 생성하며, 가치 있는 기술을 보존하고, 더 이상 유효하지 않은 가정을 식별하며, 세계의 변화에 따라 메모리를 재구성해야 한다. 학습은 배포 이전에 끝나는 일시적인 단계가 아니라 지속적으로 이루어지는 발전 과정(developmental process)이 된다.

자기 진화 지능(self-evolving intelligence)에서 지속 학습(Continual Learning)은 시간이 흐르면서 능력이 축적될 수 있도록 한다. 메모리(memory), 자기 성찰(self-reflection), 메타 학습(meta-learning), 월드 모델(world model), 자동화 설계(automated design), 평가(evaluation), 통제된 적응(controlled adaptation)과 결합하면 AGI 시스템은 매번 처음부터 다시 시작하지 않고 새로운 경험에 지속적으로 대응할 수 있다. 핵심 과제는 안정성을 희생하지 않으면서 지속적인 가소성을 확보하여, 오늘의 학습이 어제 발전시킨 지능을 지우는 것이 아니라 확장하도록 만드는 것이다.

## 06.06. Emergent Abilities

![](images/image8.png){width="7.268055555555556in" height="7.268055555555556in"}

창발적 능력(Emergent Abilities)은 지능형 시스템이 충분한 규모(scale), 풍부한 표현 능력(representational richness), 다양한 훈련 경험(training diversity), 또는 조직적 복잡성(organizational complexity)에 도달했을 때 관찰되기 시작하는 능력을 의미하며, 이러한 능력이 개별적인 명시적 기능으로 직접 프로그래밍된 것은 아니다. 자기 진화 지능(self-evolving intelligence)에서 창발은 학습된 여러 구성 요소 사이의 상호작용을 통해 각각의 구성 요소를 개별적으로 보았을 때 예상할 수 있는 수준을 넘어서는 행동이 나타날 수 있다는 점에서 중요하다.

창발(emergence)이라는 개념이 반드시 어떤 능력이 순간적이거나 신비롭게 나타난다는 것을 의미하지는 않는다. 일부 능력은 내부적으로 점진적으로 향상되지만 성능이 실질적인 임계값(threshold)을 넘어선 이후에야 측정 가능한 형태로 나타날 수 있다. 따라서 평가 방법, 프롬프트 조건(prompting condition), 과제 난이도, 측정 해상도(measurement resolution)는 능력이 불연속적으로 나타나는 것처럼 보이는지에 영향을 줄 수 있다. 창발은 설명할 수 없는 지능의 증거라기보다 세심한 분석이 필요한 경험적 현상(empirical phenomenon)으로 다루어야 한다.

대규모 신경망 시스템(large neural system)은 이러한 현상의 중요한 사례를 제공한다. 모델이 언어, 개념, 관계, 절차, 패턴에 관한 더욱 광범위한 표현(representation)을 획득하면 이전에는 분리되어 있던 여러 능력이 상호작용할 수 있다. 주로 시퀀스 예측(sequence prediction)을 위해 훈련된 시스템도 요약(summarization), 번역(translation), 분류(classification), 유추(analogy), 질의응답(question answering), 제한적인 추론(reasoning)을 보여줄 수 있는데, 이는 이러한 과제가 완전히 독립적인 메커니즘을 필요로 하기보다 학습된 표현 내부의 구조를 재사용하기 때문이다.

표현 학습(representation learning)은 이러한 과정의 중심에 있다. 충분히 표현력이 높은 내부 표현(internal representation)은 여러 후속 행동을 동시에 지원할 수 있는 관계를 인코딩할 수 있다. 하나의 맥락에서 학습된 개념이 다른 맥락에서 유용하게 사용되면서 여러 과제에 걸쳐 지식이 재조합될 수 있다. 따라서 시스템이 모든 조합을 명시적으로 훈련받지 않았더라도 기존에 획득한 구성 요소를 이용하여 새로운 해결책을 구성할 만큼 표현이 충분히 일반화되면 창발적 능력이 나타날 수 있다.

조합성(compositionality)은 창발을 가능하게 하는 또 다른 메커니즘이다. 인지(perception), 메모리 검색(memory retrieval), 계획(planning), 도구 사용(tool use), 추론과 같은 개별 기술은 처음에는 서로 분리된 능력으로 작동할 수 있다. 그러나 아키텍처가 이들을 효과적으로 조정하는 방법을 학습하면 각각의 구성 요소만으로는 해결할 수 없었던 문제를 조합을 통해 해결할 수 있다. 결과적으로 나타나는 행동은 반드시 새로운 원시 능력(primitive ability)이 아니라 기존 능력을 효과적인 순서로 조직함으로써 생성되는 상위 수준 능력(higher-order capability)일 수 있다.

규모(scale)는 여러 차원을 통해 창발에 영향을 줄 수 있다. 매개변수 용량(parameter capacity)의 증가는 더욱 풍부한 표현을 지원하고, 더 큰 데이터셋(dataset)은 더욱 다양한 규칙성을 제공하며, 추가적인 계산 자원은 더욱 깊은 최적화(optimization)를 가능하게 하고, 긴 문맥(long context)은 적응에 더 많은 정보를 제공할 수 있다. 그러나 규모만으로 유용한 창발이 보장되는 것은 아니다. 데이터 품질, 아키텍처, 목표(objective), 메모리, 상호작용, 평가, 환경 다양성이 어떤 능력이 실제로 발전하는지를 크게 결정한다.

훈련 다양성(training diversity)은 광범위하게 분포된 경험이 전이(transfer)의 기회를 제공하기 때문에 특히 중요하다. 다양한 도메인(domain), 과제, 모달리티(modality), 환경, 피드백 형태를 경험한 시스템은 겉으로 서로 다른 문제에서 반복적으로 나타나는 규칙성을 발견할 수 있다. 이러한 공유 구조(shared structure)는 이후 훈련에서 직접 목표로 하지 않았던 능력을 지원할 수 있다. 따라서 다양성은 일반화되고 재조합 가능한 역량(generalized and recombinable competence)이 창발할 수 있는 기반을 제공한다.

전이 학습(transfer learning)은 이러한 현상이 어떻게 발생하는지를 설명하는 데 도움을 준다. 하나의 과제를 위해 획득한 지식은 다른 과제에 유용한 표현, 사전 지식(prior), 절차를 제공할 수 있다. 이러한 전이가 반복적으로 축적되면 시스템은 별도의 전용 훈련이 거의 없거나 전혀 없는 새로운 과제를 해결하기 시작할 수 있다. 새로운 능력처럼 보이는 것은 실제로 이전에 학습된 여러 구조가 상호작용하면서 적절한 문제가 등장했을 때 그 결합된 유용성이 나타난 결과일 수 있다.

문맥 내 학습(In-Context Learning)은 잠재적으로 창발적인 적응 행동(adaptive behavior)의 중요한 사례이다. 모델은 현재 문맥(context) 안에서 제공된 지시(instruction)나 시연(demonstration)으로부터 패턴을 추론하고 영구적인 매개변수 업데이트 없이 자신의 응답을 변화시킬 수 있다. 이를 통해 일반 모델이 일시적으로 과제 특화 학습자(task-specific learner)처럼 행동할 수 있다. 이러한 능력은 별도로 설치된 학습 모듈이 아니라 표현, 어텐션(attention), 사전 훈련(prior training), 문맥 해석, 패턴 완성(pattern completion)의 상호작용에 의존한다.

도구 사용(tool use)은 또 다른 질적인 능력 확장을 만들어낼 수 있다. 검색 시스템, 계산기, 데이터베이스(database), 시뮬레이터(simulator), 코드 환경(code environment), 로봇 기능을 언제 어떻게 호출해야 하는지를 학습한 모델은 자신의 내부 계산을 넘어서는 연산에 접근할 수 있다. 도구 선택, 결과 해석, 검증이 효과적으로 조정되기 시작하면 결합된 에이전트(agent)는 기반 모델이나 개별 도구만으로는 효과적으로 처리하기 어려운 문제의 범주까지 해결할 수 있다.

메모리(memory) 역시 행동을 근본적으로 변화시킬 수 있다. 지속적인 메모리가 없는 에이전트는 비슷한 문제를 반복적으로 처음부터 해결해야 할 수 있다. 일화 기억(episodic memory), 의미 기억(semantic memory), 절차 기억(procedural memory)은 경험, 사실, 전략, 교훈을 상호작용에 걸쳐 축적하도록 한다. 검색(retrieval)이 충분히 맥락적이고 신뢰할 수 있게 되면 시스템은 장기 적응(long-term adaptation), 개인화된 전략(personalized strategy), 향상된 계획, 반복적인 실패의 회피와 같은 에이전트 수준의 새로운 능력을 나타낼 수 있다.

월드 모델(world model)은 객체(object), 행동(action), 동역학(dynamics), 인과관계(causality), 시간적 상태 전이(temporal transition)에 관한 지식을 통합함으로써 창발적인 계획과 예측을 지원할 수 있다. 이러한 관계가 함께 표현되기 시작하면 에이전트는 가능한 미래를 시뮬레이션하고, 대안 행동을 비교하고, 숨겨진 원인을 추론하거나, 행동의 결과를 예상할 수 있다. 이러한 능력은 개별 예측 메커니즘이 상대적으로 제한적이더라도 인지와 예측 구조(predictive structure)의 상호작용을 통해 창발할 수 있다.

체화(embodiment)는 인지와 행동이 폐쇄 피드백 순환(closed feedback loop)을 형성하기 때문에 창발을 위한 추가적인 기회를 제공한다. 로봇은 단순히 환경을 관찰하는 것이 아니라 자신의 행동을 통해 다음에 관찰할 환경 자체를 변화시킨다. 반복적인 상호작용은 감각운동 기술(sensorimotor skill), 능동적 인지(active perception), 적응적 탐색(adaptive exploration), 객체 어포던스 이해(object affordance understanding), 조정된 행동(coordinated behavior)을 만들어낼 수 있다. 이러한 능력은 센싱, 제어, 메모리, 예측, 환경 피드백의 관계에서 발전할 수 있다.

다중 에이전트 시스템(multi-agent system)은 집단 수준(collective level)의 창발을 가능하게 한다. 개별 에이전트는 제한된 정보나 전문화된 능력을 가지고 있을 수 있지만, 통신과 협력을 통해 집단은 과제를 분할하고, 발견한 정보를 교환하고, 결과를 검증하며, 집단 행동을 조직할 수 있다. 전문화된 역할(specialized role)이 동적으로 형성되면서 개별 성능을 넘어서는 집단 수준의 문제 해결 능력이 나타날 수 있다. 그러나 집단적 창발은 협력 실패, 잘못된 정보의 전파, 불안정한 상호작용 패턴을 발생시킬 수도 있다.

지속 학습(Continual Learning)은 능력이 시간에 따라 축적되도록 함으로써 창발을 강화한다. 새로운 기술은 이전의 표현을 재사용할 수 있으며, 이후 경험을 통해 더욱 일반적인 구조가 발견되면 기존 지식이 재구성될 수 있다. 초기 단계에서는 필요한 구성 요소가 아직 획득되지 않아 불가능했던 능력이 이후에 나타날 수 있다. 따라서 창발은 서로 다른 시점에 학습된 능력이 누적적으로 상호작용하면서 발생하는 발달적 과정(developmental process)이 될 수 있다.

메타 학습(meta-learning)은 새로운 능력을 획득하는 방법 자체를 개선함으로써 이러한 과정을 가속할 수 있다. 효과적인 적응 전략(adaptation strategy)을 학습한 시스템은 익숙하지 않은 과제를 습득하는 데 더 적은 예제를 필요로 할 수 있다. 이러한 전략이 일반화되면 시스템은 기존 지식으로부터 새로운 과제 특화 행동을 빠르게 구성할 수 있다. 따라서 창발적 역량은 축적된 내용 지식(content knowledge)뿐 아니라 새로운 조건에 맞추어 지식을 재구성하는 점점 더 효과적인 메커니즘에서도 발생할 수 있다.

자기 성찰(self-reflection)은 에이전트가 자신의 성공과 실패를 분석하도록 함으로써 또 다른 경로를 제공한다. 성찰(reflection)은 반복되는 추론 패턴, 유용한 전략, 비효율적인 도구 사용 순서 또는 부족한 지식을 식별할 수 있다. 이러한 교훈이 저장되고 재사용되면 체계적인 검증(systematic verification), 적응형 추론 깊이(adaptive reasoning depth), 전략적인 오류 회피(strategic error avoidance)와 같은 상위 수준 행동이 발전할 수 있다. 이러한 행동은 실행, 평가, 수정의 반복적인 순환에서 창발할 수 있다.

재귀적 자기 개선(recursive self-improvement)은 학습 또는 추론 메커니즘의 개선이 이후 능력이 발전하는 조건 자체를 변화시킬 수 있기 때문에 창발을 더욱 확장할 가능성이 있다. 향상된 메모리가 성찰을 개선하고, 개선된 성찰이 더 나은 학습을 유도하며, 더 나은 학습이 더욱 효과적인 계획을 만들어낼 수 있다. 이러한 개선 사이의 상호작용은 어느 하나의 수정만으로 설명할 수 없는 능력을 생성할 수 있으므로 시스템 수준 평가(system-level evaluation)가 점점 중요해진다.

창발적 능력(Emergent Abilities)은 유용할 수 있지만 자동적으로 바람직한 것은 아니다. 유용한 계획, 창의성(creativity), 협력(cooperation), 적응을 만들어내는 동일한 메커니즘이 의도하지 않은 전략, 기만적인 지름길(deceptive shortcut), 안전하지 않은 도구 사용, 과도한 자원 소비 또는 평가 체계의 약점을 이용하는 행동을 만들어낼 수도 있다. 설계자가 어떤 조건에서 능력이 활성화되는지 충분히 이해하기 전에 새로운 능력이 나타날 수 있기 때문에 예측, 시험, 거버넌스(governance)에 어려움이 발생한다.

능력 유도(capability elicitation)는 따라서 중요한 평가 문제이다. 시스템이 잠재적인 능력(latent capability)을 가지고 있더라도 필요한 프롬프트, 문맥, 메모리, 도구 또는 상호작용 패턴이 제공되지 않으면 일반적인 벤치마크에서 이를 발견하지 못할 수 있다. 평가는 여러 표현 방식, 환경, 난이도, 능력의 조합을 시험해야 한다. 하나의 벤치마크에서 실패했다고 해서 근본적인 능력이 존재하지 않는다고 단정할 수 없으며, 제한적인 조건에서 성공했다고 해서 강건한 일반 역량(robust general competence)이 확립된 것도 아니다.

임계값 효과(threshold effect) 역시 신중하게 해석해야 한다. 하나의 과제가 여러 하위 기술(subskill)을 동시에 필요로 한다면 각각의 구성 요소가 충분히 신뢰할 수 있는 수준에 도달하기 전까지 전체 성능은 거의 향상되지 않을 수 있다. 모든 구성 요소가 일정 수준에 도달하면 측정된 성공률이 급격하게 증가할 수 있지만 각각의 내부 구성 요소는 점진적으로 향상되었을 수 있다. 따라서 겉으로 보이는 창발은 비선형적 조합(nonlinear composition), 벤치마크 임계값 또는 측정 설계의 결과일 수도 있다.

창발을 예측하는 것은 복잡한 학습 시스템에 많은 상호작용 변수가 존재하기 때문에 여전히 어렵다. 매개변수, 표현, 훈련 데이터, 최적화, 메모리, 도구, 환경, 피드백이 작은 시스템에서 쉽게 외삽(extrapolation)하기 어려운 방식으로 결합될 수 있다. 스케일링 연구(scaling study)와 기계론적 분석(mechanistic analysis)은 중요한 증거를 제공할 수 있지만 미래에 발생할 모든 능력을 사전에 예측할 수 있다고 보장하지는 않는다. 따라서 개발과 배포 전반에 걸쳐 지속적인 평가가 필요하다.

안전성(safety)을 위해서는 의도된 능력뿐 아니라 예상하지 못한 능력의 조합도 시험해야 한다. 샌드박스 환경(sandboxed environment), 적대적 평가(adversarial evaluation), 능력 탐색(capability probe), 행동 모니터링(behavioral monitoring), 권한 경계(permission boundary), 제한된 도구 접근(restricted tool access), 단계적 배포(staged deployment)는 시스템이 광범위한 운영 권한을 획득하기 전에 새로운 행동을 발견하는 데 도움을 줄 수 있다. 능력이 증가할수록 기존에 시험된 행동이 그대로 유지될 것이라고 가정하기보다 평가 범위와 제어 메커니즘을 함께 확장해야 한다.

창발(emergence)은 AGI 아키텍처를 설계하는 방식에도 변화를 요구한다. 모든 지능적 행동을 독립적으로 지정하는 대신, 설계자는 재사용 가능한 표현, 메모리 시스템, 학습 메커니즘, 월드 모델, 도구, 협력 구조(coordination structure)를 구축하여 이들의 상호작용을 통해 유용한 능력이 형성되도록 할 수 있다. 공학적 과제는 유익한 조합(beneficial composition)이 발생할 수 있는 조건을 만들면서 동시에 관찰 가능성(observability), 제어 가능성(controllability), 강건성, 안전성을 유지하는 것이다.

자기 진화 지능(self-evolving intelligence)에서 창발적 능력(Emergent Abilities)은 축적된 학습과 상호작용이 만들어내는 시스템 수준의 결과(system-level consequence)를 의미한다. 지속 학습(continual learning)은 경험을 제공하고, 메타 학습(meta-learning)은 적응을 개선하며, 자기 성찰(self-reflection)은 교훈을 추출하고, 메모리는 이를 보존하며, 월드 모델(world model)은 예측 지식을 구조화하고, 재귀적 자기 개선(recursive self-improvement)은 선택된 메커니즘을 정교화한다. 이러한 요소의 상호작용은 개별적으로 명시적인 최적화 대상이 아니었던 능력을 만들어낼 수 있으며, 바로 이러한 특성 때문에 창발은 일반성(generality)의 중요한 원천인 동시에 고도화된 지능을 이해하기 위한 핵심적인 과제가 된다.

## 06.07. Self Evolving Systems [w/Code]

![](images/image9.png){width="7.268055555555556in" height="7.268055555555556in"}

자기 진화 시스템(Self-Evolving Systems)은 초기 설계와 배포(deployment)가 완료된 이후에도 경험으로부터 학습하고, 자신의 성능을 평가하며, 작동 방식의 선택된 구성 요소를 수정하면서 지속적으로 변화하는 지능형 아키텍처(intelligent architecture)를 의미한다. 핵심적인 동작이 엔지니어의 업데이트 전까지 고정되어 있는 기존 소프트웨어와 달리, 자기 진화 시스템은 통제된 적응 메커니즘(controlled adaptation mechanism)을 유지하여 지식, 전략, 모델, 내부 조직이 시간에 따라 발전하도록 한다.

핵심 개념은 제한 없는 자기 수정(unrestricted self-modification)이 아니라 지속적인 폐쇄 순환형 발전(continuous closed-loop development)이다. 시스템은 환경에서 행동하고 결과를 관찰하며, 이를 예상 결과 및 목표와 비교하고, 유용하거나 문제가 되는 패턴을 식별한 후 이러한 관찰을 학습 신호(learning signal)로 변환한다. 검증된 변경 사항은 이후의 운영에 통합되고 새로운 경험을 생성하여 다시 다음 순환을 시작한다. 따라서 진화(evolution)는 별도의 개발 단계가 아니라 시스템 운영 자체의 지속적인 특성이 된다.

자기 진화 아키텍처(self-evolving architecture)는 각각 서로 다른 형태의 적응을 제공하는 여러 메커니즘을 통합한다. 지속 학습(continual learning)은 시간에 걸쳐 지식을 보존하고 확장하며, 메타 학습(meta-learning)은 새로운 지식을 획득하는 방법을 개선하고, 자기 성찰(self-reflection)은 추론과 행동의 약점을 식별하며, 재귀적 자기 개선(recursive self-improvement)은 개선 자체를 담당하는 선택된 메커니즘까지 정교화할 수 있다. 이러한 요소의 조정은 개별적인 적응 기술을 보다 광범위한 발전 시스템(developmental system)으로 변화시킨다.

메모리(memory)는 이러한 개선 순환 사이의 연속성(continuity)을 제공한다. 지속적인 메모리가 없다면 각각의 적응 에피소드(adaptation episode)는 미래 발전에 제한적인 영향만 미치게 된다. 일화 기억(episodic memory)은 중요한 경험을 보존하고, 의미 기억(semantic memory)은 일반화된 지식을 축적하며, 절차 기억(procedural memory)은 효과적인 전략을 유지할 수 있다. 또한 실험, 실패, 수정, 평가에 대한 과거 기록은 시스템이 실패했던 변경을 반복하지 않고 이전에 검증된 해결책을 재사용하도록 한다.

월드 모델(world model)은 진화하는 시스템이 환경을 이해하고 예측할 수 있도록 하는 내부 표현(internal representation)을 제공한다. 시스템은 예측된 상태 전이(state transition)와 실제 관찰된 결과를 비교하여 환경 동역학(environmental dynamics)의 변화를 탐지하고, 자신의 가정에서 발생한 약점을 식별하며, 예측 지식을 업데이트할 수 있다. 향상된 월드 모델은 이후 더 나은 계획, 시뮬레이션(simulation), 의사결정, 그리고 실행 전에 가능한 행동을 평가하는 데 활용될 수 있다.

자기 성찰(self-reflection)은 운영 경험과 명시적인 진단(diagnosis)을 연결한다. 시스템은 실패한 계획, 비효율적인 추론, 예상하지 못한 결과, 불확실성(uncertainty), 과도한 자원 소비 또는 반복적인 실패를 검토하여 어떤 메커니즘을 개선해야 하는지를 판단할 수 있다. 성찰은 단순한 설명이 아니라 검증 가능한 가설(testable hypothesis)을 생성할 때 특히 가치가 있으며, 이를 통해 제안된 교훈을 이후의 실험과 관찰로 검증할 수 있다.

메타 학습(meta-learning)은 시스템이 더욱 효과적으로 학습하는 방법을 습득하도록 함으로써 적응을 확장한다. 여러 과제와 환경을 경험하면서 시스템은 어떤 표현(representation)이 효과적으로 전이되는지, 어떤 메모리를 검색해야 하는지, 어떤 업데이트 규칙(update rule)이 효과적인지 또는 특정 구성 요소가 얼마나 빠르게 적응해야 하는지를 발견할 수 있다. 이러한 학습 전략이 개선되면서 시스템은 더 적은 예제와 계산 자원으로 새로운 능력을 습득하고 기존 지식과의 간섭을 줄일 수 있다.

자동화된 모델 및 에이전트 설계(automated model and agent design)는 식별된 약점을 후보 수정 사항(candidate modification)으로 변환할 수 있다. 자동화 머신러닝(AutoML) 메커니즘은 아키텍처, 하이퍼파라미터(hyperparameter), 훈련 절차, 전문화된 모듈을 탐색할 수 있으며, 자동화 에이전트(automated agent)는 추론 워크플로(reasoning workflow), 메모리 접근, 계획 전략, 도구 사용(tool usage)을 재구성할 수 있다. 이를 통해 시스템 엔지니어링의 일부가 탐색 가능한 설계 공간(searchable design space)이 되고, 평가는 어떤 구성이 실제 개선을 제공하는지를 결정한다.

지속 학습(continual learning)은 성공적인 변경 사항이 개별적인 적응 과정 이후 사라지지 않고 축적되도록 한다. 새로운 지식은 통합되어야 하지만 이전의 유용한 능력도 계속 사용할 수 있어야 한다. 재생(replay), 정규화(regularization), 모듈성(modularity), 매개변수 격리(parameter isolation), 메모리 통합(memory consolidation), 동적 아키텍처(dynamic architecture)는 안정성(stability)과 가소성(plasticity)의 균형을 유지하는 데 도움을 줄 수 있다. 이를 통해 시스템의 진화는 하나의 일시적인 능력을 다른 능력으로 반복해서 교체하는 것이 아니라 누적적인 과정이 된다.

창발적 능력(emergent abilities)은 이러한 메커니즘이 상호작용하면서 나타날 수 있다. 메모리의 개선은 성찰을 강화하고, 향상된 성찰은 학습 우선순위를 개선하며, 더 강력한 월드 모델은 계획을 지원하고, 개선된 계획은 도구 사용을 더욱 효과적으로 만들 수 있다. 그 결과로 나타나는 능력은 하나의 명시적으로 설계된 구성 요소에 대응하지 않을 수 있다. 따라서 자기 진화 시스템에는 구성 요소의 결합으로 발생하는 유익한 행동과 예상하지 못한 행동을 모두 탐지할 수 있는 시스템 수준 평가(system-level evaluation)가 필요하다.

아키텍처는 여러 시간 척도(timescale)에 걸쳐 작동할 수 있다. 빠른 적응(fast adaptation)은 운영 중 작업 기억(working memory), 문맥(context), 위험도가 낮은 매개변수를 업데이트할 수 있다. 중기 학습은 경험을 통합하거나 전문화된 모델을 조정할 수 있으며, 더 느린 과정에서는 아키텍처, 평가 절차 또는 에이전트 조직을 수정할 수 있다. 이러한 시간 척도의 분리는 모든 관찰이 즉시 대규모 구조 변경을 일으키는 것을 방지하면서 의미 있는 장기적 진화를 가능하게 한다.

모듈성(modularity)은 이러한 과정을 통제하는 데 특히 중요하다. 인지(perception), 메모리, 추론(reasoning), 계획(planning), 월드 모델링(world modeling), 학습, 도구 사용, 제어(control)를 명확한 인터페이스(interface)를 갖는 부분적으로 분리된 구성 요소로 표현할 수 있다. 그러면 후보 개선 사항을 개별 모듈에 적용하여 전체 시스템에 영향을 미치기 전에 평가할 수 있다. 모듈형 진화(modular evolution)는 통제되지 않은 상호작용을 줄이고 실패를 더욱 쉽게 진단, 격리, 복원 및 이전 버전과 비교할 수 있도록 한다.

모든 구성 요소가 동일한 수준의 적응 가능성(adaptability)을 가져야 하는 것은 아니다. 실용적인 자기 진화 시스템은 수정 가능 구성 요소(mutable component), 조건부 수정 가능 구성 요소(conditionally mutable component), 보호된 불변 요소(protected invariant)를 구분할 수 있다. 과제 전략과 메모리 정책은 비교적 자유롭게 적응할 수 있지만 안전 제약 조건(safety constraint), 승인 경계(authorization boundary), 핵심 제어 한계(critical control limit), 근본적인 목표(fundamental objective)는 보호될 수 있다. 따라서 진화는 제한 없는 수정이 아니라 명시적으로 제한된 공간 안에서 이루어진다.

평가(evaluation)는 시스템 진화에서 선택 메커니즘(selection mechanism)의 역할을 수행한다. 후보 변경 사항은 과제 성능, 일반화(generalization), 강건성(robustness), 효율성, 학습 속도, 자원 사용량, 불확실성, 안전성과 관련된 측정 가능한 증거를 통해 개선을 입증해야 한다. 하나의 벤치마크(benchmark) 성능을 높이면서 이전에 신뢰할 수 있었던 능력을 손상시키는 변경을 자동으로 채택해서는 안 된다. 따라서 평가는 하나의 최적화 지표가 아니라 전체적인 능력 프로파일(capability profile)을 고려해야 한다.

종단적 평가(longitudinal evaluation)는 수정의 결과가 반복적인 상호작용 이후에야 나타날 수 있기 때문에 특히 중요하다. 어떤 구성은 즉각적으로 높은 성능을 보이지만 시간이 지나면서 망각(forgetting), 불안정성(instability), 계산 비용 또는 바람직하지 않은 행동 경향을 증가시킬 수 있다. 시간에 따른 성능 모니터링은 일시적인 향상과 지속 가능한 개선(sustainable improvement)을 구별하고, 변화하는 운영 조건에서도 진화적 변경이 계속 유익한지를 판단할 수 있는 증거를 제공한다.

시뮬레이션(simulation)과 샌드박스 환경(sandbox environment)은 실험을 위한 보호된 공간을 제공한다. 후보 모델, 정책(policy), 메모리 전략 또는 에이전트 조직을 실제 운영 시스템에 즉시 영향을 주지 않으면서 다양한 시나리오에서 시험할 수 있다. 적대적 사례(adversarial case), 희귀 사건(rare event), 분포 변화(distribution shift), 실패 조건을 의도적으로 적용할 수도 있다. 사전에 정의된 검증 기준(validation criteria)을 만족하는 구성만 점차 현실적이고 중요한 배포 단계로 진행하도록 할 수 있다.

버전 관리(version control), 체크포인트(checkpoint), 롤백 메커니즘(rollback mechanism)은 진화 과정 자체를 위한 기술적 메모리(technological memory)를 제공한다. 각각의 중요한 구성은 훈련 이력(training history), 평가 결과, 의존성(dependency), 권한(permission), 운영 결과와 연결될 수 있다. 새롭게 배포된 버전이 예상하지 못한 행동을 보이면 이전에 검증된 상태로 복귀할 수 있다. 따라서 진화는 되돌릴 수 없는 수정의 연속이 아니라 가역적이고 감사 가능한(auditable) 과정이 된다.

체화된 AGI(Embodied AGI)에서 자기 진화는 물리적 경험과 직접적으로 연결된다. 로봇은 변화하는 지형, 객체, 페이로드(payload), 센서 특성, 액추에이터 상태(actuator condition), 인간 행동, 운영 목표를 경험한다. 이러한 경험을 통해 인지, 위치 추정(localization), 월드 모델링, 계획, 조작(manipulation), 제어를 업데이트할 수 있다. 따라서 로봇은 환경 변화뿐 아니라 자신의 물리적 신체와 계산 자원의 점진적인 변화에도 적응할 수 있다.

적응형 계산(adaptive computation) 역시 이러한 진화의 일부가 될 수 있다. 단순하고 예측 가능한 상황에서는 가벼운 인지와 계획만 필요할 수 있지만, 익숙하지 않거나 불확실하거나 위험한 상황에서는 더 깊은 예측, 추가 센싱(sensing), 검증, 시뮬레이션 또는 추론이 필요할 수 있다. 서로 다른 상황에서 얼마나 많은 계산이 필요한지를 학습함으로써 자기 진화 시스템은 지능의 품질, 지연 시간(latency), 에너지 소비, 사용 가능한 하드웨어 자원 사이의 관계를 개선할 수 있다.

다중 에이전트 아키텍처(multi-agent architecture)는 개별 시스템의 진화를 집단(population) 수준으로 확장할 수 있다. 서로 다른 에이전트가 서로 다른 환경을 경험하고 전문화된 지식을 발전시키며, 검증된 경험을 교환하고 후보 해결책을 독립적으로 평가할 수 있다. 따라서 플릿 수준 학습(fleet-level learning)은 개별 에이전트보다 빠르게 경험을 축적할 수 있다. 그러나 하드웨어, 환경, 목표, 구성의 차이 때문에 성공적인 경험도 다른 에이전트에는 적합하지 않을 수 있으므로 전이된 지식은 맥락에 따라 평가되어야 한다.

개체군 기반 메커니즘(population-based mechanism)은 모든 구성 요소를 하나의 해결책으로 수렴시키는 대신 여러 대안 전략을 동시에 유지할 수도 있다. 후보 정책, 모델 또는 에이전트 조직을 서로 다른 조건에서 평가하여 유용한 다양성(diversity)을 유지할 수 있다. 하나의 구성이 실패하는 상황에서 다른 구성이 더 효과적일 수 있기 때문에 이러한 다양성은 강건성과 탐색 능력을 향상시키며, 비교 평가를 통해 어떤 특성을 보존하거나 결합해야 하는지를 발견할 수 있다.

자기 진화 시스템(Self-Evolving Systems)은 더 이상 유효하지 않은 지식(obsolete knowledge)도 관리해야 한다. 제한 없는 지식 축적은 과도한 메모리 사용, 충돌하는 표현, 오래된 가정, 증가하는 계산 복잡성을 발생시킬 수 있다. 따라서 통제된 망각(controlled forgetting), 압축(compression), 통합(consolidation), 가지치기(pruning), 지식 수정(knowledge revision)이 학습을 보완해야 한다. 효과적인 진화에서는 무엇을 획득할 것인지뿐 아니라 무엇을 유지하고, 재구성하고, 교체하거나 안전하게 제거할 것인지도 결정해야 한다.

시스템이 자신의 작동 방식을 수정할 수 있는 능력을 더 많이 갖게 될수록 안전성(safety)은 더욱 중요해진다. 과제 성능을 향상시키는 개선이 의도하지 않게 안전장치를 약화시키거나, 평가 체계의 약점을 이용하거나, 초기 설계에서 예상하지 못한 능력을 만들어낼 수 있다. 권한 경계(permission boundary), 보호된 목표(protected objective), 독립적 검증(independent verification), 이상 탐지(anomaly detection), 모니터링, 단계적 배포(staged deployment), 인간 승인(human authorization)을 통해 제안된 변경이 실험에서 실제 운영으로 이동하는 과정을 제한할 수 있다.

고도로 자동화된 진화 시스템에서도 인간 거버넌스(human governance)는 계속 통합될 수 있다. 인간은 상위 수준 목표(high-level objective), 보호된 제약 조건(protected constraint), 허용 가능한 위험 수준, 평가 기준, 승인이 필요한 수정 유형을 정의할 수 있다. 자동화된 프로세스는 이러한 경계 안에서 대규모 탐색과 실험을 수행할 수 있다. 이를 통해 기계는 복잡한 구현 선택을 최적화하고 인간 거버넌스는 핵심 목표와 배포 의사결정에 대한 권한을 유지하는 역할 분담이 가능하다.

성숙한 자기 진화 시스템은 따라서 지속적으로 작동하는 발전 생태계(developmental ecosystem)와 유사하다. 경험은 증거를 생성하고, 메모리는 이를 보존하며, 성찰은 교훈을 추출하고, 지속 학습은 지식을 통합하며, 메타 학습은 적응을 개선하고, 월드 모델은 예측을 지원하며, 자동화된 설계는 대안을 생성하고, 평가는 검증된 개선 사항을 선택한다. 배포는 다시 새로운 경험을 생성하여 순환을 닫고 시스템의 운영 수명 전체에 걸쳐 발전이 계속되도록 한다.

목표는 변화 그 자체가 아니다. 유용한 자기 진화(self-evolution)는 이전에 검증된 행동과의 연속성을 유지하면서 점점 더 높은 능력, 효율성, 강건성, 적응성, 검증 가능성(verifiability)을 갖는 지능을 만들어야 한다. 개선은 통제되지 않은 망각, 구조적 불안정성(structural instability), 목표 표류(objective drift)를 발생시키지 않으면서 축적되어야 한다. 진화의 품질은 시스템이 얼마나 자주 변화하는지가 아니라 그러한 변화가 다양한 실제 환경 조건에서 지속 가능한 개선을 만들어내는지에 의해 결정된다.

자기 진화 지능(self-evolving intelligence)에서 자기 진화 시스템(Self-Evolving Systems)은 지속 학습(continual learning), 메타 학습(meta-learning), 자기 성찰(self-reflection), 재귀적 자기 개선(recursive self-improvement), 창발적 능력(emergent abilities), 메모리(memory), 월드 모델(world model), 자동화 에이전트(automated agent), 평가(evaluation)가 하나의 폐쇄형 발전 아키텍처(closed developmental architecture)의 구성 요소로 통합되는 계층을 의미한다. 지능은 더 이상 훈련 이후 완성된 산출물로 취급되지 않으며, 운영 경험으로부터 학습하고 자신의 선택된 측면을 수명 전체에 걸쳐 점진적으로 재구성할 수 있는 통제된 진화 과정(controlled evolving process)으로 발전한다.
