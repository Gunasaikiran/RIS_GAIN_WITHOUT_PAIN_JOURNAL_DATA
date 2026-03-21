********** This repository contains the data collected from the experiments conducted using OAI 5G NR integrated with RIS ********
**
**--------------------------------------------------------------------------------------------------------------------------------------------------------**
1. RIS is ON
       i. UE alone throughput when RIS is Beamforming to UE alone
      ii. UE alone throughput when RIS is Beamforming to other UE
     iii. UE alone throughput when RIS is sweeping between two directions
               a. All combinations of Ts and Tc 
      iv. Both the UEs throughput when RIS is sweeping between two directions
               a. All combinations of Ts and Tc

2. RIS is OFF
       i. UE alone throughput
      ii. Both the UEs throughput
               a. All Tc values
   
4. RIS is removed from the location
       i. UE alone throughput
   
6. GRID around the position of UEs
       i. RIS is ON
                a. 00 - Both the UEs are not placed in the directions of the RIS pointing
                         i. Three different distances (D1, D2, D3)
                b. 01/10 - One UE is placed in the direction of RIS pointing and the other UE is placed in the direction where RIS is not pointing
                         i. Three different distances (D1, D2, D3)
                c. 11 - Both the UEs are placed exactly in the same directions of RIS pointing
                         i. Three different distances (D1, D2, D3)
       ii. RIS is OFF
                a. Same locations of UEs as "RIS is ON" case before
                         i. Same three different distances (D1, D2, D3)

**---------------------------------------------------------------------------------------------------------------------------------------------------------
**                

**Note:**       
1. Folder name and File names are written accordingly what data it contains
2. The notation for GRID RIS on/off cases 00/01/10/11 :
    (RIS is switching between two directions and beamforming for Ts seconds in each direction with EWMA throughput window size is Tc seconds)
    00 - Both the UEs are not placed in the directions of the RIS pointing
    01/10 - One UE is placed in the direction of RIS pointing and the other UE is placed in the direction where RIS is not pointing
    11 - Both the UEs are placed exactly in the same directions of RIS pointing
3. D1, D2, D3 are the angular distances from RIS sucha that (D1 < D2 < D3)
4. There are two UEs: UE1 and UE2
5. UE1 is at 30 degree and UE2 is at 60 degree
6. Ts is RIS switching interval in seconds : possible values are 1, 3, 5, 9, and 15
7. Tc is EWMA throughput window size in slots : possible values are 200, 2000, and 20000
                                     in seconds: possible valuesa are 0.1, 1, and 10

---------------------------------------------------- ****************************  ------------------------------------------------------------------------

