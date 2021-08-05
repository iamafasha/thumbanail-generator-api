# thumbanail-generator-api

python web based app for generating thumbnails.

## Usage 
 send a get e.g `http://localhost:8000?url=https://via.placeholder.com/150`
 
 
 #### results 
 
 ```
 {
    thumbnail:htpp://localhost:8000/thumbnail/url=https://via.placeholder.com/150
 }
 ```

 ## Steps 
   - get url to the file
   - system should download file
   - save it in system 
   - generate thumbnail 
   - create link to thumbnail
   - return status 

 ## Optimizations that will be required
    - check if link in available before processing
    - force regeneration by url
    -  