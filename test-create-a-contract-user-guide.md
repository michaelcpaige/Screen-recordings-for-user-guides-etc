# Test User Guide: Create a Contract

This guide was generated from the uploaded Edge recording JSON for **Create a Contract**.

## Purpose
Use this test to verify that a user can open the **New Contract** form and enter the core contract details.

## Prerequisites
- Access to `https://v-vsncrea-p01.tvo.org/WebPages/#/app/acquisitions/contracts`
- Permission to create contracts
- The Contracts page loads successfully

## Test Data
- **Name:** `test`
- **Department:** `Adult`
- **Fiscal year:** `1999`
- **Description:** `desc`
- **Contract type:** first option in the Contract type list

## Steps
1. Open the Contracts page:
   - `https://v-vsncrea-p01.tvo.org/WebPages/#/app/acquisitions/contracts`
2. Verify the **VSNCrea** Contracts page loads.
3. Click **New**.
4. In **Name**, enter `test`.
5. Open **Select Department**.
6. Choose **Adult**.
7. In **Fiscal year**, enter `1999`.
8. In **Description**, enter `desc`.
9. Open **Select Contract type**.
10. Choose the first available contract type.

## Expected Results
- The New Contract form opens from the Contracts page.
- The Name field accepts `test`.
- The Department field updates to `Adult`.
- The Fiscal year field accepts `1999`.
- The Description field accepts `desc`.
- A Contract type can be selected successfully.

## Notes
- The recording captures data entry only.
- The recording does **not** include a final save or submit action, so contract creation completion is not verified by this test.
