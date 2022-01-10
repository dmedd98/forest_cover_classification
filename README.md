# Forest Cover Classification Project

This project involves using deep learning to predict a forest cover type based on a variety of cartographic variables. 

The covertypes are the following:

        Spruce/Fir
        Lodgepole Pine
        Ponderosa Pine
        Cottonwood/Willow
        Aspen
        Douglas-fir
        Krummholz
        
 Independent variables were then derived from data obtained from the US Geological Survey and USFS. It contains binary columns of data for qualitative independent variables such as wilderness areas and soil type as well as continious quantitative variables such as elevation, asepct and slope.
 
 
 ### EDA
 
 The Dataset contains the information of 581012 trees, the breakdown of the trees by covertypes is the following,
 
Lodgepole Pine:       283301 <br>
Spruce/Fir:      211840 <br>
Ponderosa Pine:      35754 <br>
Krummholz:     20510 <br>
Douglas-fir:    17367 <br>
Aspen:    9493 <br>
Cottonwood/Willow:   2747 <br>

![image](https://user-images.githubusercontent.com/79603572/148829356-345b924d-4640-46c4-9123-089b22e13d86.png)

I took a look at the variable Elevation in greater detail, below you can find a histogram displaying the proportion of trees at each height as well as a boxplot showing the breakdown of elevation by cover type.

![image](https://user-images.githubusercontent.com/79603572/148829614-0686d55c-ed2e-42ea-8859-2b62bda147f8.png)
![image](https://user-images.githubusercontent.com/79603572/148829628-7cd49719-bff2-4834-9e8c-f8b0fe6e93c0.png)

