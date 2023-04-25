
# Air pressure system failures in Scania trucks

The dataset consists of data collected from heavy Scania trucks in everyday usage. The system in focus is the Air Pressure system (APS) which generates pressurized air that is utilized in various functions in a truck, such as braking and gear changes. The datasets' positive class consists of component failures for a specific component of the APS system. The negative class consists of trucks with failures for components not related to the APS. The data consists of a subset of all available data, selected by experts.


## Dataset

- [APS Failure at Scania Trucks Data Set](https://archive.ics.uci.edu/ml/datasets/APS+Failure+at+Scania+Trucks)
## Installation

Step 1 - Install the requirements

```bash
pip install -r requirements.txt

```
Step 2 - Load the data in Mongo DB

```bash
python data_dump.py

```

Step 3 - Run main.py file

```bash
python main.py

```
## Authors

- [Pranshu Chaurasia](https://github.com/pranshuchaurasia) [(Linkedin)](https://www.linkedin.com/in/pranshuchaurasia/)



## License

[MIT](https://choosealicense.com/licenses/mit/)


