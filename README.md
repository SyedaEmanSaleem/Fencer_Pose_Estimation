# 🥷 Fencer Pose

**Custom YOLOv8 Pose Estimation for Fencing**

This project fine-tunes **Ultralytics YOLOv8-Pose** to detect and analyze fencing-specific elements: **fencers, sabers, and scoreboxes**. It also estimates body keypoints, enabling detailed movement tracking and performance analysis.

---

## 📌 Highlights

* 🎯 **Domain-Specific Training**: Optimized for fencing techniques and equipment.
* 🧑‍🤺 **Pose Estimation**: Tracks athlete keypoints with YOLOv8-Pose.
* ⚔️ **Multi-Class Detection**: Identifies fencers, sabers, and scoreboxes.
* 📈 **Strong Accuracy** on a custom fencing dataset.
* 🔧 **Optimized Training** with 150 epochs and tuned hyperparameters.

---

## 📊 Results

**Detection Performance (mAP50):**

* Fencer → **0.987**
* Saber → **0.712**
* Scorebox → **0.978**

**Pose Metrics:**

* Precision → **0.534**
* Recall → **0.489**
* mAP50 → **0.480**

✅ Best weights:

```
runs/pose/train2_tuned6/weights/best.pt
```

---

## 🔮 Use Cases

* Fencing technique analysis
* Athlete training support
* Sports motion research
* Performance monitoring

---

## ⚡ Tech Stack

* [Ultralytics YOLOv8](https://docs.ultralytics.com)
* Python 3.12
* PyTorch 2.8 + CUDA acceleration

---

## 🙌 Acknowledgments

* Ultralytics for YOLOv8
* Dataset manually labeled and tuned for fencing

---

🔥 **Fencer Pose applies modern computer vision to fencing — enabling smarter analysis and training.**
