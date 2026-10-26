# BS23 PO - Clear Bill Breakdown

A mobile-focused food checkout prototype that explains each charge before a customer places a sample order. Built with HTML, CSS, and vanilla JavaScript in a single file.

## Run locally

Clone the repository and open `clear_bill_breakdown.html` in your browser:

```sh
git clone https://github.com/omarsharyr/BS23_PO.git
cd BS23_PO
```

No installation, build step, or server is required.

## Features

- Adjust item quantity and see totals update immediately.
- Switch between delivery and pick-up, with a 10% food subtotal discount for pick-up.
- Select a bill line to see an explanation of the charge.
- Apply `SAVE50` for Tk 50 off a food subtotal of Tk 500 or more. To remove it, clear the voucher field and select **Apply**.
- Review sample delivery and payment details, then place a sample order.
- Reset the checkout to try another scenario.

## Sample pricing

| Item | Amount |
| --- | --- |
| Food | Tk 745 per item |
| Delivery | Tk 17; waived for pick-up |
| Platform fee | Tk 19 per order |
| Illustrative VAT | Tk 43 per item |

One item with delivery totals **Tk 824** before discounts. Pick-up savings are rounded to the nearest whole taka; the voucher can be combined with pick-up savings.

## Project file

[`clear_bill_breakdown.html`](clear_bill_breakdown.html) contains the interface, styles, and checkout logic.

This is a demonstration only. Prices, fees, VAT, customer details, and delivery estimates are illustrative. No real orders or payments are processed, and checkout state resets when the page is reloaded.
