

### 1. Nominal Returns:
\[
\text{Nominal Return} = \frac{\text{Final Value of Investment} - \text{Initial Value of Investment}}{\text{Initial Value of Investment}} \times 100
\]

### 2. Effective Returns:
\[
\text{Effective Annual Rate (EAR)} = \left(1 + \frac{i}{n} \right)^n - 1
\]
where \( i \) is the nominal interest rate and \( n \) is the number of compounding periods per year.

### 3. Absolute Returns:
\[
\text{Absolute Return} = \frac{\text{Ending Value} - \text{Beginning Value}}{\text{Beginning Value}} \times 100\%
\]

### 4. CAGR (Compound Annual Growth Rate):
\[
\text{CAGR} = \left(\frac{\text{Ending Value}}{\text{Beginning Value}}\right)^{\frac{1}{n}} - 1
\]
where \( n \) is the number of years.

### 5. Real Return (Inflation Adjusted):
\[
\text{Real Return} = \frac{1 + \text{Nominal Return}}{1 + \text{Inflation Rate}} - 1
\]

### 6. Tax Adjusted Return:
\[
\text{Tax Adjusted Return} = \text{Nominal Return} \times (1 - \text{Tax Rate})
\]

### 7. Real Tax Adjusted Return:
\[
\text{Real Tax Adjusted Return} = \left(\frac{1 + \text{Tax Adjusted Return}}{1 + \text{Inflation Rate}}\right) - 1
\]

### 8. IRR (Internal Rate of Return):
The IRR is the rate \( r \) that satisfies the equation:
\[
0 = \sum_{t=0}^{n} \frac{C_t}{(1 + r)^t}
\]
where \( C_t \) is the cash flow at time \( t \).

### 9. XIRR (Extended Internal Rate of Return):
The XIRR is computed using a similar formula to IRR but accounts for the specific dates of cash flows:
\[
0 = \sum_{t=0}^{n} \frac{C_t}{(1 + r)^{\frac{d_t - d_0}{365}}}
\]
where \( d_t \) is the date of the cash flow \( C_t \), and \( d_0 \) is the date of the first cash flow.
