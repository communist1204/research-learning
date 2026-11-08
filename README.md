# 科研学习与积累

面向 AI 科研的论文与书籍带读 Skill。新论文先按任务、输入输出、训练与推理、关键模块和信息流讲清整篇方法，等读者确认开始后进入精读。

论文的每个精读小节分两次回复。第一回合只给忠实翻译和返璞归真解释，然后等待读者。译文可拆分长句、重排段落或改成列表，完整保留原意、论证关系、必要顺序、限定条件和引用。读者之后明确要求细讲，才在第二回合按需讲解公式、推导、图表、代码和例子。读者也可跳过细讲，下一小节重新从翻译和返璞归真开始。

将完整的 [`research-learning` 目录](research-learning/) 添加到支持 `SKILL.md` 的环境，在会话中调用 `$research-learning`。附带的 Python 工具用于按需准备论文材料和图表，依赖见 [工具说明](research-learning/references/kelip-integration.md)。

可以直接使用本轮提供的论文或书籍。需要保存进度和知识积累时，按 [资料库规则](research-learning/references/library-scope.md) 指定自己的私有资料库。研究方向、已学内容和教学偏好可按 [学习者画像](research-learning/references/learner-profile.md) 维护。持久读写和跨会话续读依赖使用环境实际提供的存储与访问能力。

论文带读方法和备料工具部分源自 [可lip 的 kelip-paper-reading](https://github.com/skJack/kelip-paper-reading)，随附文件保留其 [MIT 许可与版权](research-learning/references/kelip-upstream/LICENSE) 和 [固定版本与文件来源](research-learning/references/kelip-upstream/source.json)。证据回溯和状态恢复的设计受 [VISTA](https://github.com/joshhhhhan/VISTA) 启发。
