# Basic-javascript-Swap-Function

function swapGreenRed(pixel){
var x = pixel.getGreen();
pixel.setGreen(pixel.getRed());
pixel.setRed(x);
}

var img = new SimpleImage("palm-and-beach.png");
print(img);



for(var pixel of img.values()){
swapGreenRed(pixel);
}
print(img);


