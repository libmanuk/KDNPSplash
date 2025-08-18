# KDNPSplash

📄 What’s Inside

Each splash page is a self-contained HTML file.

The kdnpcsv.html file loads a CSV file from a relative path and uses the csv-to-html-table JavaScript plugin to render the data as a responsive, searchable table.

Includes minimal styling for easy customization or embedding.

📁 Repository Structure

/
├── css/             
|  |── bootstrap.min.css
|  |── custom.css
|  |── dataTables.bootstrap4.min.css
├── js/
│   ├── bootstrap.bundle.min.js
|   |── csv_to_html_table.js
|   |── dataTables.bootstrap4.min.js
|   |── jquery.csv.min.js
|   |── jquery.dataTables.min.js
│   └── jquery-3.3.1.min.js
├── csv/
│   ├── kdnp_titles.csv        
|── about.html
|── contribute.html
|── kdnpcsv.html
|── resources.html
└── README.md

🔧 Dependencies

This project uses:

csv-to-html-table (loaded via CDN)
jQuery and DataTables (automatically included by the plugin)
