<div align="center">

# 🌌 Vanishing Games

### *让代码消失，让体验永恒。 / Building the invisible architecture.*

[**中文简体**](#-关于我们) | [**English**](#-about-us)

---

[![Unity](https://img.shields.io/badge/Unity-2021.3+-black?style=for-the-badge&logo=unity)](https://unity.com/)
[![C#](https://img.shields.io/badge/C%23-10.0-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://dotnet.microsoft.com/en-us/languages/csharp)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

<br/>

## 📖 关于我们

**Vanishing Games** 是一个专注于 Unity 高级架构与 C# 开发工具链的开发者组织。
我们坚信：“最好的架构是隐形的”。我们的使命是构建高度解耦、可插拔且性能极致的系统，让开发者能够从繁琐的底层逻辑中解脱，专注于游戏灵魂的创造。

---

## 🛠️ 核心项目深度解析

### 1. [Capabilities-System](https://github.com/Vanishing-Games/Capabilities-System) —— 模块化游戏逻辑框架
**“以组合优于继承，重塑游戏逻辑。”**
*   **核心理念：** 基于 GDC 经典的 *Capabilities* 模式，为 Unity 开发提供了一套纯粹的 C# 组合式架构。
*   **技术优势：**
    *   **高度解耦：** 通过将“能力（Capability）”与“状态（State）”彻底分离，消除复杂的继承树，解决 Unity 脚本开发中的耦合难题。
    *   **动态扩展：** 支持在运行时动态挂载或卸载功能，非常适合大型 RPG 或复杂动作游戏的机制开发。
    *   **类型安全：** 充分利用 C# 泛型与接口，在编译阶段即可发现架构风险。

### 2. [CodeUnfucker](https://github.com/Vanishing-Games/CodeUnfucker) —— C# 代码自动化重构编排器
**“超越格式化，重塑代码的骨架。”**
*   **核心理念：** 这不是普通的 Linter，而是基于 **Roslyn (Microsoft Compiler Platform)** 的代码结构治理工具。
*   **核心功能：**
    *   **结构化重组：** 自动按照访问修饰符和逻辑关联对成员进行排序，让成千上万行的文件瞬间井然有序。
    *   **Unity 生命周期感知：** 智能识别 `Awake` / `Start` / `Update` 等生命周期方法并进行标准化归类。
    *   **语义清理：** 集成 Roslynator，不仅修剪空白，更从语义层面优化代码（如简化表达式、修剪无用 using）。

### 3. [Unity-Template](https://github.com/Vanishing-Games/Unity-Template) —— 生产力基准模板
*   **标准定义：** 沉淀了组织内部的目录规范、工程配置与必备依赖包。
*   **开箱即用：** 预设了高效的开发工作流，让每一个新项目都能站在巨人的肩膀上开始。

---

## 🚀 组织准则

-   **组合优先 (Composition First)：** 拒绝臃肿的基类，拥抱灵活的能力组合。
-   **DX (Developer Experience) 极致追求：** 工具必须像原生编辑器功能一样自然。
-   **性能导向：** 优雅的代码不应以牺牲帧率为代价。
-   **文档即契约：** 所有的系统设计都经过详尽的理论支撑与文档维护。

---

## 📊 技术洞察

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vanishing-Games&layout=compact&theme=transparent&title_color=ffffff&text_color=9f9f9f&border_color=ffffff&border_radius=10" alt="Top Languages" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Vanishing-Games&repo=Capabilities-System&theme=transparent&title_color=ffffff&text_color=9f9f9f&icon_color=ffffff&border_color=ffffff&border_radius=10" alt="Capabilities System Stats" />
</div>

<br/>

## 📬 建立联系

我们始终在寻找对底层架构和自动化工具有共同热情的合作伙伴。

- 🌐 [组织官网](https://github.com/Vanishing-Games)
- 💬 [加入社区 / Issue 反馈](https://github.com/Vanishing-Games/Capabilities-System/issues)

---

## 🇺🇸 About Us (English)

**Vanishing Games** is a developer collective focused on advanced Unity architecture and C# developer tooling. Our philosophy is rooted in the belief that the best code is "invisible"—it handles the complexity silently, allowing the player experience to shine.

-   **Capabilities-System:** A Roslyn-powered, composition-based architectural framework for Unity, inspired by GDC patterns.
-   **CodeUnfucker:** An advanced orchestration tool for structural C# refactoring, member sorting, and Unity lifecycle management.
-   **Unity-Template:** Our golden standard for project organization and workflow automation.

---

<div align="center">
<sub>&copy; 2024 Vanishing Games. "The art of vanishing into the experience."</sub>
</div>
