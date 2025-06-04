## [golangci-lint](https://github.com/golangci/golangci-lint) configuration tailored for the **Genesis Software Engineering School #5**.  
Inspired by the [Uber Go Style Guide](https://github.com/uber-go/guide/blob/master/style.md), it aims to enforce consistent, clean, and idiomatic Go code for educational and production projects.

### Installation
You can run linter with remote config (no local file needed)
```bash
golangci-lint run --config <(curl https://raw.githubusercontent.com/fabl3ss/genesis-se-school-linter/refs/heads/main/.golangci.yaml)
```

Or add config to your project
```bash
curl -o .golangci.yaml https://raw.githubusercontent.com/fabl3ss/genesis-se-school-linter/main/.golangci.yaml
golangci-lint run
```

**Feel free to PR :)** \
<img src="https://github.com/user-attachments/assets/18d7d15d-98a3-4e74-909d-73a1365d0f46" width="150" />
