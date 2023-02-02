const divForImg = document.getElementById("img-box");

const requestOne = "https://api.unsplash.com/search/photos?page=1&query=&client_id=sppufD4HqIWk8XXQ7Q1Z83BIYPNd0lFHznE5YoNZbrg";
const requestTwo = "https://api.unsplash.com/search/photos?page=2&query=expensive-cars&client_id=sppufD4HqIWk8XXQ7Q1Z83BIYPNd0lFHznE5YoNZbrg"
function makeRequestToUnsplash(requestUrl){
  fetch(requestUrl)
    .then( res => res.json())
    .then((data) => {
    
        data.results.forEach( (imageObj) =>{
          createImage(imageObj);
        });
    });
}
// the function createImage() below is a helper function used to generate an image tag for use in our web page
function createImage(imageObj){
  const imageDiv = document.createElement("div");
  const image = document.createElement("img");
  // styling for the elements
  image.src = imageObj.urls.regular;
  image.alt = imageObj.alt_description;
  image.style.margin = "20px";
  image.style.width = "600px";
  image.style.height = "500px";
  image.style.border = "solid 4px black"
  imageDiv.append(image);
  divForImg.append(imageDiv);
}
const requestUrl =
      'https://api.unsplash.com/search/photos?query=expensive-cars&client_id=sppufD4HqIWk8XXQ7Q1Z83BIYPNd0lFHznE5YoNZbrg';
    const getImagesButton = document.querySelector('.getImagesButton');


    getImagesButton.addEventListener('click', async () => {
      let randomImage = await getNewImage();
      createImage(randomImage)
    });

    async function getNewImage() {
      let randomNumber = Math.floor(Math.random() * 10);
      return fetch(requestUrl)
        .then((response) => response.json())
        .then((data) => {
          let allImages = data.results[randomNumber];
          console.log((allImages))
          return allImages;
        });
 }
//each call to makeRequestToUnsplash() returns data with 10 images in it
//so I make two calls to it to get 20 images to populate the page with images
makeRequestToUnsplash(requestOne);
makeRequestToUnsplash(requestTwo);
