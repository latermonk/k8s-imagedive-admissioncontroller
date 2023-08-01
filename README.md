# k8s-image-dive-admission-controller
k8s-image-dive-admission-controller 


# install golang 
```shell
wget https://go.dev/dl/go1.20.6.linux-amd64.tar.gz && rm -rf /usr/local/go && tar -C /usr/local -xzf go1.20.6.linux-amd64.tar.gz

```

env setting:
```shell
export PATH=$PATH:/usr/local/go/bin
```

check version:
```shell
go version
```

# Dev
```shell
git clone https://github.com/latermonk/k8s-imagedive-admissioncontroller.git && cd k8s-imagedive-admissioncontroller
```

```shell
go mod tidy
```

```shell
go run cmd/dive.go
```

---

```shell
https://github.com/wagoodman/dive
```

