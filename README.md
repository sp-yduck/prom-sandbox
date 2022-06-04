# Understand Promtool

## Official documents

- [prometheus docs](https://prometheus.io/docs/introduction/overview/)

- [unit testing rules](https://prometheus.io/docs/prometheus/latest/configuration/unit_testing_rules/)

- [alerting rules](https://prometheus.io/docs/prometheus/latest/configuration/alerting_rules/)

## ptomtool - how to use

unit test for rule - [unit testing rules](https://prometheus.io/docs/prometheus/latest/configuration/unit_testing_rules/)

`promtool test rules <test-rule-file-yml>`

syntax check for rule - [alerting rules](https://prometheus.io/docs/prometheus/latest/configuration/alerting_rules/)

`promtool check rules <rule-file-yml>`

## misc

- test starts at Unix epoch (1970/1/1 00:00:00)
- metrics values are stored in float64(golang)

  example : 0.1 + 0.2 = 0.3000...0004

- staleness marker
