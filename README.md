# TCAD

### a. Purpose
a simple application with REACT, pulled the data from axios API, look at the adding part in App.js (componentDidMount() function)
 
### b. passowrd
securing the key or password of the app can be done with appbase.io, auth0, or firebase.
 
### c. SQL

SELECT a.prop_id, a.address, a.getdate()
FROM table a
LEFT OUTER JOIN table b
ON a.prop_id= b.prop_id 
AND a.address = b.address
WHERE b.prop_id IS NULL
ORDER BY a.getdate() desc;
