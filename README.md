# 💼 Salary Slip Generator

A modern, responsive web application for generating professional salary slips with PDF export functionality. Built with vanilla HTML, CSS, and JavaScript featuring a beautiful glassmorphism design and real-time calculations.

![Salary Slip Generator](https://img.shields.io/badge/Status-Live-brightgreen) ![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

## 🌟 Features

- **Professional Design**: Modern UI with gradient backgrounds and glassmorphism effects
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile devices
- **Real-time Calculations**: Automatic calculation of totals as you type
- **PDF Generation**: High-quality PDF export with professional formatting
- **Pre-filled Templates**: Default company information for quick setup
- **Comprehensive Fields**: Support for all standard salary components

## 🚀 Live Demo

Visit the live application: [Salary Slip Generator](https://ajeetkumarrauniyar.github.io/salary-slip-generator/)

## 📋 Salary Components

### Earnings
- Basic Salary
- House Rent Allowance (HRA)
- Conveyance Allowance
- Medical Allowance
- Other Allowances

### Deductions
- Provident Fund (PF)
- Professional Tax
- Tax Deducted at Source (TDS)
- Other Deductions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and form structure
- **CSS3**: Modern styling with flexbox/grid, gradients, and animations
- **JavaScript**: Form handling, calculations, and PDF generation
- **jsPDF**: PDF generation library
- **jsPDF AutoTable**: Enhanced table formatting for PDFs

## 🏃‍♂️ Getting Started

### Option 1: Direct Download
1. Download the `index.html` file from the repository
2. Open it in any modern web browser
3. Start generating salary slips immediately

### Option 2: Clone Repository
```bash
git clone https://github.com/ajeetkumarrauniyar/salary-slip-generator.git
cd salary-slip-generator
```

### Option 3: GitHub Pages Deployment
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Your app will be available at `https://yourusername.github.io/salary-slip-generator`

## 📱 Usage

1. **Company Information**: Enter or modify company details (pre-filled with default values)
2. **Employee Information**: Fill in employee details including name, ID, designation, etc.
3. **Salary Period**: Select the month, year, and working days
4. **Salary Components**: Enter earnings and deductions (calculations update in real-time)
5. **Generate PDF**: Click the "Generate Salary Slip PDF" button to download

## 🎨 Features Overview

### Real-time Calculations
The application automatically calculates:
- Total Earnings
- Total Deductions  
- Net Salary

### Professional PDF Output
Generated PDFs include:
- Company letterhead
- Employee information
- Detailed salary breakdown
- Professional formatting
- Computer-generated disclaimer

### Responsive Design
- **Desktop**: Full-width layout with side-by-side forms
- **Tablet**: Adjusted spacing and font sizes
- **Mobile**: Stacked layout for optimal mobile experience

## 🔧 Customization

### Company Information
Update the default company information in the HTML:
```html
<input type="text" id="companyName" required value="IT MAVERICK SOLUTIONS" />
<input type="text" id="proprietorName" required value="Ajeet Kumar" />
<textarea id="companyAddress" rows="3" required>AT-PIPRA, PO-DAMODARPUR, EAST CHAMPARAN, BIHAR -845416</textarea>
```

### Styling
Modify the CSS variables for easy theme customization:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --background-color: #f8f9fa;
  --text-color: #333;
}
```

## 📦 Dependencies

The application uses CDN-hosted libraries:
- jsPDF v2.5.1
- jsPDF AutoTable v3.5.31

No local installation required - everything loads from CDN.

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 File Structure

```
salary-slip-generator/
├── index.html          # Main application file (renamed from salary.html)
├── README.md           # This file
└── assets/             # Optional: for additional resources
    ├── screenshots/    # Application screenshots
    └── docs/          # Additional documentation
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🐛 Known Issues

- PDF generation requires modern browser support for jsPDF
- Very long company addresses may need manual formatting
- Mobile browsers may have slight PDF rendering variations

## 📈 Future Enhancements

- [ ] Multiple currency support
- [ ] Salary slip templates
- [ ] Bulk generation for multiple employees
- [ ] Email integration
- [ ] Employee database storage
- [ ] Print-friendly version

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/ajeetkumarrauniyar/salary-slip-generator/issues) page
2. Create a new issue with detailed description
3. Include browser information and steps to reproduce

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- jsPDF library for PDF generation capabilities
- Modern CSS techniques for responsive design
- Community feedback for feature improvements

---

**Made with ❤️ for simplified salary slip generation**

> **Note**: This tool is for generating salary slips for legitimate business purposes. Ensure compliance with local labor laws and tax regulations.
