<!-- add-breadcrumbs -->
#Difference Entry

As per accounting standards, the debit in a accounting entry must be equal to the credit. If not, the system does allow submission of accounting transaction, thereby stopping the ledger from posting. In ERPNext, on saving an accounting entry, the system validates if the debit and credit is tallying.

<img alt="Debit Credit Not Equal" class="screenshot" src="{{docs_base_url}}/assets/img/articles/difference-entry-1.png">

To have your entry balanced, you should add one more row, select another account, and update the difference amount in it. Or you can add the difference amount in one of the Account's row itself.

On clicking the 'Make Difference Entry' button, a new Row will be added under the Journal Entry Accounts table, with the difference amount. You can edit that row to select an appropriate Account.

<img alt="Debit Credit Not Equal" class="screenshot" src="{{docs_base_url}}/assets/img/articles/difference-entry-2.gif">

On selecting an account under new row, the debit and credit entries will be tallying, and you should be able to submit the Journal Entry correctly.

<!-- markdown -->

{next}
