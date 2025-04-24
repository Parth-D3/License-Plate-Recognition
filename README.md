# License-Plate-Recognition
Programs for license plate number extraction and reading using computer vision

### Approach 1 - Using Contour Detection

This approach uses contour detection to detect the number plate. After identifying the number plate, TesseractOCr is used to extract numbers from the number plate region.

***Advantages***
<ul>
  <li>Light-Weight</li>
  <li>Efficient</li>
  <li>No training data required</li>
</ul>

***Disadvantages***
<ul>
  <li>Not accurate in noisy inputs</li>
  <li>Does not work if image is tilted i.e only works on perfectly straight images</li>
  <li>Better apprroaches using deep learning or CNNs are available</li>
</ul>
