# NSW2015
Data files for use with a range of code available in my repositories.

Each file defines the electronic records of ballots cast in each electorate in the NSW 2015 state lower house election. Each file is structured as follows.

The first line contains a list of candidate identifiers (I've used integers):
0,1,2,3

The second line contains their party affiliations (for example):
LAB,LIB,GRN,IND

You can see the list of party affiliations in Parties.txt.

The third line is a separator (-+-+-+-+-+).

From the fourth line onward, each line definds a ballot ranking (for example, (3,2,0)) and the number of ballots cast with that ranking (for example, 15). 

(3,2,0) : 15


