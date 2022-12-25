# json_jsonl
json_jsonl : Save and Load json, jsonl format

```shell
pip install json_jsonl
```

```python
import json_jsonl as jj


dd = {
    "test" : 1,
    "test2" : "e"
}


# json save and load
jj.json_save("dd.json", dd)
dd_load = jj.json_load("dd.json")


ddl = [dd_load, dd_load, {"df" : "dfd"}]


# jsonl save and load
jj.jsonl_save("ddl.jsonl", ddl)
jj.jsonl_load("ddl.jsonl")
```
