Schema:
```
"data_source": data_source,
"prompt": [{
    "role": "user",
    "content": (str) question
}],
"ability": "math",
"reward_model": {
    "style": "rule",
    "ground_truth": solution
},
"extra_info": {
    'split': split,
    'index': idx,
    'answer': (str) answer
    'question': (str) question
}
```
