Save Our Subscribers (SOS): Solving Customer Churn at MTN Ghana with Smart AI

Welcome to the MTN Ghana Customer Retention Project! This project uses machine learning (artificial intelligence) to help MTN Ghana figure out which customers are thinking about leaving the network before they actually switch, allowing MTN to offer them targeted rewards to stay.

1. Why This Project Matters (The Problem)

MTN Ghana is the largest mobile network in Ghana with over 31 million users. However, keeping customers happy is tough due to rising costs and inflation.

Normally, when a company starts losing customers (this is called churn), they might just drop their prices or run massive discount campaigns. But MTN Ghana can't do that:

Government Rules (SMP): MTN is classified as a "Significant Market Power" by the government. This means they are legally blocked from offering ultra-cheap rates that could run smaller competitors out of business.

Profit Margins: Giving discounts to all 31 million people would destroy MTN's revenue.

The Solution: "Precision Retention"

Instead of lowering prices for everyone, we built an AI system that looks at user data to find the exact individuals who are unhappy and likely to leave. MTN can then send surgical, customized rewards only to those specific people, keeping them happy while staying compliant with government rules.

2. Preparing the Data

To train our AI, we combined two data tables covering 100,000 customers:

Profile Data: General information about the user (e.g., how long they've been with MTN, how old their phone is).

Usage Data: Daily behavior (e.g., monthly calls, internet usage, and extra fees).

We cleaned up the data by filling in missing blanks (like empty fields for home sizes or vehicle indices) and capped extreme usage spikes so the AI wouldn't get confused by "super-users" who spend massive amounts of money.

3. What the Data Revealed (Our Key Discoveries)

By analyzing customer behavior, we found two main triggers that make people leave MTN:

Trigger 1: The "Bill Shock" Trap

The Myth: People leave because their regular monthly bill is too expensive.

The Reality: Regular monthly bills for loyal customers and leaving customers look exactly the same! Instead, people leave because of surprise extra charges (overages). When their monthly minutes run out and they get hit with unexpected fees, they experience "bill shock" and abandon their SIM card.

Trigger 2: The Old Phone Window

The Discovery: A customer's risk of leaving spikes dramatically once their phone is older than 365 days (1 year).

Why? Competitors know when your phone is getting old. They aggressively target you with shiny new phone upgrades and easy monthly payment plans. If MTN doesn't offer a phone upgrade first, the customer leaves.

4. How the AI Performed

We trained a machine learning model called a Random Forest Classifier on our clean data.

The Results:

Recall: 65.20% (Our Hero Metric)

This means our AI successfully catches nearly 2 out of 3 customers who are planning to leave, weeks before they actually do.

Why we focus on Recall:

If the AI makes a mistake and guesses someone is leaving when they aren't (a false alarm), it only costs MTN a cheap SMS coupon to say "We appreciate you." But if the AI misses someone who is actually leaving (a missed alarm), MTN loses that customer's business forever. Thus, catching as many leaving customers as possible is the most profitable choice.

5. The Action Plan (How MTN Saves Money)

Using the AI's predictions, MTN Ghana can launch three automated programs:

The Handset Upgrade Alert: The moment a customer's phone hits day 360, MTN automatically texts them a loyalty discount to upgrade their device using MTN's "Pick and Pay Later" financing.

Proactive Plan Resizing: If the AI notices a customer is dropping their talk time and hitting high overage fees, MTN proactively offers to upgrade them to a larger, cheaper bundle to prevent "bill shock."

MoMo Loyalty Cashbacks: Keep customers engaged with the network by sending targeted cashbacks directly to their Mobile Money (MoMo) wallets.
