# Parking-Finder
Using MVVM architecture to build parking spot finder

---

**Introduction to MVVM Architecture :**

![alt](https://images.prismic.io/intuzwebsite/2339b663-715d-40bc-a767-a39b4a76bd51_MVVM_architecture_40eb8f8bda.png?auto=compress,format)

The big the software get , the hard be to get the overview , so it is crucial that we give our projects a good structure which usually means a seperation of concerns we want to separate the **UI** , the **Business Logic** , and the **Data Source** , so that our we and our colleagues can easily and quickly understand the software that we can easily extend with more features and that we can easily test it , taht's where architetural design patterns come into play 

In andorid apps MVVM is the most popular one it stands for model view viewModel 

The Model is the data source which is often represented by a repository that just collects all data in one central place that can be a data from a database , data from a remote api or just data from both 

The ViewModel , contains the business logic , business logic is just the reel program logic that is not just updating a ui element , so for exemple filtering a list or validating a user input , the view model is in undirect communication with the model to get access to the data it needs 

lastly the view is the visible part of the app it contains all ui elements and gets events from the view model when it should update its views , important is view should not contains any business logic , it should only contains logic to directly manipulate views together this is a powerfull pattern 