# css-flag

# CSS Flag Project - Flag of Laos Recreation

Welcome to the **CSS Flag Project**! In this project, I successfully recreated the flag of Laos using only internal CSS, without altering any of the existing HTML code. This challenge required the utilization of various CSS properties, such as positioning and combinators like child and descendant, to achieve the desired flag design.

## Project Overview

- **Title**: CSS Flag Project
- **Objective**: Recreate the flag of Laos using internal CSS without altering the HTML code.

### HTML Structure

The project consists of a basic HTML structure that represents the flag elements:

- **`.flag` Class**: This class represents the outer container of the flag.

  - **`.flag > div`**: A child selector used to target the blue rectangle within the flag.

    - **`.flag > div > div`**: A descendant selector that selects the white circle within the blue rectangle.

- **`<p>` Element**: Text elements within the flag for the flag title and the country name ("The Flag of Laos").

### CSS Styling

- **Red Rectangle (`.flag`)**: A red rectangle is created using the `.flag` class, with specified dimensions and background color.

- **Blue Rectangle (`.flag > div`)**: A blue rectangle is positioned absolutely within the red rectangle, achieving the flag's design.

- **White Circle (`.flag > div > div`)**: A white circle is created using the `.flag > div > div` child combinator. It is positioned inside the blue rectangle, achieving the central element of the flag.

- **Text Styling**: The text elements within the flag are styled using CSS properties like font size, color, and text alignment to match the original flag design.

- **Descendant Combinator**: A descendant combinator is used to target the text inside the white circle, adjusting its color to black.

## Usage

Feel free to view the HTML file to see the recreated flag of Laos. This project serves as an example of how CSS can be creatively used to recreate complex designs, such as national flags, by leveraging positioning properties and CSS specificity.

Enjoy looking at the CSS recreation of the flag of Laos!