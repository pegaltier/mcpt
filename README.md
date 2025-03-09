# Source

- from neurotrader youtube channel: https://youtu.be/NLBXgSmRBgU
- another similar youtube video: https://youtu.be/3zI_l_P-lF8
- book1: https://www.amazon.com/Permutation-Randomization-Trading-System-Development/dp/B084QLXFKW?sr=8-2&language=en_US&ref_=as_li_ss_tl
- book2: https://www.amazon.com/Testing-Tuning-Market-Trading-Systems/dp/148424172X?psc=1&language=en_US&ref_=as_li_ss_tl

# Strategy

## Step 1: optimize
- donchian on btcusdt 1h
- lookback from 12 to 169
- best lookback 19 and profit factor 1.08

 ## Step 2: test
 - in sample monte carlo permutation test
 - create between 100 and 1000 random permutation of historical price
 - optimize the strategy variables on these random historical price
 - the optimized strategy on real price must be better than all the optimized on random
 - it's a proof that the strategy use a real force in the market and not an artifact of noise
