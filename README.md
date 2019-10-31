<div align="center">
  <img src="https://t3.ftcdn.net/jpg/02/48/42/64/240_F_248426448_NVKLywWqArG2ADUxDq6QprtIzsF82dMF.jpg">
</div>

# PyBioSigDt

It serve as python package to download and process Cardio and Brain signal database available as opensource

## Install
```bash
pip install pybiosigdt
```


```python
>>> import pybiosigdt as sigdt
>>> data = sigdt.Databases(name="mit-bih-arrhythmia")
>>> data.describe(clip=True)
https://physionet.org/content/mitdb/1.0.0/
>>>data.tensor() #to convert to tensors
>>>train_data,train_label,test_data,test_labels = data.split(split_size = 0.2, seed = 42)
```

For more examples, see the
[TensorFlow tutorials](https://www.tensorflow.org/tutorials/).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgement

* [Python](https://python.org)

## License
[Apache License 2.0](LICENSE)

