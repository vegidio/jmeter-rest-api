# JMeter - REST API

In this an [Apache JMeter](https://jmeter.apache.org/) template that I usually use to test the performance of my REST APIs.

The main goal of this project is to keep most configurations about endpoints, methods, bodies and responses out of the `.jmx` file; the load test parameters can be configured in the [testplan.csv](https://github.com/vegidio/jmeter-rest-api/blob/master/testplan.csv) file and also in the JSON files found in the `input` and `assertion` folders.

## Installation

* On macOS (with Homebrew):
```
$ brew install jmeter --with-plugins
```

## Configuration

TBD

## Testing

It's not recommended to do the test using the GUI of JMeter, so please use the command line interface. In the project folder type:

```
$ jmeter -n -f -t rest-api.jmx
```

## Reviewing the results

TBD

## Author

Vinicius Egidio ([vinicius.io](http://vinicius.io))
