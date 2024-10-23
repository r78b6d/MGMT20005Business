java c
MGMT20005-Business Decision Analysis
Assignment 2: Group AssignmentIntroduction: This is a group assignment of up to 3 students (1-3 students) from the same tutorial group. You are also allowed to form. a group with students of the same tutor. Note that if the group is formed with students of different tutors, you will receive zero marks for this assignment. You can complete your assignment individually, if you wish, however, you are strongly encouraged to complete this assessment in a group setting.
Weight: 25% of the total mark.
Format: PowerPoint file (.pptx/.pdf) + Recorded presentation (.mp4) + Excel workbook (.xlsx). Due date: 6pm Friday, Week 11.Submission: Only one submission (with all your files) is required for each group. Make sure you include the names and student numbers for all team members on the front slide of your PowerPoint file submission, otherwise, a penalty will be applied!
Late submission: It will attract a marking penalty. A 10% penalty will be applied for every day of late submission for up to 3 days. Assignments submitted later than 3 days after the due date will not be marked and will receive no mark.
Extension request: No extension will be provided for this assignment (since this is a group submission, no extension will be provided even for individual work).
Submission format and word limit:
1.   Prepare your submission using Microsoft PowerPoint (or similar presentation software). You can use up to 30 slides and up to 2,500 words in your slides altogether (excluding figures, tables, references, and appendices, however  the  30  slides  limit still applies). Your  slides  should  be well-organised,  coherent,  and visually appealing. Note that it is important to cover all below the requirements in your submission.
2.   A maximum of 5-minute recorded presentation outlining your analysis and assessment of your  portfolio optimisation methods used. You may choose to use the same deck of slides that you and your group have put together (or a revised slide deck) if you find this suitable and appropriate for the 5-minute presentation. You must submit an .mp4 file (or similar) for your video presentation and it is a requirement to show your face/s in your presentation recording.
Assignment DetailsThis assignment is designed to let you explore and evaluate a number of approaches for portfolio optimisation, using live   real-world    data   from   the Yahoo   finance   website.   The    relevant    URL   for   finding   stock    prices   is https://au.finance.yahoo.com/.  Under  the “Quote  lookup”, you  can  search for  the  industry/business you  are interested in to explore investment (assets).Portfolio Optimisation - Risk and Return: An investment portfolio consists of a collection of investment items (or stocks or assets) held by an individual or organisation, in which the investor seeks to purchase a variety of assets to gain a good return (profit) through increasing assets value. Individual assets vary in value from minute to minute, and whilst over time, they might grow in value, their value fluctuates over time. The possibility of such fluctuations represents a risk to the investor. Accordingly in portfolio selection, investors should wisely choose to invest across a range of assets, ideally those total value is less liable to fluctuation than the individual assets.In this assignment, you are required to use asset return data from a period of 4 years to identify the optimum portfolio using a variety of different optimisation methods. The assignment report (slides) should include three main sections: Preliminary Work, Optimisation Models and Conclusion. The requirements of each part are detailed below.
The breakdown of marks (a total of 25) is given on this document and as a Rubric in Canvas.
Preliminary Work (3 marks: Data collection + Classifications)The first stage is to identify a set of 12 investment items from which you will subsequently determine optimum portfolios using various optimisation models. You may select any global assets (including indices) whose data is provided on the Yahoo finance website. After you searched for the stock under the “Quote lookup”, go to the “ Historical data” tab, then choose the appropriate Time period, and Frequency before downloading the data.
Note: If you have problem to download data from Yahoo, you can copy and paste the data directly from the website into an Excel document.


The chosen assets must satisfy the following general conditions:
.    Each  must  have  at  least 48  months (August 2020 - August 2024) of monthly data available, up to and including August 2024.
.    They should be selected from any 4 different sectors/categories of your choice (let’s call them S1, S2, S3, and S4) e.g., banking, pharmaceuticals, media, technology, government bonds, property trusts, etc., with at least 2 assets in each category. Provide clear justification and reasoning for your choices.
.    You     need    to     calculate     the  monthly     return     of     each     asset by     (Stock_value_new     – Stock_value_old)/(Stock_value_old). Then the average return of an asset is the mean of return of that asset over 48 months. Similarly, the risk is calculated as the standard deviation of return over 48 months. A sample Excel file is provided that includes sample data with the calculation of return and risk.
.    Data  should span a  reasonable range of volatilities/risks. Classify the assets into 4 groups according to (ascending) risk (let’s call them R1, R2, R3, and R4). A simple classification approach would be to calculate the standard deviation of each asset (as explained in the previous dot point) and define risk categories based on the 4 quartiles. Therefore, R1 should include investment stocks with the lowest risk (lowest standard deviation).
.    Recall that each asset lies in one of the Rs and in one of the Ss.
Optimisation ModelsThe assignment requires you to consider two different optimisation techniques: linear programming and integer linear programming.  For  each  optimisation  model,  explain the  optimisation  approach taken, the  mathematical formulation and identify how the Excel Solver is to be used (explain any constraints used – e.g., that a var代 写MGMT20005-Business Decision Analysis Assignment 2Java
代做程序编程语言iable needs to be an integer or binary and include any necessary screenshots of how Excel Solver is implemented on your slides).
. LP model (9 marks: Mathematical Model + Excel Solver and Reports + Discussion): In this approach, the aim is to achieve the maximum overall return of the portfolio, subject to specified requirements on risk mix (percentages in R1 to R4) and category mix (percentages in S1 to S4). Note that the overall return of a portfolio (or its expected return) is calculated as a weighted average of the expected returns of all assets, where the weights represent the proportions of the portfolio that should be invested in each asset.The following investment guidelines are to be applied to the Linear Programming model: (1) Investment in the highest-risk assets shouldn’t exceed 15% of the portfolio, while the lowest risk (or equal lowest) assets should have the highest (equal or highest) investments among all other risk categories, (2) To ensure diversification, each sector category must have a minimum of 15% invested; apart from one sector that you choose (your discretion) to have a minimum of 25% invested, (3) The minimum investment in each asset should be 5%.Use Excel’s reports to comment on binding constraints, and the impacts of changes to the risk and category constraints on the optimum portfolio (sensitivity analysis). Further, if an asset(s) is not selected in your optimal solution, explain how much its return should be changed, so that asset can be included in your optimal selection.
. ILP model (5 marks: Mathematical Model + Excel Solver and Discussion): In this approach, we assume that a balanced portfolio of exactly 7 stocks is to  be chosen. The 4 asset categories (the S classification) must  be included. In addition, at most 1 of the assets can be in the riskiest group, and at least 2 must be in the least risky group. Finally, an asset from R3 can be selected only if at least one asset from R2 is selected.
Conclusion (4 marks: comparison + conclusion + overall presentation)Summarise your work (of all the above parts), present all your results comparatively, coherently and compellingly. Then, based on your assessment of the various approaches, briefly explain a strategy that you might prefer to use for this portfolio optimisation problem. Include a summary table detailing each chosen portfolio and the basis of choice, compare each of your chosen portfolios. You may wish to discuss any shortcomings of the utilised optimisation techniques.
Recorded 5-minute Presentation (4 marks)Your  task  is  to  create  a  concise  5-minute  recorded  presentation  about  portfolio  optimisation  strategies. You can imagine you are addressing a distinguished panel of executives at a leading investment firm. Begin by providing  a  comprehensive  overview  of  your  carefully  selected  12  investment  items,  showcasing  your  keen understanding  of the  market  landscape.  Afterward,  briefly  explain  a  preferred  portfolio  optimisation  strategy, providing  reasons  for  your  choice  and   including  a  summary  table  comparing  each  selected   portfolio.  This presentation should showcase your understanding of investment strategies and your ability to communicate them effectively. You may choose to use the same deck of slides that you and your group have put together to support your presentation, if you find this suitable and appropriate.Begin by providing an overview of your investment items and then assess the two approaches you have examined above  using  real-time  data  from  Yahoo  Finance.  Afterward,  briefly explain  a  preferred  portfolio  optimisation strategy, providing reasons for your choice and including a summary table comparing each selected portfolio. This presentation should showcase your understanding of investment strategies and your ability to communicate them effectively. You may choose to use the same deck of slides that you and your group have put together to support your presentation, if you find this suitable and appropriate.You must submit an mp4 file (or similar) for your video presentation. We recommend using Zoom (see Zoom Recording Basics) to record your video presentation, but you may use another tool of your choice and then upload the video file into Canvas in the submission tool with your presentation slides. It is a requirement to show your face/s in your presentation recording.
Marking guideAssignments will be marked based on the methodologies adopted and the quality of work. Given the vast range of assets to select from on the Yahoo website, it is highly unlikely that you will choose the same portfolio of stocks as another student group.It is important to pay special attention to spelling, grammar, and punctuation to avoid ambiguity and confusion. Students can include relevant graphs, tables, and other exhibits such as appendices. They must be clearly labelled and will not be included in the word count.
Marking Scheme for Assignment 1
Files
Marks
Prelim – 3 marks
Data acquisition, background and description
Excel  PowerPoint
2
Classifications, explanation of procedure
Excel  PowerPoint
1
Linear Programming – 9 marks
Mathematical model
PowerPoint
3
Solver, results and discussion
Excel  PowerPoint
3
Sensitivity Analysis and discussion
Excel  PowerPoint
3
Integer Linear Programming – 5 marks
Mathematical model
PowerPoint
3
Solver, results and discussion
Excel  PowerPoint
2
Overall Discussion and Conclusion – 4 marks
Comparison, conclusion, and overall presentation
PowerPoint
4
Recorded Presentation – 4 marks
MP4 file
4
TOTAL – 25 marks

25
Feedback prior to submission: Students can seek assistance from the teaching staff to ascertain whether their assignment conforms to submission guidelines through:
- Discussion board (Canvas): as other students can also benefit from your questions and replies.
- Consultation: with prior arrangement with your tutor or lecturer.
Feedback after submission: Your assignment feedback will be returned within two weeks of the due date in a rubric on the LMS site with an overall mark and intext/overall comments.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
