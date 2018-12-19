# Histopathologic cancer detection
Identifying metastatic cancer using machine learning

## This time we go full medical
- Our task: find malign tumor tissues in *a lot* of images
- Approach: 
  - Create a neural network model (obviously)
  - Try different 'cells' to get peak performance from it
  
### Data
#### We have over 6GB of images provided at a 96x96 size
![](https://raw.githubusercontent.com/martzdev/histopathologic-cancer-detection/master/images/clean.png) <br>- Clean patch <br>
![](https://raw.githubusercontent.com/martzdev/histopathologic-cancer-detection/master/images/malign.png) <br>- Malign patch
<br>
#### In this example you can easily 'predict' the malign one.

### Models
