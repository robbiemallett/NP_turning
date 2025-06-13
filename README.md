# METADATA

See frolov 2005 (in this repo) for more information.

## POSITION DATA           
      
Positions of the drifting stations were determined mostly by      
means of terrestrial astronomical observations. Sun fixes 
and star observations were made daily as season and weather
permitted. Positioning errors are estimated to have been
3-5 km. Starting with North Pole station NP-25, positions
were determined using satellite technology. NP-31 used the 
Satellite Navigation system. AARI reviewed all position data 
for this project using the original meteorological records.
      
The position data files received from AARI contained only       
observations that were actually made. They were delivered by      
AARI in files separate from the meteorological observations. 
The position data were in Moscow time, but were converted to 
UMT (GMT) at the Polar Science Center. Positions for day 360 
of 1988 through day 60 of 1989 were missing from the NP-31 
record. This gap has been filled by linear interpolation.   

In the \combined\, \met\, \solar\, and \snow\averaged\
directories, these observed positions have been interpolated
after some quality control to provide an approximate 
position for each meteorological observation. A simple
linear interpolation scheme was used between reported 
observations in the three- and six-hourly files in the 
directory \original\position\. The positions in 
\met\metnp*.dat and in the radiation data files are
interpolated. Interpolated positions were used in the  
combined data file of daily averaged data, 
combined\combined.dat.          

## WIND DATA
     
The most significant changes during the operating period of       
the North Pole (NP) drifting stations were in methods and       
means for measurement of wind velocity and direction, which       
vary from the rudimentary hand-held anemometers with "make-      
it-yourself" wind direction indicators to the modern       
recording instruments used since NP-22. Also, the height of       
installation of the wind velocity sensors has varied from 2       
to 11 m. The anemometer M63-M was used beginning with NP-23       
through NP-31.     
      
Table 2 lists the instrument numbers and heights of 
installation of the wind velocity sensors used for the 
measurement of wind velocity and direction. Table 3 provides 
the main parameters of the instrument. The years of
operation for each drifting station are listed in 
\document\project.txt.   
      
Table 2.  Instruments and Installation Heights Used for           
          the Measurement of Wind Velocity and Direction      
      
     Station   Instrument(s)       Height (Dates)      
     --------------------------------------------      
      NP-1      MS-13               2 m
      NP-2      8I0001M             8 m      
      NP-3      MS-13; 8I0001M      8 m      
      NP-4      8I0001M; FVL        8 m      
      NP-5      FVL                 6 m      
      NP-6      FVL; FVT            8 m      
      NP-7      FVL; FVT           10 m  
      NP-8      FVL; FVT            8 m       
      NP-9      FVL; FVT            8 m      
      NP-10     M-49                6 m      
      NP-11     FVL; FVT; M-47      8 m    
      NP-12     M-49               10 m
      NP-13     M-47; M12           6 m      
      NP-14     M-47;M-63           8 m      
      NP-15     M-63                6 m      
      NP-16     M-49               10 m
      NP-17     M-63               10 m
      NP-18     M-49; M-12          6.4 m  (11/68 - 05/69)      
                                    8.5 m  (05/69 - 10/71)      
      NP-19     M-64; M63M          6.4 m  (12/69 - 10/70)      
                                    7.5 m  (11/70 - 01/71)      
                                    9.5 m  (02/71 - 11/72)      
                                    12.0 m (11/72 - 03/73)      
      NP-20     M-47                8 m    (05/70 - 04/71)      
                                    6 m    (05/71 - 05/72)      
      NP-21     M-47               10 m
      NP-22     M-64; M-63M        10 m
      NP-23     M-63M              10 m
      NP-24     M-63M              10 m
      NP-25     M-63M              10 m
      NP-26     M-63M              11 m      
      NP-27     M-63M              10 m
      NP-28     M-63M              10 m
      NP-29     M-63M              10 m
      NP-30     M-63M              10 m
      NP-31     M-63M              10 m
      
      
Table 3.  Main Parameters of the Instruments Used for             
          the Measurement of Wind Velocity and Direction      
      
                                                 Threshold      
                                                 Sensitivity      
             Range  Range      Measurement       for speed &      
             Speed  Direction  Speed Direction   direction      
Instrument  (m/s)   (degree)   (m/s)   (degree)    (m/s)      
----------   -----  ---------  -----    --------  ----------     

   MS-13     1-20      -    (0.3+0.06V)    -        0l.8/-      
   810001M   1-15    0-360      1.0       10        1.0/1.0      
       FVL   1-20    0-360      *          *          *      
                     (at 16 compass points)      
       FVT   1-40    0-350      *          *          *      
      M-49   1.5-59  0-360  (0.5+0.05V)   10        1.2/1.2      
      M-47   1.5-50  0-360  (0.5+0.05V)   10        1.2/1.2      
      M-64   1.0-4.0 0-360  (0.5+0.05V)   10        0.8/1.5      
      M-12   1.0-4.0 0-360  (0.5+0.05V)   11.25     0.7/0.9      
                     (at 16 compass points)      
      M-63   1.0-4.0 0-360  (0.5+0.05V)   10        0.8/1.5      
     M-63M   1.0-4.0 0-360  (0.5+0.05V)   10        0.6/1.0      
      
Notes for Table 3:

1.  MS-13 measures only wind velocity.  

2.  Measurement area of wind vanes with light and heavy
    boards (FVL, FVT) depends on the observer's experience.
    The error is not less than +/- 1 meter per second for
    velocity and +/- 0.5 point (11 degrees) for direction.

3.  M=12, M-47, M-64, M-63, M-63M allow registering the wind
    velocity averaged over 10 minutes; MS-13 allows
    registering velocity averaged over 2-10 minutes.

4.  V in formulas for velocity measurement area is the
    measured wind velocity, m/s.
