# Indoor location determination using WSN RSSI and Computer Vision

Here, a hybrid CNN-LSTM agent localization in an indoor environment model based on WSN nodes' RSSI is presented.

We use four anchor nodes as beacons and one is carried by the mobile agent.

Our approach consists in transforming a WSN RSSI dataset into heatmap images (representing RSSI of the 4 beacons on a map, for each location of the mobile node) and then to apply computer vision techniques to predict the location.
