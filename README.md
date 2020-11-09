# DeepArt
When you cant create a masterpiece yourself, let a machine do it for you. Create self portraits in the style of the masters.

Give me a paintbrush and I'll create something not worth noting, or even showing. My painting skills are not very good. But being creative with data
is right up my alley. And learn an algorithm to become creative, well that's would amazing. Algorithms find patterns, patterns that exist in data. 
So the data you provide can be intepreted as the context the algorithm uses. That's what we're doing here as well, we're letting an algorithm 
learn a certain kind of pattern (based on a masterpiece of a painting) and then we're changing the context.  

See: https://cmotions.nl/deep-art-cmotions-leert-schilderen/

## Installation
The script is stand alone, however you do need to install some dependencies:
* `tensorflow-gpu`
* `scipy`
* download the vgg19: https://www.kaggle.com/teksab/imagenetvggverydeep19mat

When you don't have a computer with GPU, i suggest using an only notebook like Colab or Paperspace for example.

## Usage
To make your own painting, take the following steps.  

1. Clone this repository:
```
git clone https://github.com/kromme/DeepArt.git
```

2. Find a photo you would like to be painted.  
3. Find a style-photo, there are some suggestions in the folder `input_styles`.  
4. Open CMD in the folder (TIP: just type `CMD` in the location-path in File Explorer)
5. Type `python deepart.py <photo> <style_photo>`
6. Wait.. If it takes too long you can reduce max_pix_length (outputs smaller pictures), or n_checkpoints (stop earlier, so results gets worse)

## Examples
See a holiday photo below (an eruption of the El Fuego volcano in Guatemala) in the style of Van Gogh, Mondrian, Munch and Warhol.  
![](https://cmotions.nl/wp-content/uploads/2019/08/El-Fuego-vs-vGogh-Mondriaan-Munch-Warhol-zondertekst-915x1024.png)