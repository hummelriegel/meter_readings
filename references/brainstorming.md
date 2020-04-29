# Brainstorming

Similar Approaches:
* https://nanonets.com/blog/deep-learning-ocr/
* https://www.pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector/

Interesting Related Topics:
- Optical Character Recognition (OCR), for example tesseract
- Deep learning frameworks, e.g. pytorch/torchvision or keras/tensorflow

Sample Procedure:
1. Select Deep Learning Framework
1. Data Augmentation, Image Cropping
1. Data Loader ("generator")
1. Model fit

Additional Procedure Ideas:
- When handling text, one would use a model for text extraction and a second model (sequence2sequence) to verify correct sentences
- Possible safetynet would be a threshold that limits higher and prohibits lower numbers with a higher date (next day(s))