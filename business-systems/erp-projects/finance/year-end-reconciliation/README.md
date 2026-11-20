# Year-End Financial Reconciliation & Closing Procedure

## 1. Purpose

The purpose of this procedure is to establish a standardized year-end financial reconciliation and closing process within SAP Business One. The procedure ensures that financial transactions, subsidiary ledgers, and General Ledger balances are reviewed, reconciled, and validated before the fiscal year is finalized and the subsequent fiscal year begins.

## 2. Scope

This procedure covers:

- Inventory valuation and reconciliation
- Accounts Receivable and Accounts Payable
- Customer and vendor down payments
- Bank and checking account reconciliation
- Outstanding checks and deposits in transit
- Fixed asset and depreciation reconciliation
- General Ledger review
- Year-end adjusting journal entries
- Financial statement review
- Period-End Closing Utility
- Profit and Loss account closing and equity transfer
- Fiscal year transition

## 3. Roles & Responsibilities

**Accounting / Finance Users**
- Perform assigned reconciliations.
- Review financial reports and outstanding transactions.
- Investigate discrepancies.
- Prepare supporting schedules.

**Accounting Manager / Controller**
- Review and approve reconciliation results.
- Approve adjusting journal entries.
- Validate financial statements.
- Approve year-end closing activities.

**Business Systems / ERP Support**
- Support SAP Business One reporting and troubleshooting.
- Investigate system-related discrepancies.
- Assist with financial system configuration and period-end closing activities.

## 4. Year-End Closing Procedures

### Step 1: Inventory Valuation and Reconciliation

1. Generate the Inventory Audit Report as of the fiscal year-end.
2. Review inventory quantities and valuation by item and warehouse.
3. Identify negative inventory, unusual valuation changes, and discrepancies.
4. Review inventory adjustments and outstanding goods receipts or deliveries.
5. Generate the corresponding General Ledger inventory account balances.
6. Compare inventory valuation totals against the inventory control accounts.
7. Investigate and document discrepancies.
8. Obtain approval for required inventory adjustments.

**Expected Result:** Inventory valuation agrees with the corresponding GL inventory control accounts.

### Step 2: Accounts Receivable Reconciliation

1. Generate the Accounts Receivable Aging Report as of fiscal year-end.
2. Review outstanding customer invoices, credit memos, and unapplied payments.
3. Identify overdue balances and unusual customer account activity.
4. Review customer down payment balances and outstanding applications.
5. Generate the corresponding AR General Ledger balances.
6. Compare the AR aging totals against the GL control accounts.
7. Investigate discrepancies and document outstanding items.
8. Review potentially uncollectible balances with management.

**Expected Result:** Customer balances are reviewed and reconciled to the corresponding GL control accounts.

### Step 3: Accounts Payable Reconciliation

1. Generate the Accounts Payable Aging Report as of fiscal year-end.
2. Review outstanding vendor invoices, credit memos, and unapplied payments.
3. Identify overdue vendor balances and unresolved transactions.
4. Review vendor down payment balances and outstanding applications.
5. Generate the corresponding AP General Ledger balances.
6. Compare AP aging totals against the GL control accounts.
7. Investigate discrepancies and document outstanding items.
8. Review unrecorded liabilities and outstanding vendor invoices with management.

**Expected Result:** Vendor balances are reviewed and reconciled to the corresponding GL control accounts.

### Step 4: Customer and Vendor Down Payment Reconciliation

1. Generate reports identifying outstanding customer and vendor down payment documents.
2. Review unpaid down payment invoices.
3. Identify payments received or made that have not been applied to final invoices.
4. Verify that down payment balances are recorded in the appropriate GL accounts.
5. Compare down payment balances against the applicable GL accounts.
6. Investigate unusual or aged balances.
7. Document outstanding transactions requiring follow-up.

**Expected Result:** Down payment balances are accurately recorded, classified, and reconciled.

### Step 5: Bank and Checking Account Reconciliation

1. Obtain the final bank statements for the fiscal year.
2. Review checking account GL balances.
3. Complete bank reconciliations through the fiscal year-end date.
4. Identify outstanding checks that have not cleared the bank.
5. Review deposits in transit and unidentified bank transactions.
6. Investigate stale-dated checks and long-outstanding reconciling items.
7. Review bank fees, interest, transfers, and other transactions requiring recording.
8. Document remaining reconciling items and their subsequent resolution.

**Expected Result:** Bank accounts are reconciled, with outstanding checks and other timing differences properly documented.

### Step 6: Fixed Asset and Depreciation Reconciliation

1. Generate the fixed asset listing as of fiscal year-end.
2. Review asset acquisitions, disposals, transfers, and retirements.
3. Verify asset classifications, acquisition costs, and in-service dates.
4. Review useful lives and depreciation methods.
5. Execute or validate depreciation calculations for the fiscal year.
6. Compare accumulated depreciation against the corresponding GL accounts.
7. Compare depreciation expense against the appropriate expense GL accounts.
8. Investigate discrepancies and document required adjustments.
9. Review asset additions and disposals for appropriate financial treatment.

**Expected Result:** Fixed asset cost, accumulated depreciation, and annual depreciation expense are validated against the corresponding financial accounts.

### Step 7: General Ledger Review

1. Generate the final Trial Balance for the fiscal year.
2. Review balance sheet and income statement accounts.
3. Confirm that subsidiary ledger reconciliations are completed.
4. Investigate unusual balances and unexpected account fluctuations.
5. Review suspense, clearing, and temporary accounts.
6. Review manual journal entries and adjusting entries.
7. Verify that required accruals, prepayments, and other adjustments have been evaluated and approved.
8. Document outstanding discrepancies for management review.

**Expected Result:** General Ledger balances are reviewed and supported by appropriate reconciliation documentation.

### Step 8: Year-End Adjusting Journal Entries

1. Review proposed year-end adjustments with the accounting manager.
2. Evaluate required accruals, prepaid expenses, depreciation, and other adjustments.
3. Review applicable inventory adjustments and asset disposals.
4. Verify supporting documentation for each adjustment.
5. Obtain required approvals.
6. Record approved journal entries in SAP Business One.
7. Verify that journal entries were posted to the appropriate GL accounts.
8. Rerun relevant financial reports to validate updated balances.

**Expected Result:** Approved year-end adjustments are accurately recorded and reflected in the final financial balances.

### Step 9: Financial Statement Review

1. Generate the final Balance Sheet.
2. Generate the Income Statement (Profit and Loss).
3. Generate the Trial Balance.
4. Review account classifications and balances.
5. Compare current-year financial results against prior-year results.
6. Investigate significant variances.
7. Confirm that supporting reconciliations are complete.
8. Submit financial statements and supporting documentation for management review.

**Expected Result:** Financial statements are supported by reconciled account balances and approved adjustments.

### Step 10: Execute the SAP Business One Period-End Closing Utility

**Objective:** Close the fiscal year's Profit and Loss accounts and transfer the resulting financial balance through the designated closing account into the Retained Earnings equity account.

**SAP Business One Navigation:**

Administration → Utilities → Period-End Closing

**Preparation:**

1. Confirm that all year-end reconciliations have been completed.
2. Verify that all required financial transactions and adjusting journal entries have been posted.
3. Generate and retain a final pre-closing Trial Balance and financial statements.
4. Confirm that a database backup has been completed.
5. Verify that the appropriate posting periods are available for the closing process.
6. Confirm that the Period-End Closing Account and Retained Earnings Account are correctly configured in the chart of accounts.

**Execution:**

1. Open the Period-End Closing utility.
2. Select the fiscal year and the applicable posting period range.
3. Select the Profit and Loss accounts to be closed.
4. Specify the designated Period-End Closing Account.
5. Specify the Retained Earnings Account.
6. Execute the utility to generate the proposed closing journal entries.
7. Review the proposed account balances and closing entries.
8. Verify the posting dates and journal entry details.
9. Approve and execute the closing transactions.

**Understanding the Closing Entries:**

SAP Business One generates two corresponding journal entry transactions:

**First Journal Entry – Fiscal Year-End**

- Transfers the individual revenue and expense account balances into the Period-End Closing Account.
- Uses the final day of the fiscal year as the posting date.
- Clears the individual Profit and Loss account balances.

**Second Journal Entry – First Day of the New Fiscal Year**

- Transfers the resulting balance from the Period-End Closing Account into the Retained Earnings Account.
- Uses the first day of the subsequent fiscal year as the posting date.
- Establishes the accumulated annual profit or loss within equity.

The Period-End Closing Account functions as a temporary clearing account between the two transactions.

**Expected Result:** Profit and Loss accounts are closed, and the resulting annual profit or loss is transferred into the designated Retained Earnings equity account.

### Step 11: Validate Closing Entries and Complete Fiscal Year Transition

1. Review the journal entries generated by the Period-End Closing utility.
2. Verify that all applicable Profit and Loss accounts have been cleared.
3. Confirm that the Period-End Closing Account reflects the year-end closing result.
4. Verify that the subsequent-period journal entry transfers the balance into Retained Earnings.
5. Generate the Balance Sheet and Trial Balance to validate the closing transactions.
6. Confirm that balance sheet account balances carry forward appropriately into the new fiscal year.
7. Review the new fiscal year's posting periods and accounting period settings.
8. Once all approvals and validations are complete, update posting period statuses according to company policy, including locking the prior fiscal year where appropriate.

**Expected Result:** The prior fiscal year is properly closed, the annual profit or loss is reflected in equity, and the subsequent fiscal year is ready for business transactions.

## 5. Year-End Reconciliation Documentation

Each reconciliation should include:

- Fiscal year and reporting date.
- ERP subledger report and corresponding GL report.
- Beginning and ending balances, where applicable.
- Identified variances.
- Explanation of reconciling items.
- Supporting schedules and documentation.
- Corrective actions and adjusting journal entries.
- Preparer and reviewer information.
- Completion date and approval status.

## 6. Year-End Completion and Sign-Off

Before considering the year-end process complete:

1. Verify that all required reconciliations have been performed.
2. Confirm that outstanding financial items have been investigated.
3. Ensure approved adjustments have been recorded.
4. Verify that financial statements agree with the final Trial Balance.
5. Confirm that Period-End
