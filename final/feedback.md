# Feedback on your final

**Final Score: 54/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.


**(-3) To get full points, you needed to use more than one different file type.  You've done only CSV files**

**(-2) You've started with data that is by Country and Year and only joined on Country. As a result, you've got lots of data being duplicated.  This can mess up your later aggregations.**

**Why did you save the dataframe you created in Excel, JSON, and CSV?**

**(-1) Variable names like `final_merged_data` are a poor choice because your variable names should describe the content and purpose of this data to the user.**

**Overall, you did a great job.  Some good Python code.  The thing to focus on in the future is "what information is important for a reader to know?" And then include that information in your document.**