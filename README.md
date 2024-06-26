# Nashville-Housing-Data-Cleaning
Date Standardisation: The script begins by standardising the date format in the 'SaleDate' column, ensuring consistency across the dataset.

Address Population and Splitting: It then addresses missing property address data by updating null values through parcel ID matching. Subsequently, it separates the property address into individual columns for address, city, and state, as well as the owner's address, enhancing data organisation and analysis.

Categorical Data Handling: The script converts categorical values ('Y' and 'N') in the 'SoldAsVacant' field to more readable 'Yes' and 'No' respectively, improving data interpretability.

Data Quality Improvement: Utilizing common table expressions (CTEs) and the ROW_NUMBER() function, the script identifies and removes duplicate records based on selected criteria, enhancing data integrity
.
Additionally, it optimises the dataset by removing unused columns such as 'OwnerAddress', 'TaxDistrict', 'PropertyAddress', and 'SaleDate', streamlining the schema for efficient data management and analysis.
