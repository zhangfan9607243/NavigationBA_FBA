# Topic 1.1 - Concepts of Business Analytics

## 1. Definition of Business Analytics

**Business Analytics (BA)** is the practice of using data and models to solve business problems and improve decision-making:

- BA concerns about **using data wisely** - not just collecting numbers
- BA combines **technical skills** with **business understanding** to move from raw data to real-world impact
- BA focuses on how to **extract insight, frame decisions, and take action to creates value**, in today's data-rich environment
- BA helps organizations understand why things happen, predict what might happen next, and evaluate how to respond — not just report what happened

BA is a way of thinking:

- emphasizing a shift from **gut instinct** to **evidence-based decision-making**
- with the enduring goal of **making smarter and more confident decisions under uncertainty**
- regardless of how analytical tools evolve: dashboards, machine learning, experimentation, etc.

!!! tips "Citation"
    
    "Let the data tell its story"

    ~ Gregory Crawford, Chief Economist at Zalando


!!! tips "Citation"

    "Data are widely available; what is scarce is the ability to extract wisdom from them."

    ~ Hal Varian, Chief Economist at Google


## 2. Five Steps of Business Analytics

1. Defining the Problem:

    - Every good analysis begins with a sharp question.
    - Clearly identify the **decision to be made**, **available options**, and **what success looks like**.

2. Collecting and Cleaning Data:

    - Data is not ready to use out of the box.
    - Analysts spend significant time gathering **relevant data sources** and ensuring they're **accurate, complete, and reliable**.

3. Analyzing Data Appropriately:

    - Analysts conduct formal analysis to **identify patterns, test hypotheses, and evaluate trade-offs**.
    - This is done using **appropriate analytical tools**, ranging from **simple descriptive statistics to predictive models**.

4. Communicating Insights:

    - Even the best analysis fails if it is not understood by decision-makers.
    - Analysts must communicate insights through **clear and persuasive data stories** that clarify the decision and guide action.

5. Acting to Create Value:

    - Ultimately, analytics only matters if it leads to better decisions.
    - The goal is to use insights to **create business value**, rather than to perform analysis for its own sake.


## 3. Three Types of Business Analytics

### (1) Reasons for Classifying Business Analytics

Business analytics is not one-size-fits-all

- Different business questions require **different types of insights** 
- So, different business questions require **different analytical tools**

Business analysts should know how to use the tools and which tool matches which question:

- Choosing the wrong tool for the question can lead to misleading conclusions
- For example:

    - A model can predict which companies are likely to identify and correct mistakes in their previously published financial statements
    - But it can not understand why those mistakes occurred, or what internal controls or governance changes might have prevented them


### (2) Three Types of Business Analytics

#### (a) **Descriptive Analytics**: What happened?

Descriptive analytics focuses on summarizing and reporting **what has already occurred** in a business.

Descriptive analytics answers questions like:

- What were our total sales last quarter?
- Which products had the highest return rates?
- What were the top 10 ASX-listed companies by shareholder return last year?

Descriptive analytics does not make predictions or evaluate decisions:

- It helps managers understand performance, identify trends, and spot anomalies
- It can be thought of as the **rearview mirror** of analytics

Descriptive analytics tools include: summary statistics, tables, visualizations and dashboards

- These methods help condense large datasets into understandable formats
- They provide a foundation for further analysis by highlighting key patterns and areas of interest

#### (b) **Predictive Analytics**: What might happen next?

Predictive analytics goes a step further: it **uses past data to forecast future outcomes**.

Predictive analytics answers questions like:

- How many customers are likely to churn next month?
- How are annual depreciation expenses likely to change over the next three years?
- Will the RBA cut interest rates next month, and if so by how many basis points?

Predictive analytics does not answer causal questions:

-   For example: Sales - a forecast that sales will increase next quarter doesn't tell you why or what would happen if you changed your pricing or launched a new campaign
-   For example: Weather forecast - useful for planning, but not a substitute for experimentation or causal understanding

Predictive analytics tools include: statistical models and machine learning techniques

- These methods identify patterns and extrapolate them forward
- These models don't guarantee what will happen, but they give decision-makers a probabilistic view of likely outcomes

#### (c) **Causal (Prescriptive) Analytics**: What will happen if we act?

Causal analytics is more strategic and difficult. It tries to answer counterfactual questions: **What would happen if we did X instead of Y?**

Causal analytics answers questions like:

- What impact will a 10% price increase have on demand?
- How will merging with another firm affect our share price?
- Would switching to a new supplier improve delivery times?

Causal analytics focuses on problems that can't be answered by simply observing correlations or running a predictive model:

- This is the decision engine of Analytics
- It helps businesses not just anticipate the future, but change it deliberately

Causal analytics tools include randomized experiments (A/B testing), instrumental variables, difference-in-differences, or other econometric techniques.

- These methods are designed to isolate cause and effect
- They help decision-makers evaluate trade-offs and choose the best course of action

### (3) Comparing the Three Types of Business Analytics

| Type                  | Core Question               | Typical Tools                  | Business Use                 |
|-----------------------|-----------------------------|--------------------------------|------------------------------|
| Descriptive           | What happened?              | Summaries & Visualizations     | Reporting and monitoring     |
| Predictive            | What might happen?          | Forecasting & Classification   | Anticipating future trends   |
| Causal (Prescriptive) | What will happen if we act? | Experiments & Causal Inference | Strategy and decision-making |



## 4. Power & Limits of Business Analytics

Business analytics supports better decision-making by clarifying options and sharpening thinking, but it has inherent limitations that analysts must recognize.

Three aspects of limits of business analytics are discussed below.

### (1) Good decisions depend on good data

Basic Principle: Garbage in, garbage out.

Data quality is essential:

- Even the most advanced model cannot save an analysis built on poor-quality data, vague problem definitions, or biased assumptions

- Clean, relevant, well-structured data is a prerequisite for good insights, but not a guarantee

- The extent, to which analytics supports decision-making, depends entirely on the quality of the inputs we provide, and the care with which we interpret the results

Data collection and data management are also critical, as these choices shape the entire analytical process.

### (2) Analytics doesn’t eliminate uncertainty or judgment

Basic Principle:

- All models are simplifications under assumptions:

    - This can help us focus on what matters

    - However, the world is more complex than any model can fully capture

    - All forecast can only offer probabilities:

        - Models can never offer certainties

        - A causal estimate can quantify impact, but only under specific assumptions.

This means that even with data:

- **Uncertainty remains:** Decisions may be made under conditions of:

    - Incomplete information

    - Ambiguous results

- **Trade-offs persist:** No model can resolve managerial tensions between:

    - Short-term gains and long-term investments

    - Efficiency and innovation

- **Judgment is essential:** Good analysts don’t just run models - they:

    - **Think critically**

    - **Question results**

    - **Tell coherent stories** that connect the data to the broader context

### (3) The analyst’s role given the limits of business analytics

Basic Principle: Being a good analyst means more than knowing the right techniques:

-   A good analyst should:

    -   Understand the business problem

    -   Evaluate the quality of the data

    -   Make thoughtful decisions about how to present and interpret results

-   A good analyst should be:

    -   Honest when uncertainty is high

    -   Clear about what the data can and cannot tell us

Analytics gives us leverage to:

- Enhance leverage, not replace leadership 
- The best decisions come when rigorous analysis meets sound judgment
