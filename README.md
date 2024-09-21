java c
STAT667 Assignment #1
Please save the assignment file by appending your name as a suffix, for example, M1_assignment_JohnSmith.docx. Include any necessary code directly below the corresponding questions. Display the outcomes and provide clear responses to the inquiries. Submit the .docx file as the primary document for this assignment. Please remove the images below, as they were only intended to assist you in locating the folders. Once you have completed the task, the images are no longer necessary.1. Familiarizing Yourself with Accessing SAS Studio via SAS OnDemand.- In the ‘Files (Home)’ directory, create a new subfolder named ‘STAT667_052’.  This directory will serve as the storage location for all your course-related data and code files. To achieve this, hover over the directory, right-click your mouse, and select 'New' followed by ‘Folder’. (i.e.  -> New -> Folder)- Under STAT667_052, create another subfolder called ‘M1’.  Download the dataset M1_data.dat to your computer and then upload to this M1 folder.-1.1 Right-click the ‘M1’ folder and choose ‘Properties’.  What’s the location/path for this folder? Please provide a screenshot and written response as answers.1.2  In a similar manner, determine the location of the dataset M1_data.dat.2. Questions 2-5 are located in the SAS file named m1_assignment_Q23456.sas.  Please download this code from Canvas to your local drive and subsequently upload it to your M1 folder in SAS Studio.  Open the file by clicking on it, carefully follow the provided code and questions, and input your responses beneath each respective question within the comment section.Upon completing all five questions, remember to save your code file. Below each question, c代 写STAT667 Assignment #1R
代做程序编程语言opy and paste the relevant code as part of your assignment submission.7.    Utilize the following libname statement to access the recently established 'M1' folder. To achieve this, replace the red text below with the folder path you created in part 1.1. Navigate to the 'Libraries' tab within the left-hand panel. Click on the small triangle situated to the left of the term 'Libraries' to expand this section. For reference, consult the provided image to locate the 'Libraries' section, situated at the bottom left corner of the interface.
libname M1 “put your folderpath here”;
7.1 What’s in Libraries?  You can take a screenshot to better illustrate.7.2 Among the libraries listed here, the majority are 'public' libraries offered by SAS. Locate your individual library named 'M1.' Click on the triangle icon situated on the left side to expand the library view. What items are present within it? Can you observe the raw data file named M1_data.dat? If it's not visible, please provide an explanation for its absence.7.3 The majority of the libraries listed here are 'public' libraries supplied by SAS. Identify your individual library labeled 'M1.' Click on the triangle icon positioned on the left side to expand the library view. What contents are present within the library? Is the raw data file named M1_data.dat visible? If it's not visible, kindly provide an explanation for its absence.7.4 Execute the following code. What is the content of the M1 library now?
Data m1.assignment_1;
X=101;
Run;8. How to print “Hello UD” to the result window without employing macro variables?  You may need to involve a dataset and ‘PUT’ function.







         
加QQ：99515681  WX：codinghelp
