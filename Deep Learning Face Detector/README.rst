
Face Detection with OpenCV and Deep Learning
============================================

Usage
~~~~~

.. code-block:: bash

	# Image Input
	python face_detector.py --image <path/to/image/file> --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
	
	# Video Input
	python face_detector.py --video <path/to/video/file> --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

	# Webcam
	python face_detector.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel


