```markdown
# security-notes
> Network Security & CTF Study Notes
网络安全与CTF学习笔记仓库，用于记录学习笔记、漏洞复现、EXP脚本、靶机实验。

## 仓库简介
本仓库为个人学习存档，记录Web安全、密码学、逆向、PWN、Misc等CTF方向学习资料、解题EXP、漏洞复现实验记录。
所有内容仅用于安全学习研究，禁止未授权的攻击行为。

## 目录结构
```
security-notes/
├── docs/                # 仓库配套文档、环境搭建指南
├── notes/               # 核心学习笔记
├── exp/                 # CTF EXP / Poc 利用脚本
├── labs/                # 漏洞复现 & 靶机实验记录
├── tools/               # 自制安全小工具脚本
├── daily-log/           # 每日学习打卡日志
├── ctf-contest/         # CTF 比赛 Writeup 与脚本
├── attachments/         # 截图、pcap 等附件
├── training/            # 专项刷题训练、错题整理
├── references/          # 书籍 / 论文笔记、学习链接收藏
└── sandbox/             # 草稿、临时测试脚本
```

## 学习方向
- Web安全（SQL注入、XSS、文件上传、反序列化等）
- 密码学 Crypto
- 逆向工程 Reverse
- PWN栈/堆利用
- Misc杂项、流量分析、隐写取证

## ⚠️ 免责声明
仓库内所有代码、脚本仅用于**个人授权实验环境内学习**。
未经授权对任何系统进行渗透测试属于违法行为。

## 提交规范
- `init`: 仓库初始化、目录新增
- `daily`: 每日学习笔记更新
- `exp`: 新增/修改EXP利用脚本
- `lab`: 漏洞复现、靶机实验记录
- `note`: 更新学习笔记

## 实验环境
- OS: Ubuntu Linux (虚拟机)
- Python3
- Git
- CTF工具链：pwntools、gdb、ida、ghidra
```
