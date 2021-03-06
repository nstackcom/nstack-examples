# NStack Examples

A selection of examples we use to test `nstack` and demonstrate features - these are installed by default on our demo server at demo.nstack.com

See the [main repo](https://www.github.com/nstack/nstack) for more information, or check out the [full documentation](https://docs.nstack.com).

## Installing

Clone the repo and run `nstack build` from the project root directory

# Examples

These are all under heavy development and likely to change/improve over time.

## [Demos](https://www.github.com/nstack/nstack-examples/tree/master/demos)

A collection of basic example services that demonstrate,

* creating a basic service
* creating a basic workflow
* using environmental configuration 

## [NStack Stdlib](https://www.github.com/nstack/nstack-examples/tree/master/nstack)

A set of services that provide basic functionality for use in more complex workflows

| *Name* | *Usage* |
|--------|---------|
| `NStack.Utils` | General purpose utilities, e.g. uploading to files to S3 |
| `NStack.ImageProcessing` | Methods to process images, e.g. filters, resize, etc. |

## [Iris](https://www.github.com/nstack/nstack-examples/tree/master/iris)

A sample Python-based classifier using numpy, scipy, and scikit-learn demonstrating how to build data analysis pipelines in NStack, and the ease in creating modules with in-built data-sets and system dependencies.

Has multiple workflows exposing a http endpoint and connecting to a Postgres sample database.

## [Movies](https://www.github.com/nstack/nstack-examples/tree/master/movies)

A more complex set of modules and workflows demonstrating a fully-featured streaming workflow processes data from IMDB, cleans it, processes it, and uses to generate a subsequent piece of data. Demonstrates use of workflow concatenation, module configuration, partial workflow application, and complex types across modules including binary data.

Has multiple workflows exposing a http endpoint and connecting to a Postgres sample database.

