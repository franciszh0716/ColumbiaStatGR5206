# ColumbiaStatGR5206

https://dlab.berkeley.edu/news/getting-started-nyt-api

https://medium.com/@danalindquist/using-new-york-times-api-and-jq-to-collect-news-data-a5f386c7237b

For pandas:
https://pandas.pydata.org/docs/reference/io.html

Flat file

read_table(filepath_or_buffer, *[, sep, ...])
Read general delimited file into DataFrame.

read_csv(filepath_or_buffer, *[, sep, ...])
Read a comma-separated values (csv) file into DataFrame.

DataFrame.to_csv([path_or_buf, sep, na_rep, ...])
Write object to a comma-separated values (csv) file.

read_fwf(filepath_or_buffer, *[, colspecs, ...])
Read a table of fixed-width formatted lines into DataFrame.


Excel

read_excel(io[, sheet_name, header, names, ...])
Read an Excel file into a pandas DataFrame.

DataFrame.to_excel(excel_writer[, ...])
Write object to an Excel sheet.

ExcelFile(path_or_buffer[, engine, ...])
Class for parsing tabular Excel sheets into DataFrame objects.

ExcelFile.book
ExcelFile.sheet_names

ExcelFile.parse([sheet_name, header, names, ...])
Parse specified sheet(s) into a DataFrame.

Styler.to_excel(excel_writer[, sheet_name, ...])
Write Styler to an Excel sheet.

ExcelWriter(path[, engine, date_format, ...])
Class for writing DataFrame objects into excel sheets.


JSON

read_json(path_or_buf, *[, orient, typ, ...])
Convert a JSON string to pandas object.

json_normalize(data[, record_path, meta, ...])
Normalize semi-structured JSON data into a flat table.

DataFrame.to_json([path_or_buf, orient, ...])
Convert the object to a JSON string.

build_table_schema(data[, index, ...])
Create a Table schema from data.