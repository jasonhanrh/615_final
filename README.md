# Aruba Explorer: An Interactive Socio-Economic Dashboard

![Language](https://img.shields.io/badge/Language-R-blue.svg)
![Framework](https://img.shields.io/badge/Framework-Shiny-brightgreen.svg)

*An interactive web application built with R Shiny that provides a comprehensive overview of Aruba's geography, economy, and demographics through dynamic visualizations and data-driven analysis. This project was developed by Ruihang Han.*

---

## 🚀 Live Demo

**You can access the deployed Shiny application here:**

[**https://honb94-ruihang-han.shinyapps.io/Aruba_Ruihang_Han/**](https://honb94-ruihang-han.shinyapps.io/Aruba_Ruihang_Han/)

*(强烈建议您将屏幕录像转换为GIF，并放在此处以获得最佳展示效果)*
*[INSERT A GIF DEMO OF YOUR SHINY APP HERE]*

## 🎯 Project Goal & Purpose (The "Problem")

Information about a country's socio-economic status is often scattered across static reports and disparate databases. This project's goal was to solve this problem by creating a single, centralized, and interactive platform—the **Aruba Explorer**—where users (such as researchers, students, or prospective tourists) can explore, visualize, and understand Aruba's key development trends in an engaging and intuitive way.

## ✨ Key Features (The "Action")

The Aruba Explorer is a full-featured dashboard that provides multiple layers of analysis:

* **📈 Interactive Time-Series Analysis:** Users can dynamically visualize key economic indicators (GDP, Inflation) and demographic trends (Population, Life Expectancy) over a 30-year period. The interface includes interactive controls like sliders to filter by year range and checkboxes to toggle data series.

* **🗺️ Geospatial Mapping:** The app features interactive maps built with **Leaflet**, allowing users to explore Aruba's key cities and geography with both standard and satellite views.

* **🆚 Comparative Analysis:** To provide regional context, the dashboard includes a dedicated section for comparing Aruba's performance on key metrics (GDP Per Capita, Population, Life Expectancy) against its Caribbean peers, the Bahamas and Barbados.

* **📊 Strategic SWOT Analysis:** The application synthesizes the quantitative data into a qualitative **SWOT (Strengths, Weaknesses, Opportunities, Threats)** analysis, translating raw numbers into actionable strategic insights.

* **📚 Rich Content Integration:** Beyond the data, the app provides rich, well-researched textual and visual content on Aruba's history, culture, and traditions to give users a complete picture.

## 🛠️ Technical Details

* **Data Source:** The application fetches live, up-to-date socio-economic data directly from the **World Bank Open Data API** using the `wbstats` R package.
* **Core Framework:** The entire application is built in **R** using the **Shiny** framework.
* **Key Libraries:**
    * `shiny` & `shinydashboard`: For the core application structure and UI.
    * `leaflet`: For interactive maps.
    * `ggplot2`: For creating dynamic and static plots.
    * `dplyr` & `tidyr`: For data manipulation and wrangling.
    * `wbstats`: For programmatic data acquisition from the World Bank.
    * `shinythemes`: For professional UI styling.

## 🚀 Getting Started

You can run this application on your local machine by following the steps below, or you can directly access the **[live version online](https://honb94-ruihang-han.shinyapps.io/Aruba_Ruihang_Han/)**.

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    ```
2.  **Open in RStudio:**
    Open the `app.R` file in RStudio.
3.  **Install Packages:**
    Run the following command in the R console to install all the necessary packages:
    ```r
    install.packages(c("shiny", "leaflet", "ggplot2", "shinydashboard", "shinythemes", "wbstats", "dplyr", "tidyr", "base64enc", "png", "magick"))
    ```
4.  **Run the App:**
    Click the "Run App" button in the top-right corner of the RStudio script editor, or run the following command in the console:
    ```r
    shiny::runApp('app.R')
    ```

---

This project demonstrates an end-to-end capability in creating data products—from programmatic data acquisition and analysis to building a polished, interactive, and user-friendly web dashboard.
