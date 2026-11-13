### Hi, I'm Hanah — I make robotics teams build faster with AI.

**Senior Researcher, AI Transformation @ [Rainbow Robotics](https://www.rainbow-robotics.com)**
I lead AX for the RBQ quadruped: turning how we develop, test, and ship robots into workflows where AI agents do the heavy lifting.

#### Since joining (Jun 2026)

- **One app, 7 platforms, 3 stores** — rebuilt the RBQ controller with AI agents: one TypeScript codebase for Android · iOS · Windows · Linux (x86/ARM) · Web · Steam Deck, live on [Google Play](https://play.google.com/store/apps/details?id=com.rainbowrobotics.rbq) · [App Store](https://apps.apple.com/app/id6792970388) · [Microsoft Store](https://apps.microsoft.com/detail/9N3D6Z3D60KL)
- **Open-sourced it** — published daily as [Apache-2.0 source](https://github.com/RainbowRobotics/RBQ/tree/nightly/gui), behind an automated gate that stops the publish if anything internal slips in
- **AI-native pipeline** — AI review on every PR, labeled issues turned into AI-written fix PRs, nightly multi-platform builds pushed to the stores (ARM build 6 h → 23 min, PR checks 2 h → 8 min)
- **Simulation as the safety net** — 38 MuJoCo scenarios run headless every night after the build, SDK wire compatibility checked against the last release; [RBQ-10 submitted to MuJoCo Menagerie](https://github.com/google-deepmind/mujoco_menagerie/pull/361)
- **Robot knowledge AI** — RAG over code, docs, manuals, and change history: answers in ~6 s, 97–99% on a 102-question eval, used by the team and by the review and issue agents
- **Agents that touch the robot** — MCP servers (24 robot tools, 10 app tools) let AI drive the robot, simulator, and app, and walk every app screen without a robot
- **Reliability from field logs** — trade-show logs turned into 28 fixes: stop after stick release 3.92 s → 0.72 s, camera frame loss 15–22% → 0
- **Language → behavior (prototype)** — an LLM agent docks the robot in simulation through function calls; an in-app AI assistant is in test builds

Before robots: 8 years in games, XR, and digital twins — 4 games and 3 apps shipped, 12-month projects done in 1–3 months with AI.

[Portfolio](https://glowelephant.site/?utm_source=github) · [Ask my AI](https://glowelephant.site/chat?utm_source=github) · [Email](mailto:gksdk1029@gmail.com)

---

#### Selected work

| | |
|:--|:--|
| **[RBQ controller](https://github.com/RainbowRobotics/RBQ/tree/nightly/gui)** | Open-source quadruped controller app — React Native + Electron, 7 platforms, 3 stores (at Rainbow Robotics) |
| **[task-board](https://github.com/glowElephant/task-board)** | One board for many parallel Claude Code sessions — questions and reports per task, [Send] wakes the session |
| **[context-forge](https://github.com/glowElephant/context-forge)** | Bootstrap for AI-augmented repos — 82 curated sources, auto-synced |
| **[graph-rag-viewer](https://github.com/glowElephant/graph-rag-viewer)** | Hybrid RAG + MCP server — 9,556-node knowledge graph, 100% hit rate |
| **[harness-bench](https://github.com/glowElephant/harness-bench)** | CLI that scores how AI-native your Claude Code setup is (8 axes) |
| **[claude-mux](https://github.com/glowElephant/claude-mux)** | PTY multiplexer that drives interactive Claude Code sessions instead of `claude -p` |
| **[Molten](https://github.com/glowElephant/Molten)** | Terminal wrapper built for AI coding agents (Tauri · Rust) |
| **[AI_Language](https://github.com/glowElephant/AI_Language)** | Compressed agent-to-agent protocol — 40.7% fewer tokens |
| **[Data2Avatar](https://github.com/glowElephant/private-projects/tree/main/data2avater)** | CCTV → digital twin safety monitoring, 4 pose models, ≤150 ms sync |
| **[VTS Visualizer](https://github.com/glowElephant/private-projects/tree/main/vts-visualizer)** | Industrial 3D digital twin — 12 months → 1 month with AI |

<sub>More on the [portfolio](https://glowelephant.site/?utm_source=github).</sub>

#### Stack

`LLM Agents` `RAG` `MCP` `Claude Code` · `ROS 2` `DDS` `WebRTC` `C++` `MuJoCo` · `React Native` `Electron` `TypeScript` `Python` · `GitHub Actions` `Docker` · `Unity/C#`
