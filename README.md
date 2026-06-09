## Movie Era Posters Detection Gradio App

This is a study project for models deployment via Gradio and HuggingFace Spaces, made for course "Practical Deep Learning for Coders" by fast.ai and the University of Queensland (https://course.fast.ai/). The app takes a movie poster (it better to be tho one of American cinema) as an input, returning probabilities of the poster being drawn either in 1900s-1960s, 1970s-1990s or later on. Pretrained resnet 101 was taken as a learner with being fine-tuned on 1500 posters of each period, retreived from DuckDuckGo search queries. Quality of the resulting model is quite low with 0.35 error rate after 11 epochs, but the aim was more to play around with Gradio, rather than crating working movie poster classifier. 

The app is hosted on HuggingFace Spaces here: https://huggingface.co/spaces/victorpakholkov/movie_era_posters_detection_gradio_app

Repository includes Jupyter notebook (movies_posters_classifier), featuring the model's fine-tuning and export. If you are to recreate the app, you'd have to export the model as '.pkl' file, adding it to your repository.

'requirments.txt' features a list of required python libraries.

'app.py' features the Gradio app itself.

Example pics are provided under corresponding files.

**Feel free to use it as an example for your own projects or basis for further developments, like fine-tuning the model further or testing your own models with it!**

https://www.ozon.ru/product/otparivatel-dlya-odezhdy-ruchnoy-garlyn-gs-15-parogenerator-moshchnyy-dlya-doma-4100373055/?oos_search=false&reviewsVariantMode=1

{
    "inbounds": [
        {
            "listen": "127.0.0.1",
            "port": 10808,
            "protocol": "socks",
            "settings": {
                "udp": true
            }
        }
    ],
    "log": {
        "loglevel": "error"
    },
    "outbounds": [
        {
            "protocol": "vless",
            "settings": {
                "vnext": [
                    {
                        "address": "144.31.250.188",
                        "port": 489,
                        "users": [
                            {
                                "encryption": "none",
                                "flow": "xtls-rprx-vision",
                                "id": "bdad2e92-1d68-4c37-b791-1dd63de44578"
                            }
                        ]
                    }
                ]
            },
            "streamSettings": {
                "network": "tcp",
                "realitySettings": {
                    "fingerprint": "chrome",
                    "publicKey": "sbzxQTC3WSVzZUM_IBrhYBQf98c033pqIW8ENxODgjc",
                    "serverName": "www.ya.ru",
                    "shortId": "aff5e489026f18c8",
                    "spiderX": ""
                },
                "security": "reality"
            }
        }
    ]
}

