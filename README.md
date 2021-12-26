# OpenBusinessMap

OpenBusinessMap will be a free and open source business directory, based on the OpenStreetMap project.
It combines data from the OpenStreetMap project, as well as additional information about businesses.

    Open Business Map - OpenStreetMap-based business directory
    Copyright (C) 2019-2021  Bandira Addis Map Entertainment PLC, Addis Ababa

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.  

## User Stories

* As a business owner I want to present my information on a website

* As a business owner I want to control the information shown in the business directory and website

* As a user and business owner I am interested in accurate data in OpenStreetMap.

## Data

### OpenStreetMap

* Name (in all available languages)
* Location data
* Opening Times

### OpenBusinessMap

* All the additional data, see components below

## Componets (draft)

### OBM-directory

* Link to OSM Point (Special negative ids, containing non public items, are supported)
* Services offered
* Products offered
* Makes offered
* Pictures
* Videos (mostly as YouTube / Vimeo etc. links) ?
* Menu cards (pictures as well as structured, text based information)
* Micropage content, multilinguage
* Mapillary Links
* Editing of all data, push data to the OpenStreetMap servers which belongs there (with or without further review)

### OBM-integrity
* Caching latest OpenStreetMap data
* ability to LOCK to reviewed data version of the OSM data
* Send out notifications in case of changes for approval

### OBM-website

* Website displaying this information
* Proper SEO for the business pages
* Support subdomain, path (or own domain??)
* Proper Rich Snippetes

### OBM-wp

* Wordpress Widget showing the OpenStreetMap based information, encouraging editing the data in OSM, instead of the page itself, Kick-start pagegenerator -> From Micropage to WordPress website
