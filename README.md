# Solana wallet checker

Ocinct checks a Solana wallet before you copy trade it. Paste an address in Telegram. You get a score from 0 to 100 and the numbers behind it.

Bot: https://t.me/ocinctbot
Site: https://ocinct.com

Free plan: 3 scans a day. No wallet connection.

## What one scan shows

Score and grade from A to F.
Profit taken over 30 days and over 7 days. Realized only. Open positions are shown apart.
Share of tokens sold in profit.
Return on the money spent.
Median hold time.
Risk tags: sniper. bundler. rat trader. dev team. sandwich bot.
Who funded the wallet. Then who funded that one.

## How the score works

Five parts add up to 100.

Profit taken over 30 days: 30 points on a log scale.
Tokens sold in profit: 25 points between 30% and 70%.
Return on money spent: 15 points.
Consistency: 15 points. Last week profitable and few tokens that lost over half.
Activity: 10 points. Trades this week and tokens this month.

Each risk tag removes 20 points. Cap at 40. Large open losses remove 10.

A from 80. B from 65. C from 50. D from 35. F below.

The full weights are on https://ocinct.com/how-it-works with a live version.

## Why a score instead of a leaderboard

A leaderboard ranks by profit. A sniper with a 90% win rate looks good on it. So does a bundler. So does a wallet that stopped trading last week. The score reads the trades and tags the pattern. It also shows who funded the wallet. Ten leaderboard wallets funded by the same relay are one operator.

## Guides

https://ocinct.com/guides/why-a-90-percent-win-rate-is-a-warning-sign
https://ocinct.com/guides/how-to-trace-who-funded-a-solana-wallet
https://ocinct.com/guides/how-to-find-profitable-solana-wallets-to-copy-trade
https://ocinct.com/pricing
