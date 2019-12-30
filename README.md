# A C++ Tool for Face Data Generation

![Github](https://img.shields.io/badge/FACE-v1.0-green.svg?style=for-the-badge&logo=data:image/png)
![Github](https://img.shields.io/badge/C++-11-green.svg?style=for-the-badge&logo=python)
![Github](https://img.shields.io/badge/status-Begin-blue.svg?style=for-the-badge&logo=fire)

![Teaser image](img/example.png)
Picture: This is an example of face data generation results. This tool can separate the image into shading, albedo, and normal.

## Notice
@date: 2019.12.13

## Using 
``` python
# ① Put face image and pre-estimated key points into an input folder. Please make the name of picture and text files as image.png, kpt.txt.

# ② Go into the Release_v1.0 folder and run face_data_generation.exe in powershell.
face_data_generation.exe -i=".\\input\\1" -o=".\\output"
# Please make sure that the input folder `.\\input\\1` have the face image `image.png` and 2d key points `kpt.txt`.

# ③ The output data will be generated in the output folder which set by `-o=.\\output`. 
```

## Project
> We follow the traditional shape from shading methods and if you find any bug or mistake in implementation,
> please let me know and improve it, thank u very much! 

#### Unfinished
* Inference code.

## Related

## System Requirements
- Windows10
- C++ 11

## Q&A

## Acknowledgements
The result of shape from shading  is highly dependent on the texture changes caused by lighting. So it will have poor performance under a uniform light.

My Email is **zhuyongjie@bupt.edu.cn**, if you want to discuss face related knowledge with me, please contact me. 
