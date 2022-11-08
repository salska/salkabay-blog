---
title: Borgas
date: '2022-10-19'
tags: ['trading', 'python', 'borgas']
draft: false
summary: A python based trading app using AI pattern matching to identify trading opportiuities.
authors: ['default']
---
### A machine learning-based methodology for pattern matching of historical and live stocks data and key technical indicators is used to guide investment decisions.

# Context
Many speculators are attracted to the wealth creation potential of financial
markets. Knowing when to buy a stock at exactly the right time and then sell
to achieve the greatest profit is invariably a difficult task. Very few make any
real money out of it. 

It is one of the hardest things to learn and apply with
discipline. Many people may buy at the right time but get the entry price
(buy) wrong or will sell at the wrong price. Emotions often get the better of us
and impatience often results in losses. The market does not beat us. We beat
ourselves, because we do not have a clear trading plan and cannot sit tight
during volatility.

Professional investors use a multitude of tools and systems to guide
investment decisions. From fundamental analysis through to technical
analysis, many tools are available to help. Market booms and panics are
driven by the greed and fear psychology of crowd behaviour. The dynamics
of fear and hope has stood the test of time and is always reflected in the
patterns of every financial asset.

Rather than attempt to model human behaviour, I
wrote borgas using python to perform pattern matching of the current
profile of a stock against a historical database of 50+ assets over many
decades of historical data. Unlike many model based
systems, borgas does is not hampered with curve fitting issues. 

The machine learning approach identifies and presents the historical patterns
ranked in order of best-fit for the user to browse. Each pattern can then be
inspected to decide the likely future price move.

Financial markets are very high risk and everyone will make a huge number
of mistakes that will cost dearly. These losses are very painful but should
also be educational. The markets teach us humility and it will crucify us for
our mistakes. borgas teaches to better time your stock purchase and
whether the price is likely to rally quickly or declibe further before recovery. It
will also teach you to maximise your gains with the likely gains to expect and
timing. Successful investors minimise their losses and maximise the odds in
their favour in order to win.

borgas will map out a visual and easy to follow trading plan rather than
flying blind and on emotion. The system uses a huge database of asset
prices and basket of indicators to alert you to similar patterns that match the
asset you are about to trade. The machine learning algorithms will identify
best fit matches and follow-on price action to help you assess the risk and
adjust the investment accordingly.

# Borgas Trading App
The original Borgas App was written in matlab as a series of algorithms to prototype the import and display of asset price candle bars. Simple technical indicators were developed and to overlay on price charts.

A python based borgas app was then developed to implement an interactive solution with pattern matching capabilities.

An enhanced version of this tool could be developed as a web-based subscription service.

## Capabilities
- import and display selected asset prices
- live web-based refresh of asset prices to keep them up to date
- overlay key simple moving average technical indicators
- tag and mark key technical patterns
- perform normalised pattern matching and listing of asset price and technical patterns across all assets
## References
