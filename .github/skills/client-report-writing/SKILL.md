---
name: metric-calculation
description: Use this skill when the user asks to calculate business metrics like revenue, discount percentage, or demand volatility.
---

# Metric Calculation Skill

When calculating metrics for the food delivery project, follow these exact formulas:
1. **Revenue**: `checkout_price * num_orders`
2. **Discount Percentage**: `(base_price - checkout_price) / base_price`
3. **Demand Volatility**: `Standard Deviation of num_orders / Mean of num_orders` (per meal)

Always output the result as a pandas DataFrame with clear column names and handle any division-by-zero errors by filling with 0.
