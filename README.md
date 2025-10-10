# CSV Content Visualizer

A modern, web-based tool for visualizing CSV files with an intuitive table interface. Say goodbye to messy text editors and Excel's "Get Data" complications - just upload and view your CSV data instantly!

## ✨ Features

### 📊 **Smart CSV Parsing**
- **Auto-delimiter detection** - Automatically detects commas, semicolons, tabs, or pipes
- **Manual delimiter selection** - Override auto-detection when needed
- **Quoted field handling** - Properly processes CSV fields with quotes and special characters
- **Empty row filtering** - Automatically skips blank rows

### 🎯 **Intuitive Table Display**
- **Organized columns** - Clean, professional table layout
- **Sticky headers** - Column headers remain visible while scrolling
- **Row numbers** - Easy reference with numbered rows
- **Responsive design** - Works perfectly on desktop and mobile
- **Hover effects** - Enhanced readability with row highlighting

### 📈 **Data Insights**
- **Real-time statistics** - Total rows, columns, and non-empty row counts
- **Delimiter detection display** - Shows which delimiter was detected/used
- **File information** - Name, size, and type details

### 🔍 **Powerful Search & Filter**
- **Global search** - Search across all columns simultaneously
- **Instant filtering** - Results update in real-time as you type
- **Case-insensitive** - Find data regardless of capitalization
- **Highlight matches** - Visual feedback for search results

### 💾 **Export Functionality**
- **Download filtered data** - Export search results as new CSV
- **Preserve formatting** - Maintains original structure and delimiter
- **One-click download** - Simple, fast export process

### 🎨 **Modern User Experience**
- **Clean interface** - Professional design with green accent theme
- **Fast loading** - No server required, works entirely in browser
- **Drag & drop** - Easy file upload interface
- **Error handling** - Clear error messages for problematic files

## 🌐 Live Demo

**[Try it now!](https://romeroarcasandres.github.io/CSV-Content-Visualizer/csv-visualizer.html)**

## 💻 Getting Started

### Option 1: Use Online (Recommended)
1. Visit the [live demo](https://romeroarcasandres.github.io/CSV-Content-Visualizer/csv-visualizer.html)
2. Click "Choose CSV File" or drag & drop your file
3. Your data appears instantly in a clean table format!

### Option 2: Download and Run Locally
```bash
# Download the HTML file
wget https://raw.githubusercontent.com/yourusername/csv-visualizer/main/index.html

# Open in any modern browser
open index.html
```

### Option 3: Clone Repository
```bash
git clone https://github.com/yourusername/csv-visualizer.git
cd csv-visualizer
# Open index.html in your browser
```

## 📱 Browser Compatibility
- ✅ **Chrome 60+** - Full support
- ✅ **Firefox 55+** - Full support  
- ✅ **Safari 12+** - Full support
- ✅ **Edge 79+** - Full support
- ✅ **Mobile browsers** - iOS Safari, Chrome Mobile

## 🛠️ Technical Details
- **Pure HTML/CSS/JavaScript** - No frameworks, no dependencies
- **Client-side processing** - All parsing happens in your browser
- **Secure** - Your data never leaves your device
- **Lightweight** - Single file, fast loading
- **Standards compliant** - Follows RFC 4180 CSV specification

### Supported CSV Features
- [x] **RFC 4180 compliant parsing**
- [x] **Multiple delimiter support** (comma, semicolon, tab, pipe)
- [x] **Quoted field handling** with embedded delimiters
- [x] **Empty field processing**
- [x] **Large file support** (tested up to 10MB+)
- [x] **Unicode/UTF-8 support**
- [ ] **Multi-line fields** (planned)
- [ ] **Custom quote characters** (planned)

## 📄 License
This project is licensed under the Attribution-NonCommercial 4.0 International License - see the [LICENSE](LICENSE) file for details.



**Made with ❤️ for the data community**

*Stop struggling with messy CSV files - start visualizing!*
