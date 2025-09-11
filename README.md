# TickerPickr
A full stack web app for stock picking

[Lauren Thorve](https://github.com/laurenst17)

[Apoorv Belgundi](https://github.com/apoorvib)

[Varun Pandian](https://github.com/V-run64)

## What and Why?

We plan to build a stock picker application that helps beginner investors evaluate companies without needing advanced financial knowledge. Users can login to the app and through our system filter publicly traded stocks by industry and and interact with an adjustable sliding scales for quantitative metrics (such as P/E ratio, EPS growth, debt-to-equity, etc).

This gives users a straightforward way to explore how different financial factors affect stock choices. It also makes investing more approachable and educational for people who want to learn the basics of fundamental analysis.


As an optional feature, we may include a chatbot that explains in plain English what each metric measures, what is an ideal range, whether a higher/lower number for that metric is better, etc. This will enhance user understanding but is not required for the system to work.

## For Whom?

The application is designed for beginner investors who are interested in building wealth but don't know where to start! 


## How?

From a user’s perspective:

They log into the app and see a list of companies 

They select an industry (such as tech, healthcare, energy, etc) to narrow the list.

They adjust sliders for metrics like P/E ratio, EPS growth, debt-to-equity, etc to define their desired ranges.

The system filters the stock list and displays results that meet the criteria.

Clicking a stock brings up details, including a chart of recent performance and a short description of its fundamentals.

Users can save filters for reuse and add stocks to a personal watchlist.

(Optional) Users are notified (by email) and in there notifications (under profile) a week before, and the day of there saved stock has an earnings call.

(Optional) Users can chat with a bot to ask, “What does EPS mean?” or "Is a higher PE ratio better" and receive clear, beginner-friendly explanations.



## Scope

This project is appropriately scoped for a team of 3-4 developers:
The team will need to:

- Design and build a database to store user accounts, stock fundamentals, saved filters, saved stocks.

- Develop a backend API to fetch fundamentals, run stock queries

- Implement filtering logic so users can narrow stocks by industry and adjust sliders for quantitative metrics 

- Create an interactive front end UI 

- Integrate an external data source to populate stock data.

- The optional email notification system so users can receive alerts when a stock on their watchlist has an earnings call.

- The optional chatbot—designed to explain financial metrics in plain English—will be implemented only if time permits.
