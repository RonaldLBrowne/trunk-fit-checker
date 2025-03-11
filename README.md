# Trunk Fit Checker

A web-based tool that helps users determine if an item will fit in their car's trunk by comparing dimensions.

## Features

- **Car Selection**: Choose from popular car makes and models with pre-populated trunk dimensions
  - Toyota (Camry, Corolla, RAV4)
  - Honda (Civic, Accord, CR-V)
  - Ford (Focus, Fusion, Escape)
  - BMW (3 Series, 5 Series, X3)
  - Mercedes (C-Class, E-Class, GLC)
  - Hyundai (Elantra, Sonata, Tucson, Santa Fe)
  - Kia (Forte, K5, Sportage, Sorento)

- **Custom Dimensions**: Enter custom trunk dimensions for cars not in the database

- **Smart Comparison**: 
  - Compares item dimensions with trunk dimensions in all possible orientations
  - Provides specific feedback on why an item doesn't fit
  - Suggests optimal orientation when an item does fit

- **User-Friendly Interface**:
  - Clean, modern design
  - Responsive layout that works on all devices
  - Real-time dimension display
  - Clear success/error messages

## How to Use

1. **Select Your Car's Trunk Dimensions**:
   - Choose your car make and model from the dropdown menus, OR
   - Switch to "Custom Dimensions" tab and enter your trunk's measurements

2. **Enter Item Dimensions**:
   - Input the length, width, and height of your item in centimeters

3. **Check the Fit**:
   - Click "Check if it fits" to see the results
   - View the suggested orientation if the item fits
   - See specific feedback if the item doesn't fit

4. **Reset**:
   - Use the reset button to clear all inputs and start over

## Technologies Used

- HTML5
- CSS3 (with modern features like CSS Variables and Flexbox)
- JavaScript (Vanilla)
- Font Awesome Icons

## Development

This project is open source. Feel free to fork and enhance it. Some potential improvements could include:

- Adding more car models to the database
- Supporting different measurement units (inches, meters)
- Adding visual representation of the fit
- Including trunk shape considerations
- Adding weight limits

## License

MIT License - feel free to use this project for any purpose.
