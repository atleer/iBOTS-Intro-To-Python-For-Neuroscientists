## Frequency Analysis with numpy and matplotlib

In the exercise "What other options are available in the `chirp` function to control the change of frequency over time? Let's explore some of these methods by visualizing them in the same plot."

It's not clear that you are supposed to make linear, logarithmic, and exponentially varying chirp functions here. 
- Just need to emphasize that "methods" is a parameter in the function, I think.

- Typo: "This is a fugure-level property " -- Figure level property

#### Create composite signals

- "Create composite wave made of a 2-Hz sawtooth and a 1-Hz square wave."

Based on the solution this should be:

"Create composite wave made of a 10-Hz sawtooth and a 1-Hz square wave."

### Frequency Analysis

- Typo: "**Generates** a chirp signal that begins with frequency" -- Generate

- "Generates a chirp signal that begins with frequency of 10 Hz and increases to 20 Hz over a period of 2.5 seconds and compute amplitude spectrum."
- Based on the solution, it should be "from 20 Hz to 50 Hz".

- The sampling frequency (number of samples in linspace in creation of t) is low. Best to use a sampling frequency significantly higher than the Nyquist limit.
    - I guess in principle you can regenerate a correct signal, as the frequency information is correct. It's just the plotting of the sampled signal itself that's messed up. To avoid confusing the students, it's best to use higher sampling frquency. Especially since it says "Predict how the figure will look like" in the task text. 




