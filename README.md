# <h1>Runoff Election</h1>

<h2>Description</h2>
This project runs an election in the runoff format. This means if a candidate has over 50% of the votes they will win, if not it will eliminate the contestant/s with the lowest number of votes and use their next highest rank vote as their main vote. The programme requires command line arguments to be entered of the candidates names up to a maximum of 9. It will then ask for the number of voter, up to the value of 100. It will then ask for the preference of the first voters votes, first being their favourite and last being their least. It will then do this for every voter and store the values. If there is an invalid vote it will return an error. This is when it will see if there is over 50% of votes for a candidate and if not, then it will begin eliminating the lowest voted candidates until there is a winner. 
<br />

<h2>Link to code</h2>
https://github.com/giannisassano/RunoffElection/blob/main/RunoffCode
<h2>Languages Used</h2>

- <b>C</b> 
<h2>Code Breakdown</h2>
Walking through the code from top to bottom, we have an array of candidates, a counter for the voters and candidates, an error message to return 1 in case of bad usage, then it populates the array of candidates from the command line arguments, requests input for the number of voters, and keeps requesting the voters preferences and recording the answer, it then checks to see if there is a candidate with over 50% votes as an automatic winner, if not, then it eliminates the last place and recounts the votes with the last place candidate not included, it repeats until a winner is found, it then prints the winner.
<p align="center">
 <br/>
<img src="https://i.imgur.com/Ao7ASj1.png"/>
<br />
<br />
<img src="https://i.imgur.com/gAp1fbw.png"/>
<br />
<br />
<img src="https://i.imgur.com/HQHSFvf.png"/>
<br />
<br />
<img src="https://i.imgur.com/55aQ5UP.png"/>
<br />
<br />
 Programme in use:  <br/>
 Run with the candidates as command line arguments, enter the number of voters, type in the votes, and then it prints the winner as in the example below.<br/>
<img src="https://i.imgur.com/umA1V93.png"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
