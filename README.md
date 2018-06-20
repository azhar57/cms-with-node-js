# CMS With Node Js
Content Management System with node js, ejs template &amp; MSSQL database and IIS Web Server
Run this script before running this project. This will create a Session and save into the database
CREATE TABLE [dbo].[sessions](
    [sid] [varchar](255) NOT NULL PRIMARY KEY,
    [session] [varchar](max) NOT NULL,
    [expires] [datetime] NOT NULL
)

