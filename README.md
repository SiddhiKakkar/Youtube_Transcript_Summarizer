# Youtube_Transcript_Summarizer
YouTube videos have become an incredibly valuable source of information in today's digital landscape. However, learning from these videos can be a challenging task as it often requires a significant amount of time to extract the relevant information.To address these challenges, a YouTube transcript summarizer comes into play. By leveraging the text-based transcripts available for YouTube videos, users can access accurate information and solutions without having to watch the entire video. Transcripts offer an excellent source of information as they provide a textual representation of the audio content in a video. Utilizing natural language processing (NLP) techniques, the summarizer extracts key phrases and sentences from the transcript. This enables the generation of a concise summary that offers viewers a quick overview of the video's content. With the summarizer, users can obtain the true essence of the video's transcript and gain valuable insights without wasting their time.

This project aims to offer users a convenient solution for obtaining clean and concise summaries of YouTube videos they don't want to spend excessive time watching. To begin, the user activates the app by clicking the designated activate button. Next, they provide the URL of the video for which they desire a summary. By clicking the Transcript button, the app generates a summary specifically tailored to that particular video. Furthermore, users have the option to translate the summary into their preferred language for added convenience. Additionally, the app offers a speech feature, enabling users to listen to an audio rendition of the summary if they prefer not to read it.

**Algorithm :**

1. Extract transcript using youtube transcript api.
2. Summarize the transcript using pipelines.
3. Translate the summary into various dialecs.
4. Audio output using gTTS.

**Popular Libraries used : -**
Hugging-face
YoutubeTranscriptapi
Transformers
Tkinter(GUI)
Datetime
MBartForConditionalGeneration
PIL
