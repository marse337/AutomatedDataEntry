# AutomatedDataEntry
Using OpenRPA and Google sheets to complete a challenge
Sure, here is a description summary with an overview of the steps:

**Automating Data Entry with AutoHotKey and Google Chrome**

This video demonstrates how to automate data entry between a website and a Google Sheet using AutoHotKey and Google Chrome. The automation retrieves PO numbers from a website, navigates to a different tab to gather order details, and then enters the order information into a Google Sheet.

**Key Steps:**

1. **Activate Chrome:** The automation begins by activating a Chrome window.

2. **Identify the Correct Chrome Tab:** AutoHotKey is used to locate the specific Chrome tab containing the PO numbers.

3. **Determine Number of PO Numbers:** JavaScript is injected into the Chrome console to count the number of PO numbers present.

4. **Iterate Through PO Numbers:** A while loop iterates through each PO number, automating the data entry process for each.

5. **Retrieve PO Number:** The current PO number is extracted from the website using an XPath selector.

6. **Navigate to Order Lookup Tab:** AutoHotKey switches to the order lookup tab.

7. **Enter PO Number and Retrieve Order Details:** The PO number is entered into the order lookup tab, and the order date, order total, and order state are extracted.

8. **Navigate to Google Sheet:** AutoHotKey switches to the Google Sheet tab.

9. **Apply Filter:** AutoHotKey navigates to the filter option and applies the filter based on the extracted order state.

10. **Enter Order Details into Google Sheet:** The extracted order details are entered into the corresponding Google Sheet fields.

11. **Navigate Back to First Tab:** AutoHotKey switches back to the first tab to continue processing the next PO number.

12. **Fill Out Information:** Using XPath selectors, the automation fills out the ship date, order total, and assigned agent fields for the current PO number.

13. **Repeat Until Complete:** The while loop continues until all PO numbers have been processed and the data entry is complete.

**Conclusion:**

This automation demonstrates how AutoHotKey and Google Chrome can be effectively combined to automate data entry tasks, saving time and effort.
