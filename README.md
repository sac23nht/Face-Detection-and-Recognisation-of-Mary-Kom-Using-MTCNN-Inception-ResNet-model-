# Video Face Detection and Recognition Pipeline
<img width="511" height="296" alt="image" src="https://github.com/user-attachments/assets/57c02b06-1f74-417c-b26b-d17b8572fcd1" />


## Project Purpose

The purpose of this project is to build a complete pipeline that processes videos by extracting frames, detecting faces, and recognizing individuals automatically. This helps to analyze video content efficiently for applications like security, surveillance, identity verification, and video indexing.

## How the Project is Achieved

1. **Video Acquisition**  
   The project starts by downloading a YouTube video using PyTube and saving it locally. To focus on relevant content, the video is trimmed to a shorter segment using FFmpeg.

2. **Frame Extraction**  
   Using OpenCV, frames are extracted from the trimmed video at regular intervals (e.g., every fifth frame). These frames are saved as images for further processing.

3. **Preprocessing Frames**  
   Extracted frames are resized and normalized to prepare them for face detection models. This step ensures consistent input quality for the models.

4. **Face Detection**  
   Faces in each frame are detected using advanced algorithms such as MTCNN (a deep learning-based face detector) and traditional Haar Cascade classifiers. This enables locating and cropping faces from the frames.

5. **Face Recognition**  
   Detected faces are then analyzed using deep learning embeddings to recognize identities by comparing features. This step facilitates identification of people within the video.

6. **Visualization and Analysis**  
   Sample frames, detected faces, and recognition results are displayed for qualitative evaluation and validation of the pipeline.

## Key Learnings

- Handling video data: downloading, trimming, and extracting frames  
- Image preprocessing techniques for deep learning models  
- Application of face detection models (MTCNN, Haar Cascade)  
- Implementing face recognition through feature embeddings  
- Using OpenCV, PyTorch, and PyTube libraries effectively  
- Understanding challenges in video-based facial analytics  

## Future Applications

- Automated surveillance and security monitoring systems  
- Real-time attendance and access control solutions  
- Video content indexing and retrieval systems  
- Personalized user interaction in multimedia applications  
- Forensic video analysis and investigation tools  
- Healthcare monitoring and behavior analysis  

---

## Contact

If you have any suggestions, questions, or doubts regarding this project, please feel free to contact me at:  
**saijaya.c@gmail.com**

I would be happy to discuss and assist further!
