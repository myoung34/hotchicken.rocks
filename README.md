# Hotchicken rocks

This is deployed to fastly WASM

[Its super good](https://hotchicken.rocks/)

Terraform located [here](https://github.com/myoung34/homelab/blob/main/terraform/fastly/hotchicken_rocks.tf)

To test:

```
$ fastly compute serve
```

To deploy:

```
$ fastly compute publish
```
