# metacoin
truffle

## Test cases explained

### mc2.js

This shows how multiple tests {t1, t2, t3} interact with each other.  Each subsequent
test picks up where the previous test leaves off.  This test also shows
**sendCoin** running three times in a row prior to checking any balances.
