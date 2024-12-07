# EarDefender

The EarDefender project aims to create an advanced tool for efficiently searching social media platforms to detect video content with sound and audio recordings, and subsequently verify their authenticity through DeepFake audio detection. The application will generate a detailed report, including the number of materials retrieved, the detection methodology used, and the identification of specific audio segments recognized as DeepFake. Additionally, the report will provide links to the found content. Users will also have the option to select their preferred DeepFake detection method, allowing for customized analysis based on individual needs.

To learn more about the implementation, we encourage you to explore the following EarDefender submodules:

- [Frontend](https://github.com/tymem12/ear-defender-frontend): Responsible for the user interface (UI).
- [Connector](https://github.com/tymem12/ear-defender-connector): Manages communication between the different modules.
- [Scraper](https://github.com/tymem12/ear-defender-scraper): Handles browsing the internet and downloading audio content.
- [Detector](https://github.com/tymem12/ear-defender-model): Responsible for making predictions.

For additional information about the project, development process, and methodologies used, please refer to our application and [article](https://openreview.net/forum?id=Wr9bnLMcLQ).

The application is hosted on GCP and can be accessed [here](http://34.38.43.218:8080/). 
