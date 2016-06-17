# salmon-run-sim

SalmonRunSim roughly models a salmon run that might take place off the coast of southeast Alaska or a similar locale.  There are three entities involved in the model: salmon, fishing boats, and bears.  The program runs until all the salmon have either spawned or been caught (by human or bear).  The size of the population is monitored at set intervals, and if it drops below a certain threshold, a salmon boat is removed from the harvest—much like a fisheries department might do in the real world.  Additionally, disease pressure reduces the salmon population during the run.  On each iteration, fishing boats and bears have a probabilistic chance of catching a salmon.  If the boat fails to locate enough salmon, it risks going bankrupt.  Similarly, bears can potentially starve if they go long enough without a meal.  If a bear is a particularly good hunter, however, it increases its chance of successfully breeding.  If the number of spawning salmon meets or exceeds a target rate, then the run is considered “sustainable”.

This program is loosely based on a simulation written by the authors of <a href="https://www.amazon.com/Python-Programming-Context-Bradley-Miller/dp/1449699391">Python Programming in Context, 2nd edition.</a>
