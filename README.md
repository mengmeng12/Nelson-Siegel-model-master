My undergraduate thesis: **Analysis of the characteristics of China's national debt yield curve and macroeconomic variables**

Also see my post [here](https://mengmeng12.github.io/blog/2020/01/06/undergraduate_thesis/)


**Abstract**
Treasury yield curve describes the yield of Treasury bonds with different maturities and the relationship between them. It is generally believed that in an effective financial market, the Treasury yield curve contains abundant economic information, which is of great significance to both micro-economic and macro-economic. In this article, through **Nelson-Siegel-Svensson** model, China and the United States
Treasuries yield curve structures were estimated, and then were showed by the three-dimensional figure.
Compared the descriptive statistics relative to the United States, China's inter-bank bond yield curve short term interest rate fluctuation is bigger, and more discrete, medium and long-term yield spreads are much smaller than in the us. After that, principal component analysis was carried out, and it was clear that horizontal factor, slope factor and curvature factor were the main influencing factors of yield curve characteristics, and the relationship between principal component and macroeconomic variables was
further explored. The level factor contains the inflation information, the slope factor can reflect the market
participant's confidence and the anticipated change, the yield curve characteristic reflects quicker than the
money supply response to the monetary policy. Finally, the characteristics of the bond yield curve are
recognized. This paper believes that only by enriching the bond varieties and stimulating the vitality of
the bond market, can the bond market further play the role of interest rate discovery.




## Some work details

This [repo](https://github.com/mengmeng12/Nelson-Siegel-model/tree/master) contains codes for my undergraduate thesis. 

I found that there are some NS/NSS model implementation in python/R/matlab. Some models rate and maturity, some like QuantLib allows users model price and maturity. The jupyter notebook and R markdown will make it easier for a naive user to learn to run and use the model.

There are some requirements like Quantlib and fbonds package. Although not listed together, you can find the instruction of how to install them.

Some other analysis including PCA and a 3D+contour plot. You can also find the plot settings in figure_template.py quite useful.

Some codes are not the final version cause I wrote some codes in my girl friend's mac. All the codes can be run by a simple beginner :-D




### NS/NSS model optimization
we have fbonds in R and quantlib in python taking both rate and price as input to estimate term structure.

- Term structure optimized by fbonds in R. Using rate as input
![NSS 3D](http://i1.fuimg.com/640680/6d96936fd5491bcd.png)

![Markdown](http://i1.fuimg.com/640680/96f9bb754b4baa6d.png)

### PCA analysis
- Loadings of PCA

![Markdown](http://i1.fuimg.com/640680/9c70e4a79132e1d8.png)

- PCA ind arrow plot
![Markdown](http://i1.fuimg.com/640680/7cb7e7fa205bbe86.png)

![Markdown](http://i1.fuimg.com/640680/4d23bd9dab004f4d.png)

![Markdown](http://i1.fuimg.com/640680/2e86a67e24ca368b.png)



- screen plot
![Markdown](http://i1.fuimg.com/640680/e15fad6dd85a6981.png)




### Visualization
- PCA year/month plot

![Markdown](http://i1.fuimg.com/640680/9d9ec9b310182d91.png)

![Markdown](http://i1.fuimg.com/640680/efa3552937640d34.png)

- tSNE-plot
![Markdown](http://i1.fuimg.com/640680/04f6fe4e8656b0ac.png)



- 3D plot

![Markdown](http://i1.fuimg.com/640680/eb160f9909e4c73f.png)

![Markdown](http://i1.fuimg.com/640680/f56503392a6d8b6c.gif)

- rate distribution
![Markdown](http://i1.fuimg.com/640680/088fee22c8df4ee8.png)











