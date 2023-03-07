# crypto-twitter-price-correlation

You can find the full original dissertation thesis here: https://1drv.ms/w/s!Ap93KOBrSSIJhadFRdw0SbMMkvYkDQ?e=xJtKLz 
This script does 2 separate things:
1. Retrieve tweets from selected Twitter lists, add them to a pandas dataframe and use OpenAIs GPT-3 to attempt to retrieve crypto projects from tweets.
2. Perform statistical analysis of price vs volume of tweets.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the following libraries.

```bash
pip install pandas 
pip install openai
pip install twarc_csv
pip install textblob
pip install nltk
pip install twarc
pip install wandb
```

## Usage

```python
import relevant libraries
import pandas as pd
import openai
import requests
import twarc_csv
import textblob
import nltk
import os
import twarc
import wandb

```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
