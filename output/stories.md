2\. Functional Requirements

2.1 User Management

  -----------------------------------------------------------------------
  SN                      User Stories            Acceptance Criteria
  ----------------------- ----------------------- -----------------------
  1                       As a user, I want to    AC1: Enter
                          create an account so    name/email/password\
                          that I can access       AC2: Email validation\
                          personalized features.  AC3: Success message

  2                       As a user, I want to    AC1: Valid login\
                          log in so that I can    AC2: Invalid login
                          access my account.      error\
                                                  AC3: Remember me

  3                       As a user, I want to    AC1: Reset email sent\
                          reset my password so    AC2: Secure token\
                          that I can regain       AC3: New password saved
                          access.                 

  4                       As a user, I want to    AC1: Edit name\
                          update my profile so    AC2: Edit contact info\
                          that my details stay    AC3: Save confirmation
                          current.                

  9                       As an admin, I want to  AC1: User list\
                          view user accounts so   AC2: Search users\
                          that I can manage       AC3: Status visible
                          users.                  

  10                      As a user, I want to    AC1: Session ended\
                          log out so that I can   AC2: Redirect to login\
                          securely exit my        AC3: Cannot access
                          account.                protected pages
  -----------------------------------------------------------------------

2.2 Shopping

  -----------------------------------------------------------------------
  SN                      User Stories            Acceptance Criteria
  ----------------------- ----------------------- -----------------------
  5                       As a user, I want to    AC1: Product list\
                          browse products so that AC2: Search available\
                          I can find items to     AC3: Category filter
                          buy.                    

  6                       As a user, I want to    AC1: Add item\
                          add items to cart so    AC2: Quantity update\
                          that I can purchase     AC3: Total updates
                          multiple items.         

  7                       As a user, I want to    AC1: Shipping captured\
                          checkout so that I can  AC2: Payment processed\
                          complete my purchase.   AC3: Confirmation shown

  8                       As a user, I want to    AC1: Orders listed\
                          view past orders so     AC2: Detail view\
                          that I can track        AC3: Status shown
                          purchases.              

  11                      As a user, i want to    AC1: Search by orders
                          search for past orders  listed\
                          so I can find the       AC2: Search by detail
                          purchase easily.        view\
                                                  AC3: Search by status
                                                  shown

  12                      As a user, I want to    AC1; Validation needed
                          delete items from the   
                          cart so that I can      
                          remove unnecessary      
                          items                   
  -----------------------------------------------------------------------
