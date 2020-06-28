Hello everyone, I have implemented the test jinn network to check the number of saved transactions and the amount on the sender's account, as I wrote above.
Parameters will be dynamically changed via sending from me, so that we can quickly respond to external changes. We can also disable such checks.

JINN_CONST.TX_PRIORITY_MODE-enabling priority mode
JINN_CONST.TX_PRIORITY_LENGTH - depth view of the blocks
JINN_CONST.TX_BASE_VALUE-base for calculating the allowed number of transactions for a period
JINN_CONST.TX_FREE_COUNT - number of free transactions in the block
