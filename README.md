# Haniruth Muthuselvam

**MSc Artificial Intelligence @ University of Surrey**  
Computer Vision · Weak Supervision · Visual Representation Learning · Retrieval · Vision-Language Models

I am an AI and computer vision researcher-in-training interested in building robust visual understanding systems for real-world data. My work focuses on weakly supervised learning, retrieval-based recognition, semantic prediction, and practical computer vision pipelines where labels, viewpoints, domain shifts, or privacy constraints make learning difficult.

I am especially interested in research problems around:

- Weakly supervised and label-efficient computer vision
- Vision-language models for semantic visual understanding
- Retrieval, re-identification, and representation learning
- Privacy-preserving pedestrian and autonomous-driving perception
- Geometry-aware and 3D/spatial visual understanding
- Visual analytics and interpretable AI systems

---

## Research Direction

My current research direction is centred on **visual representation learning for real-world vision systems**.

I am interested in how computer vision models can learn useful representations when supervision is weak, noisy, incomplete, or expensive to obtain. This includes problems such as detecting abnormal events from video-level labels, retrieving visually similar objects across viewpoints, preserving useful scene information while anonymising people, and using vision-language models to connect visual patterns with semantic concepts.

Long term, I want to work on computer vision systems that are not only accurate, but also interpretable, reproducible, privacy-aware, and useful in practical research or industrial settings.

---

## Selected Research Projects

### Weakly Supervised Video Anomaly Detection  
**Repository:** [Anomaly-Detection](https://github.com/haniruth/Anomaly-Detection)

A research-facing project on weakly supervised video anomaly detection using UMIL, pre-extracted I3D video features, and CLIP text embeddings.

**Focus:**

- Reproduced a UMIL baseline for weakly supervised anomaly detection.
- Adapted the pipeline to pre-extracted I3D feature sequences.
- Added a CLIP-based semantic prediction head using frozen text embeddings.
- Evaluated anomaly detection with AUC/AP and semantic prediction with mAP/top-1 accuracy.
- Documented limitations around coarse segment-level evaluation and dataset constraints.

**Why it matters:**  
This project reflects my interest in weak supervision, video understanding, semantic prediction, and research-style experimentation under realistic dataset limitations.

---

### Geometry-Aware Vehicle Re-Identification  
**Repository:** [GeoVehicle-ReID](https://github.com/haniruth/GeoVehicle-ReID)

A vehicle re-identification project on the VeRi dataset using retrieval-oriented embeddings and geometry-aware model components.

**Focus:**

- Built a ResNet-based vehicle ReID pipeline with BNNeck retrieval features.
- Used identity classification and hard triplet loss for metric learning.
- Added local part descriptors to preserve vehicle identity cues.
- Explored pseudo-depth/visibility attention for viewpoint-aware retrieval.
- Evaluated with CMC and mAP retrieval metrics.

**Why it matters:**  
This project reflects my interest in retrieval, re-identification, viewpoint variation, and representation learning for real-world visual recognition.

---

### Classical Image Retrieval on MSRC-v2  
**Repository:** [Image-Retrieval-msrcv2](https://github.com/haniruth/Image-Retrieval-msrcv2)

A classical computer vision project comparing feature descriptors and distance metrics for content-based image retrieval.

**Focus:**

- Implemented global RGB colour histograms.
- Added spatial grid descriptors and Sobel texture histograms.
- Compared Euclidean, L1, Chi-square, Bhattacharyya, and Mahalanobis distances.
- Used PCA-reduced features for retrieval experiments.
- Evaluated ranked retrieval using precision-recall curves and average precision.

**Why it matters:**  
This project demonstrates my grounding in classical computer vision, feature design, distance metrics, and retrieval evaluation before moving into deep learning-based methods.

---

### Fine-Grained Image Classification  
**Repository:** [KnifeHunter](https://github.com/haniruth/KnifeHunter)

A fine-grained image classification pipeline using PyTorch, TIMM, EfficientNet, transfer learning, and augmentation-heavy training.

**Focus:**

- Built a supervised image classification pipeline for 543 fine-grained categories.
- Used an ImageNet-pretrained EfficientNet model.
- Applied label smoothing, AdamW, cosine learning-rate scheduling, random erasing, colour jitter, rotation, and random resized crops.
- Evaluated validation performance with top-k mean average precision.

**Why it matters:**  
This project demonstrates applied deep learning ability, experiment management, model training, and evaluation on a challenging fine-grained classification task.

---

## Current Work and Research Interests

I am currently developing my research profile around the following themes:

### 1. Weakly Supervised Visual Understanding

Many real-world computer vision tasks do not have clean frame-level, pixel-level, or instance-level labels. I am interested in methods that can learn from weaker forms of supervision, such as video-level labels, image-level labels, noisy annotations, or automatically generated semantic signals.

Relevant interests:

- Multiple instance learning
- Weakly supervised video anomaly detection
- Label-efficient learning
- Semantic supervision from vision-language models
- Evaluation under noisy or incomplete labels

---

### 2. Retrieval and Representation Learning

Retrieval systems are useful because they test whether a model has learned meaningful visual representations, not just whether it can classify into a fixed label set. I am interested in retrieval, re-identification, and metric learning problems where identity, viewpoint, background, and appearance changes make recognition difficult.

Relevant interests:

- Vehicle and object re-identification
- Metric learning
- Contrastive representation learning
- Retrieval evaluation
- Viewpoint-aware visual embeddings

---

### 3. Privacy-Preserving Computer Vision

Computer vision models often rely on datasets containing people, vehicles, streets, and public environments. I am interested in privacy-preserving approaches that reduce personally identifiable information while retaining useful visual structure for downstream perception tasks.

Relevant interests:

- Pedestrian anonymisation
- Privacy-utility trade-offs
- Autonomous-driving datasets
- Segmentation and detection under anonymisation
- Pose, shape, and scene-context preservation

---

### 4. Vision-Language and Semantic Prediction

Vision-language models provide a way to connect visual features with semantic concepts. I am interested in using pretrained models such as CLIP-style encoders to support semantic prediction, open-vocabulary recognition, anomaly explanation, retrieval, and visual analytics.

Relevant interests:

- CLIP-based semantic prediction
- Open-vocabulary visual understanding
- Image-text representation learning
- Semantic anomaly categories
- Multimodal retrieval and explanation

---

### 5. 3D and Geometry-Aware Vision

I am also interested in spatial and 3D-aware visual understanding, especially where geometry can improve robustness across viewpoints, occlusions, and scene changes.

Relevant interests:

- Geometry-aware representation learning
- Viewpoint-aware retrieval
- 3D scene representation
- Neural rendering and Gaussian Splatting
- Human and object reconstruction

---

## Technical Skills

### Programming and ML Frameworks

- Python
- PyTorch
- Torchvision
- TIMM
- NumPy
- OpenCV
- scikit-learn
- Matplotlib
- Linux / WSL
- Git and GitHub

### Computer Vision and Deep Learning

- Image classification
- Image retrieval
- Video anomaly detection
- Re-identification
- Feature extraction
- Transfer learning
- Metric learning
- Data augmentation
- Precision-recall and retrieval metrics
- Weak supervision and MIL-style learning

### Research and Experimentation

- Literature review
- Baseline reproduction
- Ablation-style experimentation
- Model evaluation
- Failure-case analysis
- Technical report writing
- Reproducible repository preparation

---

## Selected Methods and Concepts I Have Worked With

- CNN-based visual representation learning
- ResNet and EfficientNet backbones
- I3D video features
- UMIL-style weakly supervised anomaly detection
- CLIP text embeddings for semantic prediction
- Hard triplet loss and identity classification
- BNNeck features for retrieval
- PCA and Mahalanobis distance
- Histogram-based image retrieval
- Precision-recall curves, mAP, CMC, AP, AUC, and top-k accuracy

---

## What I Am Looking For

I am interested in PhD and research opportunities in computer vision and artificial intelligence, especially projects involving:

- Weakly supervised or label-efficient computer vision
- Vision-language models and multimodal learning
- Retrieval, ReID, and visual representation learning
- Privacy-preserving visual perception
- 3D/spatial computer vision
- Visual analytics and interpretable AI

I am particularly interested in research where I can combine practical implementation, careful experimentation, and a strong understanding of real-world dataset limitations.

---

## Repository Philosophy

I use GitHub to present cleaned research-facing projects as reproducible public artifacts. For each major project, I aim to include:

- Clear problem statement
- Method summary
- Dataset and external asset notes
- Reproducible commands where possible
- Verified results
- Honest limitations
- Future improvement directions

Some datasets and model checkpoints are excluded from public repositories due to licensing, size, or project-release constraints.

---

## Next Research Goals

My current goals are to strengthen my research portfolio by:

- Turning selected projects into paper-style technical reports.
- Adding clearer ablation studies and failure-case analysis.
- Building small demos for retrieval, anomaly detection, and visual analytics.
- Extending my work toward privacy-preserving pedestrian analysis and vision-language-driven visual understanding.
- Developing one flagship project that is closer to publishable research quality.

---

## Contact

- **GitHub:** [github.com/haniruth](https://github.com/haniruth)
- **Email:** [haniruth04@gmail.com](mailto:haniruth04@gmail.com)
