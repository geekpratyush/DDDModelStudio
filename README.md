# DDD ModelStudio - Strategic & Tactical Modeler

DDD ModelStudio is a high-fidelity, web-based modeling tool designed for Domain-Driven Design (DDD). It enables architects and developers to map out both **Strategic** (Bounded Contexts, Context Maps) and **Tactical** (Aggregates, Entities, Value Objects) patterns in a unified, interactive environment.

![DDD ModelStudio](https://img.shields.io/badge/DDD-Modeling-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)
[![GitHub stars](https://img.shields.io/github/stars/geekpratyush/DDDModelStudio?style=social)](https://github.com/geekpratyush/DDDModelStudio)

## 🚀 Features

### Strategic Modeling
- **Bounded Contexts:** Group related concepts and define clear boundaries.
- **Context Mapping:** Define relationships between contexts (Upstream/Downstream, ACL, Shared Kernel, Partnership, etc.).
- **Visual Flow:** Dynamic vector-based connections that reflect relationship types.

### Tactical Modeling
- **Rich Components:** Specialized elements for Aggregate Roots, Entities, Value Objects, Domain Services, and more.
- **Dynamic Field System:** Attach data fields (Name, Type, Value) to components.
- **Auto-Sizing:** Components dynamically adjust their width and height to fit their labels, internal content, and fields.
- **Standardized Icons:** Integrated FontAwesome support for visual differentiation.

### Advanced UX
- **Theme Engine:** Support for multiple themes including Dark, Light, Cyberpunk, Forest, and VS Code variations.
- **Canvas Interaction:** Smooth panning, zooming, and grid-snapping for precise layout.
- **Property Panel:** Floating, context-aware properties editor for deep customization.
- **Import/Export:** Save and load models via JSON blueprints.

## 🛠️ Technical Stack
- **Frontend:** Vanilla HTML5, CSS3, and Modern JavaScript.
- **Icons:** [FontAwesome 6](https://fontawesome.com/).
- **Typography:** Inter and JetBrains Mono (via Google Fonts).
- **Architecture:** State-driven rendering with an immediate-mode inspired canvas system.

## 🔗 Links
- **Source Code:** [GitHub Repository](https://github.com/geekpratyush/DDDModelStudio)
- **Report Issues:** [GitHub Issues](https://github.com/geekpratyush/DDDModelStudio/issues)

## 📖 How to Use

1. **Adding Elements:** Drag components from the sidebar palette (Tactical or Infrastructure) onto the canvas.
2. **Naming & Customizing:** Click on any element to open the **Floating Property Panel**. Here you can change labels, icons, and colors.
3. **Adding Fields:** In the property panel for a component, use the "Data Fields" section to add attributes. The component box will automatically grow to accommodate them.
4. **Connecting:** Drag from any of the four "Port" bubbles on an element's edge to another element.
5. **Configuring Connections:** Click a connection wire to change its relationship type (e.g., set it as an Anti-Corruption Layer).
6. **Organizing:** Drag standard components into "Actor Containers" to group them logically within a Bounded Context or Subsystem.

## 🎨 Themes
You can switch themes using the "Display Mode" dropdown in the top header. Currently supported:
- **Default Dark:** Sleek, modern zinc-style UI.
- **Cyberpunk:** High-contrast neon aesthetics.
- **Forest:** Calming green-tinted environment.
- **VS Code:** Familiar editor-style themes (Dark/Light).

## 📄 License
Open Source. Built for the DDD Community.
