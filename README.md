### Setup repository and conda environment

```
conda env create -f environment.yaml
conda activate animatediff
```

### Download Stable Diffusion V1.5

```
git lfs install
git clone https://huggingface.co/runwayml/stable-diffusion-v1-5 models/StableDiffusion/
```

### Training
To train cf attention layers
```
bash train.sh
```