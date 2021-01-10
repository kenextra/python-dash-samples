# python-dash-samples

Some data visualization examples with dash

## Setup

1. Install `pip` and `virtualenv` if you do not already have them.

1. Clone this repository:

    ```
    git clone https://github.com/kenextra/python-dash-samples.git
    ```

## How to run a sample

1. Change directory to one of the sample folders, e.g. `dash_avocado_analytics`:

    ```
    cd dash_avocado_analytics/
    ```

2. Create a virtualenv. Samples are compatible with Python 3.6+.

    ```
    python3 -m venv env
    source env/bin/activate
    ```
    *For windows*
    ```
    python3 -m venv env
    env\Scripts\activate
    ```

3. Install the dependencies needed to run the samples.

    ```
    pip install -r requirements.txt
    ```

4. Run the sample:

    ```
    python main.py
    ```

## How to host on GCP

*[Check here](https://cloud.google.com/appengine/docs/standard/python3/quickstart)*