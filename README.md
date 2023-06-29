# formOpearations
if you want to run this project first you need to follow the below steps: 
1. cd my-app
2. npm install
3.  npm start

also, you run the API's using nodemon [fileName].
create mysql table[useres] with below columns:
1. CREATE TABLE users (
  id INT PRIMARY KEY AUTO_INCREMENT,
  username VARCHAR(255) NOT NULL,
  password VARCHAR(255) NOT NULL,
  first_name VARCHAR(255) NOT NULL,
  last_name VARCHAR(255) NOT NULL,
  birth_date DATE NOT NULL,
  address VARCHAR(255) NOT NULL,
  contact_number VARCHAR(255) NOT NULL
);
