# QA
测试相关技术  
## 缺陷的定义  
我们一般从软件自身特点、团队工作和项目管理这三个方面进行分析，找出会导致软件缺陷的原因  
#### 1.软件开发过程中自身特点造成的问题  
- 软件需求定义难以做到清清楚楚，导致设计偏离目标用户的需求，从而引起功能或者产品特性上的缺陷  
- 软件系统结构复杂，而又无法构造成一个完美的层次结构或组件结构，结果将导致意想不到的问题，例如系统中对象，类太多，在众多对象、类之间调用，引用时容易出现问题  
- 新技术的采用，可能涉及技术或者兼容性问题，而事先没有考虑到  
- 对程序逻辑路径或数据范围的边界考虑不周全，容易在边界条件上出错，或者超越边界条件后缺少保护导致出错  
- 系统运行环境复杂，用户使用的计算机环境千变万化，测试环境很难完全模拟用户的各种实际环境和操作习惯，不可避免在一些特定的用户环境下系统出问题  
- 系统实际运行中的数据量要比开发、测试环境的数据量大得多，而且系统实际运行中由于各种意外会产生一些垃圾数据，从而引起系统负载和数据不兼容的过问题  
- 对于一些实时应用系统来说，如果没有精心的设计和处理，容易造成时间上无法保持精确同步，使系统行为在时间上出现不协调、不一致从而出错  
- 没有考虑或处理好系统崩溃后的自我恢复、故障转移或数据的异地备份等情况，从而存在系统安全性、可靠性的隐患  
- 通讯端口多、存取和加密手段矛盾等会造成系统安全、性能等存在问题  
#### 2.软件项目管理的问题  
- 受质量文化的影响，不重视质量计划，对质量、资源、任务、成本等的平衡性把握不好，容易挤掉需求分析、评审、测试等的时间，于是遗留的缺陷也会比较多  
- 开发周期短，需求分析、设计、编程、测试等各项工作不能完全按照定义好的流程来进行，工作不够充分，结果也就不够完整、不准确，错误较多，周期短，还给各类开发人员带来压力，从而引起一些认为的错误  
- 开发流程不够完善，存在较多的随机性和严重缺乏严谨的内审或评审机制，容易产生问题  
- 文档不完善，风险评估不足等  
#### 3.团队工作问题  
- 沟通不够，不流畅，导致不同阶段、不同团队的开发人员对问题的理解不一致  
- 项目组成人员技术水平参差不齐，或者新员工较多或培训不够等，也容易引起问题  #
