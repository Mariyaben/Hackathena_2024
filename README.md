# Drive.AI
AI Powered Driving Learning Assistance

Object Detection and Analysis Features
  1. Detecting and analyzing pedestrians crossing.
  Identifying vehicles such as cars, motorcycles, and trucks in the  nearest proximity.
Recognizing animals crossing the road we used Roboflow 

 2. Utilization of Yolo Model specifically YoloV5
  Leveraging the Yolo (You Only Look Once) model for object detection and classification.
          JSON output containing detected objects and their classifications on the road.

3. Response Generation using OpenAI's API
  Parsing the JSON output to extract relevant information about detected objects.
    Utilizing OpenAI's API to generate responses based on the detected objects.
    Providing class entity and prompt to OpenAI's API for instruction generation.
4. Integration with Google's Text to Speech
Employing Google's Text to Speech technology to convert generated responses into live voice instructions.
Delivering real-time voice instructions to the driver based on the detected objects and their classifications.
