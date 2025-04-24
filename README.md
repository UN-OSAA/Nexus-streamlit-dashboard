# Nexus Dashboard

![OSAA Logo](logos/OSAA%20identifier%20color.png)

A data-driven tool for development nexus thinking, highlighting the interplay between peace, sustainable financing, and strong institutions.

## 🚀 Overview

The Nexus Dashboard delivers interactive visualizations and analytics that connect policy and real-world impact. This tool focuses on the crucial linkage between domestic resource mobilization, sustainable financing, and institutional development across four pillars:

1. 🕊️ **Pillar 1**: Durable Peace Requires Sustainable Development
2. 💰 **Pillar 2**: Sustainable Development Requires Sustainable Financing
3. 🌐 **Pillar 3**: Sustainable Financing Requires Control Over Economic and Financial Flows
4. 🏛️ **Pillar 4**: Control Over Economic and Financial Flows Requires Strong Institutions

The dashboard currently showcases Pillar 2 with a deep dive into Theme 4: Domestic Resource Mobilization (DRM) Systems.

## ✨ Features

- **Interactive Data Exploration**: Filter and explore economic and financial indicators by country and region
- **Visual Analytics**: Intuitive charts and maps for comparative analysis
- **Structured Framework**: Organized by pillars, themes, and topics for intuitive navigation
- **Country Profiles**: Detailed country-specific indicator data
- **Embedded Mind Map**: Interactive visualization of the Nexus framework

## 📋 Content Structure

The dashboard organizes content hierarchically:

- **Pillars**: High-level conceptual frameworks
- **Themes**: Major focus areas within pillars
- **Topics**: Specific subjects within each theme
- **Indicators**: Measurable metrics for assessment

### Theme 4: Domestic Resource Mobilization (DRM) System

This version focuses on four critical DRM topics:

1. **📊 Public Expenditures**: How governments allocate resources
   - Public Expenditure Efficiency
   - Expenditure Quality

2. **🧾 Budget and Tax Revenues**: How governments collect resources
   - Tax Revenue Collection
   - Tax Administration Efficiency

3. **📈 Capital Markets**: How domestic savings are mobilized
   - Market Capitalization
   - Financial Intermediation
   - Institutional Investors

4. **🚫 Illicit Financial Flows**: How resources are lost
   - Magnitude of Illicit Financial Flows
   - Types of IFFs
   - Detection and Enforcement

## 🔧 Installation & Setup

### Prerequisites

- Python 3.8 or higher
- Git

### Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/nexus-dashboard.git
cd nexus-dashboard

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

### Using Docker

```bash
# Build the Docker image
docker build -t nexus-dashboard .

# Run the container
docker run -p 8501:8501 nexus-dashboard
```

### Development with VS Code Dev Containers

This repository includes configuration for VS Code Dev Containers, allowing you to develop in a consistent environment:

1. Install the "Remote - Containers" extension in VS Code
2. Open the repository in VS Code
3. Click "Reopen in Container" when prompted
4. The container will build and start automatically

## 📂 Project Structure

```
nexus-dashboard/
├── app.py                  # Main application file
├── requirements.txt        # Project dependencies
├── style_osaa.css          # Custom styling
├── utils.py                # Utility functions
├── data/                   # Data files
├── logos/                  # Image assets
├── pages/                  # Dashboard pages
│   ├── 0_home.py           # Home page
│   ├── 1_pillar_2.py       # Pillar 2 overview
│   ├── 2_theme_4.py        # Theme 4 overview
│   ├── 3_topic_4_1.py      # Public Expenditures
│   ├── 4_topic_4_2.py      # Budget and Tax Revenues
│   ├── 5_topic_4_3.py      # Capital Markets
│   └── 6_topic_4_4.py      # Illicit Financial Flows
└── .devcontainer/          # Development container config
```

## 🧑‍💻 Development

### Adding New Pages

1. Create a new Python file in the `pages/` directory
2. Start with importing required libraries and the `render_logo_header` function
3. Add your page title and navigation links
4. Implement your content with Streamlit components
5. Update the pages list in `app.py` to include your new page

### Styling Guidelines

The dashboard uses a custom stylesheet (`style_osaa.css`) with the following color scheme:

- **Dark Blue**: `#072D92` (Primary text, headers)
- **Orange**: `#F58220` (Accent, buttons, borders)
- **Light Orange**: `#FDF4EC` (Background for panels)
- **Red**: `#EC2E07` (Hover states)

## 📊 Data Sources

The dashboard uses data from several sources including:

- World Bank PEFA Assessments
- IMF ISORA Database
- Global Financial Integrity (GFI)
- UNODC Crime Data
- World Justice Project

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📬 Contact

For questions or feedback, please reach out to [your.email@example.com](mailto:your.email@example.com).

---

*This dashboard is part of the Nexus Dashboard | MVP Version 1.0*
