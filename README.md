# comp228-java-midterm-solved
**TO GET THIS SOLUTION VISIT:** [COMP228 Java MidTerm Solved](https://www.ankitcodinghub.com/product/comp228-java-midterm-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;60590&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP228 Java MidTerm Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Exercise 1: [ 50 marks ]

Write a Java application that implements the following class(s) as per business requirements mentioned below:

Create an abstract Loan class (Loan.java) that has the following instance variables:

<ul>
<li>Loan number</li>
<li>customer name</li>
<li>customer date of birth (This should be represented by an object of predefined Date class in java), customer address [( create a new Address class ( Address.java ) having following instance data members: House number , Street name, City, Province, Zip code. Implement getter and setter and toString() method for Address class. )],</li>
<li>loan amount</li>
<li>rate of interest and</li>
<li>loan duration i.e. time</li>
<li>Define getter and setter along with validations for all the above instance variables.</li>
<li>Loan number should only have getter method and should be declared of the type final</li>
<li>Loan amount and interest rate cannot be negative and zero.</li>
<li>Interest rate should not be more than 5.0% in any given situation.</li>
<li>Loan class should have defined two overloaded constructors: o One for initializing all the instance data members o Second for initializing only Loan number, customer name, date of birth and address</li>
<li>Declare an abstract public method double CalculateMonthlyLoanInstallment() which is used for calculating monthly loan installment amount.</li>
<li>Define toString() to display the values</li>
</ul>
Create following two subclasses of Loan class:

a) MortgageLoan (MortgageLoan.java) b) CarLoan (CarLoan.java)

For MortgageLoan class, implement the following:

<ul>
<li>Define an instance variable – property tax for yearly property tax</li>
<li>Define another instance variable –infrastructure tax for municipal infrastructure which is a fixed monthly amount added to while calculating monthly loan installment amount</li>
<li>Define getters and setters for the above and validations. Property tax and infrastructure tax should not be negative and zero.</li>
<li>A Constructor for initializing all the instance variables</li>
<li>Overriding the method – double CalculateMonthlyLoanInstallment() which calculates monthly mortgage loan installment and to this installment amount, you need to add property tax and infrastructure tax.</li>
<li>You need to override toString() method to display the object’s data.</li>
</ul>
For CarLoan class, implement the following:

<ul>
<li>Define an instance variable – yearly car insurance amount and provide getter and setter and validation. It should not be negative and zero.</li>
<li>Constructor for initializing all the instance variables</li>
<li>Overriding the method – double CalculateMonthlyLoanInstallment() which calculates monthly car loan installment ( and to this installment amount, you need to add car insurance amount. First calculate the monthly car installment and then calculate monthly car insurance. And then add them together.)</li>
<li>You need to override toString() method to display the object’s data.</li>
</ul>
Create a driver class – LoanTest (LoanTest.java) which tests above classes by at least creating two objects each of the MortgageLoan and CarLoan classes. And you are required to process them polymorphically i.e. assigning their references to Loan superclass and then processing them normally and polymorphically.

Formula for monthly installment:

Interest = (loan amount * rate of interest* time)/100 Monthly installment = (interest + loan amount)/ (time * 12) And add any other components to the monthly installment which is asked in the requirements.
