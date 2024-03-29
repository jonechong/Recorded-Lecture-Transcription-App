# Recorded-Lecture-Transcription-App
The application submodule for Recorded Lecture Transcription. Find the overview at [Recorded Lecture Transcription](https://github.com/jonechong/Recorded-Lecture-Transcription).

## Preliminary Requirements

### Interface Requirements

#### Functional

##### Primary
- User must be able to input a video (mp4 or avi).
- System must be able to extract the audio file in .wav as input for the transcription model.
- User must be able to view the lecture video alongside the caption or transcript.

##### Secondary
- Timestamping of the transcript corresponding to the lecture.

#### Non-Functional
- The system must be easily deployable with just Python and Python libraries (no node, no npm, etc.).
- The system must be easy to setup (e.g., `pip install -r requirements.txt`).
