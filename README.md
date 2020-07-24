# coral_edgetpuvision

These files are originally from below address in Coral.

`
/usr/lib/python3/dist-packages/edgetpuvision
`

I only changed detect.py file from default files; other files are not different from default files.

In detect.py, I changed the default code to use 2 Neural networks.
First NN detects face and it uses "mobilenet_ssd_v2_face_quant_postprocess_edgetpu.tflite" (Locate this file in ~/demo_files)
Second NN determines whether detected face is wearing a mask or not. It uses "mask_detector_quant_edgetpu.tflite" (Locate this file in ~/demo_files)

Please note that the program is still not very stable.
