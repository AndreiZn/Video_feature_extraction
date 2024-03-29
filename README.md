# Video_feature_extraction

| Feature | Details |
| --- | --- |
| N_faces | Number of faces in video |
| Face_size | Size of the face relative to the frame size |
| Face_emotion | Facial expressions (anger, satisfaction, happiness, etc.) |
| Celebrity_face | Name of a celebrity detected in a video |
| Face_attractiveness | Appeal of person's mimic, its naturalness |
| Posture | Person's posture -> coordinates of joints + naturalness of posture |
| Person_movement| How a person moves in a snippet - sits down/stands up/falls on the ground/jumps to the hill |
| Costume | Characters' costumes, their attributes etc. |
| Video_composition | Type of video composition (landscape, urban, rural, portrait) |
| Weather_conditions | Type of weather (good/bad + time of the season + light conditions) |
| Main_object | The object in the center of attention (a car, a person, a building, etc.) -> string (type of object) + coordinates (bounding box)|
| Main_object_movement | Where the main object moves to, its speed, direction, whether the direction is consistent over the frames and so on |
| Action_type | Type of action (fight, race, dialog, etc)
| Brand_logo | A logo of some world-famous brand (Coca-cola, BMW, etc.) -> string (brand name) + coordinates (bounding box)| 


function is_person_in_video(video_path, image_path): 
- takes as an input: path to a video (local file on disk) and path to an image (a portrait of a celebrity, for example)
- outputs whether the person is in this video

Remarks: 
1) In case of finding celebrities in videos, the image_path can be replaced by a string (by using the celebrity image database)
2) it's possible to output the video, where the person's face will be identified with a bounding box



