Download Link: https://assignmentchef.com/product/solved-homework-2-solution
<br>
5/5 - (3 votes)

<strong>Overview</strong>In this module/week’s homework assignment, you will complete 2 exercises that will allow you to practice your skill on the topics of GUI design and regular expressions that you learned about in the Reading &amp; Study materials for this module/week.



<strong>Instructions</strong>

Refer to the Homework Grading Rubric before you begin this assignment.Complete the detailed instructions for each exercise included in the sections below. For each exercise, begin with a new Java project.As you write your code, provide all pertinent documentation in the form of JavaDoc comments for all classes and methods.All class-level comments must include a description of the class along with your nameand links to any outside resources you used (other than the textbook) while writing your code.Each method must also have a comment that indicates the purpose of the method and, if applicable, the purpose of all parameters and return value.Additional in-line comments must be used to explain complex algorithms or unique solutions to the problem.Print, sign, and scan (or take a photo of) the final sheet of this homework assignment document as your pledge of academic integrity.After you have completed the exercises for this assignment, submit the following via the Blackboard submission link: a digital copy of your signed pledge sheet, a compressed folder containing your code, and any additional written requirements specified below. Failure to submit a signed pledge of academic integrity for this assignment will result in an automatic grade of zero (0) for this assignment.

<strong>Exercise 1</strong>

Spam (or junk e-mail) costs U.S. organizations billions of dollars a year in spam-prevention software, equipment, network resources, bandwidth, and lost productivity. In this exercise, you will be doing your part to help identify the likelihood that a given message is spam by assigning a spam score to a message entered by the user.

Create a graphical interface that looks similar to the one shown in Figure 1 below.

Figure 1. Graphical User Interface for Exercise 1

Table 1 below provides a list of 30 words or phrases that commonly occur in spam messages (this list is far from exhaustive). Write an application in which the user enters an email message into a JTextArea. When the user clicks the verify button, your application must scan the message for each of the 30 keywords or phrases. For each occurrence of one of these within the message, add a point to the message’s “spam score.”

As seen onBuyMeet singlesExtra incomeMillion dollarsSave big moneyOpportunityCashNo feesOnline degreeWork at homeAdditional incomeEliminate debtLower interest ratePre-approvedConsolidate your debtAvoid bankruptcyMiracleSatisfactionRisk freeFree hostingYou have been selectedWeekend getawayYou’re a Winner!OfferUnlimitedNo obligationTrialGuaranteeNo purchase necessaryTable 1. Commonly occurring spam words and phrases

After calculating the spam score of the message, the application will display the spam score to the user via a message box, similar to that shown in Figure 2.

Figure 2. Message box displaying the spam score

When the user clicks the Clear button, erase the contents of the JTextArea box (i.e., set the text property to an empty string).

<strong>Exercise 2</strong>

Dates are printed in several common formats. Two of the more common formats in the U.S. are:

04/25/1955 and April 25, 1955

Create the graphical interface as shown in Figure 3.

Figure 3. Graphical User Interface for Exercise 2

The user will enter a date in the first format above (04/25/1955) in the text box on the form. When the user clicks the Convert button, the application will display the date that was entered in the second format shown above (April 25, 1955) in a message box similar to Figure 4.

Figure 4. Message box showing converted date for Exercise 2

If the date was entered in an invalid format, your code must display a message box similar to that shown in Figure 5.

Figure 5. Message box showing invalid date error for Exercise 2