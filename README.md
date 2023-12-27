# Algorithm-for-file-updates-in-Python

<p align="center">
Project descriptions: <br/>

In this Lab access to restricted content is controlled with an allow list of IP addresses. The "allow_list.txt" file identifies these IP addresses. A separate remove list identifies IP addresses that should no longer have access to this content. I created an algorithm to automate updating the "allow_list.txt" file and remove these IP addresses that should no longer have access.

<p align="center">
Open the file that contains the allow list & Read the file contents: <br/>
<img src="https://i.imgur.com/HBZic6B.png" height="80%" width="80%" alt="Algorithm-for-file-updates-in-Python"/>
<br />

<p align="center">
Convert the string into a list: <br/>
<img src="https://i.imgur.com/waXCsWT.png" height="80%" width="80%" alt="Algorithm-for-file-updates-in-Python"/>
<br />

<p align="center">
Iterate through the remove list & Remove IP addresses that are on the remove list: <br/>
<img src="https://i.imgur.com/t7En0hD.png" height="80%" width="80%" alt="Algorithm-for-file-updates-in-Python"/>
<br />

<p align="center">
Update the file with the revised list of IP addresses: <br/>
<img src="https://i.imgur.com/eMVCoWD.png" height="80%" width="80%" alt="Algorithm-for-file-updates-in-Python"/>
<img src="https://i.imgur.com/KlHzkEf.png" height="80%" width="80%" alt="Algorithm-for-file-updates-in-Python"/>
<br />

<p align="center">
Summary: <br/>
I created an algorithm that removes IP addresses identified in a remove_list variable from the "allow_list.txt" file of approved IP addresses. This algorithm involved opening the file, converting it to a string to be read, and then converting this string to a list stored in the variable ip_addresses. I then iterated through the IP addresses in remove_list. With each iteration, I evaluated if the element was part of the ip_addresses list. If it was, I applied the .remove() method to it to remove the element from ip_addresses.. After this, I used the .join() method to convert the ip_addresses back into a string so that I could write over the contents of the "allow_list.txt" file with the revised list of IP addresses.



