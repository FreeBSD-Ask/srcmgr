# srcmgr 会议纪要

srcmgr@ 是一组 FreeBSD 开发者，旨在指导源代码开发实践。可通过 [srcmgr@FreeBSD.org](mailto:srcmgr@FreeBSD.org) 与他们联系。

## FreeBSD 源代码管理团队 [srcmgr@FreeBSD.org](mailto:srcmgr@FreeBSD.org)

FreeBSD 源代码管理团队（也称为 srcmgr，因其邮件别名而得名）负责基本系统相关的问题。[srcmgr 团队章程](https://www.freebsd.org/srcmgr/charter/) 对源代码管理团队的职责进行了更详细的说明。

* Ed Maste [emaste@FreeBSD.org](mailto:emaste@FreeBSD.org)
* Warner Losh [imp@FreeBSD.org](mailto:imp@FreeBSD.org)
* John Baldwin [jhb@FreeBSD.org](mailto:jhb@FreeBSD.org)
* Mark Johnston [markj@FreeBSD.org](mailto:markj@FreeBSD.org)

—— [FreeBSD Source Management Team <srcmgr@FreeBSD.org>](https://www.freebsd.org/administration/#t-srcmgr)

## 源代码管理团队章程

源代码管理团队（srcmgr）是一组 FreeBSD 开发者，负责监督 FreeBSD 基础系统源代码树及其由源代码树生成的产品的开发。该团队的目标是提供功能完整、稳定且高性能的基础系统工件和发布版本。基础系统由 src Git 仓库构建，包括内核、引导加载程序和用户空间。

### 职责

为了实现这一目标，srcmgr 团队承担以下职责（*斜体内的行内说明仅作描述，不具约束力*）：

* 批准源代码仓库的新提交权限和回归提交权限。
* 收回源代码仓库中闲置的提交权限。
* 定义和管理新提交者及导师的招募活动。*包括识别尚未成为提交者的活跃贡献者，并从现有提交者中招募新贡献者的导师。我们可以管理任何负责招募的子委员会。*
* 仲裁 FreeBSD 社区成员之间与源代码仓库相关的争议。
* 定义并鼓励提交者与外部贡献者之间的健康互动规范。*例如，为补丁审查制定指南和最佳实践，以及与 bugmeister@ 合作开发特定于源代码的缺陷分流工作流。*
* 定义源代码仓库变更提交策略。*例如，谁可以向仓库合并提交以及何时合并。这包括明确的权限，如回退提交和执行冻结等。另一个例子是如何维护这些政策。不同分支的策略可能不同。*
* 确保基础系统工件被生成并发布。*例如，与 re@ 合作验证发布镜像，或确保基础系统包按时发布。*
* 定义对 src 提交的期望。*例如，支持哪些工具链、是否必须跨平台构建、哪些任务在提交后进行 CI 检查、哪些提交破坏是可接受的，哪些是高度不鼓励的。*
* 按照项目规范沟通活动总结。*例如，发布月度或季度报告，举办公开会议或讨论论坛以公开做出决策等。具体形式会随着时间演变，章程中未明确规定。*
* 在需要协调时，与项目其他部分及 Core Team 合作。
* srcmgr 必须为每项章程职责保持清晰的书面政策。

完整的当前政策列表请参见 [源代码团队政策](https://www.freebsd.org/srcmgr/policies/)，这些政策旨在帮助实现上述目标。

### 成员资格

有投票权的成员任期为一年。个人成员最多可连续担任三届。成员在至少休息一整届（一年）后，可以再次连续担任三届。团队还应包括一名或多名无投票权成员（“lurkers”），作为未来有投票权成员的候选人。投票成员和 lurkers 由现有 srcmgr 投票成员选出。srcmgr 必须公布其投票成员和无投票权成员的变动。

初始团队由 Core Team 选定。Core Team 可自行决定调整成员资格。

### 权限

srcmgr 团队在 FreeBSD Core Team 的授权下运作。本章程有效，直至 Core Team 修改或废止；任何章程变更必须经 Core Team 批准。Core Team 将监督 srcmgr 并在必要时仲裁涉及其的争议。

—— [Charter for the Source Management Team](https://www.freebsd.org/srcmgr/charter/)
