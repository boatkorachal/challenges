# TAMBOON

This is a challenge project to see how good you are with Elixir or NodeJS. Included in this
repository is a CSV file of Song-pah-pa (ซองผ้าป่า). It is a white envelope with money
inside and the donor name printed on the front. They are usually collected from
multiple people in order to round up money to repair or construct new temple buildings.

But we're a payment gateway, we can do better than that. The envelope will contain,
instead, a valid credit card number (fake ones, not a real working card) and the desired donation
amount.

### EXERCISE

Write a program that, when given the CSV file, calls the [Charge API][0] to
make donations by creating a charge for each donation and produce useful summary such as
`total donations`, `successful charges`, `failed charges`, `average amount per person`, `top x donators`.

### EXAMPLE INPUT

* `donations.csv` - An example CSV file contains list of donator's name, credit card number and donation amount.

**Requirements:**

* Make donations by creating Charges to Omise.
* Produce a brief summary as an output.
* Handle errors gracefully.

**Bonus:**

* Write readable and maintainable code.
* Handle rate limit that might occurs.
* Ensure reproducible build on every machine.

 [0]: https://www.omise.co/charges-api
