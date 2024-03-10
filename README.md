<p style="text-align: center"><img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/Roger_Dubuis_Logo.jpg"></p>

<h3 style="text-align: center"> Web Scraping Project <h3>
<h4 style="text-align: center"> Scrap Data from ROGER DUBUIS Website <h3>
<hr>
<h5 style="text-align: left">Roger Dubuis is a Swiss watch manufacturer of luxury watches based in Geneva, Switzerland. The company was founded by Roger Dubuis and Carlos Dias in 1995.<br> The project aims to extract and clean data pertaining to various watches across different collections, focusing on specific fields as identified by the client.<h5>
<hr>
<hr>

- **The client identify (40 field)**

|     | field name        | note                                                                                                                                                                           |
| --- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 01  | reference_number  | Listed below product title                                                                                                                                                     |
| 02  | watch_URL         |                                                                                                                                                                                |
| 03  | type              | Blank value                                                                                                                                                                    |
| 04  | brand             | 'Roger Dubuis'                                                                                                                                                                 |
| 05  | year_introduced   | Blank value                                                                                                                                                                    |
| 06  | parent_model      | Listed below product title                                                                                                                                                     |
| 07  | specific_model    | parent model + product title                                                                                                                                                   |
| 08  | nickname          | Headline under product title (next to the reference number)                                                                                                                    |
| 09  | marketing_name    | Boxes above the product title. There might be none or multiple on a given watch. Things like boutique exclusive, # of pieces, etc.                                             |
| 10  | style             | Blank value                                                                                                                                                                    |
| 11  | currency          | USD                                                                                                                                                                            |
| 12  | price             |                                                                                                                                                                                |
| 13  | image_URL         |                                                                                                                                                                                |
| 14  | made_in           | 'Switzerland'                                                                                                                                                                  |
| 15  | case_shape        | Blank value                                                                                                                                                                    |
| 16  | case_material     | Listed under "More Details" > "Case" (the first line before the list items)                                                                                                    |
| 17  | case_finish       | Blank value                                                                                                                                                                    |
| 18  | caseback          | Listed under "More Details" > "Case" (the first line before the list items)                                                                                                    |
| 19  | diameter          | Listed under "More Details" > "Case" > the list item that starts with "Size"                                                                                                   |
| 20  | between_lugs      | Blank value                                                                                                                                                                    |
| 21  | lug_to_lug        | Blank value                                                                                                                                                                    |
| 22  | case_thickness    | Blank value                                                                                                                                                                    |
| 23  | bezel_material    | Listed under "More Details" > "Case" (the first line before the list items)                                                                                                    |
| 24  | bezel_color       | Listed under "More Details" > "Case" (the first line before the list items)                                                                                                    |
| 25  | crystal           | Listed under "More Details" > "Case" (the first line before the list items)                                                                                                    |
| 26  | water_resistance  | Listed under "More Details" > "Case" > the list item that starts with "Water Resistance:"                                                                                      |
| 27  | weight            | Blank value                                                                                                                                                                    |
| 28  | dial_color        | Listed under "More Details" > "Dial" (scrape entire field)                                                                                                                     |
| 29  | numerals          | Listed under "More Details" > "Dial" (scrape entire field)                                                                                                                     |
| 30  | bracelet_material | Listed under "More Details" > "Strap" (scrape line item that starts with "Type:" if possible)                                                                                  |
| 31  | bracelet_color    | Listed under "More Details" > "Strap" (scrape line item that starts with "Color:" if possible)                                                                                 |
| 32  | clasp_type        | Listed under "More Details" > "Clasp" first line                                                                                                                               |
| 33  | movement          | There is a section towards the bottom of the page all about the movement. This is in that section under More Details > Movement > and the line item that starts with "Energy:" |
| 34  | caliber           | There is a section towards the bottom of the page all about the movement. This is the subheading right above the heading in that section                                       |
| 35  | power_reserve     | In the Movement section. More details > Movement > the line that starts with "Power reserve:"                                                                                  |
| 36  | frequency         | In the Movement section. More details > "Technical Details" > the line that starts with "Frequency:"                                                                           |
| 37  | jewels            | In the Movement section. More details > "Technical Details" > the line that starts with "Number of rubis:"                                                                     |
| 38  | features          | Top paragraph in the Movement section                                                                                                                                          |
| 39  | description       | Main product description                                                                                                                                                       |
| 40  | short_description | Blank value                                                                                                                                                                    |

<hr> 
<hr>

- ##### I used Python in this Web Scraping Project with Libraries:
<ol>
<li> Selenium </li>
<li> Beautifulsoup </li>
<li> Pandas </li>
</ol>
