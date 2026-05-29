# GenClaw: Code-Driven Agentic Image Generation

[![Paper](https://img.shields.io/badge/Paper-Hugging%20Face-yellow)](https://huggingface.co/papers/2605.30248)
[![arXiv](https://img.shields.io/badge/arXiv-2605.30248-b31b1b)](https://arxiv.org/abs/2605.30248)
[![GitHub stars](https://img.shields.io/github/stars/yejy53/GenClaw?style=social)](https://github.com/yejy53/GenClaw)

GenClaw explores **code-driven agentic image generation**: instead of only rewriting prompts, an image generation agent uses code as a controllable visual canvas before calling image generation models for final rendering.

The core idea is simple: **think, sketch with code, then render**.

<p align="center">
  <img src="assets/teaser.jpg" width="95%">
</p>

## Highlights

🎨 **Code as a Visual Brush.** The agent creates by writing executable visual sketches—SVG, HTML/CSS, Python, lightweight 3D code—turning object count, spatial layout, and text rendering into executable, verifiable, debuggable programs. Image synthesis shifts from implicit diffusion sampling to an explicit, reasoning-friendly process.

✋ **Draw as a Human Artist.** We mirror the human creative loop—conceptualize → sketch → coloring → refine—and make every stage transparent: ideation, reference retrieval, drafting, and incremental rendering are all surfaced as inspectable, editable, revertible artifacts. Generation becomes an iterative collaboration rather than one-shot black-box inference.

🔌 **Agent Harness for Image Generation.** We plug an LLM agent's proven planning, tool-use, and reflection abilities directly into image synthesis, exploring an agent harness for image generation—so that creating images becomes a first-class capability inside the agent's toolbox, not an isolated standalone model.

## Showcase

<p align="center">
  <img src="assets/showcase.jpg" width="95%">
</p>

## Visual Examples

### Complex Scene Composition

<p align="center">
  <img src="assets/complex_scene.jpg" width="95%">
</p>

### Text Rendering and Poster Design

<p align="center">
  <img src="assets/text_rendering.jpg" width="95%">
</p>

### Physical Reasoning

<p align="center">
  <img src="assets/physical_reasoning.jpg" width="95%">
</p>

### Knowledge-Grounded Generation

<p align="center">
  <img src="assets/mind_bench.jpg" width="95%">
</p>

## Status

The technical report is available now. Code and demos are being prepared and will be released later.

## Links

- Paper: https://huggingface.co/papers/2605.30248
- arXiv: https://arxiv.org/abs/2605.30248
- Repository: https://github.com/yejy53/GenClaw

If you find this project interesting, please consider giving it a star and voting for the paper on Hugging Face.

## Citation

If you find GenClaw useful, please consider citing our technical report:

```bibtex
@article{ye2026genclaw,
  title={GenClaw: Code-Driven Agentic Image Generation},
  author={Ye, Junyan and others},
  journal={arXiv preprint arXiv:2605.30248},
  year={2026}
}
```
