******** This repository contains the data collected from the experiments conducted using OAI 5G NR integrated with RIS ********

**--------------------------------------------------------------------------------------------------------------------------------------------------------**
1. RIS is ON\
   i. UE alone throughput when RIS is Beamforming to UE alone\
  ii. UE alone throughput when RIS is Beamforming to other UE\
 iii. UE alone throughput when RIS is sweeping between two directions\
        &emsp; a. All combinations of Ts and Tc \
      iv. Both the UEs throughput when RIS is sweeping between two directions\
        &emsp; a. All combinations of Ts and Tc

3. RIS is OFF\
   i. UE alone throughput\
  ii. Both the UEs throughput\
   &emsp; a. All Tc values
   
4. RIS is removed from the location\
   i. UE alone throughput at the same UE position as RIS ON or RIS OFF case
   
6. GRID around the position of UEs\
   i. RIS is ON\
   &emsp; a. 00 - Both the UEs are not placed in the directions of the RIS pointing\
   &emsp; &emsp; i. Three different distances (D1, D2, D3)\
   &emsp; b. 01/10 - One UE is placed in the direction of RIS pointing and the other UE is placed in the direction where RIS is not pointing\
   &emsp; &emsp; i. Three different distances (D1, D2, D3)\
   &emsp; c. 11 - Both the UEs are placed exactly in the same directions of RIS pointing\
   &emsp; &emsp; i. Three different distances (D1, D2, D3)\
   ii. RIS is OFF\
   &emsp; a. Same locations of UEs as "RIS is ON" case before\
   &emsp; &emsp; i. Same three different distances (D1, D2, D3)

**---------------------------------------------------------------------------------------------------------------------------------------------------------
**                

**Note:**       
1. Folder name and File names are written accordingly what data it contains
2. The notation for GRID RIS on/off cases 00/01/10/11 :\
    (RIS is randomly switching between two directions and beamform for Ts seconds in each direction)\
    &emsp; 00 - Both the UEs are not placed in the directions of the RIS pointing\
    &emsp; 01/10 - One UE is placed in the direction of RIS pointing and the other UE is placed in the direction where RIS is not pointing\
    &emsp; 11 - Both the UEs are placed exactly in the same directions of RIS pointing
3. D1, D2, D3 are the angular distances from RIS sucha that (D1 < D2 < D3)
4. There are two UEs: UE1 and UE2
5. UE1 is at 30 degree and UE2 is at 60 degree
6. Ts is RIS switching interval in seconds : possible values are 1, 3, 5, 9, and 15
7. Tc is the EWMA throughput window size in slots : possible values are 200, 2000, and 20000
---------------------------------------------------- ****************************  ------------------------------------------------------------------------

