# PI-documentation-english
English documentation for PI.


**1. Presentation of the PI**

symploke is a digital platform created to connect mentors and mentees who are part of minority groups and face difficulties in entering the job market.


**2. Development team**

  1.  João Pedro Mota 
  2.  Guilherme Antonino
  3.  Yasmin Camille
  4.  kamila Estefane


**3. Technologies used**

  Our Project, focused on social inclusion, required an application at the  Database, taking into account our audience, identities, relationships, and others.. To design our database, we used the Br.Modelo platform to develop the Conceptual Model and Logical Model,        while for coding, we used MySQL Workbench.
  For programming, we used Python to register students, mentors, courses, and other related information.
  Our design was developed with the goal of creating an inclusive interface for people with disabilities, creative, accessible, interactive, dynamic, and clean. Before thinking about the physical aspects, we focused on user-centered methodologies and empathy, such as      the methods:
  Design Thinking: A method divided into five stages, from identifying the problem to finding solutions. A design approach centered on empathy and user needs.
  Empathy Map: Helps to understand the frustrations and expectations of our users.
  Stakeholder Map: Identifies the audience, their relevance, and their interest in the project.
  Effort vs. Impact Matrix: Determines which stages of the project are priorities, and which are future ideas, discardable, or currently inaccessible.
  Double Diamond: A diagram that divides the project into four stages: the first two focus on divergence, encouraging opinions and broad ideas, and the last two focus on convergence, limiting ideas down to priorities and useful solutions.

**4. How to Use the Application**

  - Make sure you have Python 3.x installed on your computer.
  - Install MySQL Workbench and the MySQL Server, as the system relies on a relational database.
  - Clone the project repository:
     Bash: 
     git clone https://github.com/Jaozni/PI-documentation-english.git

  - Navigate to the repository:
    Bash:
    cd symploke

  - Install all necessary dependencies:
    Bash: 
    pip install -r requirements.txt

    **2. Set up the database**

    - Open MySQL Workbench and run the SQL script located in the /database folder to create the database structure.
    - Update your database credentials (user, password, host, etc.) in the Python configuration file before running the application.
      
      **3. Run the application**
        - Once the database is properly configured, start the server by running:
          Bash:
            pyton app.py

        - The system will run locally, allowing you to:
            - Register mentors, students, and courses.
            - View and manage information stored in the database.
            - Experience an accessible and inclusive interface designed for all users.
              
      **4. Accessibility and design**
        - The interface was created based on user-centered methodologies such as Design Thinking, Empathy Map, and Double Diamond, ensuring a creative, inclusive, and easy-to-navigate experience — especially for users from minority groups and people with disabilities.
      
