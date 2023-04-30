Download Link: https://assignmentchef.com/product/solved-cs2303-programming-assignment-3-c-term-2020-mystery-mansion
<br>
<h1>(0) Prologue:</h1>

Mystery and mayhem in the Manor at 1 Drury Lane! There’s murder in the air and clues are everywhere. Inspector Gompei is stumped and has asked you for pointers on the case. Your task (and you will accept it) is to search the mansion room by room accumulating evidence. You’ll need all the I/O skillz and Linked List facilities at your disposal to crack the case. (1) Construct the Mansion.

Inspector Gompei has sent you the files you’ll need to understand the floorplan and the nature of all the rooms in the Manor at 1 Drury Lane. The “MansionRooms.txt” file will hold the keys to the rooms. Each has its number, name, and number of bits of evidence (clues) recorded in the file. You will find it handy, as per our Room struct, to include fields indicating whether you have discovered the room and whether you have searched the room, but you will need to add these yourself. Since you have not yet arrived on the scene, these values are assumed to be their defaults and are not included in the file. The first line of the file is an int sentinel representing the number of rooms in the mansion (and therefore in the file).

The file “MysteryMansionCS2303HW3.xlsx” contains the floorplan of the mansion under tab “Clue Board for HW3”<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> and an adjacency matrix for its underlying graph under tab “HW3Graph”. You should fprintf that to a file as formatted data (don’t forget your sentinel!) so that you can fscanf it in when you execute your program.

You may assume that the files contain valid information and that they are consistent. Furthermore, you can assume the floorplan is symmetric–no trapdoors or one-way passages<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a>.

1

<ul>

 <li>Make Introductions</li>

</ul>

When you arrive on the scene, you will be met by Inspector Gompei. He will ask you whether you want to do a through examination of the entire mansion, or whether you would prefer just to localize your search to a set number of rooms or until you have found a certain number of clues. Inspector Gompei will also assist you by taking you directly to the room in which you would like to begin your investigation.

<ul>

 <li>Conduct Your Investigation</li>

</ul>

As you search a room, be sure to record the clues you find. You should also remember that you have searched the room–time’s a-wastin’ and the game’s afoot! Before you leave a room, check to see what rooms are adjacent to the one you are in and add them to your list of rooms to search (perhaps only if they have not already been searched).

<ul>

 <li>File Your Report</li>

</ul>

When you have concluded your inquiry, you must file your report. Be sure to enumerate the rooms you examined–in the order you examined them. Your report should include the number of clues discovered in each room you searched as well as the subtotal of clues to that point. You should file your report in duplicate, both to the screen and to a file.

<ul>

 <li>Evaluation</li>

</ul>

Your supervisor will evaluate your report based on the following criteria:

<table width="497">

 <tbody>

  <tr>

   <td width="165">Mansion Construction</td>

   <td width="285">File I/O and Room Initialization</td>

   <td width="47">20%</td>

  </tr>

  <tr>

   <td width="165">Introductions</td>

   <td width="285">Keyboard Input and Control Flow</td>

   <td width="47">20%</td>

  </tr>

  <tr>

   <td width="165">Investigation</td>

   <td width="285">Graph Traversal (Breadth-First Search)</td>

   <td width="47">20%</td>

  </tr>

  <tr>

   <td width="165">Report</td>

   <td width="285">printf and fprintf</td>

   <td width="47">20%</td>

  </tr>

  <tr>

   <td width="165">Testing</td>

   <td width="285">Test-Driven Development Deployed</td>

   <td width="47">20%</td>

  </tr>

 </tbody>

</table>




<a href="#_ftnref1" name="_ftn1">[1]</a> For historical accuracy, there are also tabs for the original layout, before the remodeling that expanded most of the rooms.

<a href="#_ftnref2" name="_ftn2">[2]</a> Next year’s class may not be so lucky!