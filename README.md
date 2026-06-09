## Movie Era Posters Detection Gradio App

This is a study project for models deployment via Gradio and HuggingFace Spaces, made for course "Practical Deep Learning for Coders" by fast.ai and the University of Queensland (https://course.fast.ai/). The app takes a movie poster (it better to be tho one of American cinema) as an input, returning probabilities of the poster being drawn either in 1900s-1960s, 1970s-1990s or later on. Pretrained resnet 101 was taken as a learner with being fine-tuned on 1500 posters of each period, retreived from DuckDuckGo search queries. Quality of the resulting model is quite low with 0.35 error rate after 11 epochs, but the aim was more to play around with Gradio, rather than crating working movie poster classifier. 

The app is hosted on HuggingFace Spaces here: https://huggingface.co/spaces/victorpakholkov/movie_era_posters_detection_gradio_app

Repository includes Jupyter notebook (movies_posters_classifier), featuring the model's fine-tuning and export. If you are to recreate the app, you'd have to export the model as '.pkl' file, adding it to your repository.

'requirments.txt' features a list of required python libraries.

'app.py' features the Gradio app itself.

Example pics are provided under corresponding files.

**Feel free to use it as an example for your own projects or basis for further developments, like fine-tuning the model further or testing your own models with it!**

[Interface]
Address = 10.8.1.2/32
DNS = 1.1.1.1, 1.0.0.1
PrivateKey = 6+viIFJFL9BDn3VvtWJoFei7UiNfQRfkQAZvwhju2fs=
Jc = 6
Jmin = 10
Jmax = 50
S1 = 58
S2 = 57
S3 = 9
S4 = 0
H1 = 341089683-458551086
H2 = 1423593339-2004175975
H3 = 2018546589-2141035731
H4 = 2146422428-2146482034
I1 = <b 0x084481800001000300000000077469636b65747306776964676574096b696e6f706f69736b0272750000010001c00c0005000100000039001806776964676574077469636b6574730679616e646578c025c0390005000100000039002b1765787465726e616c2d7469636b6574732d776964676574066166697368610679616e646578036e657400c05d000100010000001c000457fafe25>
I2 = 
I3 = 
I4 = 
I5 = 

[Peer]
PublicKey = 7VURorJk74ffAMudgaR5EXXESj2Nw+k3KTgZAHajxD8=
PresharedKey = Fu/ntlNp2L9qFpTbZcv+fC6dle2GHIjkKN/O4bSw0/0=
AllowedIPs = 0.0.0.0/0, ::/0
Endpoint = 144.31.250.188:42481
PersistentKeepalive = 25


