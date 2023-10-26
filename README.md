<!DOCTYPE html>
<html>

<head>
    <title>SamVisualizer</title>
</head>

<body>
    <h1>SamVisualizer</h1>

    <p><strong>SamVisualizer.ipynb</strong> should be placed in the <strong>segment-anything-main/notebook</strong> directory. If you want to visualize different images, please change the line: <code>image = cv2.imread('images/185.jpg')</code> to your own image.</p>

    <p>This visualization program allows you to input positive points (left-click) or negative points (right-click) or a dense mask to obtain prediction results. Note that when generating a dense mask, 8 random sample points are simultaneously generated in the mask. These random sample points are also input into the predictor, along with the 1*256*256 mask.</p>

    <p>For reference on mask input, please visit: <a href="https://github.com/facebookresearch/segment-anything/issues/169#issuecomment-1551120325">https://github.com/facebookresearch/segment-anything/issues/169#issuecomment-1551120325</a></p>

    <p><strong>Before running the notebook, make sure to install the required packages.</strong></p>

    <p>You'll also need to download the <strong>sam_vit_4b8939.pth</strong> model file and place it in the <strong>notebook</strong> folder.</p>
</body>

</html>
