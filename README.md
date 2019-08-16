# Video_feature_extraction

function is_person_in_video(video_path, image_path): 
- takes as an input: path to a video (local file on disk) and path to an image (a portrait of a celebrity, for example)
- outputs whether the person is in this video

Remarks: 
1) In case of finding celebrities in videos, the image_path can be replaced by a string (by using the celebrity image database)
2) it's possible to output the video, where the person's face will be identified with a bounding box


| Feature | Details |
| --- | --- |
| N_faces | Number of faces in video |
| Face_size | Size of the face relative to the frame size |
| Face_emotion | Facial expressions (anger, satisfaction, happiness, etc.) |
| Celebrity_face | Name of celebrity detected in a video |
