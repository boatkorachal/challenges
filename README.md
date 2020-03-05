# ELIXIR-TAMBOON

This is a challenge project to see how good you are with Elixir. Included in this
repository is a CSV file of Song-pah-pa (ซองผ้าป่า). It is a white envelope with money
inside and the donor name printed on the front. They are usually collected from
multiple people in order to round up money to repair or construct new temple buildings.

But we're a payment gateway, we can do better than that. The envelope will contain,
instead, a valid credit card number (fake ones, not a real working card) and the desired donation
amount.

### CONTENTS

* `donations.csv` - A CSV file contains list of donator's name, credit card number and donation amount.

### EXERCISE

Write a program that, when given the CSV file, calls the [Charge API][0] to
make donations by creating a charge for each row in the file and produce an useful summary output such as
`total donations`, `successful charges`, `failed charges`, `average amount per person`, `top x donators`.

**Requirements:**

* Make donations by creating a Charge to Omise for each row in the CSV.
* Produce a brief summary as an output.
* Handle errors gracefully, without stopping the entire process.
* Writes readable and maintainable code.

**Bonus:**

* Have a good project structure.
* Be a good internet citizen and throttles the API call if we hit rate limit.
* Run as fast as possible on a multi-core CPU.
* Ensure reproducible builds on your workspace.

 [0]: https://www.omise.co/charges-api
