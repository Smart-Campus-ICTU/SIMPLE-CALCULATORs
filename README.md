# Simple Interest Calculator 
  
 A professional, lightweight tool designed to calculate the interest on a loan or investment based on the principal amount, the annual interest rate, and the time period.
  
 ## Project Overview 
 This project provides a simple yet effective interface for financial calculations. Unlike compound interest, which calculates interest on interest, this tool uses the **Simple Interest** method—ideal for short-term loans and basic savings accounts. 
  
 ### Objective 
  To help users understand their financial growth over time. 
  To provide a clean, error-resistant command-line interface. 
  To demonstrate basic mathematical implementation in a programming environment. 
  
 ## The Mathematics 
 The calculator is built upon the standard financial formula for Simple Interest: 
  
 ### 1. The Interest Formula 
 The total interest ($I$) is calculated by multiplying the principal, the rate, and the time: 
 $$I = P \times r \times t$$ 
  
 ### 2. The Total Amount Formula 
 To find the final balance ($A$), we add the interest back to the principal: 
 $$A = P + I$$ 
 Or, simplified:
 $$A = P(1 + rt)$$ 
  
 **Variables Explained:** 
    $P$: Principal Amount (The initial sum of money) 
 $r$: Annual Interest Rate (converted to a decimal, e.g., 5% = 0.05) 
 $t$: Time Period (Total number of years) 
 ## Key Features 
User-Friendly Inputs: Accepts Principal, Rate, and Time in natural units. 
Accurate Calculations: Uses floating-point precision for financial accuracy. 
Validation: Built-in checks to ensure no negative values are processed. 
Clear Outputs: Displays both the interest earned and the final total balance. 
   
 ## Getting Started 
  
 ### Prerequisites 
 You will need a terminal (Command Prompt, PowerShell, or Terminal) and a code runner (like Python, Node.js, or a C++ compiler) depending on the script you choose to include. 
  
 ### Installation & Setup 
 1.  Clone the Repository:
     ```bash 
     git clone https://github.com/Nkinyampraises/simple-interest-calculator.git  
     ``` 
 2.  Navigate to the Directory:
     ```bash 
     cd simple-interest-calculator 
     ``` 
 3.  Run the Script: 
     (Example for Python)
     ```bash 
     python calculator.py 
     ``` 
 ##  Example Calculation 
 Scenario: An investment of $5,000 at a 4.5% interest rate for 2 years. 
  Principal: $5,000 
  Rate: 4.5% 
 Time: 2 Years 
  
 Result:
 Interest Earned:$450.00 
 Final Balance: $5,450.00 

 ##  Contributing 
 Contributions are what make the open-source community such an amazing place to learn, inspire, and create. 
 1. Fork the Project. 
 2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`). 
 3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`). 
 4. Push to the Branch (`git push origin feature/AmazingFeature`). 
 5. Open a Pull Request. 
  
 ##  License 
 Distributed under the MIT License. See `LICENSE` for more information. 
 Author:NKINYAM PRAISES NCHA  
 Project Link:https://github.com/Nkinyampraises/simple-interest-calculator.git  
Fixing a typo
