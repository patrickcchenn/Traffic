For the model, firstly I arbitrarily tried using the model from the handwriting.py source code and
the accuracy was extremely low with around 5% of accuracy.Next, I tried add more hidden layers with a relatively low units and the accuracy rocketed to around 50%.
Lastly, I tried other combinations and end up finding the optimal model by increasing hidden layers with dropout on some of them while vastly increase the units.
What I can infer from this experiment is that the number of hidden layers and units substantially affects the accuracy and the time taken to train the AI(longer if there's more units and layers)
