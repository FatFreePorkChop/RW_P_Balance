# RW_P_Balance

Problem: fabric beauty score is complete irrelevent, except when you have furniture made from tiger leather--for instance.

Solution: Pawns should have a clothing score dependent on the following factors:
  Wealth: sum of all worn clthing value/1500
  Beauty: average material beauty. Items without material do not contribute
  Cleanliness: average clothing repair + 0.1
  Quality: Average quality - 1.5. Awful 0, poor 1, normal 2, good 3, excellent 4, masterwork 5, legendary 6. Additionally, add +2 for any legendary item OR +1 for any masterwork item. +1 for satisfying noble requirements. -2 for tainted.
  
Factors are scaled according to {-ln(-x) - 1, x<-1; x, -1<x<1; ln(x)+1, x>1}

