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