The path to the application for gulp in Node npm is
cmd /K "cd C:\xampp\htdocs\projects\gusto_web"

when in gusto_web directory write gulp to start it
This will tranform Scss to CSS and main.js to main.min.js and minimise them


//SQL to create table

CREATE TABLE usres (
    user_id int AUTO_INCREMENT,
    company_id int,
    user_email varchar(20) NOT NULL,
    user_password varchar(20),
    reg_date current_timestamp,
    PRIMARY KEY (user_id),
    FOREIGN KEY (company_id) REFERENCES company(company_id)
);