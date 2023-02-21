As a user i want to store and retrieve data about my books via HTTP call to the API.

Data should contain next fields:
- Name
- Author
- Year

Technical requirements:
* All needed entities and logic should be described in a separate packages (directories).

* Methods you need to implement POST (list of books), GET (list of books).

* Data should be sorted by year in ascending order (lookup sort interface).

* Year property should be stored as integer type, but as you can see inside JSON it is string (lookup MarshalJSON/UnmarshalJSON), also you need to return it as string too. Store data in-memory but use interface to create additional repository abstraction layer.

*  Code as always should be stored in remote github repo (make sure that you had done all development process on the separate branch library_v1 , and then made pull request to the main branch).

* Pay attention to your commit messages (make them clear and laconic).