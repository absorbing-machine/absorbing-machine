# Absorbing Machine
A Machine that absorbs publicly available information.
```bash
  echo '[{"role": "user", "content": "I have a question..."}]' \
    | uvx absorbing-machine \
        --provider-api-key=sk-ant-api... \
        --github-token=ghp_... \
        --mode=single
```
Or:
```bash
  pip install absorbing-machine
```
Then:
```Python
  # Python
  import absorbing_machine
```
