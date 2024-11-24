### Definition: Lookahead

$$(?= r_1)r_2 \approx r_2 \cap (r_1 .^*) $$

### Example 1

$$(?= a^*)(a|b)^* \approx (a|b)^*$$

### Example 2

$$(?= a^+)(a|b)^* \approx a^+(a|b)^* \approx a(a|b)^*$$
