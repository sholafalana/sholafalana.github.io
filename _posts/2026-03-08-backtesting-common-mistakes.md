---
layout: post
title: "5 Common Backtesting Mistakes That Wreck Your Results"
description: "Backtesting is essential — but done wrong it gives you false confidence. Avoid these five pitfalls to get results that actually hold up in live trading."
category: "Strategy"
read_time: "6 min read"
date: 2026-03-08
---
<p>Backtesting lets you evaluate a trading strategy against historical data before risking real money. Done well, it's an invaluable tool. Done poorly, it produces results that look spectacular but collapse the moment you go live. Here are the five most common mistakes.</p><h2>1. Overfitting (Curve Fitting)</h2><p>Overfitting happens when you optimise your strategy's parameters so precisely to past data that it captures noise rather than genuine market patterns. The fix: use out-of-sample testing, walk-forward optimisation, and keep your parameter count low.</p><h2>2. Ignoring Spread and Slippage</h2><p>Many traders backtest at zero spread or unrealistically tight spreads. In live trading, spread costs are real — especially for scalping strategies. Always model realistic spread and slippage.</p><h2>3. Look-Ahead Bias</h2><p>Look-ahead bias occurs when your strategy accidentally uses future data to make past decisions. Always ensure your signals use data that was genuinely available at the point of execution.</p><h2>4. Using Insufficient Data</h2><p>Testing on 6 months of data gives a narrow picture. Test across multiple years and multiple market regimes to validate robustness.</p><h2>5. Ignoring Drawdown</h2><p>A strategy that returned 300% over three years might look great — until you see it had a 60% drawdown in year two. Always evaluate maximum drawdown, drawdown duration, and the psychological feasibility of surviving the worst periods.</p>
