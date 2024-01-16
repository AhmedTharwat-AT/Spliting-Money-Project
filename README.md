# Spliting money project
----
### This is a simple `React js` practice project from jonas schmedtmann React course on Udemy , i created the project components on my own including its logic but i dont own the idea or the styles as it was already written by Jonas .

This project idea is to split money between you and your friends and keep it logged to keep adding or removing expenses , more about the project idea and how it works below.

- This project helped me practice `State Mangement` and how components can send data between each other and how to conditionally render a component.
- I learned how it can get so tedious when lifting up or driling state to reach the targeted component , so the need to learn a powerful state mangement library like `Recoil or Redux` to centeralize
the state and make the project easier to understand amd to find bugs .



## Screens
![1](https://github.com/AhmedTharwat-AT/Spliting-Money-Project/assets/89677139/846cd5e3-dc3c-4f60-a30f-1c97d2a0d020)

- First you will see a friends list with a pre-entered data , each friend has a select and delete button
- there is an `Add Friend` button to simply add a new friend to the list
  
----

![2](https://github.com/AhmedTharwat-AT/Spliting-Money-Project/assets/89677139/03312b53-056b-4472-ad4f-a767e39dae1b)

- When clicking add friend Button , a Form will apear to add a new friend
- You can enter your friend name , a random image will be attached to the new friend

----

![3](https://github.com/AhmedTharwat-AT/Spliting-Money-Project/assets/89677139/aa7a9056-ecc0-4792-af69-9024463a9297)

- When selecting a friend , another form will appear to enter the bill value and your expenses and wether you or your selected friend paying
- if you're the one paying then your friend will owe you `bill value - Your expense` . 
- if your friend pays then you will owe your friend `Your expense` . 
