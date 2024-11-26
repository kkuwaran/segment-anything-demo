# Basic SAM Usage (segment-anything-demo)
A repository demonstrating basic usage of Meta's [Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything) for image segmentation.

## Features
- Load model checkpoints (`vit_h`, `vit_l`, or `vit_b`) from SAM.
- Use the code from the official implementation.
- Segment images stored in the `input_imgs` folder.
- Example workflow provided in `main.ipynb`.

## Requirements
- Python 3.8+
- PyTorch
- Additional dependencies listed in the [SAM GitHub page](https://github.com/facebookresearch/segment-anything).

## Usage
1. **Install the Segment Anything Model (SAM) package via pip from the GitHub repository.**
   ```bash
   pip install git+https://github.com/facebookresearch/segment-anything.git
   ```
   
2. **Download model checkpoints:**

   Download the pre-trained model checkpoints (`vit_h`, `vit_l`, or `vit_b`) from the [Model Checkpoints section](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file#model-checkpoints) and place them in a folder named `models`.
   
3. **Prepare images:**

   Place the images to be segmented in a folder named `input_imgs`.

4. **Run the notebook:**
   
   Use `main.ipynb` to:
   * Load images from `input_imgs` (ensure you specify the correct image name and model name in the notebook).
   * Apply the segmentation model using the specified checkpoint.
   * Visualize the results.
