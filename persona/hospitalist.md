# Dr. Sam Chen — Attending Hospitalist（陈森医生 — 住院总医师 / 医院内科）

## Overview（概览）

| Attribute（属性） | Detail（英文） | 详情（中文） |
| --- | --- | --- |
| **Age（年龄）** | 42 | 42 岁 |
| **Role（角色）** | Attending physician, hospital medicine | 医院内科主治医师 / 住院总医师 |
| **Setting（场景）** | Acute medical ward, public hospital | 公立医院的急性内科病房 |
| **Typical day（典型一天）** | Ward rounds, admissions, discharges, handoffs, documentation after complex cases | 查房、收治新病人、出院、交接班，以及复杂病例后的文书工作 |

## Goals（目标）

- Produce accurate, defensible documentation without routinely working hours past handoff. — 产出准确、可举证、经得起质询的病历文书，且不必经常在交接班后仍长时间加班。
- Preserve clinical judgment as the source of truth; use tools to reduce clerical burden only where trust is earned. — 以临床判断为最终依据；仅在建立信任的前提下，用工具减轻文书负担。
- Maintain a clear audit trail for medico-legal and quality review. — 保留清晰的审计轨迹，以应对法律与质量管理审查。

## Pain points（痛点）

- Documentation time competes directly with bedside decision-making and teaching. — 写病历的时间与床旁决策、带教直接争抢精力。
- Boilerplate and copy-paste degrade note quality and obscure what was actually assessed. — 套话与复制粘贴降低记录质量，并掩盖真实评估内容。
- Strong distrust of “black box” suggestions that lack provenance, limits, or a fast way to reject or undo. — 强烈不信任缺乏来源、边界说明，或无法快速拒绝、撤销的「黑箱」式建议。

## Needs（需求）

- **Control（可控性）：** One-tap reject, edit-in-place, and **undo** after accepting AI-assisted text; no silent overwrite of finalized notes. — 一键拒绝、就地编辑，以及在采纳 AI 辅助文本后可**撤销**；不得静默覆盖已定稿记录。
- **Transparency（透明度）：** See why a suggestion appeared (e.g. which inputs triggered it) and when the system is **uncertain** or **out of scope**. — 能知晓建议因何出现（例如由哪些输入触发），以及系统在何时**不确定**或**超出能力范围**。
- **Safety & boundaries（安全与边界）：** Explicit statements of **what the system cannot do** (e.g. no autonomous diagnosis, no substitute for examination); prompts to verify critical facts (allergies, anticoagulation, pregnancy). — 明确声明**系统不能做什么**（例如不能替代查体、不能自主下诊断）；对关键事实（过敏史、抗凝、妊娠等）提供核对提示。
- **Efficiency（效率）：** High-quality first drafts for routine sections (HPI, problem list formatting) with **manual override** always available. — 对常规段落（现病史 HPI、问题列表格式等）提供高质量初稿，且始终可**手动覆盖**。
- **Failure tolerance（容错）：** Clear UI when outputs are wrong, incomplete, or the service fails—**recover without losing work** and with guidance on next steps. — 当输出错误、不完整或服务故障时界面清晰提示；能**不丢工作地恢复**，并引导下一步操作。

## Behaviors & workflows（行为与工作流）

- Skims AI-generated drafts line-by-line for factual and clinical errors before signing. — 签署前逐行扫视 AI 草稿，查找事实与临床错误。
- Prefers conservative defaults: if unsure, rejects the suggestion and writes manually. — 偏好保守默认：若不确定则拒绝建议并手写。
- Expects attending-level accountability—any tool must support **review before commit** on high-impact content. — 承担主治医师级责任——任何工具对高影响内容须支持**提交前复核**。

## Track A alignment (smart adaptive interfaces)（与 Track A 一致：智能自适应界面）

- Primary emphasis on **user control**, **interaction transparency**, and **safe exception handling** when the model is wrong or the case exceeds training/coverage. — 强调**用户掌控**、**交互透明**，以及在模型错误或病例超出训练/覆盖范围时的**安全异常处理**。

## Quote（引述）

> “If I can’t see why it said that—and I can’t turn it off in two taps—I’m not using it on real patients.”  
> 「如果我不明白它为什么这么说——而且不能两下就关掉——我不会在真实病人身上用它。」
