## [ 仅参数名不一致 ] torch.Tensor.outer

### [torch.Tensor.outer](https://pytorch.org/docs/stable/generated/torch.Tensor.outer.html?highlight=outer#torch.Tensor.outer)

```python
torch.Tensor.outer(vec2)
```

### [paddle.Tensor.outer]()

```python
paddle.Tensor.outer(y)
```

两者功能一致且参数用法一致，仅参数名不一致，具体如下：

### 参数映射

| PyTorch | PaddlePaddle | 备注                                                                 |
| ------- | ------------ | -------------------------------------------------------------------- |
| vec2    | y            | 如果类型是多维 `Tensor`，其数据类型应该和 `x` 相同，仅参数名不一致。 |
