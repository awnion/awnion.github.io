{%- set content = load_data(path=path, format="plain") -%}
```{{ language | default(value="") }}
{{ content | trim }}
```
