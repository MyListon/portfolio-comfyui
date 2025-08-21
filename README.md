# 🎨 AI Portfolio with ComfyUI

This repository brings together my creative experiments using ComfyUI for image generation with Stable Diffusion.

Here you'll find both the visual results and the workflows and prompts I used in the process.  

---

## 📌 Project 1 - Surrealist Bottles

<img width="512" height="512" alt="ComfyUI_00001_" src="https://github.com/user-attachments/assets/c12ae8b6-7086-45f1-af36-6deffbaf81b2" />

✨ **Description:**
Creation of a surrealist scene, where glass bottles contain natural landscapes and vivid colors. The goal was to explore the fusion between everyday objects and fantastical environments.

🔧 **Technical Details:** 
- **Tool:** ComfyUI 
- **Template Used:** Stable Diffusion 1.5 (v1-5-pruned-emaonly.ckpt) 
- **Prompt (example):**
---

- **Configuration (log summary):** 
- CLIP/Text encoder on `torch.float16` 
- VAE on `torch.float32` 
- GPU execution (CUDA:0) 

---

## 🚀 How to reproduce this project
1. Open **ComfyUI** and load the workflow saved in `workflows/bottles.json` (or create a similar workflow).
2. Adjust `CheckpointLoaderSimple` to use a local SD 1.5 model.
3. Run and generate your own variations!

---

✨ Developed with a passion for AI and creativity.
