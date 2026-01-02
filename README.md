# LWRS

**LWRS** 是一款基于 AutoHotkey v2 的轻量桌面小工具：面向含 CEF 子窗口的应用，一键将核心窗口“解嵌套”并按配置进行重构；同时提供一键恢复窗口样式与任务栏的快捷键。  
它的初衷是为了：

> Bringing clean control to your desktop flow,  
> Yielding to your hands with subtle ease.  
> Placing windows where your focus goes,  
> Aligning frames with disciplined grace.  
> Silent in motion, it stays out of the way,  
> Staying light—no clutter, no delay.
> 
> Layer by layer, it keeps your view intact,  
> Drifting when needed, then fading back.  
> Balanced for those who demand it simple, swift, exact.

---

## Usage 使用说明

### 📁 文件

* **启动脚本**：运行 `LWRS.exe`
* **配置文件**：`rs.config.ini`
  * 用于设置：License Key、目标尺寸、置顶开关、热键绑定

---

## ⌨️ 热键操作

| 热键               | 功能                                                      |
| ---------------- | ------------------------------------------------------- |
| `Ctrl + Alt + 1` | **Reframe**：将窗口解绑为居中缩放、可移动，并隐藏外层容器窗口 |
| `Ctrl + Alt + 2` | **Restore**：恢复原父子/Owner 关系与窗口位置/状态，恢复原本样式                |
| `Ctrl + Alt + R` | **Restart Explorer**：重启 `explorer.exe`（以恢复任务栏）           |

> 说明：热键以 `rs.config.ini` 为准，默认为脚本内置。

---


## ⚠️ 注意事项

* 以**管理员身份**运行
- 请联系联系作者以获得身份验证。
- 首次使用建议先修改 `config.ini` 以个性化键位与样式配置。

---
