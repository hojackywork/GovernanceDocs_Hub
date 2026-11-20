# GovernanceDocs Hub

四治理引擎的**公開產品文件層**——引擎程式／治理面／skill 正本的公開投影（AGENT-PTC1 正本一份、其餘投影）。

- 內容一律由各引擎**生成產物**發佈（不自手抄；引擎側有閉集一致性測試鎖），每份文件帶版本戳。
- 敏感清單：無本機絕對路徑／個資／憑證／內部立案編號；含此類的文件只發「公開版」。
- 同步：ProjectOS release CI 自動推 tools.html；其餘引擎落地後比照。

## 目錄

| 引擎 | 文件 |
|---|---|
| project-os | [plugin.html](project-os/plugin.html)——Plugin：MCP 19 枚全表（Read/Write、blocked 候選、人審後操作） |
| project-os | [cli.html](project-os/cli.html)——CLI：正式／觀測指令按機制分組（由 catalog.py 生成） |
| project-os | [faq.html](project-os/faq.html)——FAQ 公開版（機械 scrub） |

## 分層對照

| 層 | 位置 | 公開性 |
|---|---|---|
| 引擎程式＋治理面 | ProjectOS_Dev 等（私有） | 不公開 |
| Skill 正本 | Skills_Hub（私有） | 不公開 |
| Norm 正本 | hojackywork-norm org | 安裝版目錄 |
| 產品公開文件 | **本 hub** | ✅ 公開（GitHub Pages） |
