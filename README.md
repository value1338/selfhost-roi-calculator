# Server ROI & Justification Tool
<img width="1004" height="1139" alt="grafik" src="https://github.com/user-attachments/assets/3b89b3f0-9117-4cf9-82fc-a9cc046f8f9d" />

A standalone HTML/JS calculator to help justify home server costs against streaming subscriptions. It calculates the break-even point based on hardware investment, power consumption, and monthly recurring costs vs. savings.

**Live Demo:** [http://www.mind-co.de](http://www.mind-co.de)

## Features

- **Investment Calculation:** Hardware costs, Setup fees, Drives.
- **OpEx Calculation:** Power usage (Watts/kWh price), VPS, VPN, Usenet/Indexer costs.
- **Savings:** Compare against Netflix, Disney+, etc.
- **Result:** Monthly diff and ROI time in months/years.

## Usage

1. Download `index.html`.
2. Open in any browser.
3. Done.

No build step, no npm, no backend.

## Configuration

The tool is contained entirely within a single file. To change default values (currency, electricity price, default services), simply edit the `index.html`.

Look for the JavaScript section at the bottom or the input `value` attributes in the HTML to hardcode your local defaults.

## License

MIT. Do whatever you want with it. 
