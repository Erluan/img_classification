# img_classification

Create a "img" folder.

Add two or more folders with pictures (objects, animals, flowers, people) in the "img" folder to make a "retrain", classifying the imgs. After the "retrain" is done, execute the Training Test to classify your sample.

Inside training_test.py, change the path in the tf.gfile.GFile("path/to/folder/retrained_labels.txt")] to get the correct "retrained_label.txt"

Inside training_test.py, change the path in the tf.gfile.FastGFile("path/to/folder/retrained_graph.pb", 'rb') to get the correct "retrained_graph.pg"

