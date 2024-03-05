# Multithreaded Data Analysis and Downloader in C++

 

### Objective: Develop a C++ program that downloads a public dataset from the U.S. government's open data portal ([https://catalog.data.gov/datasetLinks](https://catalog.data.gov/dataset) to an external site.) and utilizes multithreading to perform data analysis on the dataset.

Your job is creatively devise a strategy that can use threads to analyze and process data in the dataset. 

## Requirements:

1. **File Download:**
    - Download a large dataset in CSV or JSON format from the provided URL using a function to download a file. Use given code example. 
2. **Multithreaded Data Analysis:**
    - Utilize a multithreaded strategy to concurrently analyze the dataset, enhancing efficiency and performance. Employ distinct threads dedicated to identifying both the most common and least common elements, as well as the smallest and largest values. Leverage multiple threads to harness parallel processing, thereby optimizing resource utilization and accelerating the analysis process.
3. **Data Parsing:**
    - Develop a parser to extract relevant information from the dataset. This could involve parsing CSV or JSON data, depending on the format of the downloaded dataset.

4. **Thread Synchronization:**
    - Employ proper synchronization mechanisms (e.g., mutexes or other thread-safe structures) to ensure that threads do not interfere with each other during the analysis.
5. **Output Results:**
    - Display the results.
6. **Clean Code and Documentation:**
    - Write modular and well-documented code following C++ best practices. Include comments explaining the logic and purpose of key sections of the code.
7. **Include a Makefile.**

### **Deliverable:** A C++ code that implements the coding requirements. Provide the source code by copying and pasting it directly (avoid using screenshots of the code), and include screenshots displaying the output from a variety of test cases. Use your creativity and think about different test cases.

You may work in group 2-4, each member should submit the project, remember to include everyone's name on your project file that describes individual contributions, please use the group evaluation form:

### Group Members:
1. **[Your Name]**
2. **[Member 2's Name]**<br>
[For each member - fill out five reporting criteria]

- **Role:**
[Specify role, e.g., Project Manager, Researcher, Designer, Developer, etc.]
- Tasks Completed:
[List specific tasks or activities the student was responsible for.]
- **Challenges Faced:**
[Highlight any challenges the student encountered and how they addressed them.]
- **Achievements:**
[Mention any notable achievements or contributions the student made to the project.]
- **Contribution and Performance Rates:**
[1 being the lowest, 10 being the highest. This section allows each group member to provide a numerical score for their teammates, fostering communication and reflection on group dynamics.]

*You can work by yourself too.

Reminder: Late submissions of programming assignments will incur a penalty. For each hour a submission is delayed beyond the deadline, one point will be deducted from the assignment's total score. This policy has been implemented to ensure fairness and consistency in evaluating student work. 