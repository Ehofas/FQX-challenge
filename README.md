# FQX Technical challenge

The Business rules behind our product are quite difficult, therefore it is suggested to read through and let it sink in your head through the night or so :)

**N.B. We are looking for readable, scalable and maintainable code, one would call production-ready and we will assume the deliverable is something you would also consider production-ready. As a frontend developer, we also expect you to deliver "tasty" UX and UI.**


**The goal of the challenge:**

Create: 
1) A responsive form where you can fill up all the fields required.
2) A nice "visualization", which would give a quick glance of what user has entered (feel free to improvize)

**The business background:**

We enable a corporation to define a corporate finance eNote deal. It first inserts the financing amount (=the amount of money needed) and the payment date (=the date when the investor should pay the money). Then, in the following, the corporation defines the eNote Due Date (=the date when the corporation has to pay the money back), the difference is the maturity. Because the investor wants to make a certain profit, the eNote Face Value (=the amount of money the corporation has to pay back) must be a bit higher than the purchase price. The difference is the Agio. To help to calculate the eNote Face Value, you can insert either the Agio %, the Agio CHF or the APR % (=the annual interest rate). Then the other fields including the Face Value are automatically filled out. Of course, you can also directly insert the Face Value (then the other 3 fields are calculated).

**The form:**

**There should be 8 fields that are used for calculations:**

 • purchasePrice
 
 • paymentDate
 
 • dueDate
 
 • maturity
 
 • agioPercentage
 
 • agioValue
 
 • aprPercentage
 
 • faceValue
 
