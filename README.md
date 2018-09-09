## notebooks 📓

ipython notebooks with notes and experiments for deep learning. Mostly with keras and tensorflow.

### What can you find

- A [binary classification](binary_classification.ipynb) for movie 🎥 reviews based on the IMDB dataset.
- A [multiclass classification](multiclass_classification.ipynb) for newswires 🗞 based on the Reuters dataset.
- A [regression](regression.ipynb) for predicting house prices 🏡 based on the Boston housing dataset.

### How to play with the notebooks

1. Install [docker](https://www.docker.com/) 🐳.
2. Clone this repository and run:

```
docker run -p 8888:8888 -v $(pwd):/src stanete/tensorflow
```

### License

    Copyright 2018 David Stanete

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
