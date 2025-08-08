# Harold Bryan Santos

### Outputs:
***

## Exercise 1: Creating an ArrayList and Adding Elements (add)
        1. Prediction:
            What do you think will be the output?
                -I think the output will be "Is the list empty initially? true" since 
                and when you create an array and you dont put any elements inside it, it will just return
                empty. The next one is "Current tasks: 
                [Secure the perimeter, Establish communication, Report status"] because now that we used add method
                we added some task for it to print and the third one is "Number of tasks: 3" since we added 3 
                tasks inside it.
        2. Observation:
            Now, run the code. What is the actual output?
                -Is the list empty initially? true
                Current tasks: [Secure the perimeter, Establish Communicaiton, Report Status]
                Number of tasks: 3
## Exercise 2: Accessing and Modifying Elements (get and set)
        1. Prediction:
            What do you think will be the output?
                -I think the first output will be "Item at index 1: Map" since when we add the equipments
                the second one we add is the map and since this is an array as we count the items inside it 
                we will begin counting at 0 thats why the item that will print is Map, the second one output is
                "List before modification: [Compass, Map, Radio]" because since we already added some items inside it   
                java will just call toString and print it, the third one is "List after modification: [GPS, Map, Radio]"
                because when we use set method we will change an item in a certain index which is index 0 and modify the
                array thats why it will print the GPS instead of the compass
        2. Observation:
            Now, run the code. What is the actual output?
                -Item at index 1: Map
                List before modification: [Compass, Map, Radio]
                List after the modification: [GPS, Map, Radio]
## Exercise 3: Inserting and Removing Elements (add at index and remove)
        1. Prediction:
            What do you think will be the output?
                -I think the first output will be "List after insertion: 
                [Primary Objective, Secondary Objective, Tertiary Objective]" since this is a arraylist we 
                can jsut inserted an item inside of the array at index 1 and it will just 
                move the Tertiary Objective into index 2, and then the second output will be 
                "Removed objective: Tertiary Objective" and "List after removing by index: [Primary Objective, Secondary Objective]
                since the product we will remove is at index 2 and as we have already inserted and move tertiary in index one, 
                tertiary will be the one that will be remove and print the list that the tertiary is now removed,
                the third one output will be "List after removing by object: [Secondary Objectives]" that is because we used removing by 
                its value not index and now since we removed tertiary and now primary so that the only one that will 
                print is the secondary obj.
        2. Observation:
            Now, run the code. What is the actual output?
                -List after insertion: [Primary Objective, Secondary Objective, Tertiary Objective]
                Removed objective: Tertiary Objective
                List after removing by index: [Primary Objective, Secondary Objective]
                List after removing by object: [Secondary Objective]
## Exercise 4: Searching the List (contains and indexOf)
        1. Prediction:
            What do you think will be the output?
                -I think the first output will be "Does the list contain 'Bravo'? True" because contains means 
                he will be checking the exact same value that we input inside the arraylist and since we added bravo
                it will return true, the second output will be "Index of 'Charlie': 2" since we are in an array we will start
                counting in zero and also since we added charlie as a third one it will return index 2, the third output will be 
                "Index of 'Delta': -1" since delta does not exist in the arraylist.
        2. Observation:
            Now, run the code. What is the actual output?
                -Does the list contain 'Bravo'? true
                Index of 'Charlie': 2
                Index of 'Delta': -1
## Exercise 5: Iterating Through the List
        1. Prediction:
            What do you think will be the output?
                -I think the first output will be
                --- Using an Enhanced For-Loop ---
                Role: Leader
                Role: Medic
                Role: Engineer
                Role: Scout
                since we are using an enhanced for loop or for each loop here java will just print
                Role: till every items inside the arraylist print, the second one is 
                --- Using a Standard For-Loop with index ---
                Role at index 0: Leader
                Role at index 1: Medic
                Role at index 2: Engineer
                Role at index 3: Scout
                because now that we are using a traditional for loop we can iterate the number or show 
                its index while looping it.
        2. Observation:
            Now, run the code. What is the actual output?
                --- Using an Enhanced For-Loop ---
                Role: Leader
                Role: Medic
                Role: Engineer
                Role: Scout

                --- Using a Standard For-Loop with index ---
                Role at index 0: Leader
                Role at index 1: Medic
                Role at index 2: Engineer
                Role at index 3: Scout
## Exercise 6: Clearing the List (clear)
        1. Prediction:
            What do you think will be the output?
                -I think the first output will be "Intel count before mission: 2" and
                "Intel list: [Enemy position: Sector 4, Weakness: Power generator]" 
                that is because we added 2 item inside the arraylist and print it
                as for the second output it will be "Intel count after mission: 0" and 
                "Is the intel list empty now? true" and lastly "Intel list: []" because
                at first before printing we used clear method to delete every item inside the 
                array so when we check how many mission is remaining it will return zero and since 
                its empty it will return true for the second print and at the third print it will just return
                empty bracket.
        2. Observation:
            Now, run the code. What is the actual output?
                -Intel count before mission: 2
                Intel list: [Enemy position: Sector 4, Weakness: Power generator]

                Intel count after mission: 0
                Is the intel list empty now? true
                Intel list: []

