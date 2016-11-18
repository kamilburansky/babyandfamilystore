# babyandfamilystore
MAIN TESTS FROM THE POSSITION OF CUSTOMER for webpage https://www.babyandfamilystore.co.uk/ 


1. Homepage = https://www.babyandfamilystore.co.uk/ - tested
2. Search Results Page = search for string "monitor" - tested
3. Login my account - tested
4. Create my account - tested
5. Order Form Page without account as Guest - partially tested
6. Product Details Page
4.Order Confirmation Page


Options to config in test:

-searching
final String searchingWord = "monitor"; - word, that is usually used in this webpage, can be changed
final String searchingSpecificWord = "Tomy Baby Digital Monitor TF525";  - try to find a specific item with this name, can be changed

-creating/logging user
final String emailAccount = "kamilburansky@gmail.com";  //- creating account using this email, can be changed
final String firstName = "Kamil"; //- creating account using this firstName, can be changed
final String lastName = "Buransky"; //- creating account using this lastName, can be changed
final String passwordString = "_123passworD123";  //- creating/logging account using this password, can be changed


