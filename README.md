## Movie Era Posters Detection Gradio App

This is a study project for models deployment via Gradio and HuggingFace Spaces, made for course "Practical Deep Learning for Coders" by fast.ai and the University of Queensland (https://course.fast.ai/). The app takes a movie poster (it better to be tho one of American cinema) as an input, returning probabilities of the poster being drawn either in 1900s-1960s, 1970s-1990s or later on. Pretrained resnet 101 was taken as a learner with being fine-tuned on 1500 posters of each period, retreived from DuckDuckGo search queries. Quality of the resulting model is quite low with 0.35 error rate after 11 epochs, but the aim was more to play around with Gradio, rather than crating working movie poster classifier. 

The app is hosted on HuggingFace Spaces here: https://huggingface.co/spaces/victorpakholkov/movie_era_posters_detection_gradio_app

Repository includes Jupyter notebook (movies_posters_classifier), featuring the model's fine-tuning and export. If you are to recreate the app, you'd have to export the model as '.pkl' file, adding it to your repository.

'requirments.txt' features a list of required python libraries.

'app.py' features the Gradio app itself.

Example pics are provided under corresponding files.

**Feel free to use it as an example for your own projects or basis for further developments, like fine-tuning the model further or testing your own models with it!**

vpn://AAANxnja7VdbT-s4EH7nV1TVeQOK42uClpUqCrSw9LD0sOLSoypNHAhtk2ySFljEf9-xnbbpwTzA80lBGX_zeWbszEyc160GXM0gTUo_TmReNPcbdxpT1-tK0iz_6R7Um6BWdB3Am4Q6yPW4S3YpcxmDAW_uWMhYkR2KCfMIId4uRog6gnmCWelE0TFyXEY5c4HugB_CBHGsdKrpDuUUY4rdXS26GBFqo_d05H-MG-gZuZS6jovgcuCfoOUlBOUeJ3zMmaCCIC4EjCkXaow8wD0ueSQQj7gngIewwIKhpSUnQAj-EKvGyrgHovuLpfd-PO6AZVi2cAOEWaDn_WoHjx013xWKh4Hv8ACHm7ZgXPfEgcN1rC53Nv0gApLiQMgsXK7AeFMLQZSJyI8kZn9a91M_XKuGfKihH2rYR5rTQGms-XU685-VkiG7Nk50_lm1A50OzLXq9NKYsOr04jyrSq_O6m3qF-UISi-KVV01X4eJgodQTkMYD20FNWzurFjYsKyVVOcRw7OWUJ1HK56tdmq8XhXd76L5StHUN7J6gHWIvIfoe4i9g04DA9UTRBWCQRnagOOkypw6PKgeK3PrYBUiE3WwCtKrY1WUdYv-dJo-yXAUZ4VS3hnc6FBL__bWfIPv7yvIID9XloJpLJOyFxofvZcuic5l9-mWLLzB4PGcPF_Oc94up-1bf3y8zW_CvcSdnXjJ-UEtHGMEolkuvuW2nBZ5z8jyeDGayBfDK8LZNSsXV6LNOrNOtiizG3kUkav7v2OWzxPae0hxPumcPAyoxVs2H69NfTVw3SGMibteUso88gP5czhM2mGYy6JoHDSWq9kjGPBOfwDYt4vL3nn78mYEw53Gt8HR4fd-pxoD6QKW6ZfyTL4A91OrHCanAczhSoBk0u617D-DzJQ8cJTkKgkrSSiJgOQpgYKgWF3FsnU5UKlp9tYGSmXJ3s9Aqazbm9gw6SmPvzvXlzoX7J56KOpOqjut7szc4e_uQspc5ebFfDyNA5Nd4p-ryzQ_nQgaRe3zeXjvX7Kj6-ujwSPuP21PyNmP-9t213987rgHOjNl8eDnMjSzj-d7STntZ_gv79_j7Mf4NlhsR4c8nEp80u09Ts76e9_pePAE3UTNbpu207tQdbHqMzsN3VqGyVESZmmclDq9aIs4LcxQy3HdfYohIZR7OAbHRQnleyZl5k_jhVQZpRKvVpUPaVH2_ZlcvoTrpmq0WTmvGETUm3O2cgL9QWYj7aZ6Adff3lmalwrWwa3RYrJuK5_an7XlQuYLmW92qE89KGjTb8PEdrBRQasTjQ7aSsjTMg3S6WihtiHVJzJsIxbzcSLLkW8anTm46U5nPVCVuZ8UyvlIO1D0eZg1N4hvm_PWnz6K7c8S-V_s78KXDl5Pe9syryPzrRTKyJ9Py8MP5614RZDHWVktb6C3u-Gs1EmhD5tOS_9qsPk-0om7gpfZZj6d6rnW3Hrb-h8MBEXB
