# Reactivation Email Campaign

## Description
NexaMobile is a telecommunications company that offers a variety of mobile plans to its customers. They aim to provide excellent service and competitive pricing to maintain customer satisfaction and loyalty. NexaMobile is looking to re-engage customers who have been inactive by offering a significant discount on mobile plan renewals.

## Scenario

NexaMobile wants to target customers who no longer have an active mobile plan with them and have been inactive for the past 6 months. They will offer a 50% discount for the first 3 renewals to encourage these customers to reactivate their plans. The email campaign will be personalized based on the last mobile plan the customer was on, utilizing a specific plan Matrix data extension that includes details of the mobile plans and special offers.

## Requirements

- Personalization: Emails must be personalized with the customer's first name and specific details about the mobile plans.
- Dynamic Content: The email should dynamically display the offers (OfferA and OfferB) based on the last mobile plan ID the customer was on.
- Data Retrieval: Use AMPscript to retrieve relevant data from the Plan
Matrix Data Extension using lookup functions.
- Discount Information: Clearly communicate the 50% discount offer for the first 3 renewals.
- Reactivation Link: The reactivation link needs to have the following parameters added: CustomerID, OfferPlanID 
(e.g. NexaMobile.com/reactivate?custID=1001&offerID=201)


## Email Template

**Subject Line:** <br>
`<FirstName>`, We Want You Back! 50% Off Just for You! 🚀

**Email Body:** <br>
Hi `<FirstName>`,

We miss you! It's been a while since you've been with us, and we have a special offer just for you. We are offering a <strong>50% discount</strong> on your first 3 renewals if you reactivate your plan with us.

Based on your last plan, here are two exciting options for you:

**Option 1:**
- **Plan Name:** `<Offer A PlanName>`
- **Data:** `<Offer A GB>` 
- **Price per Month:** `<Offer A Price at 50% Off>` for the first 3 renewal (then `<Offer A Price>` for remaining renewals)
- `<a href="<Reactivation Link>"Reactivate Offer 1</a>`

**Option 2:**
- **Plan Name:** `<Offer B PlanName>`
- **Data:** `<Offer A GB>`
- **Price per Month:** `<Offer B Price at 50% Off>`
- `<a href="<Reactivation Link>"Reactivate Offer 2</a>`

Don't miss out on this great opportunity to come back to TelcoTech and enjoy premium service at an unbeatable price. Click the link below to reactivate your plan and start saving!

Best regards, <br>
The TelcoTech Team

Click `<unsubscribe>` to opt out of all marketing communications.




