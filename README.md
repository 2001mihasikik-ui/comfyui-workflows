# ComfyUI Workflows

This repository contains several ComfyUI workflows for architectural image generation, controlled editing, and iterative refinement.

## Included workflows

### 1. Fast Architecture Generation
Text-to-image workflow for generating architectural concepts and early-stage visual directions.

### 2. Reference Guided Generation
Workflow using reference images and ControlNet-based guidance for more controlled composition and scene development.

### 3. Inpainting Refinement
Mask-based workflow for correcting local areas, refining geometry, and improving selected parts of the image.

## Tools and methods used

- ComfyUI
- Stable Diffusion
- ControlNet
- Inpainting
- Upscaling
- Prompt-based iterative refinement

## Repository structure

- [Workflows](./workflows) — exported ComfyUI JSON workflows
- `examples/` — generated output examples
- `screenshots/` — screenshots of node-based workflow setups

## Notes

These workflows were created for practical visual tasks, including architecture-oriented concept generation, controlled scene editing, and local image refinement.
