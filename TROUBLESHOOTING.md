
---

### **4. CI/CD Pipeline (`.github/workflows/test.yml`)**
```yaml
name: Basic Tests

on: [push, pull_request]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: ShellCheck
        uses: ludeeus/action-shellcheck@1.1.0
