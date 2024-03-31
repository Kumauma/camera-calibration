# Camera Calibration Program
A program that performs simple camera calibration and lens distortion correction

## How to Use
* <h4>Camera Calibration</h4>
    Change the name of the input_file variable in the main code part to the name of the chessboard video in the same directory as the file, put the number of nodes on the chessboard in the board_pattern variable (horizontal , vertical) and execute it.
    <br><br>During execution, you can visually check whether the chessboard is being recognized correctly by pressing the SPACE key.
    <br>In an image where you can see the intersections of the chessboard, press Enter to select that image. The selected image will be used in the camera calibration process.
    <br><br>Once you have selected a sufficient number of images, press the ESC key to exit the image selection.
* <h4>Distortion Correction</h4>
    After the camera calibration is completed, a guide appears in the console window and when the Enter key is pressed accordingly, lens distortion correction is performed according to the previous result value.
    <br><br>You can pause by pressing the Space key, and you can compare it with the original image through the Tab key.

## Recommendation
Please take at least 10 images for accurate result values and lens distortion correction.

## Execution Results
fx = 976.37275504
<br>fy = 990.95638403
<br>cx = 940.47875902
<br>cy = 525.37448011
<br>rmse = 0.7333029907973493

* <h4>Before correcting lens distortion</h4>
![image](https://github.com/Kumauma/camera-calibration/assets/51203951/e93fd2e3-dd24-41a6-ad38-a20cc33c0492)
<br>
* <h4>After correcting lens distortion</h4>
![image](https://github.com/Kumauma/camera-calibration/assets/51203951/a1680879-fe3a-4aa4-9670-bc930a289744)
