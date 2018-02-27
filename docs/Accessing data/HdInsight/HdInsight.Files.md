﻿# HdInsight.Files
Returns a table containing the properties and contents of the blobs found in the specified container from an Azure storage vault.
***
function (account as text, containerName as text) as table
***
# Descrition 
Returns a table containing a row for each blob file found at the container URL, <code>account</code>, from an Azure storage vault. Each row contains properties of the file and a link to its content.
# Category 
Accessing data
