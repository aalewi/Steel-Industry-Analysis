# SteelIndustryAnalysis

![Steel Industry Photo](steelindustry.jpeg)
### Aaliyah Lewis
An analysis on Steel Industry Data Provided by Kaggle along with Machine Learning Algorithms    

# **Background Information**  

**Data:**  
https://www.kaggle.com/datasets/csafrit2/steel-industry-energy-consumption/data   
**Sources:**   
[Active Power vs Reactive Power](https://eshop.se.com/in/blog/post/difference-between-active-power-reactive-power-and-apparent-power.html#:~:text=What%20is%20Active%20Power%3F,lights%2C%20light%20bulbs%2C%20whatever.)

[Lagging vs Leading Power](http://www.differencebetween.net/technology/difference-between-leading-and-lagging-power-factor/)

**Link to Colab Notebook:**    
https://colab.research.google.com/drive/1i8Q2mHq9kQernBIsHlxXyPzCWosUqEFz?usp=sharing    

The purpose of this analysis is to understand the impacts of energy consumption on the Steel Industry and determine what factors are important.

**Important Definitions:**  
Active power is the usable or consumed electrical energy in an AC circuit and has units of watt (W) or kilowatt (kW). True power or real power is another name for active power, and it's the kind that actually does useful work.

Reactive power is the alternating current flowing back and forth in an electric circuit. The unit used for reactive power is volt-amperes reactive (VAR) or kilovolt-ampere active (kVAR). R.P., a term also used for imaginary power or wattless power, is the form of energy stored and released by the reactive components within current flowing through an electric circuit--most commonly inductors (inductance) and capacitors (capacitance).

The term ‘lagging power factor’ is used where the load current lags behind the supply voltage.

For capacitive circuits, where the load current leads the supply voltage, the term ‘leading power factor’ is used. It is a property of an electrical circuit that signifies that the load current is capacitive, meaning capacitive loads will cause a leading power factor.

# **Analysis Overview:**   
* Exploratory Analysis:
    - Check Data for Nulls & Correlations
    - Explore Trends within the data
* Data Manipulation:
   - Change categorical fields to numerical fields for data modeling
* Data Modeling:
  - Linear Regression
  - Keras Deep Learning
