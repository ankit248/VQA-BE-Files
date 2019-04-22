Python API and Evaluation Code for v1.0 release of the VizWiz dataset.
===================

This release of the dataset consists of
- 20,000 training image/question pairs, 3,173 validation image/question pairs, and 8,000 test image/question pairs.

## Requirements ##
- python 2.7
- scikit-image (visit [this page](http://scikit-image.org/docs/dev/install.html) for installation)
- matplotlib (visit [this page](http://matplotlib.org/users/installing.html) for installation)

## Files ##
./Images/
	VizWiz_train_000000000000.jpg
	VizWiz_train_000000000001.jpg
	VizWiz_train_000000000002.jpg
	VizWiz_train_000000000003.jpg
	...
	Total: 31173, train: 20000, test: 8000, val: 3173

./Annotations/
	train.json
	test.json
	val.json

./PythonHelperTools
- This directory contains the Python API to read and visualize the VizWiz dataset
- vqaDemo.py (demo script)
- vqaTools (API to read and visualize data)

./PythonEvaluationTools
- This directory contains the Python evaluation code
- vqaEvalDemo.py (evaluation demo script)
- vqaEvaluation (evaluation code)

./Results
- test_fake_results.json (an example of a fake results file to run the demo)

## References ##

## Developers ##
- Qing Li (sealq@outlook.com)
- Code for API is based on [MSCOCO API code](https://github.com/pdollar/coco), [MSCOCO evaluation code](https://github.com/tylin/coco-caption), and [VQA API code](https://github.com/GT-Vision-Lab/VQA).

