#Lab 2 Answers

Q: What is the complexity of each of the four search methods in terms of array or list size n?
A: The complexity of the first method findTeamPosition (array) would be O(n) because of the one loop in terms of n it goes through. 
   The complexity of the second same method, but for a list, would be O(n). 
   The complexity of the third method findTeamMinFunding (array) would also be O(n). 
   The complexity of the fourth same method, but for a list, would be O(log(n)) because the running time is proportional to the amount of time n can be divided by two as seen in the while loop.
   
Q: What happens in the case of binary search if the array is not sorted?
A: The binary search goes in order based on the array being presorted, so if the array is not already presorted, 
   then the search would not conduct properly and the result would be incorrect or impossible to be found by the search.

Q: What is the purpose of constructor argument validity checking?
A: Checking the validity of the contructor arguments verifies and specifies what variable one is talking about and using.

Q: What is the purpose of using the keyword `final` with variables and arguments?
A: Using the keyword ensures that no change will happen to that variable. It will always have the value declared to it initially.

Q: What are alternatives to using `Optional` and how do they compare?
A: The different alternatives to using Optional can include using loops and declaring variables as null to account for the other
   options that would be possible, however using Optional makes that process much easier and quicker, because less code.