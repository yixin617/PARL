<p align="center">
<img src="../../.github/PARL-logo.png" width="300"/>
</p>

PARL是一个主打高性能、稳定复现、轻量级的强化学习框架。

## 使用场景
- 想要在**自己的环境**中尝试使用强化学习解决问题
- 想快速调研下**不同强化学习算法**在同一个问题上的效果
- 强化学习算法训练速度太慢，想搭建**分布式**强化学习训练平台
- python的GIL全局锁限制了多线程加速，想**加速python代码**


PARL文档全览
<table>
  <tbody>
    <tr align="center" valign="bottom">
    <td>
      </td>
      <td>
        <b>构建智能体（基础）</b>
        <img src="../images/bar.png"/>
      </td>
      <td>
        <b>开源算法库</b>
        <img src="../images/bar.png"/>
      </td>
      <td>
        <b>并行训练（进阶）</b>
        <img src="../images/bar.png"/>
      </td>
    </tr>
    </tr>
    <tr valign="top">
    <td align="center" valign="middle">
      </td>
      <td>
        <li><b>教程</b></li>
            <ul>
          <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#BOHB">入门：解决cartpole问题</a></li>
          <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#BOHB">智能体（Agent）搭建示例</a></li>
          <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#BOHB">保存模型和加载模型</a></li>
          <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#BOHB">绘制训练曲线</a></li>
            </ul>
        </ul>
      </ul>
      </td>
      <td align="left" >
        <ul>
          <li><b>前沿算法</b></li>
            <ul>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#BOHB">MADDPG</a></li>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#TPE">ES</a></li>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#TPE">SAC</a></li>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#TPE">TD3</a></li>
            </ul>
          <li><b>经典算法</b></li>
            <ul>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#BOHB">PolicyGradient</a></li>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#TPE">DQN</a></li>
            <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#SMAC">DDPG</a></li>
            <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#MetisTuner">PPO</a></li>
            </ul>
          <li><b>并行算法</b></li>
            <ul>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#BOHB">A2C</a></li>
              <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#TPE">GA3C</a></li>
            <li><a href="docs/zh_CN/Tuner/BuiltinTuner.md#SMAC">IMPALA</a></li>
            </ul>
        </ul>
      </td>
      <td>
      <ul>
        <li><b>教程</b></li>
            <ul><li><a href="docs/zh_CN/TrainingService/PaiMode.md">部署集群</a></li>
            <li><a href="docs/zh_CN/TrainingService/KubeflowMode.md">入门教程</a></li>
            <li><a href="docs/zh_CN/TrainingService/FrameworkControllerMode.md">加速案例</a></li>
            </ul>
            <ul><li><a href="docs/zh_CN/TrainingService/DLTSMode.md">集群信息监控与debug</a></li>        
      </ul>
      </td>
    </tr>
  </tbody>
</table>
