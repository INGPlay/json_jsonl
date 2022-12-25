# json_jsonl
json_jsonl : Save and Load json, jsonl format

## install
```shell
pip install json_jsonl
```

## import
```python
import json_jsonl as jj
```

## Save and Load json format
```python
# dictionary
dd = {
    "test" : 1,
    "test2" : "e"
}

# json save and load
jj.json_save("dd.json", dd)
dd_load = jj.json_load("dd.json")

```

## Save and Load jsonl format
```python
# dictionary list
ddl = [{"test" : 1, "test2" : "e"}, 
       {"test" : 1, "test2" : "e"}, 
       {"df" : "dfd"}]

# jsonl save and load
jj.jsonl_save("ddl.jsonl", ddl)
jj.jsonl_load("ddl.jsonl")

```
