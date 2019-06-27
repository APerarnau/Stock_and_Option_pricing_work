# Stock_and_Option_pricing_work
## calls_color2-2_Leg.ipynb Notebook

### Extension of the code for one option is presented here for two options. Extending this to an arbitrary amount of options is straightforward.
The use of this code is the same as before but is it repeated here as a recap.

### General inputs and parameters:

**Ifree**:		‘risk free’ interest rate %

**Div**:		stock dividend %

**Precio**:		stock price

### The parameters deltaPrecio, subDays and subPrices control the display:

**deltaPrecio**:	range around stock price of the plot

**subDays**:	interval for calculations skip. Too many the graph will be cluttered; too few it will lack features.

**subPrices**:	idem as before but for prices.


### Specific Option#  (1 or 2) data

**exPrecio#**:	exercise Price of the option

**vol#**:		option volatility

**pagado#**:	if True the option was bought if False the option was sold

**opPrecio#**:	option’s price (bought or sold)

**esCall#**:		IF True the option was a CALL if false it was a PUT

**no#**:		number of options bought or sold


### There are two extra displays in addition to the ‘Spectral’, both use the ‘seismic’ reversed palette. This palette has the advantage of contrasting high/low end colors which I can see easily, but also, by centering the color bar around zero the neutral, or zero gain boundary, can be visualized. This is very useful when using these strategies because the profit/loss frontier is explicitly there to see. 
### This type of visualization is far more useful than the traditional ‘time slices’. Kudos to http: https://www.optionsprofitcalculator.com for the original idea. In here I did the personalization that I wanted.
