# Response to reviewers of "Spreadsheet modeling and wrangling with Python"

I'd like to thank the reviewer and the editor for their thoughtful comments on this paper. I have
done by best to address them.


## Editor comments


**Comment 1**

I would like to apologize to the author for the delay in the review.  Although two reviewers accepted the assignment, one of them, at this point, is 65 days late with the review – therefore, I decided to proceed with a single review.

My first request to the author is to include other related ITE publications either as part of the literature review or to the other relevant sections.  Here is a short list of links to start:
•       https://pubsonline.informs.org/doi/pdf/10.1287/ited.2021.0261
•       https://pubsonline.informs.org/doi/full/10.1287/ited.2023.0285
•       https://pubsonline.informs.org/doi/pdf/10.1287/ited.2022.0275

**Response 1**

In the opening paragraph I refer to the seminal issues of ITE but didn't reference specific papers. I've rectified that and have added the following references.

- Alderson DL (2022) Interactive computing for accelerated learning in computation and data science. INFORMS Transactions on Education 22(2):130–145, URL http://dx.doi.org/10.1287/ited.
2021.0261.
- Baker K (2000) Gaining insight in linear programming from patterns in optimal solutions. INFORMS Transactions on Education 1(1):4–17, URL http://dx.doi.org/10.1287/ited.1.1.4.
- Bell PC (2000) Teaching business statistics with microsoft excel. INFORMS Transactions on Education 1(1):18–26, URL http://dx.doi.org/10.1287/ited.1.1.18.
- Carraway RL, Clyman DR (2000) Integrating spreadsheets into a case-based mba quantitative methods course: Real managers make real decisions. INFORMS Transactions on Education 1(1):38–46, URL http://dx.doi.org/10.1287/ited.1.1.38.
- Evans JR (2000) Spreadsheets as a tool for teaching simulation. INFORMS Transactions on Education 1(1):27–37, URL http://dx.doi.org/10.1287/ited.1.1.27.
- Isken MW (2003) Data cleansing and analysis as a prelude to model based decision support. INFORMS Transactions on Education 3(3):23–75, URL http://dx.doi.org/10.1287/ited.3.3.23.
- Isken MW (2014) Translating a lab based spreadsheet modeling course to an online format: Experience from a natural experiment. INFORMS Transactions on Education 14(3):120–128, URL http://dx.doi.org/10.1287/ited.2013.0123.
- Powell SG (2001) Teaching Modeling in Management Science. INFORMS Transactions on Education 1(2):62–67, ISSN 1532-0545, URL http://dx.doi.org/10.1287/ited.1.2.62.
- Ragsdale CT (2001) Teaching management science with spreadsheets: From decision models to decision support. INFORMS Transactions on Education 1(2):68–74, URL http://dx.doi.org/10.1287/ited.1.2.68.
- Savage S (2001) Blitzograms—interactive histograms. INFORMS Transactions on Education 1(2):77–87, URL http://dx.doi.org/10.1287/ited.1.2.77.

The publication by Alderson (2022) is very relevant and I'm not sure how I missed seeing that. I've integrated it into the paper and cited it. Thank you for bringing it to my attention.

"One particularly relevant example are the courses in computation offered by the Naval Postgraduate School and described in Alderson (2022). In their courses, Jupyter notebooks (discussed in more detail in the next section) play a prominent role in providing an interactive development and learning environment for Python within an operations research context."

In the first version I avoid citing my own work in ITE even though it is quite relevant. It now seems appropriate now to add these and I have done
that in the section describing my speadsheet based analytics course.

**Comment 2**

Second, I found it difficult to follow the structure of the environment within which the course it taught.  Could the author please include a graphic or a table to add a visualization to the explanation of where in the program’s curriculum the AAP course fits in, and where in the AAP course the EwP module fits in.

**Response 2**

I understand. I've added more explanation to the relevant paragraph. As opposed to adding a table or graphic that abstracts the details, I'm encouraging the readers to visit the relevant course landing pages as they include nicely structured topic outlines that make it very clear how EwP fits in to the Python material covered by our PCDA and AAP courses.

Here's the reworked paragraph:

"At our institution, The EwP module is part of a business course entitled  [Advanced Analytics with
Python](http://www.sba.oakland.edu/faculty/isken/courses/aap) (AAP). The students taking this course have already taken the PCDA course within which they learned fundamental Python programming within the context of data analytics over seven weeks. The PCDA course ends with intro to the [scikit-learn library](https://scikit-learn.org/stable/index.html) for doing predictive modeling in Python and the AAP course begins where the PCDA course ends. The EwP module follows immediately after the modules on machine learning and builds on the Python fundamentals which were covered in the PCDA course. The EwP module could also be used as part of a semester long Python based analytics course in which the Python modules covered in the PCDA course are followed by more advanced topics such as EwP or other topics in our AAP course. The only reason the EwP module is not included in the PCDA course is that Python is only covered in half of that course - the other half being an introduction to R and Linux. If you visit the open access [PCDA course
website](http://www.sba.oakland.edu/faculty/isken/courses/pcda/)  and [AAP course
website](http://www.sba.oakland.edu/faculty/isken/courses/aap/), you can see the topic outline for each course and how the EwP module is positioned."

I'd like to stress that a big part of my paper is that it isn't just a paper. It is backed by a huge amount of public, freely available and Creative Commons licensed course websites and course content. Anyone who is interested in adapting my materials for their course is free to do so. Everything other than all of the homework assignments are publicly accessible from the course websites. That's why throughout this paper I provide hyperlinks to relevant parts of the EwP course website or course content. This allows the reader to have a richer reading experience - instead of just a paper which necessarily is limited by what it can contain, the reader can view the entirety of the Jupyter notebooks, in html format, which make up the modules. ITE is an online journal and I'm trying to take advantage of the capabilities offered by such a platform.

**Comment 3**

Are the students already familiar with the Jupyter notebook environment from their PCDA course, and therefore the instructor continues using the same environment, or are the students using a different development environment in their preceding course?  

**Response 3**

Yes, we use Jupyter notebooks as well as a integrated development environment (either Spyder, PyCharm, or VSCode) in the PCDA course. The same tools are used in the AAP course. All of the technical and logistical details of both courses are described in excruciating detail in the public course websites linked to in the paper. 


**Comment 4**

The same with source control – it is not clear to me why the program chose to include software engineering related discussion about source control in the EwP module of the AAP course, could the author please add a bit of discussion around that?

**Response 4**

I didn't choose that. Version control is covered in the very first module of the AAP course and students use git and GitHub for the ML module that precedes the EwP module. The following sentence is in the original version of the paper:

"Students are reminded of the importance of version control and we initialize a git repository for our budding package. The basics of version control were already covered in the first week of the course."

Again, the AAP course website main page at [http://www.sba.oakland.edu/faculty/isken/courses/aap/](http://www.sba.oakland.edu/faculty/isken/courses/aap/) contains a detailed topic outline and the reader can see what is covered when.


**Comment 5**

Third, would it be possible to add the learning goals of the EwP module and suggested methods for assessments?

**Response 5**

Each submodule of EwP has a number of learning objectives that appear at the top of each
submodule course webpage. I've added screenshots of these objectives so that readers can see
how the objectives are presented to the students.

As for assessment, in the final section of the paper, *Classroom experience and the future*, we described and made available for download an assignment that we have used for assessment of this material. It covers all aspects of the EwP module. 

**Comment 6**

Fourth, the author should also address the comments and suggestions provided by Reviewer 1.

Thank you for the submission to ITE and sharing your ideas and experiences with our academic community.  My apology again for the delay in the review process.

**Response 6**

See below for comments and responses to Reviewer 1.

## Reviewer #1 comments

Thank you taking the time to review my paper and to provide thoughtful feedback.

**Comment 1**

In the Introduction section, there appears to be too much emphasis on offering
the EwP approach as an alternative to Excel due to its limitations. I don’t think
many folks will buy the argument. The discussion seems to shortchange Excel’s
ability to set up connections with externally managed data while maintaining the
flexibility and ease of summarizing data in Excel. An alternative is to simply
suggest previous work in Excel by students provides a good launch point for
developing the more advanced programming skills in Python.

**Response 1**

I'm definitely not trying to offer EwP as an alternative to Excel. I've taught an Excel based spreadsheet modeling course for over 20 years and have used Excel extensively in both industry as well as in academic settings. I love spreadsheets and have for a long time. But, they do
have their limitations and the better our students are at assessing when a spreadsheet is and is not appropriate, the better off they will be. This is not some novel argument. Excel bashing is rampant in corporate IT and analytics settings. Quite honestly, even Jupyter notebooks have major shortcomings when it comes to productionizing analytical models implemented in Python and I mention this in the paper - and that's why I also make students use an actual IDE to write code in addition to the things we do in notebooks. There's a lot of nuance in knowing how to effectively wield tools like Excel and Python in professional analytics environments. This is a big part of the motivation behind the development of my courses and in writing this paper. 

My intent is to provide an interesting way for business students to learn more advanced Python concepts through a very familiar lens of spreadsheet modeling. In addition, I want to expose them to the abilities of Python in automating manipulation of spreadsheets. Now with MS announcing the inclusion of Python within Excel, the complementary nature of these two powerhouse tools will become even more important. To that end, I've modified the beginning of that paragraph as follows:

"Despite numerous calls for, and predictions of, the eradication of spreadsheets from the business world, Excel and other spreadsheets are \href{https://benn.substack.com/p/the-next-billion-programmers}{alive and well}. Their flexibility is unparalleled and it is unrealistic to expect them to disappear anytime soon. If anything, the [recent announcement by Microsoft](https://techcommunity.microsoft.com/t5/excel-blog/announcing-python-in-excel-combining-the-power-of-python-and-the/ba-p/3893439)
 that users will be able combine Python scripts with Excel formulas within the same workbook, will likely solidify Excel's place in the analytics space."

**Comment 2**

In sections 3.2 and 3.3, it would have been nice to see more figures illustrating
the coding associated with Goal Seek and Monte Carlo simulation exercises.

**Response 2**

I wrestled with this when writing the paper. Instead of including more figures, I opted, as I described above, to include prominent hyperlinks to HTML versions of the notebooks in the relevant section headers. 

For example:

3.3. Notebook 3: Monte-Carlo simulation (html version)

I also added explicit language early in the paper that highlighted these hyperlinks and encouraged readers to use them.

"While all of the notebooks are publicly available (see Section 6), links to html versions of
each of the notebooks are provided throughout the document and readers are encouraged to use
them while reading to see exactly how each topic is presented."

My intent is for the reader to open this html version in a browser tab and then they can see the entire notebook. Code snippets taken out of context are not nearly as useful as following the narrative flow of the notebook - this is the real strength of Jupyter notebooks for teaching.

If the reviewers really want me to add more code screenshots, I can, but I'd really prefer readers look at the (html versions of) the actual notebooks. Of course, the actual Jupyter notebooks are also available from the course website.


**Comment 3**

In section 7, the author(s) need to more fully address the roll out of Python in
Excel. Does this alter their pedagogy? It may not if the focus is develop the skills
outlined in the Introduction and listed below
o  teaching relevant and more advanced Python to business students using familiar and
simple modeling examples,  conveying a sense of the software design and development
process,  acting as a tour guide for a learning journey,  teaching students to think and
act like a software developer, not just an analyst
In any case, I think the paper needs a more comprehensive discussion regarding
this development.

**Response 3**

I've added reference to this development in the opening section as I mentioned in Response 1 above. I've also added a bit in the last section:

"Rumors have swirled for a number of years that Microsoft was considering adding Python as a first class language alternative to VBA within their MS Office suite of packages \cite{cimpanuMicrosoftConsidersAdding2017}. During the review process for this article, this development [finally
materialized](https://techcommunity.microsoft.com/t5/excel-blog/announcing-python-in-excel-combining-the-power-of-python-and-the/ba-p/3893439)
, albeit in a limited roll out to beta testers. This has potentially enormous implications for the future of both Excel and Python. At this point, it is probably safe to say that this development further underscores the importance of business analytics students adding Python to their set of analytical toolbox."

Other than that, I'm not in a position to say a whole lot more right now. The roll out was restricted to those with Beta Channel access (which I do not have). It appears right now that this feature is designed to run in the Azure cloud environment, which is a little concerning. It's also not clear if we'll be able to write full blown code modules in Python instead of Excel VBA. It's just too early to know how this is going to play out.
If and when this development is widely released, then certainly I will develop a teaching module to add to my AAP class and will likely add a very introductory module to my spreadsheet based analytics course. This will be a rich area for collaboration between the Excel and Python communities. Pretty exciting development but pales a bit in comparison to the chaos around Microsoft and OpenAI right now. :)

**Editing Comments**

On page 5, 2 nd paragraph – The sentence “ After running the cells, they appear as show
in Figure 2.” – The word show should be changed to shown

**Response**

Oops. It's fixed now.







