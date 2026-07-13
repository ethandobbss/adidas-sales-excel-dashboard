# Duplicate MRN Analysis Project


![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

![Dashboard](assets/dashboard.png)

---
## Problem Description

Raw sales data on its own doesn't tell a clear story, it's hard to see where revenue is concentrated or how retailers and regions compare. This project turns a large volume of raw Adidas sales data into a clean, easy-to-read Excel dashboard that surfaces those trends at a glance.

## Dataset Information

The dataset was sourced from Kaggle, and can be found in data/. You can find the exact dataset I used [here](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset).

## Design Rationale



## Outcome

The final product is a presentation, which you can view [here](pptx/presentation.pdf). This analysis surfaced clear opportunities to reduce duplicate MRN creation and improve resolution efficiency:

- Internal Registration was the leading source of duplicate MRNs.
- Incorrect address entry, DOB typos, and transposed names were the top contributing factors, pointing to a need for stronger input validation at the point of registration rather than downstream cleanup.
- Duplicate events took an average of 9 days to resolve, indicating room to streamline the investigation and merge process.

Recommended next steps include:

- Tightening registration-time validation
- Prioritizing fixes for the top contributing factors
- Investing into automation software to avoid user errors
- Establishing specific, department-level resolution targets

## Future Enhancements

Here are some ideas I would explore if I kept building this project further:

- Create a darkmode variant to reduce eye strain

## Contact Information

You can contact me via email at [ethan-jacob@comcast.net](mailto:ethan-jacob@comcast.net) or connect with me on [LinkedIn](https://www.linkedin.com/in/ethan-dobbs).

Thank you for reviewing my Duplicate MRN Analysis Project! I hope this project gives useful insight into how I approach data analysis.

## License

This project is licensed under the [MIT License](LICENSE).
 
