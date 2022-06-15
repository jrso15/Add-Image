## Add Image

A basic React App that can Add Image and randomly remove image.
It has two section when displaying the images: `Carousel` and `Simple listing`.

### Running the local environment ###

There are two ways of running the local environment: natively via Local or via Docker

To run the project on your localhost:
  1. Clone the repository and run `git clone https://github.com/jrso15/Add-Image.git`
  2. Go to the project `cd Add-Image`
  3. Get the required node modules by installing `npm i` or `npm install`
  4. Run `npm start` to run the project.
  5. Confirm everything is set up properly by opening [http://localhost:3000](http://localhost:3000) in your browser.

### Via Docker ###

  1. Build our image using this command: `docker build -t emapta-exam:latest`
  2. To run the docker container in your terminal: `docker run --name exam -d -p 3000:3000 emapta-exam:latest`
  3. To confirm it's working open up `localhost:3000` again without running npm start.

### npm run build ###

Builds the app for production to the `build` folder.

## Deployed via Netlify

To access the link: 
`https://janille-olegario-add-image.netlify.app/`
