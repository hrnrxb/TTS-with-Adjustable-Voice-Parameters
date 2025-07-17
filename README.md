# 🗣️ Text-to-Speech (TTS) Bot with Adjustable Voice Parameters

Welcome to the Text-to-Speech project! This is an interactive demo allowing you to convert text into speech while adjusting parameters like Speed, Pitch, and Volume. Additionally, a visual waveform of the generated audio is displayed.

---

## 🚀 Live Demo

You can try the live demo of this project directly on Hugging Face Spaces:
[https://huggingface.co/spaces/hrnrxb/TTS-with-Adjustable-Voice-Parameters](https://huggingface.co/spaces/hrnrxb/TTS-with-Adjustable-Voice-Parameters)

---

## ✨ Features

* **Text-to-Speech Conversion:** Transforms input text into natural-sounding speech.
* **Adjustable Voice Parameters:**
    * **Speed:** Control the speaking rate of the generated voice.
    * **Pitch:** Adjust the fundamental frequency (highness or lowness) of the voice.
    * **Volume:** Control the loudness of the audio output.
* **Waveform Visualization:** Visually displays the audio waveform of the generated speech in real-time.
* **Simple User Interface:** Built with Gradio for an intuitive and easy-to-use experience.

---

## 🛠️ Technologies Used

* **Python:** The primary programming language.
* **Coqui TTS (TTS Library):** A powerful text-to-speech library for high-quality audio generation.
* **Hugging Face Transformers:** Utilized for leveraging state-of-the-art language models.
* **Gradio:** For rapidly building interactive web interfaces for machine learning models.
* **PyTorch:** The deep learning framework powering Coqui TTS.
* **NumPy:** Essential for numerical operations and handling audio data arrays.
* **SoundFile:** For reading and writing audio files.
* **Matplotlib:** Used for plotting and visualizing the audio waveforms.
* **Hugging Face Spaces:** The platform for deploying and sharing ML demos.
* **GitHub:** For version control and collaborative development.

---

## ⚙️ How It Works

The project takes text input from the user and feeds it to the Text-to-Speech model (specifically `tacotron2-DDC` in this case). The model then converts the text into an audio signal. This audio signal is saved as a `.wav` file, and simultaneously, its waveform is plotted and saved as an image file. Gradio then presents both the generated audio and the waveform image to the user via the web interface.

---

## 💻 Running Locally

To run this project on your local machine:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/TTS-Gradio-Demo.git](https://github.com/YourGitHubUsername/TTS-Gradio-Demo.git)
    cd TTS-Gradio-Demo
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows:
    # .\venv\Scripts\activate
    # On macOS/Linux:
    # source venv/bin/activate
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the `app.py` script:**
    ```bash
    python app.py
    ```
    Once executed, a local link (and potentially a public share link if `share=True` is enabled in Gradio) will appear in your terminal, which you can open in your web browser.

**Just a little note from me:** This is my very first TTS project, and while this field isn't my primary area of work, it was an incredibly fun and cool experience! 😄 If you spot any issues or have ideas for improvement, please feel free to contribute by opening an issue or a pull request. Let's fix it together! 😁✌️
