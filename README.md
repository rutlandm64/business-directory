# Business Directory

## Overview
This project is a comprehensive business directory that allows users to easily find information about various businesses in their area.

## Directory Structure
```
/business-directory
│
├── src
│   ├── index.js         # Main entry point of the application
│   ├── components        # React components
│   └── styles           # CSS stylesheets
│
├── data
│   └── businesses.json   # JSON file containing business data
│
├── public
│   └── index.html       # Main HTML file
│
└── README.md            # Project documentation
```

## Data Format
Businesses are stored in a JSON format within the `businesses.json` file. Each business entry contains the following fields:
- `id`: Unique identifier for the business
- `name`: Name of the business
- `address`: Physical address of the business
- `contact`: Contact information (phone/email)
- `category`: Business category/type

Example:
```json
{
  "id": "1",
  "name": "Example Business",
  "address": "123 Example St, Example City, EX 12345",
  "contact": {
    "phone": "123-456-7890",
    "email": "info@example.com"
  },
  "category": "Example Category"
}
```

## Contribution Guidelines
We welcome contributions to this project! To contribute:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## How to Add/Update Businesses
To add or update businesses:
1. Open the `data/businesses.json` file.
2. To add a new business, insert a new object following the existing format.
3. To update an existing business, find the object by its unique `id` and modify the fields as needed.
4. Save the file, then commit your changes and push them using the steps outlined in the contribution guidelines.