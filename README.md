# Photo to Organic Knit

An open-source Codex skill that reimagines photographs as concept-driven, handcrafted knitted-wool art posters.

> 一个开源的 Codex Skill，将照片重新创作为具有概念设计感和手工质感的毛线针织艺术海报。

Instead of applying a textile filter, the skill selects a few defining elements from the source, removes secondary detail, and invents a new composition. Crochet, knit, boucle, felt, loose fibers, irregular textile edges, editorial negative space, and single-strand yarn lettering bring the final poster to life.

> 它并非简单叠加织物滤镜，而是从原图中筛选少量关键元素，舍弃次要细节，再重新设计构图。最终画面融合钩针、针织、圈圈纱、毛毡、松散纤维、不规则织物边缘、编辑式留白，以及单根毛线组成的标题。

## Before and After

### 效果对比

The most recognizable anchors remain, while hierarchy, shapes, negative space, and visual flow are rebuilt as tactile textile art.

> 保留原图中最具辨识度的元素，同时将画面层级、形状、留白和视觉动线重新构建为具有触感的毛线艺术。

<p align="center">
  <img src="assets/train-before-after.png" alt="Steam train before and after" width="48%">
  <img src="assets/forest-before-after.png" alt="Misty forest before and after" width="48%">
</p>

## Features

### 特点

- **Source-aware orientation** — Landscape, portrait, and square images keep their original orientation.<br>
  **匹配原图方向** — 横图、竖图和方图均保持各自的画幅方向。

- **Intentional selection** — Elements are sorted into retain, transform, and discard groups before generation.<br>
  **主动筛选元素** — 生成前将原图内容分为保留、转化和舍弃三组。

- **True reinterpretation** — One clear visual concept guides at least three structural changes to the original composition.<br>
  **真正的二次创作** — 以一个明确的视觉概念为核心，对原构图进行至少三项结构性改变。

- **Strong art direction** — Negative-space symbols, textile islands, yarn paths, scale contrast, and layered collage create a distinctive poster.<br>
  **鲜明的设计语言** — 灵活运用负形、织物岛屿、毛线路径、尺度对比和分层拼贴。

- **Editorial breathing room** — A compact textile vignette leaves generous space for covers and brand layouts.<br>
  **编辑式留白** — 控制针织主体占比，为封面和品牌视觉保留充足空间。

- **Organic imperfections** — Loose fibers, stray yarn, and uneven edges replace machine-perfect repetition.<br>
  **自然手作痕迹** — 通过抽丝、散线和不规则边缘，避免机械般整齐的效果。

- **Single-yarn title** — A readable two-to-four-word thematic title is formed from one continuous strand by default.<br>
  **单根毛线标题** — 默认加入清晰的两至四词主题标题，以单根毛线自然摆成。

## Installation

### 安装

Copy the `photo-to-organic-knit` folder into your Codex skills directory:

> 将 `photo-to-organic-knit` 文件夹复制到 Codex Skills 目录：

```bash
cp -R photo-to-organic-knit "${CODEX_HOME:-$HOME/.codex}/skills/"
```

Restart or refresh Codex so it can discover the skill.

> 重启或刷新 Codex，使其发现新 Skill。

## Usage

### 使用

Attach a photograph and invoke the skill:

> 上传一张照片并调用 Skill：

```text
Use $photo-to-organic-knit to turn this photo into an organic knitted-wool illustration.
```

You can also provide exact title text:

> 也可以指定准确的标题文字：

```text
Use $photo-to-organic-knit on this image and add the title "Wind Through Pines" in clear single-strand yarn handwriting.
```

By default, landscape sources produce landscape illustrations, portrait sources produce portrait illustrations, and square sources remain square.

> 默认情况下，横图生成横版插图，竖图生成竖版插图，方图保持方形。

## Repository Structure

### 仓库结构

```text
photo-to-organic-knit/
├── SKILL.md
├── agents/openai.yaml
├── assets/style-reference.png
└── references/style-spec.md
```

## License

### 许可证

Released under the MIT License. See [LICENSE](LICENSE).

> 本项目采用 MIT License，详见 [LICENSE](LICENSE)。
