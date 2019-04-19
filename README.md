# TeamM
Rahul Sharma 40020034  
Rafael Bis Ferreira 40042321  
Harmeet Singh 40053592  
Harmandeep Kaur 40091199  
Yann Kerichard 40059813  

# Directory Structure
- Reports
    - Project Name
    - Test Coverage Reports
    - PI test report
- Configuration Files (Contains pom.xml and build.gradle required to run PI testing and Test Coverage)
- Data
    - Result (Figures of correlation data)
    - Metric 5 and 6 (Contains collected data for both metrics from JIRA)
    - correlation.ipynb (Jupyter notebook with code to calculate all the correlation)
    - Test coverage and Mutation Score Data (Data from reports in csv format used to calculate correlation)

# Running Test Coverage
- Include the corresponding pom/gradle file into the project root folder. Plugins with their specification are already included in the pom files as per our requirements.
- Run
```
mvn clean install
mvn clean test
```

# Running PI testing
- Include the corresponding pom/gradle file into the project root folder. Plugins with their specification are already included in the pom files as per our requirements.
- Run
```
mvn org.pitest:pitest-maven:mutationCoverage

```
