Hi,

This a simple GenAI-Image project focusing on speed and low computeration power to be inference on Colab. Based on my findings, Stable Difussion Turbo provide good balance between performance and computeration power
(it only needs around 5gb Vram). Though not a sophiscated app like ComfyUI, it a decent app that gets the job done.


(As it is Streamlit on colab, it use ngrok for exposing port. Thus, need ngrok acc for auth token. Alternatively, you can use localtunnel (it did not properly for me it maybe it depending the region) )


Just sharing if anyone interested.

Code reference:

https://huggingface.co/docs/diffusers/en/tutorials/autopipeline?autopipeline=text-to-image
https://huggingface.co/stabilityai/sd-turbo
https://github.com/MdyCode-AIE/Document-query-Paddle-OCR-FastModel-library-Simple-context-injection-through-Streamlit
