# Algorithmic-Trading-in-Python

 3 Key Learings:
	
  1.Learn to Analyze market data with python
	
  2.Design your own trading strategies
	
  3.Automate your trading strategies
  
  Book That help :
  
 Book read a vast number of books available on this subject. I have come to find that while there are a lot of good books out there that actually help you gain useful information, there are even more books that are just pure play marketing material shoved down the throats of the ignorant reader.

Below are my recommendations of books, categorized based on different aspects of the business that you may be interested in understanding.

Basics: For the layman who is new to this field and wants a headstart.
1) Inside the Black Box by Rishi Narang - Great book for a headstart on all the different aspects of quant trading. Very general information, but broadly brushes through every aspect of the business.
2) Quantitative Trading by Ernie Chan - Perfect book to get started on all the basic concepts with details on backtesting and some simple strategies to get started on with.

Programming: Depends, which platform you want to use. There are tons of books and online tutorials available on each programming language. I'd recommend the following on Python and Java.
1) Learning Python by Mark Lutz - Covers basics of python. Good to get you started.
2) Head First Java by Kathy Sierra - Great book on JAVA, right from basics to advanced.

Market Microstructure: Before you learn anything about algo strategies, it is most important to understand how trading works and how the different stakeholders interact with each other to create a market.
Trading and Exchanges by Larry Harris - Covers market microstructure in grave depth. A must read before diving into strategies to get a good understanding of the markets.

Strategies: Good books on strategies of varied nature (Momentum, Trend Following, Pairs Trading, Greeks etc). I have also categorized these books based on the kind of strategies that the books focus on.
1) Algorithmic Trading by Ernie Chan - A more advanced book by Ernie, with a number of interesting strategies to try out and backtest. Lot of good theory explaining the basic concepts behind the existence of different types of market behaivour and how to capture them.
2) Mechanical Trading Systems by Richard Weissman - Great book for strategies. Covers a plethora of momentum and mean reversion strategies on multiple time frames, along with backtested results.
3) Following The Trend by Andreas Clenow - I consider this book, one of the best reads on the topic of Trend Following, a very popular trading strategy.
4) Pairs Trading by Ganapathy Vidyamurthy - Very good book on a popular trading strategy known as Pairs Trading.
5) How to Make Money in Stocks by William O Neil - An excellent read on a very interesting fundamentals based quant model, called CANSLIM.

Options Strategies: I cover options strategies under a different topic, considering that they are much more complex as compared to equities/futures.
1) Options Volatility and Pricing by Sheldon Natenberg - One of the best books on options for a begginer, working your way up from the basics all the way upto greeks and volatility trading.
2) The Bible of Options Strategies by Guy Cohen - Good book to get upto speed on all the different options setups and their specific greeks.
3) Volatility Trading by Euan Sinclair - Very advanced and in depth book on the concept of Volatility Trading. I believe it to be the best on this subject.

Risk Management: The most imporatant aspect of quant trading which is often overlooked.
Position Sizing by Van Tharp - A gem of a book that explains the idea of risk management and money management using different techniques.

My advice to a budding algo trader would be to research thoroughly before going live with a strategy. Consider yourself a risk manager rather than a money manager. Managing risk comes first, then come returns.




#### SOme comment from trading experts :


1.  I would like to learn algo trading. Where should I start?
I have started coaching/helping a talented programmer/friend who refuses to watch “keep up with Kardassians” and other enlightening TV shows at night. He wants to do something productive.

There are three distinctive skill sets involved:

programming, as in the ability to translate concepts and techniques into eligible code
market knowledge, as in distinguishing what really matters from the ambient noise and
psychology, as in the ability to watch your car crash in slow motion and then start again
Programming

Check out Luca Parlamento. He publishes some interesting libraries on Python on his Twitter. Check out Timothy Gouskov and Qiao Wang: they are legit HFT traders.

You can check various platforms such as quantocracy, qplum, quantstart and a few others which names I forget. They are on this lovely thing called the worldwideweb. Most of them are for beginners to intermediates. They will cement basic concepts.

One drawback is their insistence on signal processing. This is a tropism I have noticed with a lot of professional quants. They want to purify signal from noise. It is noble, but you can’t achieve superior returns only with better entries.

Market knowledge

90% of the market gurus are charlatans, the other half don’t share their secret sauce.

Case 0: do not subscribe to paying market newsletters

Case 1: 0 exception to Case 0

Forget also about all the finance gurus, strategists, analysts and what not. I used to compile their forecast accuracies for years. I took their forecasts for the year to come, compared with the actual one year down the road, repeated over 1, 3, 5 years. Those clowns make weather forecasters, fortune tellers and politicians look good.

This is the only formula that will ever matter.

Trading edge = Win% * Avg Win% - Loss% * Avg Loss%

Cliff Asness publishes interesting stuff. You can also go to SSRN as well. Vastly academic though. Van Tharp is good too. There are quite a few people who are genuine. They usually do not charge, but share. Go to Andrew Swanscott’s podcast and of course my buddy Michael Covel. You can forget about Fama & French: they have no live track record. Rationale is: would you trust a chef who has never spent a day in a restaurant’s kitchen?

Read all the classics: Schwager, Lefebvre, Loeb, Darvas, Covel, etc.

Remember those three axioms:

complexity is a form of laziness: you will be tempted to decorate your strategy like a Christmas tree. If you have not found a simple and elegant solution, then you have not worked hard enough.
profits look big only to the extent losses are kept small: focus relentlessly on losses, particularly false positives. Profits do take care of themselves
money is made in the money management module: whether you bet 1$ or 1,000$, outcome and sustainability will be different.
Psychology

Why do you need to focus on psychology? It is one thing to build a Ferrari, it is another to have the testicular fortitude to drive it

Van Tharp does a good job. Brett Steenbarger publishes good stuff too.

Rande Howell remains my favourite. He has a radically different approach from anyone else. He uses Jung Pearson Miller archetypes to rewire the trading committee. This is transformative work. He coaches at Van Tharp come and train with him… He was my coach.

As a professional short seller, I grew more interested in neurosciences, the hard wiring behind psychology. I simply need close quarter combat trading psychology to do my job. So, I bundled up a bunch of techniques that will be explained in my book, one of them I taught to an ex-fighter pilot who flies commercial now. The guy clocked his 2nd ever best score in commercial flight sim after trying it. I just could not believe it myself !!!

This list is far from exhaustive. Those are the three areas you need to focus on. Best of luck and enjoy the journey!








2.   Why do people conduct algo trading for companies but not for themselves?
I’m a systematic trader, trading both fully automated and non-automated mechanical algorithms.

I just woke up here in Bangkok, checked the markets (first thing I do in the day). It’s 4.40am on Saturday, sleeping in is for employees.

This is a screencapture of the daily profit/loss for my last few weeks


And this is why most algo traders for companies prefer it that way. Out of the last 9 trading days I lost money on 5 of them. On some of those days I lost quite a lot of money.

I haven’t made a mistake in several months. These last few weeks represent literally perfect trading. And I lost money.

At a glance it’s quite difficult to know if I am even profitable.

Most people find it incredibly difficult to do a job well, and still lose money most days. And most professional traders lose money on more days than they win.

Generally it brings up strong feelings, which tend to induce mistakes, which make more errors in a feedback loop.

Honestly, if I wasn’t an unemployable ex-con I’d prefer to do it on someone else’s dime and clock a salary too!







3.   What is the future of algorithmic trading?
Originally Answered: What is the future of Algorithmic Trading?
Jeff Bezos of Amazon said this:

“I very frequently get the question: 'What's going to change in the next 10 years?'

And that is a very interesting question; it's a very common one.

I almost never get the question: 'What's not going to change in the next 10 years?'


Jeff Bezos has certainly changed

Instead of thinking what about algorithmic trading is going to change in the future, think of what about it is not going to change.

There are 3 things that aren’t going to change.

1st: Getting there first won’t change

The faster trader wins.

Spotted the same futures being priced differently at 2 separate exchanges? Be the first to buy the cheaper one and short the pricier one.

Spotted a slow hedge fund buying tons of XXX shares at one exchange? Be the first to buy all the XXX shares at the other exchanges and sell it back to the slow poke at a higher price.

This is the world of high frequency trading.

2nd: Information advantage won’t change

The trader with the better information wins.

Get data on foot traffic. See which branded bag stores are people going to.

Get satellite imagery data on stockpiles. See which timber company can’t clear their inventory.

This is the world of alternative data.

3rd: Better analysis won’t change

The trader who can analyse data more effectively wins.

Use machine learning models to:

Analyse large quantities of data without being explicitly told what to look for
Understand texts (in large quantities and different languages)
Interpret images
Output a prediction fast
This is the world of… yup, machine learning.







4.  What books do you recommend for someone to get into algorithmic trading at a beginner level? It would be better if you mention books that also teach profitable algorithmic trading strategies. I want to be able to trade for a hobby.
“Trade for a hobby” is a good way to put it, because hobbies are an expense, not a source of revenue.

I’m not trying to be a jerk, I just need to be 100% brutally honest with you, because you deserve the truth.

If you do want to trade as a hobby, the straightforward route is to join a hobbyist community, such as Quantopian or Quantiacs. They have lots of resources, including book lists.

If you’d like some ideas from me (your mileage may vary), I might combine self-study and experimentation through the following steps:

Read stories of successful traders while learning to manipulate data in Excel

Market Wizards

A Man for All Markets

How I Made $2, 000, 000 in the Stock Market

The Alchemy of Finance

The Quants

While doing this, grab historical data from Yahoo! Finance and create your own backtest spreadsheet to simulate real entries and exits, with a simulated P&L, from real data.

Gain knowledge about markets while advancing to Python

Investor's Business Daily Guide to the Markets

Random Walk Down Wall Street

Security Analysis

Beating the Street

Studies in Tape Reading

At the same time, use Python to recreate those models you built in Excel. Now start experimenting with new trading ideas.

Learn trading psychology while executing your first live trades

Reminiscences of a Stock Operator

Trading in the Zone

The Intelligent Investor

The Disciplined Trader

The Complete Turtle Trader

At the same time, open an account with a broker (Interactive Brokers is popular, though I’ve not used it personally), using money you 100% expect to lose. This is your first semester of tuition. Start executing some of the trades you developed above.

Advance to specialist books while developing your own trading systems

Dual Momentum Investing

CFA Program Curriculum

Market Microstructure For Practitioners

A Complete Guide to the Futures Market

Option Volatility & Pricing

Now you’re ready to pay up the rest of your tuition. Put more money in an account and expect to lose 100% of it again.

At this point, you’ve learned to trade as a hobby. Now think through everything you’ve done — what worked, what failed — and create something by yourself that you can be proud of.


