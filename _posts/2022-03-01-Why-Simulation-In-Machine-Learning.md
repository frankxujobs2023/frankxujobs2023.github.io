Sometimes it is necessary to introduce simulation into machine learning training. 
Today I will explain why and give you a real project example to show the value of Simulation.
> AI is something like - Everyone talks about it, nobody really knows how to do it, everyone thinks everyone else is doing it, so everyone claims they are doing it.
> Personaly, I feel like **Simulation** face the same probelm.


## Why Simulation in Machine Learning？
Simulation can be a valuable tool when developing a machine learning model for several reasons:

**Data scarcity**: Machine learning models require large amounts of data to be trained effectively. 
However, in some cases, data may be scarce or difficult to obtain. 
Simulation can be used to generate synthetic data that can be used to train and test the model, 
reducing the reliance on real-world data.

**Cost**: Collecting and labeling data for a machine learning model can be costly, 
especially if it requires physical experimentation or data collection. 
Simulation can be a more cost-effective alternative, 
allowing for the creation of a large and diverse dataset at a lower cost.

**Risk**: Some applications of machine learning, such as autonomous vehicles or medical diagnosis, 
can be risky if the model is not trained and validated properly. 
Simulation can be used to create a safe testing environment to evaluate the model's performance without putting people or equipment at risk.

**Iteration**: Machine learning models are often developed through an iterative process, 
with the model being refined based on feedback from testing and validation. 
Simulation can provide a more efficient testing and validation environment that allows for quick iteration and refinement of the model.

Overall, simulation can be a useful tool for developing and testing machine learning models in situations where data is scarce, cost is a concern, 
or the risk is high. However, it's important to ensure that the simulation accurately reflects the real-world environment and data 
that the model will ultimately be applied to, to ensure that the model is robust and effective in the real world.

## An Example - Prioritization Model with Discrete Event Simulation
### 1. Summary
Most companies will face an issue when they grow to a large scale - What is the best way to organize and prioritize the tasks that fed into the system? 
For instance, Companies will assign existed tasks to their technician to process. Usually, tasks first in will be assigned and processed first, 
we call the process strategy as first in fiest out. This is the most common way to deal with huge amount of tasks.

However, this might not be the best way to deal with many tasks. Consider such a simple scenario: Two tasks A, B are in the queue, A came into the system eariler than B,
but B is more urgent and introduce more revenue, which task would you process first? The answer is process task A for sure, 
it turnes out that first in first out strategy does not even work in such a simple scenario. 
So it is worthy developing a data-driven model to provide a better task prioritization strategy. 
Specifically, this model will be able to generate a prioritization score for each task and assign technician to all tasks accordingly.

To develop this model, we need historical data

### 2. 
