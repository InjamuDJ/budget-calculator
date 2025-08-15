# budget-calculator
Performance Incentive Budget Calculator

This repository contains a simple, secure, and easy-to-use web-based calculator for managing a performance incentive budget. The tool helps you automatically redistribute funds among different categories based on which ones have a winner, removing the need for any manual math.

# How It Works
The calculator is a single HTML file that uses JavaScript to perform all the calculations in real-time. It's designed to be a static website, which means it doesn't require a back-end server or a database. This makes it very lightweight and fast.

The core logic follows the redistribution formula you provided:

When a category is marked as a winner (by checking its box), the tool identifies all winning categories.

It calculates the "Remaining Total %" by summing the original percentage allocations of only the winning categories.

It then recalculates each winner's share by dividing their original percentage by the "Remaining Total %" and multiplying the result by the total budget.

The amounts are instantly updated in the table, and the total at the bottom is recalculated.

# Key Features
No Manual Math: Automatically calculates budget amounts as soon as you select a winner.

Simple and Intuitive: A clean, user-friendly interface with checkboxes.
