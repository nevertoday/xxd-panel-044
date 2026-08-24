<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 044 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 044

### Press the source's defining form into one restrained field of pure gold

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D7AE42?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-183A3E?style=flat-square)](#)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> THIN GOLD · FRONTAL PLANE · SOURCE-DARK GROUND · HAMMERED TRACE · QUIET ORDER

The decisive source silhouette is laid directly on a dark plane in real thin gold—foil, hammered sheet, pressed metal, or shallow cast material—with soft sheen, marks, folds, edge lift, and selective breaks.

## Why this Skill exists

The style is source-dependent, not a decorative preset. Its operative transformation is:

```text
lock decisive silhouette and structure → preserve three cues → flatten volume into one thin gold material image → choose a source-related deep pure ground → distribute soft metallic reflection through hammering, embossing, folds, edge lift, and foil breaks → photograph frontally without distortion → integrate copy as pressed or low-contrast material detail
```

If an unrelated photograph could replace the source without materially changing recognition, construction, placement, material, colour, whitespace, and copy, the result does not belong to this Panel.

## The visual contract

- Preserve at least three cues across contour, proportion, pose, direction, action, opening, structural turn, or relation.
- Use a thin, planar material logic: gold foil, hammered sheet, pressed metal, or shallow cast layer lies on the surface; it is never a freestanding 3D sculpture or heavy gold block.
- Render high-purity gold with refined matte-to-soft sheen, gentle reflection, small hammer marks, embossing, edge undulation, folds, shallow relief, and selective foil breaks.
- Use a perfectly frontal, level camera and a deep, clean, restrained source-related ground with large quiet space and no perspective distortion.
- Keep one gold subject as the sole focus; reflection follows real material relief without mirror glare, vulgar yellow, or luxury-advertising drama.

Complete aesthetic constraints and rejection rules live in the Skill and production prompts. They preserve the original brief without turning its historical 3:4 canvas into a hidden default. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-044-prompt.en.md)

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091168463775736248) · 22 August 2026<br>
> GPT2 × gold leaf × reinterpretation × aesthetic prompt × VOL.044

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091168463775736248"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 044 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091168463775736248"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 044 sample 2"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091168463775736248">View the original post and full prompt →</a></p>

These samples demonstrate the 044 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 044 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 044 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 044 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy and locale

Automatic copy, exact custom copy, or text-free output is confirmed before generation. Copy follows the intended audience rather than the command language, and exact user wording remains verbatim.

Project-specific copy rule: Use one extremely short subject, action, emotion, or metaphor title and only necessary microcopy. Integrate native type as fine metal embossing, shallow relief, edge-aligned marking, or low-contrast print belonging to the same plane.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Selectable controls and inline parameters

When the host provides genuine interactive controls, the Skill prefers card-style selection: output modes and ordinary output sizes are multi-select, while copy mode and wallpaper relationship are single-select. Size choices include auto-fit, source aspect, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, and custom ratios or pixels. Without an interactive control, it falls back to a clear multiline numbered menu rather than showing fake checkboxes.

Every setting can also be supplied as an inline variable:

```text
/xxd-panel-044 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text auto --locale ja-JP
```

Supported parameters include `--mode`, repeatable or comma-separated `--size`, `--text auto|custom|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, and `--out`. Complete parameters skip all preflight questions; partial parameters trigger only the missing questions. Different aspect ratios are independently recomposed, and the four-device wallpaper pack remains a separate branch rather than being multiplied by ordinary sizes.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-044.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-044" ~/.codex/skills/xxd-panel-044
```

Claude Code users may link the same folder under `~/.claude/skills/xxd-panel-044`. Restart the agent session after installation.

```text
$xxd-panel-044
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

Full specifications: [Skill workflow](SKILL.md) · [source archive](references/044-source.md) · [English prompt](references/xxd-panel-044-prompt.en.md) · [Chinese prompt](references/xxd-panel-044-prompt.zh-CN.md)

## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

### In-depth consultation · CNY 299/hour

One-to-one in-depth consultation for using Skills. Contact Xiaoxiaodong through WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills User Community · CNY 99

A one-time fee joins the Skills user community for workflow sharing and peer discussion; hourly consultation is separate.

### Knowledge Planet + Member Prompt Library · CNY 699/year

One annual payment opens both Knowledge Planet and the member prompt library. Join either side, then contact Xiaoxiaodong on WeChat for the other access.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>Gold becomes meaningful when it preserves form instead of performing wealth.</strong></div>

---

<div align="center">

## Support this open-source project

Chinese-language support may use Xiaoxiaodong's own WeChat or Alipay reward codes; other editions use Buy Me a Coffee. Support is optional and never changes access to the open-source project.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
