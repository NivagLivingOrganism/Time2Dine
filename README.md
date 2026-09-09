# Time2Dine
A web application that connects diners with restaurants offering discounts during off-peak hours.

Built for **Melbourne Hackathon 2026**.

## Installation

1. have uv preinstalled by running the following in powershell: 

'''
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
'''

2. git clone this repo 
3. cd to the time2dine directory in the terminal 
4. run the website with the following command

'''
uv run reflex run 
'''

The application will then be available locally through the Reflex development server.


## Overview

Restaurants often have unused tables during quieter periods, while diners are looking for better-value dining experiences.

This platform allows:

* Diners to discover discounted restaurant offers
* Restaurants to create and manage off-peak discounts
* Administrators to review and manage restaurants
* Diners to claim offers and complete transactions
* Diners to earn loyalty points

The platform follows the core user journey defined by the hackathon challenge.

## Tech Stack

* **Python** — Application logic
* **Reflex** — Web application framework
* **Database** — [Add database here]
* **Payment** — Simulated/mock payment
* **Git/GitHub** — Version control

## Features

### Diner

* Sign up and sign in
* Phone-number and verification-code style login
* Browse restaurants
* View restaurant details
* View available discounts
* Claim discounts
* Complete a simulated payment
* View loyalty points
* Redeem loyalty points

### Restaurant

* Register as a restaurant partner
* Manage restaurant information
* Create off-peak offers
* Set offer availability
* Manage active offers
* View claimed offers
* View restaurant activity

### Administrator

* Review restaurant applications
* Approve or reject restaurants
* View participating restaurants
* Manage restaurant information
* View platform activity

## Business Model

The platform takes a **2% commission** from each transaction.

Payments are simulated for the hackathon rather than using real money.

## Loyalty Program

Diners earn:

```text
$1 spent = 1 loyalty point
```

Points can be redeemed at:

```text
500 points = $10 platform credit
```

## Hackathon Scope

This project is a functional prototype developed for **Melbourne Hackathon 2026**.

The hackathon permits the use of Python and a range of frontend/backend frameworks, databases, APIs and development tools.

The prototype focuses on demonstrating a complete user journey rather than implementing every possible feature.

## Future Improvements

Potential future features include:

* AI-powered restaurant recommendations
* Location-based discovery
* Maps
* QR-code offer redemption
* Restaurant analytics
* Personalised offers
* Demand forecasting
* Fraud detection
* Smart loyalty rewards

These are examples of optional features suggested by the hackathon brief.

## Team

Built by **[Team Name]** for Melbourne Hackathon 2026.

---

**Status:** 🚧 In Development
