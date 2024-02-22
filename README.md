<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo" width="80" height="80">
  <p>
    Empower your sales process with automated PDF generation for your sales documents.
    <br />
    <a href="https://empress.eco/">Visit Our Website</a>
    ·
    <a href="https://grow.empress.eco/">Documentation</a>
    ·
    <a href="https://github.com/empress-eco/pdf_on_submit/issues">Report a Bug</a>
    ·
    <a href="https://github.com/empress-eco/pdf_on_submit/issues">Request a Feature</a>
  </p>
</div>

## About The Project

### 📖 Overview
Empress PDF on Submit is an efficiency-boosting tool that automatically generates and attaches a PDF to your sales documents upon submission. It's ideal for professionals handling Quotations, Sales Orders, Sales Invoices, Delivery Notes, and Dunning operations.

### 🌟 Key Features
- Instant PDF generation upon sales document submission.
- Option for background PDF generation for large volume of documents.
- Customizable active doctypes.
- Selection of Default Print Format and Print Language.

## Getting Started

### Technical Stack and Setup Instructions

The project is built with Empress, a full-stack web application framework based on Python and JavaScript. 

**Installation Process:**

**For Empress Cloud Users:**
1. Navigate to your Empress Cloud dashboard and click the "New Site" button.
2. In Step 2 ("Select apps to install"), choose "PDF on Submit".
3. Complete the new site wizard.

**For Self-Hosted Users:**
Execute the following commands in your terminal:
```sh
cd Empress-bench
bench get-app https://github.com/empress-eco/pdf_on_submit.git
bench --site YOUR_SITE_NAME install-app pdf_on_submit
```
> Note: Replace `YOUR_SITE_NAME` with your actual site name.

### Usage
To customize the settings, search for **PDF on Submit Settings** in the search bar. Here, you can select the DocTypes for which this app is active and enable background PDF creation for instant workflow continuation.

To modify the Default Print Format:
1. Open the list view of a supported DocType.
2. Navigate to Menu > Customize.
3. In the "View Settings" section, select a Default Print Format.

The language of the created PDF is determined by the "Language" field of the current document.

## Contributing
We welcome your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

Please ensure your contributions align with the project's design principles and standards. For more details, refer to our [Contribution Guide](https://github.com/empress-eco/pdf_on_submit).

## License and Acknowledgements

### License
This project is under the MIT License. All your contributions are also licensed under the MIT License. For more details, see [License](https://opensource.org/licenses/MIT).

### Acknowledgements
We extend our heartfelt gratitude to the Empress Community, the architects behind the essential tools that power this project. Their innovation and unwavering dedication have been instrumental in building the foundational elements and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.