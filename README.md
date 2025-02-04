Let's understand the problem in detail and take n = 8 (chess board) ,There are 64 squares on a chess board and you have to place 8 queens without any constraints . The equation is 64 C 8 = 64!/(8!56!) , Therefore there are 4.4 billion unique ways to place 8 queens on a chess board.

![image](https://github.com/user-attachments/assets/06d49b2b-036b-4b8b-9985-0d0bc90de921)


here are some of the examples you can visualise to place 8 queens without attacking each other.
![image](https://github.com/user-attachments/assets/54d70fb7-ebc9-4f3b-81fa-1e3acfe7d641)


![image](https://github.com/user-attachments/assets/2b519457-a4ea-45d8-9e21-dc87ff9c0a20)

Now coming to the problem , no two queens should attack each other . There are only 92 unique ways that exist to place 8 queens on a chess board without attacking each other.
if you want to derive that in random the probability is 92/4.4 billion == 0.0000000203

![image](https://github.com/user-attachments/assets/8892688b-2881-482a-a8ab-d706e7632ab2)

Below is a video of how backtracking works 

https://github.com/user-attachments/assets/a4de8039-5dbf-41b4-b0f6-471f3fbe1aaa

