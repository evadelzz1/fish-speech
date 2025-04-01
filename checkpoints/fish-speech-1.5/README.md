---
tags:
- text-to-speech
license: cc-by-nc-sa-4.0
language:
- zh
- en
- de
- ja
- fr
- es
- ko
- ar
- nl
- ru
- it
- pl
- pt
pipeline_tag: text-to-speech
inference: false
extra_gated_prompt: >-
  You agree to not use the model to generate contents that violate DMCA or local
  laws.
extra_gated_fields:
  Country: country
  Specific date: date_picker
  I agree to use this model for non-commercial use ONLY: checkbox
---


# Fish Speech V1.5

**Fish Speech V1.5** is a leading text-to-speech (TTS) model trained on more than 1 million hours of audio data in multiple languages.

Supported languages:
- English (en) >300k hours
- Chinese (zh) >300k hours
- Japanese (ja) >100k hours
- German (de) ~20k hours
- French (fr) ~20k hours
- Spanish (es) ~20k hours
- Korean (ko) ~20k hours
- Arabic (ar) ~20k hours
- Russian (ru) ~20k hours
- Dutch (nl) <10k hours
- Italian (it) <10k hours
- Polish (pl) <10k hours
- Portuguese (pt) <10k hours

Please refer to [Fish Speech Github](https://github.com/fishaudio/fish-speech) for more info.  
Demo available at [Fish Audio](https://fish.audio/).

## Citation

If you found this repository useful, please consider citing this work:

```
@misc{fish-speech-v1.4,
      title={Fish-Speech: Leveraging Large Language Models for Advanced Multilingual Text-to-Speech Synthesis}, 
      author={Shijia Liao and Yuxuan Wang and Tianyu Li and Yifan Cheng and Ruoyi Zhang and Rongzhi Zhou and Yijin Xing},
      year={2024},
      eprint={2411.01156},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2411.01156}, 
}
```

## License

This model is permissively licensed under the CC-BY-NC-SA-4.0 license.