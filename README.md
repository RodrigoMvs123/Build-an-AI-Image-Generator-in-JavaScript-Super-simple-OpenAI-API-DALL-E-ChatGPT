# Build-an-AI-Image-Generator-in-JavaScript-Super-simple-OpenAI-API-DALL-E-ChatGPT

Build an AI Image Generator in JavaScript! (Super simple!) | OpenAI API DALL-E ChatGPT


https://www.youtube.com/watch?v=l3TLQuwr4G0


index.html
<!DOCTYPE html>
<html lang=”en”>
<head>
          <meta charset=”UTF-8”>
          <meta http-equiv=”X-UA-Compatible” content=”IE=edge”>
          <meta name=”viewport” content=”width=device-width, initial-scale=1.0”>
          <title>AI Image Generator</title>
<link rel=”stylesheet” href=”styles.css”/>

</head>
<body>
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" id="visual" viewBox="0 0 900 600" version="1.1"><rect x="0" y="0" width="100vw" height="100vw" fill="#001220"/><path d="M0 394L21.5 390.3C43 386.7 86 379.3 128.8 384C171.7 388.7 214.3 405.3 257.2 414.7C300 424 343 426 385.8 423.8C428.7 421.7 471.3 415.3 514.2 412.3C557 409.3 600 409.7 642.8 413.3C685.7 417 728.3 424 771.2 417.3C814 410.7 857 390.3 878.5 380.2L900 370L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#fa7268"/><path d="M0 430L21.5 436.8C43 443.7 86 457.3 128.8 462.5C171.7 467.7 214.3 464.3 257.2 463C300 461.7 343 462.3 385.8 463.2C428.7 464 471.3 465 514.2 459.8C557 454.7 600 443.3 642.8 438.7C685.7 434 728.3 436 771.2 432.3C814 428.7 857 419.3 878.5 414.7L900 410L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#eb5967"/><path d="M0 514L21.5 514.3C43 514.7 86 515.3 128.8 510.7C171.7 506 214.3 496 257.2 492.7C300 489.3 343 492.7 385.8 493C428.7 493.3 471.3 490.7 514.2 485.7C557 480.7 600 473.3 642.8 471.7C685.7 470 728.3 474 771.2 474.3C814 474.7 857 471.3 878.5 469.7L900 468L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#da3f67"/><path d="M0 543L21.5 544.8C43 546.7 86 550.3 128.8 551.8C171.7 553.3 214.3 552.7 257.2 547.7C300 542.7 343 533.3 385.8 527.2C428.7 521 471.3 518 514.2 523.5C557 529 600 543 642.8 547.3C685.7 551.7 728.3 546.3 771.2 544.3C814 542.3 857 543.7 878.5 544.3L900 545L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#c62368"/></svg>



<header>
         <h1>AniaAI Image Generator </h1>      
</header>
<section class=”images-section></section>
<section class=”bottom-section”>
<div class=”input container”>
          <input/>
          <div id=”submit-icon”></div>
</section>
</section>


<script src=”app.js”></script>

</body>
</html>


https://app.haikei.app/
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" id="visual" viewBox="0 0 900 600" width="900" height="600" version="1.1"><rect x="0" y="0" width="900" height="600" fill="#001220"/><path d="M0 394L21.5 390.3C43 386.7 86 379.3 128.8 384C171.7 388.7 214.3 405.3 257.2 414.7C300 424 343 426 385.8 423.8C428.7 421.7 471.3 415.3 514.2 412.3C557 409.3 600 409.7 642.8 413.3C685.7 417 728.3 424 771.2 417.3C814 410.7 857 390.3 878.5 380.2L900 370L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#fa7268"/><path d="M0 430L21.5 436.8C43 443.7 86 457.3 128.8 462.5C171.7 467.7 214.3 464.3 257.2 463C300 461.7 343 462.3 385.8 463.2C428.7 464 471.3 465 514.2 459.8C557 454.7 600 443.3 642.8 438.7C685.7 434 728.3 436 771.2 432.3C814 428.7 857 419.3 878.5 414.7L900 410L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#eb5967"/><path d="M0 514L21.5 514.3C43 514.7 86 515.3 128.8 510.7C171.7 506 214.3 496 257.2 492.7C300 489.3 343 492.7 385.8 493C428.7 493.3 471.3 490.7 514.2 485.7C557 480.7 600 473.3 642.8 471.7C685.7 470 728.3 474 771.2 474.3C814 474.7 857 471.3 878.5 469.7L900 468L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#da3f67"/><path d="M0 543L21.5 544.8C43 546.7 86 550.3 128.8 551.8C171.7 553.3 214.3 552.7 257.2 547.7C300 542.7 343 533.3 385.8 527.2C428.7 521 471.3 518 514.2 523.5C557 529 600 543 642.8 547.3C685.7 551.7 728.3 546.3 771.2 544.3C814 542.3 857 543.7 878.5 544.3L900 545L900 601L878.5 601C857 601 814 601 771.2 601C728.3 601 685.7 601 642.8 601C600 601 557 601 514.2 601C471.3 601 428.7 601 385.8 601C343 601 300 601 257.2 601C214.3 601 171.7 601 128.8 601C86 601 43 601 21.5 601L0 601Z" fill="#c62368"/></svg>


app.js
// do NOT deploy this API key or upload onto GitHub.
const API_KEY = “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”
const submitIcon = document.querySelector(“#submit-icon”)
const inputElement = document.querySelector(“input”)
const imageSection = document.querySelector(‘images-section’)


const getImages =  async () => {
           const options = {
                  method: “POST”,
                  headers: {
                      “Authorization”: ‘Bearer ${APY_KEY}’, 
                      “Content-Type”: “application/json” 
           },
           body: JSON.stringify({
                      prompt: inputElement.value,
                      n: 4,
                       size “1024x1024” 
}) 
}
      try {
         const response =  await fetch (“ https://api.openai.com/v1/images/generations”, options)
         const data = await response.json()
         data?.data.forEach(imageObject => {
             const imageContainer = document.createElement(“div”)
             imageContainer.classList.add(“image-container”)
             const imageElement = document.createElement(“img”) 
             imageElement.setAttribute(“src”, imageObject.url)
             imageContainer.append(imageElement)
             imageSection.append(imageContainer)
})

    } catch (error) {
           console.error(error)
    }
}

submitIcon.addEventListener(‘click’, getImages )


https://platform.openai.com/docs/api-reference 
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

https://platform.openai.com/docs/api-reference/images 

styles.css
body {
     margin: 0;
     padding: 0;
     background-color: rgb(198, 35, 104) ;
     display: flex;
     flex-direction: column;
     width: 100vw;
     height: 100vh;
     justify-content: space-between;
     align-items: center;
     font-family: “Trebuchet MS”, sans-serif;
}

header {
     color: rgb (255, 255, 255);
     height: 150px;
     display: flex;
     align: center;
     width: 100%;
     justify-content: center;
     
}

svg {
     position: absolute;
     top: 0;
     left: 0;
     z-index: -10;
}

.bottom-section {
     width: 100%;
     display: flex;
     justify-content: center;
     height: 150px;
}


.input-container {
     width: 100%;
     max-width: 600px;
     position: relative;
}
input {
     width: 100%;
     border: none;
     font-size: 20px;
     padding: 10px;
     border-radius: 5px;
     box-shadow: rgb (38, 57, 77) 0 20px 30px -10px;
     box-sizing: border-box;
     
}


# submit-icon {
     position: absolut;
     top: 10px;
     right: 30px;
     cursor: pointer;     
}

.images-section {
     width: 100%;
     max-width: 600px;
     display: flex;
     flex-wrap: wrap;
     justify-content: space-between;
     padding: 10px;
}

.image-container {
      width: 40%;
      border-radius: 15px;
      overflow: hidden;
      box-shadow: rgb(38 57 77) 0 20px 30px -10px;
}

.image-container img {
      width: 100%;
}
