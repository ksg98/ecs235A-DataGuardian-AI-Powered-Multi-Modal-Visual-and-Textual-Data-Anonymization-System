# DataGuardian: AI-Powered Multi-Modal Visual and Textual Data Anonymization System

## Overview
DataGuardian is a real-time privacy protection system that utilizes OpenAI's Vision API and Microsoft's Presidio for detecting and anonymizing sensitive information from visual and textual data streams.

## Quick Start
1. Open the Colab notebook: [DataGuardian Colab](https://colab.research.google.com/drive/1Y4A6P_EijA4C_HgU0z6_lSCMj1vgXb8U?usp=sharing)
2. Replace `"your-key-here"` with your OpenAI API key in the designated cell
3. Run all cells in order
4. Access the Gradio interface through the provided link

## Features
- Real-time webcam feed analysis
- Multi-language text detection (EN, ES, FR, DE, RU, NL)
- Privacy-focused data anonymization
- Live performance metrics
- User-friendly Gradio interface

## Modular Files and Main Notebook
The project is structured into modular Jupyter Notebooks for deeper understanding and functionality.  

### Modular Files:
- **Step1_Installation_and_Setup.ipynb**: Covers installation and setup of dependencies.
- **Step2_Utility_Functions_and_Configurations.ipynb**: Defines utility functions and system configurations.
- **Step3_NLP_and_Entity_Recognizers_and_Custom_Analyzers.ipynb**: Explains the NLP engine, entity recognizers, and custom analyzers.
- **Step4_AI_Model_Integration.ipynb**: Integrates AI models like OpenAI Vision API with the system.
- **Step5_Gradio_Interface_and_Application_Launch.ipynb**: Builds the Gradio interface and launches the application.

### Main Notebook:
- **Realtime_Visual_data_anonymisation.ipynb**: Combines all steps into a unified, runnable notebook. Follow the instructions in the **Quick Start** section to execute.

## System Requirements
- OpenAI API key
- Web browser with camera access
- Google account for Colab

## Technology Stack
- OpenAI GPT-4 Vision API
- Microsoft Presidio
- spaCy NLP Models
- Gradio
- OpenCV
- Python 3.10+

## Privacy Notice
- All processing is done in real-time
- No data is stored or saved
- API calls are made securely

## Support
For issues or questions:
1. Check the Colab notebook comments
2. Open an issue in this repository
3. Contact the maintainers

## License
MIT License

## Acknowledgments
- OpenAI for Vision API
- Microsoft for Presidio
- Gradio team for UI framework
