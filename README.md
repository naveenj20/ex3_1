## NAME: NAVEEN JAISANKER
## REG. NO.: 212224110039

# EXERCISE-3


# AIM:

To develop a UiPath workflow that demonstrates the use of Repeat (While) and Do-While loops using a Sequence or Flowchart.

# PROCEDURE:

Step 1: Create Project

Open UiPath Studio → Create a new Process.

Name it LoopingDemo.

Step 2: Repeat (Using Assign + While)

Drag a Sequence into the main panel.

Declare variables:

counter → Int32 → Default: 1

limit → Int32 → Default: 5

Use an Assign activity:

counter = 1


Add a While loop:

Condition: counter <= limit

Inside the loop:

Message Box: "Count: " + counter.ToString

Assign: counter = counter + 1

After the loop, insert a Message Box: "Loop ended"

Step 3: Do-While Example

Drag a Do While activity.

Declare variable:

firstRun → Boolean → Default: True

Inside the Do While:

Message Box: "This block runs at least once"

Assign: firstRun = False

Condition:

firstRun = True


# WORKFLOW:

Your workflow consists of:

Repeat loop (While)

Assign counter = 1

While (counter <= limit)

Message Box (Count value)

Increment counter

Message Box (“Loop ended”)

Do While loop

Message Box (“This block runs at least once”)

Assign (firstRun = False)

Condition → firstRun = True

# OUTPUT:

<img width="471" height="478" alt="Screenshot 2025-09-06 100948" src="https://github.com/user-attachments/assets/80e76451-e127-46ed-b5e2-a9c1d47640ed" />

Count: 1

<img width="416" height="401" alt="Screenshot 2025-09-06 100951" src="https://github.com/user-attachments/assets/889df602-ec25-43e4-a09b-c74aa45409ff" />

Count: 2

<img width="346" height="347" alt="Screenshot 2025-09-06 100954" src="https://github.com/user-attachments/assets/3f0766c8-21c9-49da-96f3-f90c82e34ea9" />

Count: 3

<img width="375" height="429" alt="Screenshot 2025-09-06 101029" src="https://github.com/user-attachments/assets/0d32f4b6-8d9d-479b-9761-0f83569bcd90" />

Count: 4

<img width="327" height="426" alt="Screenshot 2025-09-06 101032" src="https://github.com/user-attachments/assets/3476b713-5465-4386-9aa9-ad6ad91dd5e7" />

Count: 5

<img width="310" height="301" alt="Screenshot 2025-09-06 101035" src="https://github.com/user-attachments/assets/de65e826-67be-4a8b-a25c-46f2bfc2f954" />

Loop ended

<img width="461" height="379" alt="Screenshot 2025-09-06 101037" src="https://github.com/user-attachments/assets/a6546e3c-3732-412e-a6a1-fdfb1b7b476f" />

This block runs at least once

RESULT:

Thus, the UiPath workflow for demonstrating Repeat (While) and Do-While loops was created and executed successfully.
