# SublimeMSSQL

## Better MSSQL Editing features for Sublime Text

### Build System

Included is a build system that makes use of the command line tool `sqlcmd`.

This tool is installed as standard with Microsft SQL Server Client Tools. You can search for a client only version on the [Microsoft Web Site][sqlcmd].

The standard build command will execute the SQL in the editor and output the results to the SublimeText console. The default SQL Server should be defined in the environment variable `ST_DEFAULT_SQLSERVER`

There is an additional option to execute the SQL and send the output to a text file. This will out the text to `$file.out`

### Snippets

This package will also add a host of useful snippets for editing MSSQL in SublimeText. Including:

*   Select, Where, Join, Use
*   Templates for Scalar functions
*   Templates for Table functions

[sqlcmd]: http://www.microsoft.com/en-us/download/search.aspx?q=microsoft%20sql%20server%20feature%20pack