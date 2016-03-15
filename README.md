# JSON-To-HTML
Json data to html table data

'empdata.json
{
  "data": [
    {
      "name": "Garrett Winters",
      "designation": "Accountant",
      "salary": "$170,750",
      "joining_date": "2011/07/25",
      "office": "Tokyo",
      "extension": "8422"
    }
  ]
}'
Step 1: First you need the datatables plug-in in place to start working and datatables css, jquery and datatables js framework.
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/t/dt/dt-1.10.11/datatables.min.js"></script>
<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/t/dt/jq-2.2.0,dt-1.10.11/datatables.min.css"/>

Step 2: Having the required datatables files in place, now we have to link them to the html file. Create a file ‘index.html’ and link the datatables ‘css’ and ‘js’ files like this.

Don'f forget to include the jquery library before datatables ‘js’ file as the plug in is built over jquery.

Step 3: Finally we should populate the html table with the data from json source by mapping to the right table columns.

JSON Data Displayed in HTML Table using jQuery Datatables Plug-in.

Step 4: Excute the index.html file using localhost server to display table data. (tomcat, http server, wampserver)
