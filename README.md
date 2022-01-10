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
 
 
 ## EDA
 
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

![image](https://user-images.githubusercontent.com/79603572/148829759-9ac6a400-4297-40f5-a420-cb43c7d101cd.png)
![image](https://user-images.githubusercontent.com/79603572/148829795-6e159f6b-919e-4b0d-a8bd-4265c2f6821a.png)

There are 4 different wilderness areas in the dataset, lets check out how many trees are in each one.

![image](https://user-images.githubusercontent.com/79603572/148829908-a46a2b14-9d17-40d1-805c-9c740c4cb570.png)


## Model

For this project, I have chosen to use a Sequential Neural Network, trained on 75% of the data and results tested on the remaining 25%. <br>


Below you can find the Neural Network Architecture of the model, the model was configured with an Adam optimizer with a learning rate of .0001

![image](https://user-images.githubusercontent.com/79603572/148830240-eee43edd-4fb1-4b02-bba2-627f5d02d19f.png)

# Results

On the test set, the model returned an accuracy of 85%, the confusion matrix below shows the model's predictions for each class as long with their true values.

![image](https://user-images.githubusercontent.com/79603572/148831706-d8ee0ee4-7f5d-4353-8cb1-127436606993.png)



