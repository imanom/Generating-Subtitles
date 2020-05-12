# Generating-Subtitles

The code in this project show steps to generate subtitles for your video file.

Note:

1. Python libraries mostly work on wav audio formats, so I converted the video to audio (.wav extension) in the code.
2. Google Cloud APIs work properly on locally stored files only if the audio files are < 1 minute. 
(Otherwise you need to store the file on Cloud Bucket)
So, while converting the audios here, I also trimmed the audio to 50 second duration.


### Links
1. https://cloud.google.com/resource-manager/docs/creating-managing-projects 
To create a Google Cloud project with billing enabled

2. https://cloud.google.com/speech-to-text/docs/libraries#client-libraries-install-python
To create service account for using google speech to text API.

3. Also, install ffmpeg using this in your anaconda console--> ffmpeg - conda install -c conda-forge ffmpeg
 
