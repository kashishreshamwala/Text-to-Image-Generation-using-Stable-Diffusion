# 🖼️ Text-to-Image Generation Project

This notebook demonstrates how text can be turned into images using multiple generative AI techniques.  
It implements:

✅ Stable Diffusion (Hugging Face diffusers)  
✅ GAN-based Text-to-Image Simulation  
✅ Conditional GAN (CGAN) with text + label conditioning  
✅ Text preprocessing & embedding  
✅ Dataset analysis with visualizations  
✅ Gradio web interface for interactive image generation  
✅ Optional LoRA-style domain refinement simulation

---

## 🔧 Features Implemented
### ✅ 1. Stable Diffusion
- Converts natural language prompts into realistic images  
- Supports guidance scale, schedulers, seeds, image sizes
- Saves output images + metadata

### ✅ 2. GAN-based Pipeline Simulation
- Demonstrates conceptual text → embedding → generator → image pipeline
- Includes cross-attention over token embeddings

### ✅ 3. Conditional GAN (CGAN)
- Takes categories (“Circle”, “Square”, “Triangle”) as inputs
- Uses text prompts + category embeddings
- Generates colored shapes procedurally

### ✅ 4. Dataset Analysis (CIFAR-10)
- Class distribution bar plot (Matplotlib)
- Sample image grid
- Resolution statistics
- Insights included in notebook

---

##  How to Run
1. Install libraries
   ```bash
   pip install -r requirements.txt

2. Open notebook and run cells in order

3. Last cell launches Gradio UI:
   ```bash
   interface.launch(share=True)
