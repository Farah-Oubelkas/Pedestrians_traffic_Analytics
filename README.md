# Pedestrians_traffic_Analytics

![Pedestrians](https://raw.githubusercontent.com/Starofall/CrowdNav/master/Image1.jpg)


### Description
Future vehicle systems for active pedestrian safety will not only require a high recognition performance but also an accurate analysis of the developing traffic situation.
In this project, we worked on Pedestrian Path Prediction.

### Minimal Setup
* Download the Pedestrians_traffic_Analytics code
* Run `python setup.py install` to download all dependencies 
* Install [SUMO](http://sumo.dlr.de) & set env var SUMO_HOME
   1. Download SUMO from http://prdownloads.sourceforge.net/sumo/sumo-src-0.32.0.zip?download
   2. Extract and note the full path to the directory
   3. Set SUMO_HOME to point to this directory
* Install [Kafka]
* Create a topic "farah" 
*run Zookeeper, Then Kafka 
*run a consumer of the topic farah
* Run `python run.py`


### Notes

* The prediction part is in 'Pedestrian_path_predictor.ipynb'. 