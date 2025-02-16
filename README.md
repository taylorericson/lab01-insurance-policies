# lab01-insurance-policies
## CSC 240 - Writing Classes Lab 1

A project completed as part of the class CSC 240 at Parkland College.

Directions: 
-
Design, implement, and test three classes (Auto, Home, Life) that represent different insurance policies. A policy contains information used by an insurance company to provide financial assistance in the event of an accident. It also contains information used to compute how much money, also called a commission, an insurance agent can make when selling the insurance policy to an individual, or the insured. Each type of policy is listed below along with the formula used to compute the commission. Develop instance variables, constructors, get/set methods, a method to compute the commission, and a toString method for each class.

Auto insurance policy
-
Policy information includes:
    - name of insured
    - make and model of automobile
    - amount of liability coverage in dollars
    - amount of collision coverage in dollars
Sales commission is based on the formula:
commission = (liability + collision) * 30%

Home insurance policy
-
Policy information includes:name of insured
    -house square footage
    -amount of dwelling coverage in dollars
    -amount of contents coverage in dollars
    -amount of liability coverage in dollars
Sales commission is based on the formula:
commission = (liability * 30%) + ( (dwelling + contents) * 20% )

Life insurance policy
-
Policy information includes:
    - name of insured
    - age of insured
    - amount of term life coverage in dollars
Sales commission is based on the following formula:
commission = term life * 20%

Create a driver class, named PolicyTest, whose main method as shown below creates objects from each type of class, sets each object with sample data for the information below, and prints the commission totals based on the formulas below. You are not required to prompt a user for the information in this lab.
