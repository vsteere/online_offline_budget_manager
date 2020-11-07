# Budget Manager Application with Offline capabilities

This MVC application allows the users to manager their budget through debit and credit entry, graphically rendering the activity and balances. The data is stored in a NoSQL Mongo database which enables the user to return to it at a later time to see their balances and activity.

As an added feature, it uses Service Worker and IndexedDB technologies so the user is able to enter data even when the application is ran offline. Once an internet connection is once again established, the data is moved to the database, so no activity is lost, even when entered offline. 

## Pictures
![image of app](/public/pic1.JPG?raw=true "online function")
![image of app](/public/pic2.JPG?raw=true "offline function")


## Links
GitHub Repository: https://github.com/vsteere/online_offline_budget_manager
Deployed Application :https://secret-eyrie-63779.herokuapp.com/

