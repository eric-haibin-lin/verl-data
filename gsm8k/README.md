Schema:
```
"data_source": data_source,
"prompt": [{
    "role": "user",
    "content": question
}],
"ability": "math",
"reward_model": {
    "style": "rule",
    "ground_truth": solution
},
"extra_info": {
    'split': split,
    'index': idx,
    'answer': answer
}
```
