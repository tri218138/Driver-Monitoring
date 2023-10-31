```
set SNAPSHOT "hopenet_alpha1.pkl"
set FACE_MODEL "mmod_human_face_detector.dat"
set VIDEO_DOWNLOADED_PATH "data/Conan Drives With Tom Cruise  CONAN on TBS.mp4"

# Run
python deep-head-pose/code/test_on_video_dlib.py --snapshot $SNAPSHOT --video $VIDEO_DOWNLOADED_PATH  --face_model $FACE_MODEL  --n_frames 2000 --fps 20
```
