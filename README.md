# Trajektorien-Extraktion-aus-Drohnenvideos
Based on the drone detection road section video, the actual size of different car models and the size change pattern when turning are calculated.
The video was taken with 29.97 fps.  The csv contains the following information:
Frame and object_id is clear I guess, pos_x and pos_y refer to the pixel coordinate, length_px and width_px are the values in pixels as detected in the video. Category_id belongs to the road user type (0 is car, etc.), conf is the detection confidence – these two values are more or less irrelevant for you.
Position_x and position_y refer to the global position of the center point in EPSG 4647. Bbox_x_start belongs to the left bounding box edge coordinate, ccox_x_end to the right; bbox_y_start to the top and bbox_y_end to the bottom edge of the bounding box in pixel coordinates. And finally bbox_length_m and bbox_width_m belongs to the transformed bounding box values to m, i.e. the real world distances.
the link of he video and relevant dataset:https://drive.google.com/drive/folders/1fI1z5qSizS5oIDfceKSwNb0eI3d9D3Wn?usp=sharing
