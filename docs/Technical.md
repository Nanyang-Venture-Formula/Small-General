# docs

This is a template for docs deploying to gh-pages


# LEDs

Calculations for Current Limiting Resistors (CLRs):

Taking into consideration the LED's $V_{F}$ and $I_{F}$, and input Voltage $V_{IN}$: 

we can calculate the CLR with the formula $R = \dfrac{(V_{IN}-V_{F})}{I_{F}}$.

### User LED.

| Factor     | Value |
| ---------- | ----- |
| $V_{IN}$ | 3.3V  |
| $V_{F}$  | 2.5V  |
| $I_{F}$  | 4mA   |

$R = \dfrac{(V_{IN}-V_{F})}{I_{F}} = \dfrac{(3.3-2.5)}{0.004} = 200 \Omega$
