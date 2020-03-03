use docker image from https://www.chiefdelphi.com/t/team-100-power-cell-detection-with-deep-learning/378057

https://hub.docker.com/r/akrantz/powercell-detection

use this command to create output_tfilte_graph_edgetpu.tflite:
edgetpu_compiler output_tflite_graph.tflite

rename output_tflite_graph_edgetpu.tflite model.tflite

upload to rpi with wpilib image
