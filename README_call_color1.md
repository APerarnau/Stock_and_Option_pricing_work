# Call Color 1

 
This is the first version of the code I wanted to make. The idea is to have a visualization of how the price of a call option evolve with time.

This is barebones. No fancy IO. I want to test, experiment, and then use the blocks for a more ambitious project.

There are two sets of inputs. The first refers to the stock: no 'risk' interest rate and stock price/dividends. The second are specific to the option: exercise price, beginning and end dates, volatility, call bought or sold and at what price. There are also plotting parameters, like how much to subdivide the time or the price ranges.

There is an example of output, obtained with the uploaded parameters, in a png file.

The output makes sense. If a call is bought for 6.4$ to an exercise price of 300$, at expiration, the buyer will make money only after the price surpasses the exercise plus the money spent in buying the call. The buyer can make money also when the stock were to rise in price earlier in time. However, if the stock does not rise its price the buyer loses money, this is shown in the red region. The roles are reversed when the buyer becomes a seller; if the stock price rises above breakeven, money is lost. When the price goes down or stays, money is made. Obviously this is a naked call.

The color scale is SPECTRAL. Probably not too conventional but the color contrast is good. The user can change the palette.

As usual, these are my experiments. I have tested the code but there is no warranty that it is good or not. Use it at your own risk.
