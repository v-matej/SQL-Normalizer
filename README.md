# SQL Normalizer Project
The SQL Normalizer project is a Python-based tool designed to facilitate the normalization of functional dependencies and attributes in a relational database. It employs classes to parse the dependencies and determine the primary key of the relation, ensuring compliance with the Third Normal Form (3.NF) and Boyce-Codd Normal Form (BCNF) standards.

# Introduction
Relational databases often require normalization to enhance data integrity and eliminate redundancy. The SQL Normalizer project offers a convenient Python-based solution for normalizing functional dependencies and attributes. By leveraging class-based parsing techniques, it efficiently determines the primary key of the relation and generates normalized relations adhering to the 3.NF and BCNF standards.


SQL Normalizer Project
The SQL Normalizer project is a Python-based tool designed to facilitate the normalization of functional dependencies and attributes in a relational database. It employs classes to parse the dependencies and determine the primary key of the relation, ensuring compliance with the Third Normal Form (3.NF) and Boyce-Codd Normal Form (BCNF) standards.

Table of Contents
Introduction
Installation
Usage
Functionality
Technologies Used
Examples
Contributing
License
Introduction
Relational databases often require normalization to enhance data integrity and eliminate redundancy. The SQL Normalizer project offers a convenient Python-based solution for normalizing functional dependencies and attributes. By leveraging class-based parsing techniques, it efficiently determines the primary key of the relation and generates normalized relations adhering to the 3.NF and BCNF standards.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/sql-normalizer.git
Navigate to the project directory:

bash
Copy code
cd sql-normalizer
Set up a virtual environment (optional but recommended):

bash
Copy code
python3 -m venv venv
source venv/bin/activate
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
To utilize the SQL Normalizer project, follow these steps:

Ensure you have a properly formatted input file describing the functional dependencies and attributes. The attributes should be listed in the form of A, B, C, etc. The file should be a plain text file, such as a .txt file.

Execute the Python script normalizer.py with the path to your input file as an argument:

bash
Copy code
python normalizer.py path/to/input_file.txt
The program will parse the provided input, determine the primary key of the relation, and generate the normalized relations. The results will be displayed in the console.

# Functionality
The SQL Normalizer project offers the following functionality:

Parsing and validation of functional dependencies and attributes using class-based techniques.
Determination of the primary key of the relation based on the dependencies.
Normalization of the relations to achieve 3.NF and BCNF.
Displaying the resulting normalized relations.

# Technologies Used
The SQL Normalizer project utilizes the following technologies:

Python: The primary programming language used to develop the project.
Object-Oriented Programming (OOP): The project employs classes to parse functional dependencies and attributes, enhancing code organization and maintainability.
