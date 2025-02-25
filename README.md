# AI Deal Finder

AI Deal Finder is a project aimed at helping users find the best deals on various products by analyzing offers and providing recommendations. This tool uses an ensemble of agents and advanced algorithms to track, compare, and alert users about discounts on products from various online sources.

## Project Overview

The project consists of several Python scripts and modules that work together to provide a comprehensive deal-finding experience. These modules include agents for tracking prices, performing discount analysis, and handling specific tasks like warm-ups, messaging, planning, and scanning.

### Key Features:
- **Price Tracking:** Monitor the prices of products across different platforms.
- **Discount Calculation:** Estimate discounts and compare prices to find the best deals.
- **Multiple Agents:** Use different agents (e.g., `RandomForestAgent`, `SpecialistAgent`, etc.) to handle different aspects of the deal-finding process.
- **Web Scraping:** Fetch product details, prices, and availability from external websites.
- **Data Analysis:** Analyze the data to estimate deal values and determine the best offers.

## Installation

To use the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/igopalakrishna/AI_Deal_Finder.git
   cd AI_Deal_Finder

    Install the required dependencies:

    pip install -r requirements.txt

    Set up environment variables (if needed), especially for external APIs or services.

Usage

To use the tool, run the main script:

python app.py

The app will begin monitoring deals and provide alerts based on your preferences.
Project Structure

The project is organized as follows:

AI_Deal_Finder/
├── agents/
│   ├── app.py
│   ├── deal_agent_framework.py
│   ├── hello.py
│   ├── items.py
│   ├── keep_warm.py
│   ├── llama.py
│   ├── log_utils.py
│   ├── memory.json
│   ├── price_is_right.py
│   ├── pricer_ephemeral.py
│   ├── pricer_service.py
│   ├── pricer_service2.py
│   ├── testing.py
├── README.md
└── requirements.txt
<img width="284" alt="image" src="https://github.com/user-attachments/assets/dff01a6d-1465-4760-ae6a-ef5db472d277" />


Important Files:

    app.py: The main entry point for the application.
    deal_agent_framework.py: The framework for managing different deal agents.
    memory.json: Stores information about product deals, including prices, descriptions, and discounts.
    pricing_agents/: Contains various agents that handle pricing and deal evaluation.

This project is licensed under the MIT License.
