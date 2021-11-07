# An-Automated-System-for-Sorting-Tomatoes
AI based Computer Vision-Automation

The idea of this research is to design a machine vision-image processing based sorting system with the goal of sorting vegetables, particularly tomatoes, depending on attributes such as fresh and rotten, to suit customer requests. 

The algorithms used are Resion of Interest (ROI) and Scale Invariant Feature Transform (SIFT) to detect the cracks and shrinkages in it. 

The system comprises a conveying unit, illumination and capturing unit, and a sorting unit. Physical and mechanical features were extracted from the samples provided, and the detection algorithm via Matlab by image processing was designed accordingly. To recognise tomatoes, a color-based index was created. They were then fed in a row on a conveyor belt. When they arrive at the middle of the camera's field of view, using a sensor, the tomatoes are made to stop and a picture is taken. The image will be immediately analysed by Matlab through Raspberrypi, and the tomato's quality is verified. When the tomato passes, a signal was transmitted to the interface circuit, and an appropriate actuator located at the end of the conveyor belt and powered by a step motor was activated, directing the tomato to an appropriate collection point. As a result, the rotting tomatoes are distinguished from the fresh ones. 
