# Video Face Detection and Recognition Pipeline
<img width="511" height="296" alt="image" src="https://github.com/user-attachments/assets/57c02b06-1f74-417c-b26b-d17b8572fcd1" />

## Project Purpose

The purpose of this project is to build a complete pipeline that processes videos by extracting frames, detecting faces, and recognizing individuals automatically. This helps to analyze video content efficiently for applications such as security, surveillance, identity verification, and video indexing.

## How the Project is Achieved

### 1. Video Acquisition
- Download a YouTube video using PyTube.
- Save the video locally in a structured directory.
- Trim the video to a relevant shorter segment using FFmpeg to reduce processing time.

### 2. Frame Extraction
- Load the trimmed video using OpenCV.
- Extract frames at regular intervals (e.g., every fifth frame) to reduce redundancy.
- Save extracted frames as individual image files in an organized folder.

### 3. Preprocessing Frames
- Resize frames to a consistent resolution.
- Normalize image data to match the input requirements of face detection models.
- Apply any necessary color space conversions for model compatibility.

### 4. Face Detection
- Apply face detection algorithms on each frame:
  - Use MTCNN for deep learning-based, high-accuracy face detection.
  - Use Haar Cascade classifiers as a classical alternative for face localization.
- Crop and save detected face regions from frames.

### 5. Face Recognition
- Extract facial embeddings using a pre-trained deep learning model (e.g., FaceNet).
- Compare embeddings against known identities or across frames for recognition.
- Use distance metrics like cosine similarity or Euclidean distance for matching.
- Set thresholds to decide recognition or unknown status.

### 6. Visualization and Analysis
- Display extracted frames and detected faces with bounding boxes.
- Annotate frames with recognized individual names or IDs.
- Provide qualitative results to validate the pipeline performance.

## Key Learnings

- Mastery of video handling: downloading, trimming, and frame extraction.
- Deep understanding of image preprocessing tailored for face analysis.
- Practical experience with face detection using both classical and deep learning methods.
- Implementation of face recognition through feature embeddings and similarity measures.
- Proficiency with libraries like OpenCV, PyTorch, PyTube, and MTCNN.
- Insights into challenges of working with video-based facial analytics such as varying frame rates, lighting, and occlusions.

## Future Applications

- Automated surveillance and security monitoring systems.
- Real-time attendance and access control solutions.
- Efficient video content indexing and retrieval platforms.
- Personalized multimedia user interaction based on face recognition.
- Forensic analysis and investigative video tools.
- Healthcare monitoring systems analyzing patient behavior and expressions.

---

## Contact

If you have any suggestions, questions, or doubts regarding this project, please feel free to contact me at:  
**your.email@example.com**

I would be happy to discuss and assist further!

