# MustangsMatter

This is a corrected [submission](https://devpost.com/software/smu-mental-health-and-wellness) for the HackSMU VI hackathon's SMU OIT challenge, which ran from October 5-6, 2024. The challenge statement was:

> Develop a comprehensive health and wellness platform for students. It should integrate SMU’s mental health resources, fitness tracking, SMU’s telemedicine services, and provide a support network for peer-to-peer counseling.

Our project integrates an AI chatbot to help students set personal health goals and refer them to SMU's health and wellness resources.

This submission may be viewed live [here](https://wellness-web-app.onrender.com/).

## Deploying

This project was built with Python 3.12.13. The required dependencies for pip can be found in `requirements.txt`.

This project contains several secrets which must be provided as environment variables, specifically:
* `MONGODB_USER`: The username to authenticate into the MongoDB database
* `MONGODB_PASS`: The password to authenticate into the MongoDB database
* `MONGODB_SUBDOMAIN`: The subdomain hosting the MongoDB database
* `PROPELAUTH_BASE`: The auth URL from PropelAuth frontend integration settings
* `PROPELAUTH_KEY`: The API key from PropelAuth backend integration settings
* `HUGGINGFACEHUB_API_TOKEN`: The API key to communicate with the HuggingFace LLM
