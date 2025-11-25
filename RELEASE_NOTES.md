# Code Switch v0.1.9

## 更新亮点
- 💰 **新增 Claude Opus 4.5 计费支持**：添加 `claude-opus-4-5-20251101` 模型价格数据，支持完整的费用计算（输入/输出/缓存/批量处理）。

## 价格详情
| 类型 | 价格 |
|------|------|
| Input | $5.00 / MTokens |
| Output | $25.00 / MTokens |
| Cache Read | $0.50 / MTokens |
| Cache Creation | $6.25 / MTokens |
| Batch Input | $2.50 / MTokens |
| Batch Output | $12.50 / MTokens |

---

# Code Switch v0.1.8

## 更新亮点
- 🚀 **供应商路由更稳**：移除 Level 分组后按列表顺序重试，日志与失败提示更清晰，成功率统计也不再误将失败计为成功。
- ⚙️ **开机自启动**：新增"开机自启动"开关，安装后可一键配置后台随系统启动。
- 📥 **cc-switch 导入优化**：即使未检测到默认配置也可直接导入，旁路上传提示更友好。
- 🛠️ **构建与 CI 提升**：完善缺失的模型编辑组件，补齐 Node/NSIS 配置并新增自动发布工作流，减少跨平台构建故障。
