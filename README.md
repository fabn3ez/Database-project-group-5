CREATE TABLE Beneficiaries (
    beneficiary_id INT PRIMARY KEY AUTO_INCREMENT,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    age INT,
    gender VARCHAR(10),
    location VARCHAR(100),
    household_size INT,
    health_status VARCHAR(255)
);
