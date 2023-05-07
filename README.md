# Medical Shap-E
This repository contains an implementation of [Shap·E](https://github.com/openai/shap-e), a powerful tool for generating 3D assets using implicit functions, based on the work by OpenAI. Shap·E is a conditional generative model that creates textured meshes and neural radiance fields, offering an efficient and user-friendly way to generate high-quality 3D models for various applications. Additionally, this implementation includes code for converting `PLY` files into `STL` format.
Official paper can be found [here](https://arxiv.org/abs/2305.02463).

![_A human liver](https://user-images.githubusercontent.com/37108394/236678466-d7d8a63d-5288-49d9-922a-2626ab523119.png)

## Installations
To run the code in colab, you will need to install, clip (by OpenAI), blobfile and trimesh (for PLY-STL conversion).

```
pip install blobfile
pip install trimesh
pip install git+https://github.com/openai/CLIP.git
```

## ✍️ Blog Post
For a more detailed explanation of the process, please refer to our [blog post](https://pycad.co/medical-shap-e/).

## 📩 Newsletter
Don't miss out on the latest news and trends in medical imaging. Subscribe to our newsletter at [pycad.co/join-us](https://pycad.co/join-us/) to stay informed.
