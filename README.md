# CPAP Analyzer

A web-based application for analyzing CPAP therapy data, currently optimized for Philips DreamStation 2 devices. Upload your CPAP data files and gain insights into your sleep therapy patterns, compliance, and treatment effectiveness.

## Features

- **File Upload Support**: Easy drag-and-drop or click-to-upload interface for CPAP data files
- **Philips DreamStation 2 Compatibility**: Optimized parsing and analysis for DreamStation 2 data formats
- **Data Visualization**: Interactive charts and graphs showing sleep therapy metrics
- **Treatment Analysis**: Detailed breakdown of therapy sessions, AHI trends, and compliance tracking
- **Export Functionality**: Generate reports and export analyzed data
- **Privacy-Focused**: All data processing happens locally in your browser

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- CPAP data files from your Philips DreamStation 2 device

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cpap-analyzer.git
cd cpap-analyzer
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

### Using the Application

1. **Upload Data**: Click the upload area or drag and drop your CPAP data files
2. **Review Data**: The app will automatically parse and display your therapy information
3. **Analyze Trends**: Use the interactive charts to explore your sleep therapy patterns
4. **Generate Reports**: Export summaries and detailed reports of your therapy data

## Supported File Formats

Currently supports data files from:
- Philips DreamStation 2 (.csv, .txt formats)

*Additional device support planned for future releases*

## Data Privacy

Your CPAP data is processed entirely within your browser. No data is transmitted to external servers, ensuring complete privacy and security of your sensitive health information.

## Development

### Project Structure

```
cpap-analyzer/
├── src/
│   ├── components/         # React components
│   ├── utils/             # Data parsing and analysis utilities
│   ├── styles/            # CSS and styling files
│   └── types/             # TypeScript type definitions
├── public/                # Static assets
├── tests/                 # Test files
└── docs/                  # Documentation
```

### Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Running Tests

```bash
npm test
```

### Building for Production

```bash
npm run build
```

## Roadmap

- [ ] Support for additional CPAP device manufacturers (ResMed, Fisher & Paykel)
- [ ] Advanced analytics and trend prediction
- [ ] Data comparison tools for tracking therapy adjustments
- [ ] Mobile-responsive design improvements
- [ ] Offline functionality with Progressive Web App features
- [ ] Integration with health tracking platforms

## FAQ

**Q: Is my CPAP data secure?**
A: Yes, all data processing happens locally in your browser. Your files are never uploaded to any server.

**Q: What CPAP devices are supported?**
A: Currently optimized for Philips DreamStation 2. Support for other devices is planned.

**Q: Can I use this on mobile devices?**
A: The app works on mobile browsers, though the desktop experience is currently more optimized.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the CPAP community for feedback and testing
- Inspired by the need for better patient access to therapy data analysis
- Built with modern web technologies for optimal performance

## Support

If you encounter issues or have questions:
- Open an issue on GitHub
- Check the [documentation](docs/) for detailed guides
- Review existing issues for common solutions

---

**Disclaimer**: This tool is for informational purposes only and should not replace professional medical advice. Always consult with your sleep specialist or healthcare provider regarding your CPAP therapy.
