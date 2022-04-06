### An Environment Transformation-based Framework for Comparison of Open-World Learning Agents

实在不好理解。这篇论文的意义是，虽然novelty还是与模型相关无法独立描述，但这里基于环境变化描述的novelty八个方面可以作为思考和描述模型可能面对的novelty的工具。

1.In action selection problems, we refer to environments as “discrete-time” or “continuous”, “single-agent” or “multi-agent”, “deterministic” or “stochastic”.

![image-20220311091817992](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311091817992.png)

![image-20220311092007059](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311092007059.png)

2.We have developed a set of dimensions for classifying environment-based novelty that are intended to assist in exploration of what makes novelty in the environment challenging for an agent to recognize, characterize, and respond to.

and formal description for environment

3.a.![image-20220311092051372](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311092051372.png)

![image-20220311092105897](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311092105897.png)

3.b.![image-20220311093826292](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311093826292.png)

α is the observing agent, omegaM is the modified environment

![image-20220311093856914](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311093856914.png)

### Anticipatory Thinking Challenges in Open Worlds: Risk Management

区分感知挑战与认知挑战，并分别给出解决方案。认为开放世界游戏如Dungeon Crawl Stone Soup（DCSS）是认知挑战理想的示例领域，并提出了该示例的高级解决方案。

![image-20220311091133716](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311091133716.png)

1.![image-20220311101329721](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311101329721.png)

2.

![image-20220311101544688](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311101544688.png)

3.![image-20220311101834470](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311101834470.png)

![image-20220311101846823](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311101846823.png)

4.![image-20220311102748556](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220311102748556.png)

### Towards a Unifying Framework for Formal Theories of Novelty

当代理从实验室走向开放世界时，管理新颖的、未知的或无法分配的输入是至关重要的。与新奇相关的问题包括对正常输入的新奇扰动的容忍度，当输入包含新奇的项目时的检测，以及适应新奇的输入。虽然在这些领域进行了重要的研究，但明显的差距是缺乏超越问题领域的新颖性的正式定义。作为一个由多个研究小组和不同领域的研究人员组成的团队，我们已经亲眼目睹了不明确的新颖性问题所带来的困难，以及不一致的定义和术语。因此，我们提出了第一个新颖性形式化理论的统一框架，并利用该框架正式定义了一组新颖性类型。我们的框架可以应用于广泛的领域，从符号人工智能到强化学习，并超越开放世界图像识别。因此，它可以用来帮助启动新的研究工作，并加速这些重要的新奇相关问题的正在进行的工作。



### Open-World Learning for Radically Autonomous Agents

The paper first specify the challenge of open-world learning more fully by illustrating the challenge through example, defining the elements of open-world autonomy agents, proposing a framework for presenting the environments and their transformation, and then discuss about the ways to solve the challenge by listing paradigms that have been proposed and could support open-world learning and designing reliable testing ways for open-world agents.



### Constraints on Theories of Open-World Learning

在本文中，我研究了在发展开放世界学习理论时所面临的挑战。在定义了这个问题之后，我回顾了化学、生物、地质学和人工智能历史上的一些理论，以及归纳偏见对限制学习过程的重要性。经典的认知架构为这种指导提供了一个来源，但它们的普遍性在这方面提供的帮助很少。相反，我建议为嵌入代理提供更多约束的体系结构具有更大的潜力，因为它们承诺用于描述环境的领域知识的形式，以及在它们之上运行的流程。此外，我假设自主主体必须包括驱动行为的动机结构，环境的变化也可以导致他们的修正。我认为，一个完整的开放世界学习应该对这些能力的基础结构和过程做出承诺。

认为约束对于使开放世界学习有效是必要的，更强的归纳偏好对开放世界学习有利，提出开放世界学习体系包含的内容（基于内容的架构，认为自主主体必须包括驱动行为的动机结构。

![image-20220318091024194](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220318091024194.png)

1.![image-20220318091622601](C:\Users\86153\AppData\Roaming\Typora\typora-user-images\image-20220318091622601.png)

Physical symbol system believes that learning agent structure includes symbols and symbol structures and structure's mental processes.

Production system assume that AI memories can memorize symbol structures and regard learning process as matching rules and alter memory contents that generates new learning possibilities.

Heuristic search also claims that AI learning must includes structures storing candidate solutions, solution generators, solution choosing methods and process for looking for new-method and  solutions.

2.Cognitive architecture is a theory about AI's learning framework, or we can say it describes how to constructure AI's mind like human. memories that store domain content, the representation of such content, and the processes that create, access, and modify these elements, and programming language. Generally it defines and divides ai's short-term (encoded as symbol  structures) and long-term memories (acessed by matching structures), and also includes how learning process is creating new memory elements by measuring performance.

3.Use generic characteristics as architecture constraints that includes four long-term knowledge contents to characterize the environment in a descriptive way. also needs short-term structures to describe past, present, and current situations and events. And this declarative structures is ambiguous, thus a complete content-laden architecture also needs how the AI system is drived, which also includes four mechanisms.

4.prescriptive knowledge structures includes processes of operating those contents. updating Motivations may have unexpored unknown impacts on the agents but there are some mechanisms to support this. and will make evaluation difficult. A choice is to ensure gradual changes in motivation.



### Learning from Synthetic Data Addressing Domain Shift for Semantic

Visual Domain Adaptation is a problem of immense importance in computer vision. Previous approaches showcase the inability of even deep neural networks to learn informative representations across domain shift. This problem is more severe for tasks where acquiring hand labeled data is extremely hard and tedious. In this work, we focus on adapting the representations learned by segmentation networks across synthetic and real domains. Contrary to previous approaches that use a simple adversarial objective or superpixel information to aid the process, we propose an approach based on Generative Adversarial Networks (GANs) that brings the embeddings closer in the learned feature space. To showcase the generality and scalability of our approach, we show that we can achieve state of the art results on two challenging scenarios of synthetic to real domain adaptation.Additional exploratory experiments show that our approach: (1) generalizes to unseen domains and (2) results in improved alignment of source and target distributions.

视觉域适应是计算机视觉中一个非常重要的问题。以前的方法表明，即使是深度神经网络也无法跨域学习信息表示。这个问题在获取手工标注的数据极其困难和繁琐的任务中更为严重。在这项工作中，我们着重于在合成域和真实域中调整分段网络学习的表示。与以往使用简单的对抗目标或超像素信息来辅助过程的方法相反，我们提出了一种基于生成对抗网络(GANs)的方法，使嵌入更接近于学习的特征空间。为了展示我们的方法的通用性和可伸缩性，我们展示了我们可以在两个具有挑战性的从合成到真实领域适应的场景中实现最先进的结果。进一步的探索性实验表明，我们的方法:(1)可以推广到不可见域，(2)可以改善源和目标分布的对齐。

这篇论文中的检验手法在许多方面可疑，包括基准线选择、参照方法数量不足、检验领域不足（是否本就是相近领域？）等。



### Science Birds Novelty: an Open-world Learning Test-bed for Physics Domains

Successfully operating in open worlds is a hallmark of human intelligence but still remains a major challenge to modern Artificial Intelligence (AI) systems. With the increasing reliance on autonomous systems (e.g. self-driving vehicles, vacuuming robots), being able to handle unforeseen situations has become a crucial ability for any AI agent that can safely and effectively operate alongside humans. As to facilitate the research in developing agents that are capable of reacting to unexpected events, we propose a test-bed named Science Birds Novelty based on the Angry Birds domain. We also demonstrate a use-case of our test-bed, the AIBIRDS Competition Novelty Track and present the results of the competition. 

在开放世界中成功运行是人类智能的标志，但仍然是现代人工智能(AI)系统面临的主要挑战。随着人们对自动驾驶系统(如自动驾驶汽车、吸尘机器人)的依赖日益增加，对于任何能够安全和有效地与人类一起操作的人工智能代理来说，能够处理不可预见的情况已经成为一项至关重要的能力。为了促进开发能够对突发事件做出反应的agent的研究，我们基于《愤怒的小鸟》领域提出了一个名为Science Birds Novelty的试验台。我们还演示了我们的测试平台——AIBIRDS竞赛新颖性跟踪的一个用例，并展示了竞赛的结果。



### RMA: Rapid Motor Adaptation for Legged Robots

Successful real-world deployment of legged robots would require them to adapt in real-time to unseen scenarios like changing terrains, changing payloads, wear and tear. This paper presents Rapid Motor Adaptation (RMA) algorithm to solve this problem of real-time online adaptation in quadruped robots. RMA consists of two components: a base policy and an adaptation module. The combination of these components enables the robot to adapt to novel situations in fractions of a second. RMA is trained completely in simulation without using any domain knowledge like reference trajectories or predefined foot trajectory generators and is deployed on the A1 robot without any fine-tuning. We train RMA on a varied terrain generator using bioenergetics-inspired rewards and deploy it on a variety of difficult terrains including rocky, slippery, deformable surfaces in environments with grass, long vegetation, concrete, pebbles, stairs, sand, etc. RMA shows state-of-the-art performance across diverse real-world as well as simulation experiments. Video results at https://ashish-kmr.github.io/rma-legged-robots/.

在现实世界中，腿部机器人的成功部署要求它们能够实时适应看不见的场景，如地形变化、载荷变化、磨损等。针对四足机器人的实时在线自适应问题，提出了一种快速电机自适应(RMA)算法。RMA由两个组件组成:一个基本策略和一个适应模块。这些组件的组合使机器人能够在几分之一秒内适应新的情况。RMA完全在模拟中训练，没有使用任何领域知识，如参考轨迹或预定义的脚轨迹生成器，部署在A1机器人上，没有任何微调。我们训练RMA在一个不同的地形生成器使用生物能量启发奖励，并部署它在各种困难的地形，包括岩石，湿滑，变形表面的环境，草，长植被，混凝土，鹅卵石，楼梯，沙子等。RMA在不同的真实世界以及模拟实验中显示了最先进的性能。视频结果在https://ashish-kmr.github.io/rma-legged-robots/。
