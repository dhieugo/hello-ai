python 2.7

Download training data from link below

http://download.tensorflow.org/example_images/flower_photos.tgz

Run retrain

python retrain.py --bottleneck_dir=tmp/bottlenecks --how_many_training_steps 500 --model_dir=tmp/inception --output_graph=output/retrained_graph.pb --output_labels=output/retrained_labels.txt --image_dir=flower_photos/