# Lab 5 test set

The leaderboard scores detections on the **val** split of the Ultralytics `brain-tumor` dataset (223 images; auto-downloaded by `YOLO(...).train(data='brain-tumor.yaml')`).
Submit a JSON list of `{image, class, conf, bbox:[x1,y1,x2,y2]}` in pixel coordinates. Metric: mAP@0.5.
