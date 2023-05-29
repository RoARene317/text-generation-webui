
# API Documentation
## [GET] /api/v1/model
This is for retrieving the API model name. It's also used for retrieve whether the model is loaded or not, and connection test to the API.
## [POST] /api/v1/model
It's formatted in JSON and the format is in here.
```
{

"prompt":  "",

"max_new_tokens":  180,

"do_sample":  true,

"temperature":  0.6,

"top_p":  0.9,

"typical_p":  1,

"repetition_penalty":  1.1,

"encoder_repetition_penalty":  1,

"top_k":  0,

"min_length":  0,

"no_repeat_ngram_size":  0,

"num_beams":  1,

"penalty_alpha":  0,

"length_penalty":  1,

"early_stopping":  false,

"seed":  -1,

"add_bos_token":  true,

"stopping_strings":  [

""

],

"truncation_length":  2048,

"ban_eos_token":  false,

"skip_special_tokens":  true,

"epsilon_cutoff":0,

"eta_cutoff":0,

"mirostat_mode":0,

"mirostat_tau":0.1,

"mirostat_eta":0.1,

}
```
The parameter is the same with the parameter that you set in the parameter settings in OobaBooga.
```
