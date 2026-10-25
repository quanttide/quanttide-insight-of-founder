# 迷雾中的司令部 · 实现

一句话：先把真相与认知焊成一条可复算的管线，数值与界面才有地方挂。

管线由三段组成：引擎只算真相，关卡把事件翻成报告，认知层只读报告。三段之间只走命令与事件，谁在下令、界面长什么样都不改变这条路径。围绕这条路径，实现判断分成下面五篇。

- [determinism.md](./determinism.md)：引擎内部如何保证可复算。
- [contract.md](./contract.md)：两层之间靠什么立约，入口如何换人。
- [replay.md](./replay.md)：一局打完，凭什么查清发生了什么。
- [acceptance.md](./acceptance.md)：什么时候算做完，谁说了算。
- [params.md](./params.md)：数值放在哪，准不准怎么兜底。

玩法层的判断见 [../game/index.md](../game/index.md)。
