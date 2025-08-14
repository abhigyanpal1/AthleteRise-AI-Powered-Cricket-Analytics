# AthleteRise – Real-Time Cover Drive Analysis 🎯

This project analyzes a cricket cover drive **from a full video** in real-time using **MediaPipe Pose**.  
It overlays **biomechanical metrics**, gives **live feedback cues**, and generates a final **multi-category evaluation**.

---

## 🚀 Features
- ✅ Full-length video analysis (`output/annotated_video.mp4`)
- ✅ Pose skeleton overlays (MediaPipe)
- ✅ Per-frame metrics:
  - Front **elbow angle**
  - **Spine lean** vs vertical
  - **Head-over-knee** alignment
  - **Front foot direction**
- ✅ Real-time feedback cues (`✅` good / `❌` needs work)
- ✅ Final evaluation (`output/evaluation.json`) with scores (1–10):
  - Footwork  
  - Head Position  
  - Swing Control  
  - Balance  
  - Follow-through
- ✅ Handles missing detections gracefully  
- ✅ Logs average FPS

---

## 📂 Repo Structure


athleterise-cover-drive/
├── cover_drive_analysis_realtime.py   # main script
├── requirements.txt                   # dependencies
├── README.md                          # documentation
├── .gitignore                         # ignore cache/files
└── output/                            # generated outputs (gitignored)
    ├── annotated_video.mp4
    └── evaluation.json

