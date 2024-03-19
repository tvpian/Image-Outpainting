# Image_Outpainting

# Implicit-Neural-Representations

### Implemented a simple feedforward network to compress the image 
### Initial model Results:-
- Reported PSNR 27.7
- Ground truth(left image) with the reconstruction image (right):-
<p align="center">

<img  alt="simple_model"  src="results/og_output.png"  width="100%" />
</p>


### Outpainted Image (20 pixels)
<p align="center">

<img  alt="outpainted"  src="results/outpainting.png"  width="50%" />

</p>


### Improved model by using positional encoding
-  Reported PSNR 29.2 and better reconstruction
- Comparison of initial and Improved model with each other and ground truth:-
<p align="center">
<img  alt="comparison"  src="results/modified_output.png"  width="100%" />

</p>


## References :-
- [Fourier Features Let Networks Learn
High Frequency Functions in Low Dimensional Domains](https://arxiv.org/pdf/2006.10739.pdf)
