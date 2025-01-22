<h1>
  <span class="headline">Python ExchangeRate API Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Open your Terminal application and navigate to your `~/development/labs` directory:

```bash
cd ~/development/labs
```

Make a new directory called `currency-exchange-api-lab`, then enter this directory:

```bash
mkdir currency-exchange-api-lab
cd currency-exchange-api-lab
```

Create a new file `currency-exchange-api.py` and copy the code snippet below into the new file.

```bash
touch main.py
```

Before starting the lab exercise, run the following commands:

```sh
pip3 uninstall urllib3
pip3 install 'urllib3<2.0' requests
```

Open the contents of the directory in VSCode:

```bash
code .
```

Follow the instructions found in exercise to complete the Python functionality for requesting currency exchange data.

## Starter Code

```py
# Import requests package

COMMAND = ""
while COMMAND != "q":
    COMMAND = input(
        "Choose [e] to get exchange rates, or [q] to quit: ")
    if COMMAND == "e":
        target_currency = input("Enter the target currency code (ex: EUR): ").upper() amount = float(input(f"Enter the amount in {base_currency}: "))

    # Your code here
```
