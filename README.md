# arm-curl-counter

Detects bicep curls and stretch for both the right arm and left arm.
Using positions of shoulder, elbow, wrist, their relative positions are used to calculate the angle at 
the ankle as the pivot, and the vector dot product formula cos theta = (a . b)/(|a||b|).
If the angle surpasses a large threshold a stretch is counted, and if surpasses an acute angle threshold, a flex is counted.

Use with webcam, though lighting can affect accuracy of detection.
