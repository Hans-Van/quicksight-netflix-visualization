# Amazon QuickSight Project: Netflix Dataset Visualization

## Project Overview
This project showcases data visualization using **Amazon QuickSight** to analyze a large Netflix dataset of shows and movies. The goal was to create interactive dashboards that reveal insights into Netflix's content library.

🚀 Explore the interactive dashboard created using Amazon QuickSight. Visualize the breakdown of Netflix content by release year, type, and genre.

📄 **Download the Dashboard PDF**:  
[Netflix Dashboard PDF](Sheet_1_2024-12-23T23_48_49.pdf)

## Key Features
- **Visualization**: Graphical breakdown of movies vs TV shows by release year.
- **Data Filtering**: Filtering content by genre and release year.
- **Dashboard Setup**: Clear and concise dashboards with labeled charts.
- **Exporting**: Ability to export dashboards as PDFs.

## Project Workflow
1. **Upload Data to S3**: 
   - Stored `manifest.json` and `netflix_titles.csv` in S3.
   - Edited the S3 URI in `manifest.json` to ensure accurate referencing.
2. **QuickSight Setup**:
   - Created a free QuickSight account.
   - Connected the S3 bucket to QuickSight via the Datasets tab.
3. **Dataset Integration**:
   - Used `manifest.json` to inform QuickSight about the dataset structure.
4. **Visualization**:
   - Dragged relevant fields into the AutoGraph space to visualize data.
   - Created graphs comparing movies vs TV shows across release years.
5. **Filtering and Refining**:
   - Applied filters to focus on specific genres and years.
6. **Dashboard Finalization**:
   - Labeled dashboard elements for clarity.
   - Exported dashboards to PDF.

## Tools & Technologies
- **Amazon QuickSight**
- **Amazon S3**
- **CSV Dataset**

## How to Run
1. Upload your dataset to an S3 bucket.
2. Edit the `manifest.json` file with the correct S3 URI.
3. Connect the S3 bucket to QuickSight.
4. Create visualizations by dragging dataset fields into the dashboard.
5. Apply necessary filters and export as needed.

## Notes
- The project took approximately **1.5 hours** to complete.
- Troubleshooting errors with manifest.json was an unexpected challenge.

## Contact
For questions or collaborations, feel free to reach out:
- **Email**    : johannes.vanderpuije@gmail.com
- **LinkedIn** : www.linkedin.com/in/johannes-vanderpuije

## Credits
This project was completed with the support of the NextWork community, a fantastic resource for hands-on learning in cloud and tech skills. Visit NextWork for more information.
**Website**: [NextWork.org](https://community.nextwork.org)
