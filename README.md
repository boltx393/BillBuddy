# Invoice Generator - React App
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

A React-based Invoice Generator that allows users to add items with configurable quantities, prices, tax rates, and discounts. Users can generate professional-looking invoices and download them as PDFs. This app utilizes [jspdf-react](https://www.npmjs.com/package/jspdf-react) to convert the invoice from a canvas format to a downloadable PDF.

### Live Demo
[Live Demo](https://invoice-generator-react.netlify.app/)

### Screenshots
<img src="https://i.imgur.com/wRetnxk.png" style="width: 100%; height: auto;">
<img src="https://i.imgur.com/AZChaei.png" style="width: 100%; height: auto;">
<img src="https://i.imgur.com/Bz3K3DE.png" style="width: 100%; height: auto;">

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/invoice-generator
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the app:
   ```bash
   npm start
   ```
4. Build the app for production:
   ```bash
   npm run build
   ```

### To-Do

- [x] Parse data into Preview Modal
- [x] Implement Currency Picker
- [x] Calculate Tax and Discounts
- [ ] Integrate Firebase DB for invoice storage
