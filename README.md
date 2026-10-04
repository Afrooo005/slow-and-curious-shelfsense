# ShelfSense — Slow and Curious

A student grocery inventory demonstration, built with HTML, CSS and JavaScript.

Open index.html or serve this directory with any static web server. GitHub Pages can publish directly from main / root.

Features: landing page, local inventory CRUD, expiry review, reorder CSV, five supported inventory question types, synthetic dataset and answer exports. Edits stay in local browser storage. No accounts, email collection, payments or supplier orders.

Sample reference date: 26 September 2026. The synthetic dataset differs from earlier ShelfSense submissions; update numerical screenshots and examples accordingly.

Question routing uses multinomial Naive Bayes with 35 training phrases. Forecasting compares ordinary least-squares trend against a recent seven-day mean on a selection holdout. This is not an independent accuracy estimate.

Design reference: https://www.figma.com/design/kTBMfijZqGjV10D6lQP1h4/Selfsensess
