# Photo to Organic Knit

一个开源的 Codex Skill，将照片重新创作为具有概念设计感和手工质感的毛线针织艺术海报。

An open-source Codex skill that reimagines a photograph as a concept-driven, handcrafted knitted-wool art poster.

它会保留原图方向和少量关键识别元素，主动舍弃或抽象次要细节，并重新设计构图、层次与视觉动线。最终画面融合钩针、针织、圈圈纱、毛毡、松散纤维、不规则织物边缘、编辑式留白，以及单根毛线组成的标题。这是一种真正的二次创作，而不是在照片上叠加毛线滤镜。

It preserves source orientation and a few recognition anchors, then deliberately discards or abstracts secondary detail, invents a new composition, and applies tactile crochet, knit, boucle, felt, loose fibers, irregular textile edges, editorial negative space, and single-strand yarn lettering. It is genuine reinterpretation—not a wool filter over the original photograph.

## 效果对比 · Before and After

Skill 会保留原图中最具辨识度的元素，同时重新构建画面层级、形状、留白和视觉路径。

The skill keeps the most recognizable anchors while rebuilding hierarchy, shapes, negative space, and visual flow.

<p align="center">
  <img src="assets/train-before-after.png" alt="Steam train before and after" width="48%">
  <img src="assets/forest-before-after.png" alt="Misty forest before and after" width="48%">
</p>

## 特点 · Features

- 自动匹配横图、竖图或方图的原始方向。 / Matches landscape, portrait, or square orientation.
- 生成前将原图元素分为保留、转化和舍弃三组。 / Sorts elements into retain, transform, and discard groups.
- 建立一个明确的视觉概念，并改变原构图至少三项结构特征。 / Builds one visual concept and changes at least three structural qualities.
- 灵活使用负形、织物岛屿、毛线路径、尺度对比或分层拼贴。 / Uses negative space, textile islands, yarn paths, scale contrast, or layered collage.
- 控制主体占比并保留充足留白，适合封面与品牌视觉。 / Keeps generous negative space for cover and brand layouts.
- 加入克制的抽丝、散线和不规则边缘，保留真实手作感。 / Adds restrained loose fibers and irregular handmade edges.
- 只重塑关键元素，不照搬示例主体，也不描摹原图构图。 / Reimagines only key elements without tracing the source layout.
- 默认加入清晰的 2–4 词主题标题，使用单根毛线形成的儿童手写字。 / Adds a readable 2–4 word title in childlike single-strand yarn lettering by default.

## 安装 · Install

将 `photo-to-organic-knit` 文件夹复制到 Codex Skills 目录：

Copy the `photo-to-organic-knit` folder into your Codex skills directory:

```bash
cp -R photo-to-organic-knit "${CODEX_HOME:-$HOME/.codex}/skills/"
```

重启或刷新 Codex，使其发现新 Skill。 / Restart or refresh Codex so it can discover the skill.

## 使用 · Use

上传一张照片并调用 Skill： / Attach a photograph and invoke the skill:

```text
Use $photo-to-organic-knit to turn this photo into an organic knitted-wool illustration.
```

也可以指定准确的标题文字： / You can also specify exact title text:

```text
Use $photo-to-organic-knit on this image and add the title "Wind Through Pines" in clear single-strand yarn handwriting.
```

默认情况下，横图生成横版插图，竖图生成竖版插图，方图保持方形。

By default, landscape sources produce landscape illustrations, portrait sources produce portrait illustrations, and square sources remain square.

## 仓库结构 · Repository Structure

```text
photo-to-organic-knit/
├── SKILL.md
├── agents/openai.yaml
├── assets/style-reference.png
└── references/style-spec.md
```

## 许可证 · License

本项目采用 MIT License。 / Released under the MIT License. See [LICENSE](LICENSE).
