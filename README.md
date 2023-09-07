# Melody Generation using LSTMs

In this project, I learned how to create melodies using Long Short-Term Memory networks. Here, we took music partitions 
from the [German dataset](https://kern.humdrum.org/cgi-bin/browse?l=essen/europa/deutschl) and converted the sequence of notes and rests it into a 
time series. By doing so, we transform the problem into something a RNN can attempt to predict. Melodies have long-term 
structural patterns, which make them very suitable for LSTMs.

For this project, we are using the [ESAC database](http://www.esac-data.org/) which has over
20k traditional folk songs from all over the world.

Resources:
- Valerio Velardo - The Sound of AI (https://www.youtube.com/@ValerioVelardoTheSoundofAI)
