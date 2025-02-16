# test 2

## UMAFall

### 2.1 UMAFall diffusionAD (not DDPM)

|       | Box Plot | Reconstruction Error | Performance |
|-------|----------|---------------------|-------|
| sub18-only | ![alt text](image.png) | ![alt text](image-1.png) | ![alt text](image-2.png) | 
| all subjects | ![alt text](image-3.png) | ![alt text](image-4.png) | ![alt text](image-5.png) | 

### 2.2 UMAFall DDPM using UNet (difference by timestep)

|       | Box Plot | Reconstruction Error | Performance |
|-------|----------|---------------------|-------|
| sub18-only (100) | ![alt text](image-6.png) | ![alt text](image-7.png) | ![alt text](image-8.png) | 
| sub18-only (1000) | ![alt text](image-9.png) | ![alt text](image-10.png) | ![alt text](image-11.png) | 

### 2.3 UMAFall DDPM using CNN encoder -> PCA -> TransUNet (difference by timestep)

|       | Box Plot | Reconstruction Error | Performance |
|-------|----------|---------------------|-------|
| sub18-only (100) | ![alt text](image-30.png) | ![alt text](image-31.png) | ![alt text](image-32.png) | 
| sub18-only (1000) | ![alt text](image-33.png) | ![alt text](image-34.png) | ![alt text](image-35.png) | 

----
----
---


## SisFall

### 2.3 SisFall diffusionAD (not DDPM)

|       | Box Plot | Reconstruction Error | Performance |
|-------|----------|---------------------|-------|
| SA01-only | ![alt text](image-36.png) | ![alt text](image-37.png) | ![alt text](image-38.png) | 
| all subjects | ![alt text](image-39.png) | ![alt text](image-40.png) | ![alt text](image-41.png) | 

### 2.5 (Maybe with other subject not SA01?) SisFall DDPM using UNet (difference by timestep) 

|       | Box Plot | Reconstruction Error | Performance |
|-------|----------|---------------------|-------|
| SA01 (100) | ![alt text](image-12.png) | ![alt text](image-13.png) | ![alt text](image-14.png) |
| SA01 (1000) | ![alt text](image-15.png) | ![alt text](image-16.png) | ![alt text](image-17.png) | 
| SA12 (100) | ![alt text](image-18.png) | ![alt text](image-19.png) | ![alt text](image-20.png) | 
| SA12 (1000) | ![alt text](image-21.png) | ![alt text](image-22.png) | ![alt text](image-23.png) | 

### 2.6 SisFall DDPM using CNN encoder -> PCA -> TransUNet (difference by timestep)

|       | Box Plot | Reconstruction Error | Performance |
|-------|----------|---------------------|-------|
| SA01 (100) | ![alt text](image-24.png) | ![alt text](image-25.png) |![alt text](image-26.png) |
| SA01 (1000) | ![alt text](image-27.png) | ![alt text](image-28.png) | ![alt text](image-29.png) | 