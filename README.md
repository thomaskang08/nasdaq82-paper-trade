# NASDAQ-82 Paper Trade

A forward paper-trading record for a long/short strategy on 82 NASDAQ names,
run in an Interactive Brokers paper account from $100,000.

`index.html` is regenerated after every trading session and published here. It
shows the account value, every holding, what the broker actually filled, and the
orders decided for the next session.

Simulated money. Each day's orders are written to disk and hashed before the
opening price they trade at exists, so no future information can reach them.
