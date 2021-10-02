**Elo customer loyalty prediction**

The purpose of this project is to build a customer loyalty predictive model for the Brazil based financial services association - Elo.

Cards issued by Elo being one of the most prolific transaction media in Brazil, the company has over a period of time built up partnerships with numerous merchants introducing promotional offers, discounts, additional customer services etc. All this is expected to help Elo increase its business, customer base and customer retention.

Towards that end Elo has developed a metric, called customer loyalty. The more the customer loyalty of a certain customer the more business Elo can expect from that particular individual. Elo has also tried to design a predictive model for this metric, so that decisions regarding discounts, promotional offers etc., can be made thereby increasing Elo’s market. However, it is not up to the mark and our aim is to come up with a better model.

We have been given the records of around 30 million transactions and various associated details from which we have to extract meaningful features so as to predict the customer loyalty of the members holding the cards.

**File description:**

- Modelling ELO Customer Loyalty.docx - gives a brief introduction and describes the various aspects of this project. It serves as a brief report.
- ELOCustomerLoyaltySparkVersion.ipynb - A version of the project implemented in spark. Majorly feature creation is done here.
- ELOCustomerLoyaltyNormalNonSparkVersion.ipynb - A full-fledged non-spark version implemented using the usual numpy - pandas - sklearn platform.
- The reason for 2 versions - spark and non-spark - is provided in Modelling ELO Customer Loyalty.docx, under the section _Spark and non-spark versions_.
