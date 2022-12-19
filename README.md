# Team-Fete-des-Vignerons

## Introduction

This project is a part of the assignment of the module Digitalization of Business Processes in Master of Science in Medical Informatics and in Business Information Systems. Students have to digitalise a pro-cess and deliver modelling artefacts as Business Process Model and Notation and Decision Model and Notation with the appropriate source file and code. Furthermore, students provide documentation of the complete process and the link to the workflows and instantiations. 

## Scenario
Cats have been human companions for millennia, and their fanbase seems to be ever and ever rising, with an estimated 1.8 million living in Swiss households in 2022 (https://de.statista.com/statistik/daten/studie/283732/umfrage/katzen-in-der-schweiz/). 

In this scenario, one cat named “Cat” plays a leading role with his owner Simon. Most of the time, Cat eats, lie around, and explores different environments and areas. Sometimes, Cat can be challenging. Especially, if Simon forgets to feed him. In those cases, Cat tries to get back at his owner. Peculiarly, the cat tries to wake up him in different ways to get fed. Therefore, Cat walks around meowing. Cat intentionally broke a vase, so the loud smashing sound would wake Simon up, but it was not successful. Moreover, Cat climbs onto the cupboard to try to jump on Simon’s face. But suddenly the cupboard falls on Simon and hurts him. This resulted in several injuries on Simon's face, broken bones, lengthy treatment, and a long stay in the hospital. Finally, Simon receives the medical bill of 1 Mio. CHF which he passes to his Health Insurance. 

The Health Insurance “Medical Health Insurance” shortened MHI is in doubt about the invoice. In gen-eral, more and more people try to get refunds for all kinds of expenses even if they are not a customer of MHI. Furthermore, even the hospitals use incorrect ICD-Codes to get treatment and hospital stays reimbursed which does not rely on the main cause of the admission to the hospital. Therefore, MHI agents check all medical bills in detail by their hands and disputed the invoice by different Medical Codes (e.g., ICD) which were not suitable for that case in relation to the doctor’s documentation. MHI work along with CHECKMEDICAL from Bern for further assistance. They are focused on checking medi-cal bills based on their long-term medical experience and support MHI in clearing their fraudulent medi-cal bills. 

All previous points were painstaking and the agent of MHI needs a lot of time for it. Therefore, the el-derly CEO of MHI decided to give digitalization a try, and asked FHNW students to set up the following processes:

 - Through an online form, the customer should be able to send in the medical bill with their details 
 - The system checks automatically if the customer is one of the existing clientele. 
 - Non-registered customers should be contacted and will be handled as potential customers for the future. 
 - The system runs through the details of the customer and checks the insurance policy and the duration of the contract. 
 - The system goes through the ICD on the medical bill and verifies if the case can be referenced to the case of Simon. 
 - The system will send a mail to CHECKMEDICAL company for detailed clearance if the ICD does not rely to the case of Simon.
 - Medical bill with incorrect ICD will be rejected and the customer and hospital will be informed. 
 - The refund amount will be calculated if the medical bill reference to correct ICD and to an existing customer. 
 - The refund amount will be calculated according to insurance policy type and duration of the contract with MHI.
 - As a final part, the customer will be informed about the payment, the case will be registered in MHI-Database and the financial department will be informed to release the payment. 

# High Level Process
<img width="726" alt="Screenshot 2022-11-07 at 20 37 15" src="https://user-images.githubusercontent.com/106623917/200399156-4833248c-4116-4848-ace1-f14bcfff3c54.png">

# Assumptions

# Features

# Methodologies
The project team activated a Trello board to support agile implementation of the project. Initial brainstorming was done using design thinking techniques and literature search supported by external outreach.

## Organisational

It is hosted on Github. Contributions are made via branches. Local commits are pushed regularly. Pull requests (especially into main) have to be approved by a second person, who after approval also merges the branch.
Features and Requirements are tracked as Issues on Github.
Branch names follow the pattern: `<Issue Number>/<Title/Description of ticket in noun form with hyphens>`
Merge request names follow the pattern: `<Requirement- or Issue ID>: <Title/Description of ticket in noun form>`
Examples: Branch `2/Addition-of-Code-Styles-to-Readme` will result in the PR: `2: Addition of Code Styles to Readme`
Commits always have a commit message in the form of an action.
Example: Commit `Add commit style to Readme-file` into branch `2/Addition-of-Code-Styles-to-Readme`.

## Members
 - Lukasz Kaczmarek
 - Banujan Ragunathan
 - Andreas Hetschel
 - Grégory Witmer

## References
1. https://whatfix.com/blog/insurance-client-onboarding
Use digital applications and tools to manage the onboarding process digital applications and tools to manage the onboarding process
Provide clarity on their new insurance coverage and plan
Create a personalized experience
Provide documentation and tutorials on any client self-service online portals
Have an omnichannel communication strategy
Show your policyholders you understand their concerns and needs
Reach out on a consistent, regular basis

2. https://blog.agencyzoom.com/the-ultimate-3-step-onboarding-process-for-insurance-clients
Day 1: Welcome Packet
Day 14: The “Welcome Call”
Last step: the pre-renewal call

3. https://www.doxee.com/blog/customer-experience/easy-onboarding-process-insurance/
the first stages of the buyer’s journey are crucial
21% of insured persons have changed insurance providers in the last two years, especially in the automotive sector. The most important point to note here: just over half of them made this decision when it was time to renew their policy.
focus on onboarding actions to strengthen the relationship with current customers, holding them by the hand in both the initial phase and during all subsequent phases of the relationship.
manage customer experience while also maintaining security and compliance
an easy onboarding process must facilitate the insured’s experience in fully understanding (in a way that is intuitive) the content of the policy.
digital channels (email, website, social media) which make it easier and faster for customers to read and understand policy, and minimizes the risk of customer churn.

4. https://www.amsive.com/2022/09/26/digital-is-reshaping-the-customer-onboarding-process-in-insurance/
Target to communicate
Think omnichannel
Push products, services, and people
Future cross sell


