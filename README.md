# RV Solar Panel Calculator Plugin

## Description
The RV Solar Panel Calculator is a WordPress plugin designed to help RV owners estimate the number of solar panels, battery capacity, and MPPT charge controller size needed based on their daily energy usage. This tool provides an easy-to-use form where users can input their energy requirements and get a quick estimate to assist in planning their solar setup.

## Features
- **Daily Energy Usage Input:** Users can input the total energy their RV consumes in a day.
- **Solar Panel Wattage Input:** Users can input the wattage rating of their solar panels.
- **Sunlight Hours Input:** Users can input the average number of sunlight hours their location receives per day.
- **Panel Voltage Input:** Users can input the actual operating voltage of their solar panels.
- **Calculation Results:** Provides an estimate of the number of solar panels needed, the required battery capacity, and the MPPT charge controller size.

## How to Use
1. **Daily Energy Usage (in watt-hours):** Enter the total energy your RV consumes in a day. For example, if your RV uses 2000 watt-hours per day, enter "2000".
2. **Solar Panel Wattage (in watts):** Enter the wattage rating of the solar panels you plan to use. For instance, if you have 200-watt panels, enter "200".
3. **Average Sunlight Hours per Day:** Enter the average number of sunlight hours your location receives per day. This can vary depending on your geographic location. A common estimate is between 4 and 5 hours, so you can start with that.
4. **Panel Voltage (actual):** Enter the actual operating voltage of the panels you are looking to get. For instance, nominal 12V panels typically output around 18V under optimal conditions. If you are unsure, a good average to use is 18V for 12V panels.

Once you have entered these values, click "Calculate" to see the estimated number of solar panels, battery capacity, and MPPT charge controller size needed for your setup.

## Installation
1. Download the plugin files and upload them to your WordPress site under the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.

## Shortcode
Use the following shortcode to embed the calculator on any post or page:

```html
[rv_solar_calculator]
