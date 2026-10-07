# simple-krw-vuln

`simple-krw-vuln` 是一个 `Windows` **漏洞收集**仓库，专门收集 **简单、稳定** 的 **内核任意内存读写漏洞**。

每一个 CVE 编号文件夹下都是 **可编译且稳定复现** 的 `Exploit` 而不是 `POC` ，以 **权限提升** 或 **终止安全软件** 为示例证明漏洞有效。

## 当前项目收集

```
simple-krw-vuln/
├── CVE-2024-35250/   # Windows Kernel Streaming (ks.sys) 不可信指针解引用
├── CVE-2026-62735/   # Windows HTTP.sys 堆溢出 / 整数溢出
└── README.md
```

## 免责声明

滚木
