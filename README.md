### [Bitsnap](https://bitsnap.io) Metrics

[Bitsnap](https://bitsnap.io) provides numerous Operational Metrics for Verifiable Business Intelligence.

## IN DEVELOPMENT

NOT READY FOR PRODUCTION USE.

### Industry Specific Metrics


### Accounting Metrics


### CRM Metrics


### Customer Feedback Metrics

### Payroll Metrics

### HR Metrics

### Inventory Management Metrics

### Management Metrics

### Repository Metrics

### Time Tracking Metrics

### Usage

```go
package main 

import (
  "time"
)

func main() {

}

```

### Development

Install [asdf](https://asdf-vm.com/guide/getting-started.html) with all the dependencies

```bash
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.14.0
# Add the following to ~/.bashrc:
echo '. "$HOME/.asdf/asdf.sh"' >> ~/.bashrc
# Completions must be configured by adding the following to your .bashrc:
echo '. "$HOME/.asdf/completions/asdf.bash"' >> ~/.bashrc
```

```bash
# install asdf

asdf plugin add golang
asdf plugin add golangci-lint 
asdf plugin add ko
asdf plugin add goreleaser

go install golang.org/x/tools/cmd/goimports@latest
go install mvdan.cc/gofumpt@latest
go install github.com/onsi/ginkgo/v2/ginkgo@latest
```

### Code generation

```bash
go generate ./...
```

### Testing

```bash
ginkgo run ./...
```

### TODO
- [ ] provide [Apache Flink](https://flink.apache.org/) [JNI source](https://nightlies.apache.org/flink/flink-docs-master/docs/dev/datastream/sources/) binding
- [ ] provide [Argo Events](https://argoproj.github.io/argo-events/) source binding
- [ ] benchmarks

## License

[Bitsnap Metrics](https://www.bitsnap.io/metrics) golang package is licensed under the terms of [MIT License](LICENSE).