After deleting only the Vote POD, nothing happened on the GUI, and I was able to vote successfully, indicating that nothing happened on the application end. The Volte POD was recreated after deletion.
The same observations were made after deleting the Worker POD.
After deleting the DB POD, the results were cleared on the GUI. In the CLI, the DB POD was recreated.
Since the DB POD stores all the data, including the results, deleting the DB POD refreshes (clears) all the data.
We observed that no issues occur when any POD other than the DB POD is deleted. However, when the DB POD is deleted, all data stored in the database is cleared.
