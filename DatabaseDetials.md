This file contains MySQL Database detials for the Meeting Room Pro (MR Pro) application project.

Database - navsingh_MRPro

MySQL Database User Name -  navsingh_MRProAdmin and password - QWERTY123q 
(All privileges)

*****

Inserting Geo-spatial Polygon into the MySQL Database

INSERT INTO `Buildings` (`Name`, `Shape`) VALUES ('Apt 15', PolyFromText('POLYGON((50.866753 5.686455, 50.859819 5.708942, 50.851475 5.722675, 50.841611 5.720615, 50.834023 5.708427, 50.840744 5.689373, 50.858735 5.673923, 50.866753 5.686455))'));

Reference: https://gis.stackexchange.com/questions/23900/how-to-add-polygon-in-mysql-database
