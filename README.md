<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Cascadia+Code&weight=700&size=17&color=0078D7&center=true&pause=100000&lines=Hi,+I'm+Yaozong+Zheng.+A+Backend+Engineer" alt="Hi"/>
  <p>
    <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="28px" height="28px"/>
    <strong>I'm currently focused on RAG &amp; Multi-Agent systems and open to job opportunities.</strong>
  </p>
  <p><strong>📮 Reach me: <a href="mailto:2363959478@qq.com">2363959478@qq.com</a></strong></p>
  <p>
    <code>🎓 硕士研究生</code>
    <code>📍 China</code>
  </p>
</div>
<table>
<tr>
<td valign="top" width="50%">

### 🧭 工作经历

<strong>CCTC</strong> -- <code>后端开发工程师 · AI 应用方向</code> -- <code>2025.9 ~ 至今</code>

负责城市体检 AI 平台核心链路的架构设计与研发：RAG 检索、多智能体编排、流式交互与 Java / Python 微服务治理。

<!-- 有新的真实工作/实习经历，按上面格式在此追加 -->

</td>
<td valign="top" width="48%">

### 🌟 技能与荣誉

**Backend**

`Java` `Spring Boot` `MyBatis-Plus` `MySQL` `Redis`

**AI / LLM 应用**

`Python` `FastAPI` `RAG` `LangGraph` `Chroma`

**Frontend & DevOps**

`Vue` `Docker` `Linux` `Git`

**🏆 荣誉证书**

- 📜 软件设计师 · 软考中级
- 🎖️ 研究生学业奖学金 · 一等奖 / 二等奖

> 🚀 持续关注 LLM 应用与 Agent 工程化

</td>
</tr>
</table>

## 📦 项目经验

**城市体检 AI 助手与报告自动生成平台** —— RAG + 多智能体驱动的长文报告生成系统

<code>Spring Boot</code> <code>FastAPI</code> <code>LangGraph</code> <code>Chroma</code> <code>Redis</code> <code>MySQL</code>

- 🎯 **S/T**：城市体检数据多源异构、指标解读高度依赖专家经验、人工成稿周期长且质量不稳定——目标是构建「数据 → 检索 → 生成 → 审核」全流程自动化的报告生成系统
- 🏗️ **A · 架构**：设计 Java / Python 微服务分工：Spring Boot 承接业务、权限与会话（15+ 业务模块，支撑 Web 与小程序双端），FastAPI 承接 AI 计算密集链路，独立部署、按需扩缩
- 🔍 **A · RAG**：落地混合检索方案：Chroma 向量语义召回与 Whoosh BM25 精确匹配互补，叠加多查询生成与重排序，兼顾召回率与精度；构建 Mineru「解析 → 分块 → 向量化」异步流水线，支撑大批量文档入库
- 🤖 **A · Agent**：基于 LangGraph 编排五智能体状态图（任务分解 → 数据分析 → 指标解读 → 报告撰写 → 审核打分），设计「审核-重写」闭环与模型分级路由 / 降级链，保障长文成稿质量
- 📡 **A · 交互**：设计 SSE + WebSocket 双通道流式协议，8 类消息（step / thinking / content / review 等）实时反馈生成过程
- 🏁 **R**：实现城市体检报告从多源数据到成稿的全流程自动生成，多轮「审核-重写」显著提升成稿效率与质量稳定性 <!-- 有真实量化数据（效率提升 X% 等）告诉我，我补进去 -->

**老年人智能疗程用药提醒系统**（独立开发 · [elder](https://github.com/zyz18802283164-ux/elder)）

<code>Spring Boot</code> <code>MyBatis-Plus</code> <code>MySQL</code> <code>Vue</code> <code>JWT</code>

- 前后端分离，独立设计并实现患者、药品、疗程方案、用药记录等 10 个业务模块
- 覆盖健康档案、风险预警、紧急联系人 / 紧急求助、数据看板全流程
- 基于 JWT 登录认证、统一响应封装与标准 Controller → Service → Mapper 分层架构

<!-- 有新的真实项目，按上面格式在此追加 -->
