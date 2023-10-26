# SamVisualizer

SamVisualizer.ipynb should be placed in the segment-anything-main/notebook directory. If you want to visualize different images, please change the line: image = cv2.imread('images/185.jpg') to your own image.

This visualization program allows you to input points or a dense mask to obtain prediction results. Note that when generating a dense mask, 8 random sample points are simultaneously generated in the mask. These random sample points are also input into the predictor, along with the 1256256 mask.

For reference on mask input, please visit: https://github.com/facebookresearch/segment-anything/issues/169#issuecomment-1551120325

Before running the notebook, make sure to install the required packages.

You'll also need to download the sam_vit_4b8939.pth model file and place it in the notebook folder.
