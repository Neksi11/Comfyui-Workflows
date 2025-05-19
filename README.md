# Comfyui-Workflows
💍 ComfyUI Dual-Image Jewelry Fusion Workflow  Short Description (for GitHub subtitle): A ComfyUI visual pipeline for merging model and product shots using CLIP Vision, ControlNet, and mask guidance — ideal for photorealistic jewelry and fashion composites.

🚀 How It Works

💡 Component 1: Model (e.g. a woman wearing earrings or rings)
💡 Component 2: Jewelry object (isolated ring/earring)
✨ Merged Output: Photorealistic mockup of product on the person

⚙️ Tools Used:

CLIP Vision (for embedding understanding of components)
ControlNet (for spatial guidance)
Masking (via SAM or external/manual mask)
Image combiners & prompt conditioning

📚 how_to_run.md

💪 Requirements:
ComfyUI
ControlNet extension (enabled)
CLIP Vision support (usually built-in)
SAM/MANUAL Mask support if using mask guidance

✅ Steps:

Download this repo or folder contents
Open ComfyUI locally
Click Load → select dual_component_merge.json from workflows/
Drag and drop your own images (model photo and jewelry product)
Modify prompt conditioning if needed (optional)
Click Queue Prompt → Enjoy result!

Tips:

Use high-resolution PNGs for cleaner output
The better the segmentation/masking, the more realistic the final output
Avoid overly reflective jewelry for first tests

💼 Licensing
This repository and workflow are licensed under MIT License — free to use, remix, or adapt with credit. No pretrained models are included here. You must use your own .safetensors or .gguf model weights.
