# AutoReport: Automated Report Generation from CSV Files

AutoReport is an AI-powered tool that automatically generates a PDF report from a CSV file using the LangChain framework and OpenAI. Whether you have data but aren't sure how to summarize it, or you just need a quick analysis, AutoReport can do the job for you.

This tool can be particularly useful in industries where data is abundant but time and resources for analysis may be limited. Examples include:

- **Marketing:** Summarizing campaign performance data
- **Finance:** Rapid analysis of financial statement data
- **Healthcare:** Quick summary of patient data or research findings
- **Retail:** Summarizing sales performance or inventory data

Please note, AutoReport currently supports CSV files up to around 25MB in size.

## Setup and Running the Project

1. Clone this repository to your local machine.
2. Install the required Python libraries.
3. Open the Jupyter notebook titled `workflow`.
4. In the third cell of the notebook, replace the existing CSV file with the path to your CSV file.
5. Run the notebook. Please note that it might take up to five minutes to execute completely and may face errors.
6. The report will be outputted as `report.pdf` in the project's root directory.

## Limitations

This tool currently supports smaller CSV files (around 25MB).

## Getting Help

For suggestions, advice, contribution questions, or to reach the creator personally, please send an email to [evanfen@wharton.upenn.edu](mailto:evanfen@wharton.upenn.edu).

## Contributions

We welcome and appreciate all contributions. If you have ideas for improvements or notice any bugs, please open an issue. To contribute, please follow these steps:

1. Fork the project.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Push the changes to the branch (`git push origin feature/YourFeature`).
5. Submit a Pull Request.
