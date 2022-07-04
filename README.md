# Patch Match Stereo
Unipd, 3D data processing course, homework

The original repository is https://github.com/ibergonzani/patch-match-stereo.
In this repository, the code is a little changed, and completed by the student to understand the algorithm better

## Usage
To compile open a terminal from the parent folder of ```patchmatch``` and type the following commands in order:
```
cd patchmatch
mkdir build && cd build
cmake ..
make 
```
Download the dataset from the following link:
```
https://drive.google.com/file/d/1_YXEvGN0vBgTGij5ohSlUAP7h9GoYkzw/view
```
Execute it using:
```
./patchmatch path/to/dataset
```
where path/to/dataset is one between Aloe, Cones, Rocks1 (already provided)


## results
Here is the results of the completed code:
1) Aloe
   Left Image MSE error: 18.9002 Right Image MSE error: 30.5163
   ![Capture](https://user-images.githubusercontent.com/58342884/177178534-461b74e1-d4e0-45c0-8452-915243fab309.PNG)

2) Cones
   Left Image MSE error: 46.2973 Right Image MSE error: 37.6949
   ![Capture](https://user-images.githubusercontent.com/58342884/177178666-3e9d582f-9e0f-4cf4-bcf6-f69d680ebe88.PNG)

3) Rocks1
   Left Image MSE error: 18.9306 Right Image MSE error: 24.348
   ![Capture](https://user-images.githubusercontent.com/58342884/177178730-845b6c6b-f264-4c6f-9a3c-5a770d00dbbe.PNG)
