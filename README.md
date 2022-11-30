# Bayesian-Networks
The task of this project is predicting whether or not a sick horse survived, noted by the "outcome" variable in the data, based upon past medical conditions. I chose this dataset because there are alot of NAs (not a numbers) in the data. And dealing with them is the main struggle here. Also because of the proportion of NA's, imputation would not work porperly in this case. However, Bayesian networks have the ability to take into account the whole data due to their probabilistic nature and I've exploited this ability in this project.
There are ten features in the dataset. In order:

- surgery: If the horse had a surgery record.
- age: If it is an adult or a young horse.
- temperature of extremities(temp_of_extermities): a subjective indication of peripheral circulation.
- peripheral pulse: normal or increased p.p. are indicative of adequate circulation while reduced or absent indicate poor perfusion.
- mucous membranes: a subjective measurement of colour.
- capillary refill time: a clinical judgement. The longer the refill, the poorer the circulation.
- pain: a subjective judgement of the horse's pain level.
- peristalsis: an indication of the activity in the horse's gut. As the gut becomes more distended or the horse becomes more toxic, the activity decreases.
- abdominal distention: an animal with abdominal distension is likely to be painful and have reduced gut motility. a horse with severe abdominal distension is likely to require surgery just tio relieve the pressure.
- outcome: what eventually happened to the horse? Lived, Died or was euthanized.

I have exploited Parameter Learning methods, Structure Learning methods, and Approximate Sampling analysis on the dataset, utilizing pgmpy.

