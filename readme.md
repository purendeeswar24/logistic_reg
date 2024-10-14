streamlit run app6.py --server.port 8502

-- code to connect to database

CREATE DATABASE heart_data;
USE heart_data;

CREATE TABLE user_inputs (
    id INT AUTO_INCREMENT PRIMARY KEY,
    age INT,
    sex INT,
    bp INT,
    cholesterol INT,
    heart_disease INT
);


select * from user_inputs;