# Arabic-Sentiment-Analysis-With-Emojis

**Arabic sentiment analysis with giving more score to emjis**
---

* We can control emjis weight and data through YAML file, we can add any +ve or -ve emjis.

* We can also change the effect of emogis by changing the value of a parameter in the YAML file called "emoje_weight", 0.6 is a good starting value, but we can increase/ decrease emojis effect by chaging its value.

* it takes value between 0 to infinity , but if it is larger that 2, the emoje weight will big enough so the code will return the result according to the emoje only.

---
## Data

You can find the data used for testing here "1.text":
https://drive.google.com/drive/u/0/folders/1KWS7me9LYnpwfYywF5bn1dzt-omThrUP

## Resources:

 https://huggingface.co/CAMeL-Lab/bert-base-arabic-camelbert-da-sentiment?text=%D8%A3%D9%86%D8%A7+%D8%A8%D8%AE%D9%8A%D8%B1
