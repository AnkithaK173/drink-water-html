# drink-water-html

This project is a simple, static web page for tracking daily water intake visually. The goal is to promote hydration by providing a visual layout of glasses, each representing 250 ml of water. Users can refer to this layout to track their intake mentally.

**Project Files**

1. index.html: Defines the structure and content of the page.
   
2. style.css: Adds styling to create an appealing visual design.
   
**Features**
Water Intake Goal Display: Shows a daily target of 2 liters of water.

Remained and Percentage Display: Provides a static indicator of the total goal (2 Liters) and the initial state (0%).

Static Cup Layout: Each cup represents 250 ml, encouraging users to keep track visually without clicking.

**Code Overview**

**HTML Structure (index.html)**

The main <div class="cup"> serves as a placeholder for the remained amount and percentage.

The <div class="cups"> contains eight smaller cups (<div class="cup cup-small">) representing each 250 ml portion.

**CSS Styling (style.css)**

Global Styles: Sets a blue background, white text, and center-aligned layout.

Main Cup (.cup): Styled with a white background and blue border for a visually pleasing center display.

Small Cups (.cup-small): Each small cup is styled with rounded corners, blue background, and white text to simulate the look of individual glasses of water.

**Future Enhancements**

To make this tracker interactive, JavaScript could be added. Each click on a cup could update the remained amount and percentage.
