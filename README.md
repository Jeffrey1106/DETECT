# DETECT: Deception Tracking Through Eye Cues Technology

> Note: This project has just been started and is mostly research as of now.

Welcome to DETECT! This project aims to revolutionize the field of deception detection by leveraging advanced gaze tracking technology. Utilizing the powerful MediaPipe framework, DETECT analyzes eye cues to offer a new dimension in understanding and interpreting human behavior.

## 📜 Overview

DETECT (Deception Tracking Through Eye Cues Technology) is a cutting-edge project designed to track and analyze eye movements to assist in identifying potential deception. By triangulating the position of the iris, DETECT provides valuable insights into gaze patterns that can be indicative of truthfulness or deception.

## 🚀 Features

- **Real-Time Gaze Tracking:** Accurate triangulation of the iris location for precise gaze direction analysis.
- **MediaPipe Integration:** Harnesses the power of MediaPipe for efficient and reliable eye cue extraction.
- **Deception Insights:** Provides a foundation for further research into gaze patterns and their correlation with deceptive behavior.

## 🛠️ Installation

To get started with DETECT, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/DETECT.git
   cd DETECT
   ```

2. **Set Up a Virtual Environment:**
    - Using conda (recommended):
    ```bash
    conda create --name detect
    conda activate detect
    ```
   - Using venv:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```
   - Docker: Will be done on 1st MVP
   - Others: Task will be left to the reader

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## 🔧 Usage

1. **Run the Application:**
   - To run it with live webcam (inbuilt only as of now):
   ```bash
   python iris_detect.py --webcam
   ```
   - To run it with a separate image:
   ```bash
   python iris_detect.py --image <image-path>
   ```

2. **Start Analyzing:**
   - The application will initiate your camera and begin tracking eye movements.
   - Use the provided interface to view and analyze gaze data.

<!-- ## 📚 Documentation

For detailed documentation and usage instructions, please refer to the [Wiki](https://github.com/bingKegeta/DETECT/wiki) or the `docs` directory. -->

<!-- ## 🎯 Contributing

We welcome contributions to enhance DETECT's capabilities! If you have ideas, bug reports, or wish to contribute, please follow these steps:

1. **Fork the Repository**
2. **Create a New Branch**
3. **Make Your Changes**
4. **Submit a Pull Request**

Please review our [Contribution Guidelines](CONTRIBUTING.md) before getting started. -->

<!-- ## 💬 Contact

For questions or support, feel free to reach out to us:

- **Email:** <email>
- **Issues:** [GitHub Issues](https://github.com/bingKegeta/DETECT/issues) -->

<!-- ## 🔗 Links

- [GitHub Repository](https://github.com/yourusername/DETECT)
- [Project Wiki](https://github.com/yourusername/DETECT/wiki)
- [Documentation](docs/) -->

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---
<!-- 
Thank you for your interest in DETECT! We look forward to your contributions and hope you find our technology useful in advancing the study of human behavior. Happy detecting!

--- -->