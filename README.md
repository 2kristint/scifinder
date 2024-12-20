<a name="readme-top"></a>

# Scifinder

This project generates a data table of chemical compounds with key properties for each compound. The properties include:
<ul>
<li>Name
<li>2D Structural Models
<li>Molecular Weight
<li>Density
<li>Hazards Information
</ul>
The application utilizes the PubChem API to fetch compound details and images. It also includes web scraping to extract hazard information from PubChem's HTML content using BeautifulSoup.

## Built With

### Python Libraries:
<ul>
<li>PubChemPy: For searching and retrieving chemical compound data.
<li>Requests: For making HTTP requests to the PubChem API.
<li>BeautifulSoup: For parsing XML responses from the PubChem API.
<li>Pandas: For organizing and displaying tabular data.
<li>IPython.display: For rendering HTML content.
</ul>
