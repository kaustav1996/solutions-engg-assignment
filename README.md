## Solutions Engineering Assignment: API Data Visualization with React, Python, Docker, and Scripting

### Assignment Overview:
You are tasked with creating a solution that involves calling scraping data from https://sahamati.org.in/fip-aa-mapping/, visualizing it, and packaging the application using Docker for easy deployment. The assignment will require proficiency in React for frontend development, Python for backend processing and scraping, Docker for containerization, scripting for automation, and version controlling using Git.

### Assignment Details:
1. **Task Description:**
   - Develop a web scraper that fetches data from [Sahamati AA Website](https://sahamati.org.in/fip-aa-mapping/).
   - Implement a scheduled cron job that makes the scraper scrape and download the data every day and store it.
   - Store data in any Database of your choice. 
   - Anumati, CAMS, CRIF, DIGIO, etc are the AAs.
   - Aim is to plot a time series graph for each AA against the number of Entities that are Live, Testing phase / NA .
   - Process the retrieved data using Python for any necessary backend operations.
   - Visualize the processed data in a meaningful way using React for the frontend.
   - You can add mock data for a few days for the sake of the visualisation
   - Setting up mock data should be automated
   - For example for CAMS it might look like :
     <img src="Solution_Engg_Assignment.png" alt="AA x FIP Integration progress graph" width="300" />

2. **Technical Requirements:**
   - Utilize React for building the frontend components and user interface.
   - Implement Python scripts for handling API requests, data processing, and any backend logic.
   - Containerize the application using Docker and Docker Compose to ensure easy deployment and scalability.
   - Create scripts to automate the process of building the Docker image and running the application.

3. **Key Steps:**
   - Design the frontend interface using React to display the fetched and processed data.
   - Develop Python scripts to interact with the website, scrape the data, process the data, and serve it to the frontend.
   - Containerize the application using Docker, ensuring all dependencies are included.
   - Write scripts to automate the building and execution of the Docker image.

4. **Deliverables:**
   - Fully functional web application that visualizes the data as mentioned in the required format.
   - Dockerized application with clear instructions on how to download and run it.
   - Documentation detailing the API used, data visualization techniques, and the overall architecture of the solution.

### Assessment Criteria:
- **Functionality:** The application should effectively scrape, process, and visualize data from the website.
- **Code Quality:** Clean, well-structured code in React, Python, and Docker configuration files.
- **Containerization:** Docker image should be correctly built and easily deployable.
- **Automation:** Scripts should simplify the process of downloading and running the application.
- **Version controlling:** Appropriate commits are to be made with progress and deliverables.

### Additional Tips:
- Focus on modularity and reusability in your code to showcase best practices.
- Test the application using unit tests thoroughly to ensure it works as expected before submission.
- Please don't use too much generative AI. We will use AI detectors to check.
- Please take your time and build it. Our bar for this role is quite high.
- **Submit the github link to the repo used for the project. We would go through the readme and follow instruction provided to run and test the application**

All the best!
