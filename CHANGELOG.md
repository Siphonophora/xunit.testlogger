# Changelog

## Unreleased (v3.1.x)

## v3.0.56 - 2021/01/31

- Refactor to support [core testlogger][]
- Compatibility: minimum framework is netstandard1.5 and TestPlatform 15.5.0
- Use test run start and end times for run duration reporting for assembly. See #26
- Escape control characters from the generated xml. See #25
- Token expansion for `{assembly}` and `{framework}` in results file. See
  https://github.com/spekt/testlogger/wiki/Logger-Configuration

[core testlogger]: https://github.com/spekt/testlogger
