# CWCDwebsite
Proposed CWCD website

- Process for users
    - Go to website and create a user id and password
    - Go to water office and request that access property account(s) be added to user account
        - Sign a release, acknowledging that water orders can be made with the user account
        - Manager looks to see who already has access that property account(s)
    - From the website, users can
        - See how much water they have, how much they have used
        - Edit an ongoing order
        - Make a new order
    - Once a new order is made, users receive an email confirmation

- Website form as I see it
    - Several different tabs might be available other than water orders
        - SCADA to board members
        - Work log for manager
        - Dam inspections
    - Water Order Section
        - Need https
        - mySQL for authentication
            - Good summary at https://codeshack.io/secure-login-system-php-mysql/
                - Includes password hashing, cookies    
        - Javascript (Datepicker) for selecting dates

- Database: CWCD
    - Table: accounts
        - Column: id
        - Column: user
        - Column: password
        - Column: email

    - ACCOUNTS
        


- Questions
    - Previous board member discussions 
