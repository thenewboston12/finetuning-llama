2  finetuning LLaMa-3.1-70B-Instruct model 

**MI-LLama-v4** contains the 70B model finetuned on the whole MI dataset (AnnoMI + Obesity + RCT)
PARAMS: LoRa Rank: 8, Alpha 16, Learning-rate 5e-5


**MI-LLama-v4.5** contains the 70B model finetuned on the some part of the  MI dataset (Obesity + RCT)
PARAMS: LoRa Rank: 8, Alpha 16, Learning-rate 5e-5


## Datasets being used:

- `final_dataset.json` Obesity Pilot + AnnoMI + Obesity RCT
- `obesity_RCT_pilot_only.json` Obesity Pilot + Obesity RCT (NO AnnoMI)
