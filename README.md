ITCS6162/ITCS8162 - Knowledge Discovery in Databases Course

Project Requirements:
● Add 6 new features to 1 datasets. You need to motivate the choice of these additional features, and shortly describe each of them (type, source) and motivate its choice.
● Analyze the attributes in your datasets - which one should be used as stable/flexible attributes and how to define your analytical task (hypothesis).
● Describe patterns you defined in Lisp-Miner in the report and justify the choice of the defined pattern (hypothesis) you are extracting.
● Attach the exported text file with the action rules you have extracted.
● Analyze a couple of the rules (with the best support) so that to suggest actions that should be taken for the chosen countries to change their status to less fragile.

In this project we were given Fragile State Index (FSI) dataset for all the countries which is available at https://fragilestatesindex.org/excel/ and we have extended the dataset by adding 6 new features namely Inflation rate, Birth rate, Death Rate, GDP Rank, Life Expectancy, Economic Growth. We extracted this data from different sources.
Using the values for these newly added features, and using the feature Total as our decision feature with discretization we replace numbers with concepts such as:
1. Alert
2. Warning
3. Stable
4. Sustainable
Using the above concepts we find the best classifier for our dataset with the help of software WEKA and using classification algorithms like Random Forest, Simple Logistic and K-star. After finding the best classifier, we find the action rules and from these rules we can get the action which needs to be performed to change the state of the country from Alert to Stable or Sustainable.

Six new features that we have added to the data are:
1. Birth Rate
2. Death Rate
3. Gross Domestic Product (GDP)
4. Economic Growth
5. Inflation Rate
6. Life Expectancy

