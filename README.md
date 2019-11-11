# Spont_stim_spiking_A1

The data is composed of neuronal activity recorded in the primary auditory cortex (A1) of 6 anesthetized rats. The experimental procedures and spikes sorting procedures have been previously described in Mochol et al. (2015). Briefly, rats were anesthetized with urethane (1.5 g/kg body weight) and silicon microelectrodes (Neuronexus) with 32 or 64 channels were inserted in deep layers (depth, 600–1,200 μm) of the primary auditory cortex. The spiking activity from single units and multi-units (i.e., neurons that were not well isolated) was simultaneously recorded during spontaneous activity and in response to acoustic “clicks” (5-ms square pulses; interstimulus interval, 2.5 or 3.5 s). 
We divided each recording session into Ne adjacent epochs of 100 s, each one containing 12–29 stimulus presentations. Within each 100-s epoch the data was separated into spontaneous activity, i.e., the activity during 1.5-s intervals preceding each stimulus (i.e., 18–43.5 s of spontaneous activity in total for each epoch), and stimulus-evoked activity, i.e., the activity right after the stimulus onset.

The spontaneous activity can be found in the files: Spontaneous_rat, where rat=1,...,6. 
Data format:
Column 1: spike times
Column 2: neuron index firing at time given by column 1
Column 3: epoch index, from 1 to Ne
Column 4: Unit type code: 1 = nicely-sorted single unit (SUA); 2 = multi-unit (MUA)

The stimulus-evoked activity can be found in the files: Stimulus_rat, where rat=1,...,6 (only for SUA units). 
Data format:
Column 1: spike times
Column 2: neuron index firing at time given by column 1
Column 3: epoch index, from 1 to Ne
Column 4: stimulus repetition within the corresponding epoch

References:
Mochol G, Hermoso-Mendizabal A, Sakata S, Harris KD, de la Rocha J (2015) Stochastic transitions into silence cause noise correlations in cortical circuits. Proc Natl Acad Sci USA 112, 3529–3534. DOI: 10.1073/pnas.1410509112
