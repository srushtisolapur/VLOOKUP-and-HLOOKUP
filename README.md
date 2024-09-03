# Excel Data Analysis - VLOOKUP and HLOOKUP Example

This project demonstrates how to use Excel's VLOOKUP and HLOOKUP functions through a sample dataset containing student names and their marks in various subjects. The project illustrates the application of these functions to retrieve specific data points from a table.

## Project Structure

1. **Dataset**
   - The dataset consists of student names and their marks in subjects such as Kannada, English, Hindi, Maths, and Science.
   - The sheet also includes a section dedicated to demonstrating the VLOOKUP function.

2. **Key Operations**
   - **VLOOKUP**: The project uses the VLOOKUP function to retrieve specific student marks based on the student name.
   - **HLOOKUP**: Although not explicitly shown in the data preview, HLOOKUP could similarly be used to fetch data based on the column headers.

## Example Data

| Name    | Kannada | English | Hindi | Maths | Science |
|---------|---------|---------|-------|-------|---------|
| Srushti | 87      | 56      | 89    | 67    | 78      |
| Sheetal | 98      | 67      | 80    | 78    | 64      |
| Manjula | 78      | 59      | 78    | 59    | 50      |

## VLOOKUP Example

The VLOOKUP function is used in this project to find a student's marks in a specific subject. For example, to find "Srushti's" marks in "Kannada", you would use:

```excel
=VLOOKUP("Srushti", A2:F4, 2, FALSE)
```

## Conclusion

This README provides an overview of the purpose and functionality of the Excel sheet, with a focus on explaining the VLOOKUP function. You can use or adapt this for your GitHub repository. &#8203;:contentReference[oaicite:0]{index=0}&#8203;
