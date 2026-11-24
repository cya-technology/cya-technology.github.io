**Custom Financial Reporting – Trial Balance with Cost Center Reconciliation**

Developed a custom Crystal Reports financial reporting solution integrating backend SQL views to provide GL-level trial balances with detailed cost center allocations. Designed hierarchical reporting sections to display individual GL account balances, cost center activity, debit and credit totals, and reconciled ending balances.

**1. Crystal Reports – Custom Trial Balance**
Shows:
- GL account number and description.
- Beginning balance, debits, credits, and ending balance.
- Cost center breakdown nested under each GL account.
- Individual cost center subtotals.
- Grand totals across all accounts.
  
**2. Crystal Reports – Report Design**
Illustrates the grouping structure:
- Group Header: GL Account
- Details: Cost Center
- Group Footer: GL Account subtotal
- Report Footer: Grand total
  
**3. SQL Server – Backend Views**
Shows an example SQL view named vw_GL_TrialBalance_CC, which combines:
- GL account information.
- Cost center information.
- Beginning balances.
- Debit and credit activity.
- Ending balances.
4. Reconciliation Tables
The illustration shows the relationship between transaction-level data, summarized GL balances, and the reporting view.
