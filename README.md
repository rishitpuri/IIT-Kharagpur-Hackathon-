# IIT-Kharagpur-Hackathon-
Any drug in the US market is prescribed by the HCPs (Health Care Practitioners) to patients thereby making HCPs as the
actual customer of a pharmaceutical company. Companies promote the drug to HCPs through multiple promotional
channels:

    Sales Rep Calls: A sales representative visits the HCP, in-person, and details about the drug, its usage, efficacy,
    benefits etc.
    Sample Drops: Free drug samples are shared with the HCP who can then prescribe those drugs to the patients,
    and check their benefits and effects
    Emails: Details of the drug usage, efficacy, safety procedure, side effects etc are shared with the HCPs through
    email campaigns to enable them to know more about the drug
    Speaker Programs: Pharmaceutical companies organize events and awareness programs related to the drug and
    disease area. HCPs are invited to be speakers in such events, thereby initiating a soft promotion for the brand
    drug
    Vouchers Dropped: Coupons and vouchers are shared with the HCPs which they can share subsequently with their
    patients along with prescriptions. The vouchers can provide a discount on drug purchases thereby ensuring
    popularity with the patients

Pharmaceutical companies therefore want to engage each HCP with the best possible promotional channel and maximize
their brand prescriptions (Brand Rx). The brand drug in question is a skin disease drug in the US market, launched in 2018
and is one of the prominent drugs in the skin disease market.

#ASK

Based on the datasets shared, project background and promotional constraints, the ask is to identify the best promotional
channel for every HCP for the upcoming week. The best channel should be identified among three channels – sales rep
calls, emails, and sample drops. The best channel should meet the promotional constraints shared and should maximize the
brand TRx for the upcoming week for that HCP. The frequency of promotion of the channel should not be considered while
identifying the best promotional channel.

#EXPECTED SOLUTION

The model solution should predict the best possible channel for the HCP for the upcoming week (first week of Feb’20)
among three promotional channels – Sales Rep calls, Emails, and Sample Drops by utilizing Brand Rx (prescriptions) as the
maximization criteria.
The candidates must ensure that model predictions are fed through the promotional constraints shared and that the final
channel recommendations meet both the criteria – Brand Rx maximization and promotional constraints.
