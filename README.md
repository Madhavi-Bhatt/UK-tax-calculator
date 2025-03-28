# UK Tax Calculator 2023/24

A modern, feature-rich UK tax calculator web application that helps users calculate their take-home pay, tax deductions, and generate professional payslips.

## Features

### Core Functionality
- **Real-time Calculations**: Automatic calculations as you type, no need for a calculate button
- **Dual Calculation Modes**:
  - Gross to Take Home: Calculate net pay from gross salary
  - Take Home to Gross: Calculate required gross salary for desired take-home pay
- **Flexible Income Input Periods**:
  - Yearly
  - Monthly
  - Weekly
  - Daily

### Tax Calculations
- Income Tax calculation based on 2023/24 tax bands
- National Insurance contributions
- Student Loan repayments (Plan 1 and Plan 2)
- Pension contributions
- Custom tax code support
- Personal allowance adjustments for high earners

### Detailed Breakdown
- **Tax Band Visualization**:
  - Personal Allowance usage
  - Basic Rate (20%) band
  - Higher Rate (40%) band
  - Additional Rate (45%) band
- **Comprehensive Results**:
  - Gross Income
  - Income Tax
  - National Insurance
  - Student Loan Repayments
  - Pension Contributions
  - Net Income

### Take Home Pay Analysis
- **Multi-period Breakdown**:
  - Yearly take-home pay
  - Monthly take-home pay
  - Weekly take-home pay
  - Daily take-home pay
- **Tax Insights**:
  - Effective tax rate
  - Marginal tax rate
  - Detailed tax band breakdown

### Professional PDF Payslip
- Generate detailed monthly payslips
- Company header and employee information
- Payments and deductions breakdown
- Year to Date (YTD) summaries
- Professional formatting with color-coding
- Payment information and timestamps

### Tax Code Calculator
- Built-in tax code calculator
- Common tax code explanations
- Interactive tax code selection
- Personal allowance calculations
- Tax-free amount display
- Emergency tax indicators

### User Interface
- **Modern Design**:
  - Clean and responsive layout
  - Bootstrap 5 styling
  - Mobile-friendly interface
- **Real-time Elements**:
  - Mini calendar display
  - Current time and date
  - Tax year information
- **Visitor Analytics**:
  - Total visitor counter
  - Calculation counter
  - Session tracking

### Sharing and Export
- PDF export functionality
- Social sharing capabilities
- Clipboard copy fallback
- Export validation checks

### Progressive Web App (PWA)
- Installable as a standalone application
- Offline functionality
- Service worker support
- Mobile-optimized experience

## Performance

This project is optimized for speed and efficiency. Key performance features include:

- **Fast Loading**: Optimized assets and critical CSS
- **Real-time Calculations**: Debounced for optimal performance
- **Efficient DOM Updates**: Minimized reflows and repaints
- **Smart Caching**: Local and session storage optimization
- **Resource Optimization**: Minified assets and lazy loading

For detailed performance metrics and optimization techniques, see [PERFORMANCE.md](PERFORMANCE.md).

## Technical Details

### Built With
- HTML5
- CSS3 (with Bootstrap 5)
- Vanilla JavaScript
- jsPDF for PDF generation
- Font Awesome icons
- Google Fonts (Inter)

### Browser Support
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

### Performance Optimizations
- Automatic calculations
- Efficient PDF generation
- Local storage for visitor tracking
- Responsive image handling
- Minified resources

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/uk-tax-calculator.git
```

2. Open `index.html` in your web browser

No additional dependencies or build steps required.

## Usage

1. Select calculation mode (Gross to Take Home or Take Home to Gross)
2. Choose your preferred input period (Yearly/Monthly/Weekly/Daily)
3. Enter your income
4. (Optional) Add your tax code
5. (Optional) Select student loan plan
6. (Optional) Enter pension contributions
7. View real-time calculations and breakdowns
8. Export payslip or share results as needed

## Contributing

We welcome contributions! Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing to the project.

### Development Guidelines
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

### Code Style
- Follow the existing code style
- Use meaningful variable names
- Add comments for complex logic
- Keep functions focused and small
- Write clean, maintainable code

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- HMRC for tax band information
- Bootstrap team for the UI framework
- jsPDF team for PDF generation capabilities
- Developed by Madhavi Bhatt

## Contact

For any questions, suggestions, or contributions, please contact:
- Developer: Madhavi Bhatt


## Keywords
UK tax calculator, take home pay calculator, salary calculator, income tax calculator, National Insurance calculator, student loan calculator, tax code calculator, UK salary calculator, gross to net calculator, net to gross calculator, 2024/25 tax calculator, UK tax bands, personal allowance calculator 
