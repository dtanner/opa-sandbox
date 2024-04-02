# opa-sandbox
Open Policy Agent sandbox

docs: https://openpolicyagent.org/docs/latest
playground: https://play.openpolicyagent.org

```shell
cd basic

# manual evaluation
opa eval --format raw --data policy.rego 'data.policy.allow' --input input.json

# run tests
opa test . 
```

