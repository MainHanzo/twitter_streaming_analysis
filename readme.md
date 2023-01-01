A simple twitter steaming sentiment analysis tool to practice spark streaming module

## Installation

You need jupyter notebook set up for this project.
Additionally, you will need to set up a twitter developper account for testing.
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install.

```bash
pip install -r requirements.txt
```

## Usage

1. launch the Main.ipynb notebook to create the kafka instance which connects to twitter API filtering on certain keywords and rules
2. launch the spark_streaming.ipynb notebook to start a spark session which analyse the tweet sentiment from the source kafka.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
