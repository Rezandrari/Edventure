Built for GarudaHacks 6.0. in 2025 by a team of four, consisting of Rezandra Rizky Irianto (me), M. Satria.R.P., Valerie V. Wilson, and Khalisa Zahra.

How to deploy manually:
1. Clone the repo
2. Open terminal or VSCode and go to the Edventure directory
3. Run npm install
4. Install playwright browser by running npx playwright install --with-deps chromium 
5. Copy .env.example into .env and replace all the values inside with your own values
6. To run development: run npm run dev
7. To run production: run npm run build followed with npm run start
8. Now you can access the WebApp through browser
9. You will be required to login before accessing the app
10. Now you need to insert your personal data/CV to giving the AI more context about you
11. After finishing and being redirected to the home page, you can now swipe the card. Left to discard and right to save
12. Now you can use the app freely

How to re-crawl data:
Make request into http://3000/api/spider/revalidate with POST. It Will crawl source automatically and insert into Qdrant
