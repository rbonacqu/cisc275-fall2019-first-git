# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
3 Dog objects are created and then 2 Animal/Dog objects are used for the compare method inside the Comparator.

3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?

The Comparator constructor call is on Line 16:
	Collections.sort(dogs, new Comparator<Animal>() {

The class definition for the Comparator is line 18:
	public int compare(Animal a, Animal b){
