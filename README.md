# Yolov5 models from ultralytics yolov5 that work on coral edgetpu with all 81 classes.


I made this repository because i spent too much time changing ultralytics, tensorflow and edgetpu_compiler versions to try to get the yolov5 export for coral edge tpu to work. The problem was version inconsistencies (latest versions of tensorflow will NOT work for some reason) and edgetpu_compiler being hardcoded without the experimental -a flag (map all to coral). It is not the case that you can only detect a few classes on coral edgetpu, as you will see with these models, and you will also not get the pesky libusb error.
