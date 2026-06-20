# 抖音喜欢批量管理删除（2026）

一个基于 Tampermonkey 的用户脚本，用于在网页版抖音中批量取消“喜欢”内容，实现自动化清理操作。

适用于：https://www.douyin.com/

---

## 功能特性

- 自动进入“批量管理”模式
- 自动执行“全选 / 取消全选”
- 自动点击“取消喜欢”
- 自动确认弹窗
- 自动滚动加载下一批内容
- 实时统计已处理数量
- 支持开始 / 停止控制
- 悬浮控制面板，无需开发者工具

---

## 使用逻辑

脚本循环执行以下流程：

1. 进入批量管理模式  
2. 全选当前页面内容  
3. 点击“取消喜欢”  
4. 确认操作  
5. 滚动加载下一批  
6. 重复执行

---

## 安装方法

### 1. 安装 Tampermonkey

Chrome / Edge / Firefox 扩展：

https://www.tampermonkey.net/

---

### 2. 新建脚本

进入 Tampermonkey 控制台：
<img width="608" height="109" alt="image" src="https://github.com/user-attachments/assets/7334fe27-d4dd-4bc4-8cde-f41e0a007168" />
把代码粘贴进去<img width="952" height="489" alt="image" src="https://github.com/user-attachments/assets/9571b32f-55de-4609-a734-78d63798059f" />
