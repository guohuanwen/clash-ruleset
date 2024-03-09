# Clash ruleset

## How to use

- example:

copy and paste this to the `rule-providers` block of your clash config file.

```yaml
  openai:
    type: http
    behavior: classical
    url: "https://raw.githubusercontent.com/guohuanwen/clash-ruleset/main/ruleset/openai.yaml"
    path: ./ruleset/openai.yaml
    interval: 86400
```

then in the `rules` block:

```yaml
  - RULE-SET,openai,Proxy
```

Mind the indent.

## ruleset list

- openai

https://raw.githubusercontent.com/guohuanwen/clash-ruleset/main/ruleset/openai.yaml
