# Lab 7 – Neural Style Transfer using VGG19

## Objective
To implement Neural Style Transfer (NST) using a pretrained CNN and generate a stylized image by combining:

- Content of one image
- Style of another image

The final image preserves the structure of the content image while applying the artistic style of the style image.

---

## Concept

Neural Style Transfer is a deep learning technique that separates and recombines the content and style of images.

- Content Image → provides the structure and objects
- Style Image → provides colors, textures, and artistic patterns

A pretrained VGG19 model extracts features from both images and optimizes a new image using loss functions.

---

## Tools and Libraries

- Python
- PyTorch
- Torchvision
- Matplotlib
- Google Colab

---

## Steps Performed

1. Import required libraries
2. Load content and style images
3. Load pretrained VGG19 model
4. Freeze model weights
5. Extract content and style features
6. Compute Gram Matrix for style representation
7. Define loss functions:
   - Content Loss
   - Style Loss
   - Total Loss
8. Optimize the target image
9. Generate the final stylized image

---

## Expected Output

The generated image should:

- Preserve the structure of the content image
- Transfer the texture and colors of the style image
- Produce an artistic appearance similar to the style image

---

## How to Run

1. Open the notebook in Google Colab
2. Upload two images:
   - `content.jpg`
   - `style.jpg`
3. Run all the cells
4. The stylized image will be generated at the end

---

## Learning Outcome

After completing this lab, students will understand:

- Feature extraction using CNN
- Difference between content and style representations
- Use of Gram Matrix in style extraction
- Image optimization using neural networks

---

