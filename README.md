# 🏠 Buy vs Rent Financial Simulator

An interactive financial simulator that helps evaluate whether buying a ₹2 crore property or renting a similar property and investing the available capital is the better long-term financial decision.

This project was created using a **single prompt across multiple AI platforms – ChatGPT, GitHub Copilot, and OpenCode** – to explore how different AI-assisted development tools interpret requirements and generate working applications.

## 🎯 Project Objective

Buying a house is one of the biggest financial decisions for an individual. However, comparing the monthly home loan EMI with rent alone doesn't provide the complete picture.

This simulator evaluates both scenarios by considering:
- The cost of purchasing and maintaining a property.
- Home loan repayments and interest.
- Rent escalation over time.
- Investment opportunities available to renters.
- Property appreciation and inflation.
- Taxes and transaction costs.

The objective is to compare the long-term net worth under both scenarios and identify the potential break-even point.

## 💰 Initial Financial Assumptions

| Parameter | Initial Value |
|---|---:|
| Property Price | ₹2 Crore |
| Home Loan | ₹1.5 Crore |
| Down Payment | ₹50 Lakh |
| Loan Interest Rate | 8% |
| Loan Tenure | 20 Years |
| Initial Monthly Rent | ₹50,000 |
| Property Appreciation | 5% annually |
| Rent Inflation | 5% annually |
| Investment Return | 10% annually |

All assumptions are adjustable within the simulator.

## ✨ Key Features

### 1. Buy vs Rent Comparison
- Compare buying and renting over 5, 10, 15, 20 and 30 years.
- Calculate the buyer's property equity and outstanding loan.
- Calculate the renter's accumulated investment corpus.
- Compare the final net worth of both scenarios.

### 2. Investment Strategy
The renting scenario considers investing:
- The initial down payment and associated purchase costs.
- The monthly difference between ownership expenses and rent.

Investment return assumptions can be adjusted using different investment strategies.

### 3. Adjustable Financial Parameters
- Property price and loan amount.
- Loan interest rate and tenure.
- Rent and annual rent escalation.
- Property appreciation.
- Maintenance and property taxes.
- Stamp duty and registration.
- Investment returns.
- Inflation and estimated tax impact.
- Property selling costs.

### 4. Interactive Financial Visualizations
- Net-worth comparison over time.
- Wealth composition comparison.
- Break-even year estimation.
- Year-wise financial projections.

### 5. Financial Projections
Detailed annual breakdown including:
- Annual rent.
- Annual EMI.
- Maintenance and ownership expenses.
- Interest and principal repayment.
- Property value.
- Outstanding loan.
- Investment corpus.
- Net worth under both scenarios.

### 6. Export and Reporting
- Download year-wise projections as CSV.
- Print or save the simulator as PDF.

## 🤖 AI-Assisted Development Experiment

An interesting aspect of this project was the development approach.

The same application requirements were provided through a single prompt to three different AI-assisted development platforms:

| Platform | Tool |
|---|---|
| ChatGPT | OpenAI |
| GitHub Copilot | Microsoft |
| OpenCode | Open-source AI coding agent |

**Experiment objective:**

Explore how different AI platforms translate the same natural-language requirements into an application, including their approach to:
- Requirement interpretation.
- UI and UX design.
- Financial calculation logic.
- Interactive functionality.
- Code structure and completeness.

This also demonstrates how a well-defined prompt can serve as a common starting point for comparing AI-generated solutions.

## 🛠️ Technology

- HTML5
- CSS3
- JavaScript
- HTML Canvas for charts
- AI-assisted application development

No backend, database, external framework or installation is required.

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   ```

2. Navigate to the project directory.

3. Open the HTML file in Chrome, Edge or any modern browser.

4. Adjust the financial assumptions and explore the results.

## 📊 Financial Methodology

**Buying scenario:**

Net Worth = Property Value − Outstanding Loan − Estimated Selling Costs

**Renting scenario:**

Net Worth = Investment Corpus − Estimated Investment Gains Tax

The renter's initial investment includes the capital otherwise required for the purchase, while subsequent monthly contributions reflect the difference between ownership expenses and rent.

The simulator uses simplified financial assumptions. Actual investment returns, tax liabilities, property appreciation and ownership expenses may differ.

## ⚠️ Disclaimer

This project is intended for educational and financial planning exploration only. It does not constitute investment, legal or tax advice.

Actual financial outcomes depend on market conditions, individual tax eligibility, loan terms, property location and other factors.

## 💡 Key Learning

This project was an experiment in **AI-assisted application development and prompt-driven prototyping**.

Rather than building the application entirely through manual coding, the same detailed requirement was used across multiple AI platforms to explore their capabilities and evaluate the resulting applications.

The broader takeaway: AI can accelerate application development, but financial calculations, assumptions, edge cases and generated outputs still require human validation.

---

**Built with curiosity and AI-assisted development.** 🚀
