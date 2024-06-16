# Image Processing Microservice

### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. Run the development server with `npm run dev`

### Endpoint

GET /filteredimage?image_url={{URL}}
endpoint to filter an image from a public url.

1. validate the image_url query
2. call filterImageFromURL(image_url) to filter the image
3. send the resulting file in the response
4. deletes any files on the server on finish of the response
   QUERY PARAMATERS
   image_url: URL of a publicly accessible image
   RETURNS
   the filtered image file

### Custom Domain Name

http://imageprocessingmicroservice-dev.us-east-1.elasticbeanstalk.com/
