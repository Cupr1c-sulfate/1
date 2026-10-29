# 最终交付文件

本目录保存当前云环境实际保留的最终版本：**PET氨解与含氮产物：10篇论文系统学习**。采用 `delivery-reviewed` 的内容复核版本，没有混入早期草稿或原始上传文献。

## 下载

- [完整学习包 ZIP](pet-nitrogen-learning.zip)
- [学习笔记 Markdown](pet-nitrogen-learning.md)
- [交互学习网页 HTML（下载后用浏览器打开）](pet-nitrogen-learning.html)
- [整体方法论](pet-nitrogen-learning.learnkb/methodology.md)
- [知识库目录](pet-nitrogen-learning.learnkb/INDEX.md)
- [内容 JSON](pet-nitrogen-learning.page.json)
- [原静态交付检查记录](pet-nitrogen-learning.delivery.json)
- [本次文件清单与SHA-256](manifest.json)

在iPhone Safari打开GitHub文件页面后，使用 **Raw / Download raw file** 下载；私有仓库需要先登录有访问权限的GitHub账号。HTML需要下载后打开，GitHub文件页面不会直接运行该网页。

## 缺失与验证边界

- 此前PET醇解24页PDF及对应HTML/Markdown/ZIP没有保留在当前云环境快照中。尝试重新读取两篇旧上传PDF均失败，不能假称这些文件已交付。
- 本次任务未生成Word或Excel文件。
- 网站准备包缺少内容，属于未完成草稿，不纳入最终交付。
- 所有本次纳入文件都已逐个读取；JSON解析、HTML解析、PNG解码、ZIP CRC及包内文本检查通过。未重新执行完整浏览器交互验收。
- 未上传密钥、凭据、环境变量文件、Git配置或缓存。`manifest.json` 记录各交付文件的长度和SHA-256。
