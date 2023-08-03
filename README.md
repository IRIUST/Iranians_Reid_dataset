# IRIUST Dataset

This dataset is being completed...

### About dataset

The IRIUST dataset is different from the international datasets and has been prepared according to the culture and environment of Iran. Also, it has been tried to record raw dataset movies from places and conditions that maintain a range of challenges (quality of movies, amount of light, diversity, etc. ) in the dataset. Field-of-view overlap exists among different cameras. Therefore, this dataset can be a good representative of the real world dataset.
These videos were recorded by cameras with different resolution quality in places such as Iran University of Science and Technology, Al-Aima Mosque, Arbaeen procession, local fruit shop and supermarket in Tehran, the details of which are given separately in the table below.

| Location  | Cameras | Total hours | Resolution |Num of day|
| ------  | :---:  | :---:  | :---:  | :---:  |
| Iran University of Science and Technology  | 17 | 383 h| Variable| 5|
| Al-Aima Mosque | 5 | 40 h| 960×1080 | 2|
| local fruit shop | 7 | 38 h | 944×1080 | 1 |
| local supermarket | 6 | 124 h | 1280×1944  | 4 |
| Arbaeen procession | 2 | 3 h | 1280×720 | 5 |

Currently, more than 270,000 frames containing 32,668 annotated border boxes with 1501 identities have been annotated among the prepared raw videos. The IRIUST dataset has three salient features:

First, it uses the YOLO model trained on the COCO dataset as a pedestrian detector.
Second, it uses the ByteTrack model trained on the Crowd HumanN dataset as pedestrian tracking.
Third, because the above artificial intelligence models may not have sufficient efficiency (such as not detection when entering and leaving the camera range, not detection veiled people, not detection pedestrians' equipment, or ID Switching, etc.), human annotators modify the annotations made so that the least possible bugs occur in the training of the models in terms of the dataset.

### Download dataset
The dataset package is can be downloaded from any of the following links:

[Link 1] (Google Drive)

### Bboxes naming convention
In bbox "D1_F29115_ID5.jpg", "D1" is the name of the first camera.

"F29115" is the 29115th frame in camera "D1".

"ID5" is the name of the 5th identity in synchronized cameras.
