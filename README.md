# Social-distancing-detector-using-YOLO
The proposed YOLO model leads to a very accurate social distancing monitoring in challenging conditions, including partial visibility, and lighting variations.

The novel generation of the coronavirus disease (COVID-19) was reported in late
December 2019 in Wuhan, China. Due to the ongoing coronavirus pandemic, numerous lives
have been lost. The main route for the spread of this virus is airborne. The best way to stop the
spread of this virus is to wear a mask and practice social distancing. Unfortunately, many people
do not tend to take this simple government mandated guideline seriously. This results in a daily
spike in the number of cases reported. Vaccines have helped us stop the spread of this virus to
a large extent but there is no assurity that these vaccines prove effective once new variants
appear. To combat this issue we can run our algorithm on CCTVs across the nation to record the
violations of social distancing guidelines and impose a fine on violating personnels.

In the hope that this work may in some way contribute to mankind, this is dedicated to all
the human beings battling this deadly virus. Monitoring social distancing is almost impossible if
done physically and also increases the risk of catching the virus by the personnel monitoring
this. Even if monitoring is done by humans through CCTVs, identifying people violating the
guidelines will prove quite painstaking and will require a huge workforce and still prove to be
ineffective.

To solve this, I have created this monitoring system that requires no human supervision
and will work efficiently.
In the present scenario, with more things moving to the digital platform, a digital solution is the
most befitting way to overcome such a challenge and avoid physical contact. Social Distancing Monitor offers a digital approach at monitoring violations of social distancing. Yolo algorithm provides accurate and fast detection each time a safety coincidence indicator is detected, supplying extra information like depth analysis, permitting correct and dependable analysis.

WORKFLOW

Step 1: Data collection for Machine learning model (COCO Dataset). 

Step 2: Applying ML algorithm (Yolov3) and storing data.

Step 3: Computing pairwise distance between centroids of bounding boxes and their relative depths.

Step 4: Checking if euclidean distance b/w two centroids is greater than the recommended distance(120px in our case).

Step 5: Testing the model on test data 

Step 6: Test and document the final system.

Why YOLO not CNN?

Yolo algorithm is the most modern computer vision algorithm . It is based on Regression , instead of selecting the interesting part of the image it produces classes and boundary boxes for whole image in one run of the algorithm.

It is 100x faster than the CNN model and is appropriate for real time monitoring.

CNN produces more false alerts than YOLO, thus has low accuracy at higher FPS.

Another key difference is that YOLO sees the complete image at once as opposed to looking at only a generated region in CNN. This contextual information helps in avoiding false positives.

CONCLUSION

Our model successfully detected the social distancing violations in a live camera feed accurately.
Our model reported an accuracy of 94.6% at 12FPS and 88.6% at 24.1FPS which are good enough to perform real time monitoring.

![image](https://user-images.githubusercontent.com/117010199/198875351-f4eee131-75de-4b05-86d3-707ca5595456.png)
![image](https://user-images.githubusercontent.com/117010199/198875591-878858f2-c370-4764-8401-128083d68be0.png)


