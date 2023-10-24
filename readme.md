# Teacher Salary Benchmarks

### "Teacher Salary Benchmarks" (A map that displays base teacher salaries across the United States)

---

This web map displays teachers' starting rates without and with a masters degree. The data was obtained from the National Education Association [https://www.nea.org/resource-library/teacher-salary-benchmarks] and placed in a CSV file which also contained state names and latitude/longitudes that were assigned to each state. Next, using the open source tool [geojson.io](http://geojson.io) the CSV file was converted to a geoJSON file which contained the names of states, the starting salary without a masters degree, and the starting salary with a masters degree; it was then loaded into VSCode as a javascript file. Using [Leaflet](https://leafletjs.com/) JavaScript library, the geoJSON features were displayed through a circleMarker function where the radiuses of the circles were determined by a getRadius function. 