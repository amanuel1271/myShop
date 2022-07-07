# MyShop

In Myshop, clients are able to sell or buy products according to the need. Clients have to signup first before being able to buy/sell. After signing up, they can login using their email and password credentials. To buy a product, the client must add to cart and order the products and pay using the test cards given below. To sell a product, the client must enter the Add product page and input the title, image file(jpg or jpeg),price and description.

# Languages,Frameworks and databases
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

# Design
 
- This app uses the MVC design pattern
- It uses Express js and other libraries to navigate between the frontend and handling the routes. I used EJS(Templating engine) and CSS for the frontend.
- Mongoose ODM is used to connect and access the MongoDB database, which stores user info, product info and also session info.
- The app uses sessions, authentication and validation to handle users.
- It uses stripe to make online payment, the following are available test cards for online payment

    CardType   Card Number  CVC            Date
    Visa	4242424242424242	Any 3 digits	Any future date
    Visa (debit)	4000056655665556	Any 3 digits	Any future date
    Mastercard	5555555555554444	Any 3 digits	Any future date
    Mastercard (2-series)	2223003122003222	Any 3 digits	Any future date
    Mastercard (debit)	5200828282828210	Any 3 digits	Any future date
    Mastercard (prepaid)	5105105105105100	Any 3 digits	Any future date
    American Express	378282246310005	Any 4 digits	Any future date
    American Express	371449635398431	Any 4 digits	Any future date
    Discover	6011111111111117	Any 3 digits	Any future date
    Discover	6011000990139424	Any 3 digits	Any future date
    Diners Club	3056930009020004	Any 3 digits	Any future date
    Diners Club (14-digit card)	36227206271667	Any 3 digits	Any future date
    JCB	3566002020360505	Any 3 digits	Any future date
    UnionPay	6200000000000005	Any 3 digits	Any future date
    
    # Demo
 ![Demo](https://user-images.githubusercontent.com/50099232/177853628-990240b4-69ac-41bb-9e67-a6341f19ffb7.gif)

