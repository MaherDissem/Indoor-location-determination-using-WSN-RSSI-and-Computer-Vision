# Indoor location determination using WSN RSSI and Computer Vision

Here, a hybrid CNN-LSTM AI model is created to localize a mobile agent within an indoor environment using the Received Signal Strength (RSS) from a set of nodes consisting a Wireless Sensor Network (WSN).

Four anchor nodes are used as beacons and one is carried by the mobile agent.

Our approach consists in transforming a WSN RSSI dataset into heatmap images (representing RSSI of the 4 beacons on a map, for each location of the mobile node) and then to apply computer vision techniques to predict the (x,y) location as an image regression problem.
