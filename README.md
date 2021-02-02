# Plotly Dashboard - Belly Button Biodiversity

Built a full stack interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/) from Public Science Lab.

**Technologies used:**

` Plotly.js | D3.js | Javascript | Python | SQLAlchemy | Flask | HTML and CSS `

**Deployment:**

The dashboard Flask app was deployed using `Heroku.`

Visit [Biodiversity Dashboard](https://belly-button-dashboard-sheetal.herokuapp.com) Project.

### Plotly.js

Used Plotly.js to build interactive charts the dashboard. Following were the different plotly charts:

* PIE chart that uses data from the samples route (`/samples/<sample>`) to display the top 10 samples.
* Bubble Chart that uses data from the samples route (`/samples/<sample>`) to display each sample.
* Gauge Chart to plot the Weekly Washing Frequency obtained from the route `/wfreq/<sample>`


![Example Dashboard Page](static/Images/dashboard_part1.png)
![Example Dashboard Page](static/Images/dashboard_part2.png)







