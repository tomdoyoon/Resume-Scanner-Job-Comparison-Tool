# Resume-Scanner-and-Match-Tools

# ABSTRACT

This project is an attempt to scan and compare your resume with a job post. The objective is to provide the user with a percentage similarity score based on keywords and key phrases. According to the BLS, on the last day of December 2022 there were approximately 11 million job openings. Per an ADP report, published in August 2022, workers who left their current company for another opportunity saw a median raise of 16.1% in annual pay. 

There are two applications that vary the method of inputting a resume and a job description. The first application takes in the user’s resume through the form of a PDF and takes a job post through the form of a LinkedIn URL. The code then identifies the job description section and cleans the HTML tags before further preprocessing of the job description. The other application intakes the resume and the job description through copy and paste. This method allows for a more accurate comparison of a resume and a job description.

Both applications preprocesses the data, tokenizes the text, and filters the extracted keywords and key phrases before comparing the resume with the job post using a Levenshtein distance metric.

Future iterations of this project leaves room for industry specific keyword generation, cleaner LinkedIn job description scraping, and using cosine similarity to measure the similarity between a resume and a job post.   


# TABLE OF CONTENTS

-	LinkedIn Resume Scanner and Match Tool: PDF and LinkedIn application
-	Text Resume Scanner and Match Tool: Copy and paste application

