# atr-
trading indicator  that you can use To determine tp/sl

# ATR Trading Guide: Stop Loss & Take Profit Strategies

## 1. What is ATR?
**Average True Range (ATR)** is a volatility indicator that:
- Measures market volatility over a set period (default: 14 days)
- Higher ATR = More volatility
- Lower ATR = Less volatility

> 📊 *ATR doesn't predict direction, only volatility intensity*

## 2. Using ATR for Stop Loss (SL)
### Formula:


| Trade Type | Calculation           | Example ($100 entry, $5 ATR) |
|------------|-----------------------|------------------------------|
| **Buy**    | Entry - (2 × ATR)     | $100 - (2×5) = **$90**       |
| **Sell**   | Entry + (2 × ATR)     | $100 + (2×5) = **$110**      |

## 3. Using ATR for Take Profit (TP)
### Formula:


| Trade Type | Calculation           | Example ($100 entry, $5 ATR) |
|------------|-----------------------|------------------------------|
| **Buy**    | Entry + (3 × ATR)     | $100 + (3×5) = **$115**      |
| **Sell**   | Entry - (3 × ATR)     | $100 - (3×5) = **$85**       |

## 4. Risk/Reward Ratio Example
```python
# Sample calculation
entry = 100
atr = 5
sl = 2 * atr  # $10 risk
tp = 3 * atr  # $15 reward

print(f"Risk-Reward Ratio: 1:{tp/sl}")  # Output: 1:1.5




