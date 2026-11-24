# YOLOv8 Pose Person Tracking

Final project for DSAI 352. A notebook that detects and tracks people in video with YOLOv8x-pose and draws their movement routes.

## What it does
- Runs yolov8x-pose.pt on each frame to detect people.
- Keeps a track for each person and draws their route with a distinct colour (draw_routes, get_distinct_colors).
- Predicts the next position from the average of the last 3 velocities (predict_next_position).
- track_and_draw(input_path, output_path, track_multiple=False, conf_threshold=0.7) writes an annotated output video.

## Run
Open AhmedSameh_202201124_DSAI352_FinalProject.ipynb in Jupyter or Colab, set the input and output video paths, and run all cells.

## Requirements
Python, ultralytics, OpenCV, NumPy.
