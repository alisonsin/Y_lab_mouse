DataFrames for 1) Timestamp ;  2) Sampling [ i)1s  ii) 1ms ]

*Done*
- 2) Sampling in 1ms for rotary encoder data [session.runningspeed]

- 1) Lick timestamp dataframe [session.licks]
   I. timestamps
       (in ms)
       
- Reward dataframe
   I. timestamps  II. volume  III.autorewarded
        (in ms)       5/10/20       TRUE 

- 1) Audio timestamp 



To do:
1) fix licks (use round())
2) turn digital data into continuous binary 000001111
3) raster plot lick data!




**Possible Analysis Directions**

DataFrame - Raw Timestamp for each type of reward (volume); Lick Timestamp


DataFrame - segregating volume of reward <-> amount of licks
1) lick after each 5ul reward
2)                 10
3)                 20


DataFrame - Evolution of In bewteen Stimulus Licks
1) number of lick in between reward
2) time stamps of reward


