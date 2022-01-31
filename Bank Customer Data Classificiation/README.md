<h1> Bank Customer Data Classification </h1>

<h2> OVERVIEW </h2>
Using data science in the banking industry has become a necessity to keep up with the competition. Banks collect, analyze, and store massive amounts of customer data. 
Machine learning and data science tools can harness this data to learn more about their clients behavior. Propensity modelling uses this large amount of data to make customer behavior predictions and retarget customers. Predictive analystics driven by such machine learning models can be used to determine which customers are more likely to avail a service such as buying a personal loan. This helps banks engage iwth customers through personalized customer interactions in relevant context.
<br><br> The key to success in marketing is to make a customized offer that suits the particular client’s needs and preferences. Data scientists utilize the behavioral, demographic, and historical purchase data to build a model that predicts the probability of a customer’s response to a promotion or an offer. Therefore, banks can make an efficient, personalized outreach that suits the particular customer's needs and preferences and improve their relationships with customers.
<br><br>
<h2> ABOUT THE DATA: </h2>
The data in context is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget. The dataset contained in the file Bank.xls contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign. The dtaa file attributes are:
<ol>
  <li> ID : Customer ID </li>
  <li> Age : Customer's age in completed years </li>
  <li> Experience : #years of professional experience </li>
  <li> Income : Annual income of the customer </li>
  <li> ZIP Code : Home Address ZIP code.  </li>
  <li> Family : Family size of the customer </li>
  <li> CCAvg : Avg. spending on credit cards per month </li>
  <li> Education Level.
    <ol> <li> 1. Undergrad </li> 
      <li> 2. Graduate </li> 
      <li> 3. Advanced/Professional </li>
    </ol>  
  <li> Mortgage : Value of house mortgage if any. ($000) </li>
  <li> Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited </li>
  <li> Personal Loan : Did this customer accept the personal loan offered in the last campaign? </li>
  <li> Securities Account : Does the customer have a securities account with the bank? </li>
  <li> CD Account : Does the customer have a certificate of deposit (CD) account with the bank? </li>
  <li> Online : Does the customer use internet banking facilities? </li>
  <li> Credit card : Does the customer use a credit card issued by UniversalBank? </li>
</ol>
<h2> OBJECTIVE </h2>
The classification goal is to predict the likelihood of a liability customer buying personal loans by conducting:
<ol> 
  <li> Exploratory Data Analysis </li>
  <li> Preparing the data to train a model </li>
  <li> Training and making predictions using a classification model </li>
  <li> Model evaluation </li>
</ol>
