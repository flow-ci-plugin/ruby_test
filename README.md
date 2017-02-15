
# ruby_test Step
Run test use `bundle exec rake`

### INPUTS
* `FLOW_ENABLE_FAILURE` - 

## EXAMPLE 

```yml
steps:
  - name: ruby_test
    enable: true
    failure: true
    plugin:
      name: ruby_test
      inputs:
        - FLOW_ENABLE_FAILURE=$FLOW_ENABLE_FAILURE
```
