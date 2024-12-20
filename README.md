<p align="center">
<img src="https://github.com/user-attachments/assets/d18f9919-e0b5-43bd-81a1-a08d1644961a" alt="Azure Banner"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Network Protocols</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create access folders in the Domain Controller
- Add sharing permissions to all folders except "accounting"
- Log into a user and try to write in a read-only folder
- Try to write in a read-write folder
- Try to access the no-access folder
- Confirm that the "accounting" folder is not visible, as it has no sharing permissions
- Create a security group called "ACCOUNTANTS"
- Add security group to the "accounting" folder
- Confirm "accounting" folder is visible in a user's account, because of sharing permissions
- Confirm that the user cannot access the folder
- Add a user to the "ACCOUNTANTS" security group
- Conform user can now access "accounting" folder

<h2>Installation Steps</h2>

<p>
<img width="1136" alt="Screenshot 2024-12-19 at 5 44 33 AM" src="https://github.com/user-attachments/assets/0ec9cc78-447d-4dea-b385-1f43c4b78690" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1136" alt="Screenshot 2024-12-19 at 6 02 16 AM" src="https://github.com/user-attachments/assets/35650e6f-071e-496c-8734-d53636131d6e" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1133" alt="Screenshot 2024-12-19 at 6 02 41 AM" src="https://github.com/user-attachments/assets/49d49d63-d6dc-42c1-a2ad-5541279add3d" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1144" alt="Screenshot 2024-12-19 at 6 03 26 AM" src="https://github.com/user-attachments/assets/17a64af1-b87e-4354-969b-3f050f1b6421" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1134" alt="Screenshot 2024-12-19 at 6 03 43 AM" src="https://github.com/user-attachments/assets/7947b527-5cc0-473a-b1ba-d933c944de3c" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="752" alt="Screenshot 2024-12-19 at 6 09 39 AM" src="https://github.com/user-attachments/assets/de06b61d-27ac-4f71-ba6a-3d2ba6f3e0b9" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1074" alt="Screenshot 2024-12-19 at 6 11 36 AM" src="https://github.com/user-attachments/assets/a96977bc-2353-479d-b344-7bc464073c0a" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1129" alt="Screenshot 2024-12-19 at 6 13 00 AM" src="https://github.com/user-attachments/assets/cd455ad6-c1a0-4f4f-a5cf-dd7c950fddc2" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1128" alt="Screenshot 2024-12-19 at 6 13 57 AM" src="https://github.com/user-attachments/assets/74e9f81b-5469-47a4-aef9-c1ba93e3ebf0" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="493" alt="Screenshot 2024-12-19 at 6 17 52 AM" src="https://github.com/user-attachments/assets/60967c2a-cc71-4b3a-90ae-1390af37e3b0" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="401" alt="Screenshot 2024-12-19 at 6 18 08 AM" src="https://github.com/user-attachments/assets/4bddf430-33e9-4922-bf24-f59af690b141" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img width="1127" alt="Screenshot 2024-12-19 at 6 19 52 AM" src="https://github.com/user-attachments/assets/adb5ce91-ea71-4e7b-ba0d-3e6602cadc3f" />

</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
