# Denoising Diffusion Probabilistic Model
coded by: Youngmin Ryou
## How to use
### Training
1. open [team 25]ddpm.ipynb
2. mount google drive and write proper root directory
3. go to the cell after 'Training setting'
4. depending on whether you want to use adaptive loss or not, choose proper diffuser model declaration.
5. depending on wheter you want to use adaptive loss or not, input proper arguments to the trainer function.
6. Train
7. After train,  you can do sampling & FID, IS evaluation in the same notebook.
8. write proper result dir in the cell after 'Trained result & sampling'
9.  Run all cells after, then you will get 10240 sampled images and the final cell will report computed FID and IS values.

## ddpm_for_sampling.ipynb
This notebook is for generating progressive generation figures and create generated samples from learned model.

1. mount google drive and write proper root directory
2. set the result_dir to the directory where the model parameter which you want to generate samples from exists.
3. goto diffuser model declaration part and choose whether you will use model with adaptive loss or not.
4. generate progressive images and samples. you will get 10240 generation samples by default.

## result_analysis.ipynb
1. setup proper directories. 
2. set gen_img_dir to the directory where generated samples exists.
3. run and get FID, IS
   
## Pretrained data
you can download here

https://drive.google.com/drive/folders/1NlzJbFREUa8KiDxfTe4Xo90F_Njw5H2i?usp=share_link