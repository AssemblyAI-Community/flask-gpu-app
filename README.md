# Flask GPU app

Example app that demonstrates how to run a Flask app with a free GPU using Google Colab and ngrok.

- Read the blog post: [free stable diffusion app with a gpu backend](https://www.assemblyai.com/blog/build-a-free-stable-diffusion-app-with-a-gpu-backend/)
- Watch the YouTube tutorial: [https://youtu.be/wBCEDCiQh3Q](https://youtu.be/wBCEDCiQh3Q)

## Instructions

- Open the Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AssemblyAI-Examples/flask-gpu-app/blob/main/notebook.ipynb)

- Go to [ngrok.com](ngrok.com), get a free API token, and in the Colab replace`YOUR-AUTHTOKEN-HERE` with the token.

- Set the runtime to GPU

- Click on `Runtime -> Run all`

- In the output cell you should see a url similar to this: Running on `http://5fdc-104-196-187-169.ngrok.io`. Open this url and use your app.
