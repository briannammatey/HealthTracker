# Welcome to the Health Tracker

## What does this Tracker do?
This tracker aims to help individuals, track their health, and plan out healthy habits. My inspiration to this, is that I have been an advocate for finding solutions to deal with PCOS, and helping women who suffer from it, and mainting your weight, food, calorie intake, and mental health is the most important thing to help with it.
<br>
This health tracker has ***FIVE*** different sections:
- Calorie Intake
- Workout Plan
- Food Plan
- Mental Health Plan


# FEATURES
## Health class
This is section is the main class, where all the classes are called, and where the main menu is showcased. This ia basically the starter for the code.

## CalorieTracker class
This section, is a simple way to track your calorie intake, and see if it matches with your goal. This section first asks what your calorie intake goal is today, using the Scanner class. Then using a while loop, it asks the user to input the amount of calories they intook today. It uses a function called dailycaloriecounter, which changes the the static variable dailycalorie. With this it is later compared to the users' goal, and the code tells them if they have reached the goal, if they have eaten less than their goal, or if they have eaten greater

## WorkoutPlan class
In this section, the user will be able to generate a workout plan, based on their muscle group. The user will get to pick if they are *beginner, intermediate or expert*, Then they will pick between full body workouts, arm workouts, core workouts and leg workouts.In this code the Random class is used, while also using the Stacks class, to efficiently pick a randomized workout plan for the user. After the user can simply pless 3 if they are done.

## FoodPlan class

In this section, there are *FOUR* different categories:
- Normal Food Guide
- Vegan Food Guide
- PCOS Food Guide
- Interactive Food Plan
### Normal Food Guide
The Normal Food guide section generates, healthy food options that will ensure that users should get the healthy fats, proteins, and nutritions that they need. They also include Goals that users should maintain and also lists foods and drinks to avoid. With this section, the information is shown using a typewriter format (basically when each letter is typed one by one).

### Vegan Food Guide
The Vegan Food guide section generates healthy food options, catered to people that are Vegan, and gives information for the users to get the nutritions they need, and also lists what food, and drinks they should avoid. This information is shown using a typewriter format also.

### PCOS Food Gude
The PCOS Food guide ection generates healthy food options, catered to people that have Polycystic Ovarian Syndrome, and gives users the information to maintain a sustainable diet, and also lists what food and drinks to avoid. This  information is also shown using a typewriter format also.

###  Interactive Food Plan
Uses the HashMaps Class and the Scanner Class to allow the user to input their food options, for Breakfast, Lunch and Dinner, and after lists out the users food options.

## Mental Class
There are *THREE* sections to this guide
- Breathing and Meditation exercises 
- Mental Health Advice
- Daily Journal

### Breathing and Meditation exercise (My personal favorite)
Utilizes the Time class, to have timed breathing exercises, where the function quietTime, lists out the amount of time left for the users to breathe. This section has a total of three differet breathing exercises, encouraging users to try different breathing techniques/

### Mental Health Advice
This section uses the Scanner class for user input, and asks the user how they are feeling, listing options such as Happy/Excited, Sad/Depressed, Bored/Unfufilled, Tired, Stressed/Overwhlemed, and Fine. With each option this program provides the user with advice, on what to do if they are feeling this way, and ways to change their mood for the better, giving them specific tasks to do.

### Diary Section
This section utilizes the DiaryEntry class, and the Diary class, while executing in the Mental class.
- The DiaryEntry class is used to hold accessor methods, and to override the toString Method. Also to initialize Linked List fields. Leading to efficient usage in the Diary Class
- The Diary class is used to hold methods such as deleteEntry, addEntry, and printAllEntries, maintaining linked lists methods, to create an efficient journal for the user to use
- Now in the Mental class, the switch method isused to be able to add entries, delete entries based on the date, and to be able to list out all the users entries



