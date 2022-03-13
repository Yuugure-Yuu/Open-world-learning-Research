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

