## Intro

[TalentSee](http://www.talentsee.com) operates a universal discounting system for our customers.

This assignment is a very small task to create a Discount calculator.

For reference, Gift Aid is calculated as follows:

[NumberofCredits] * ([DiscountRate] / (100 - [DiscountRate]))

- This assignment takes an average of about 30 minutes.
- We use [NUnit](http://www.nunit.org) and [Moq](http://code.google.com/p/moq) at TalentSee, references have been added using [NuGet](http://nuget.codeplex.com/) Packages. Everything is in place for you to just write the code (no "File > New Project" required).

## Task requirements

- All stories to be completed with an appropriate level of testing.
- No actual database implementation is required, feel free to stub it out.
- Your code should trend towards being SOLID.
- Please [download]( https://github.com/IanCowley/TalentSeeTechnicalTest) the [TalentSee test repository]( https://github.com/IanCowley/TalentSeeTechnicalTest), complete the tasks as you see fit.
- Send us a Dropbox/Skydrive/whatever link to your zipped code to ian.cowley@talentsee.com but please do not send attached zip files via email!

## Task Stories

Please complete each story in order.

---

### Story 1

As a **customer**  
I want **to see my discount total calculated according to the discount rate**  
So that **I know how much I will save with my current discount rate**

#### Acceptance criteria

- Discount calculated at a discount rate of 20%.
- Supported by unit tests.

---

### Story 2

As a **site administrator**  
I want **to be able to change the applicable discount rate**  
So that **I don't need to change the code when the discount rate changes**

#### Acceptance criteria

- Current discount rate is retrieved from data store.
- Discount total amount is calculated based on the current rate in the data store.

---

### Story 3

As a **customer**  
I want **to see my discount total rounded correctly to 2 decimal places**  
So that **I'm not confused about how much will save**

#### Acceptance criteria

- Total amount correctly rounded to 2 decimal places (1.316 should round to 1.32).

---

### Story 4

As an **sales person**  
I want **to supplement the discount total based on discount types**  
So that **we will have additional discoun types available**

#### Acceptance criteria

- 5% supplement added for enterprise subscriptions.
- 3% supplement added for small to medium subscriptions.
- No supplement should be applied as standard.

---

Thanks for your time, we look forward to hearing from you!