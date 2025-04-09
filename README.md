# Request URL Parser

This tool allows you to parse and compare request URLs, extracting their parameters and displaying them in a tabular format.

## Features

- Parse a single URL to extract its parameters.
- Compare two URLs to highlight differences in their parameters.
- Copy the parsed or compared data to the clipboard.
- Clear all input fields and reset the interface.

## How to Use

### Parsing a Single URL

1. Enter a valid request URL in the "Enter your Request URL" input field.
2. Click the **Parse URL** button.
3. The parsed URL and its parameters will be displayed in a table.

### Comparing Two URLs

1. Click the **Add to Compare URL** button. This will reveal a second input field.
2. Enter the first URL in the "Enter your Request URL" field.
3. Enter the second URL in the "Paste second URL to compare..." field.
4. Click the **Compare URLs** button.
5. The comparison results will be displayed in a table, highlighting differences between the two URLs.

### Copying Data

- After parsing or comparing, click the **Copy Parsed Data** button to copy the table data to the clipboard.

### Clearing Fields

- Click the **Clear** button to reset all input fields and hide the results table.

## Example URLs

- Single URL: `https://example.com?param1=value1&param2=value2`
- Comparison: Compare two URLs with similar or different parameters to see the differences highlighted.

## Notes

- Nested parameters (e.g., `key=value1&key2=value2`) are supported and displayed in a structured format.
- Invalid URLs will prompt an alert asking for valid input.

## License

This project is licensed under the MIT License.
