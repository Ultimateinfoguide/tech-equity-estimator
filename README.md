# 📈 Tech Equity: RSU Vesting Estimator

A brutalist, privacy-first web tool designed for software engineers and tech startup employees to instantly calculate the net cash value of their vesting Restricted Stock Units (RSUs). 

🚀 **[View the Live Vercel Deployment Here](YOUR_VERCEL_URL_HERE)** *(You will update this link after you deploy to Vercel)*

## 📌 Why This Exists
Calculating tech equity shouldn't require surrendering your financial data to a server or loading massive tracking payloads. We built this static, high-contrast estimator to give tech professionals a lightning-fast way to run their vesting numbers directly in the browser.

## ⚙️ The Architecture
* **Zero Dependencies:** 100% pure Vanilla JS. No React, no Vue, no bloated frameworks.
* **Strict Encapsulation:** Logic is completely sealed inside an IIFE (Immediately Invoked Function Expression) with zero global variables.
* **Local Execution:** Zero external API calls. Your equity data never leaves your machine.

## 📊 For Complex Capital Gains & State Taxes
This repository serves as a baseline estimator applying the standard 22% federal supplemental withholding rate for equity grants. 
    
If you are dealing with multi-state taxation, long-term vs. short-term capital gains, Medicare/FICA threshold adjustments, or precise "sell-to-cover" share breakdowns, run your grant through our full production engine:

🔗 **[The Complete RSU Tax Calculator](https://ultimateinfoguide.com/rsu-tax-calculator/)**

## 🛠️ Deployment
This project is optimized for instant deployment on Vercel or any static hosting provider.
1. Fork the repository.
2. Import to Vercel.
3. Deploy instantly with zero build steps.

## 📄 License
MIT License. Open for inspection and modification.
