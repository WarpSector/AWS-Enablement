# Domain 2: Security and Compliance
# (2C: AWS Cloud Management and Compliance)

## AWS Organizations
  * #### Overview
    * AWS Organizations is created with an **AWS Management** account - this account becomes the root of the hierarchy of accounts you either create or invite into the AWS Organization account you've created.
    * AWS Organizations allows you to consolidate multiple AWS accounts into **organizational units (OU)** that you create and centrally manage (re: "Production" accounts go into a "Production OU", "Development" accounts go into a "Development OU", etc.).
    * **Service Control Policies (SCPs):** are applied to OUs and can control tagging as well as available API actions.
  * #### Feature Sets
    * **Consolidated Billing:** allows you to consolidate the bills from all of the accounts into one bill and allows you to take advantage of discounts from aggregated services.
        * **Paying Account:** an independent account that exists only to pay the consolidated bill and does not have access to the root account or the OUs.
        * **Linked Accounts:** independent accounts that get linked the to Paying Account so the Paying Account is able to consolidate the bill. 
    * **All Features:** allows you to access all of the features on top of the Consolidated Billing feature available through AWS Organizations including SCPs.  

## AWS Control Tower
  * #### Overview
