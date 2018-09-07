# Learning Aerial Image Segmentation From Online Maps

This is the ground truth data generated for the publication

    Learning Aerial Image Segmentation From Online Maps
    Pascal Kaiser, Jan Dirk Wegner, Aurélien Lucchi, Martin Jaggi, Thomas Hofmann, Konrad Schindler
    IEEE Transactions on Geoscience and Remote Sensing 55 (11), 6054-6068, 2017/11
    https://doi.org/10.1109/TGRS.2017.2719738

Ground truth of Berlin, Chicago, Paris, Potsdam, and Zurich consist of aerial images from Google Maps 
and pixel-wise building, road, and background labels from OpenStreetMap. Ground truth of Tokyo consists 
of one aerial image from Google Maps and manually generated, pixel-wise building, road, and background labels. 

Pixel-wise labels are provided as PNG images in RGB order. Pixels labeled as building, road, and
background are indicated by RGB colors [255,0,0], [0,0,255], and [255,255,255].

RGB channel means of aerial images
    Berlin   R: 79.94162, G: 84.72064, B:  78.94711
    Chicago  R: 86.46459, G: 85.73488, B:  77.14777 
    Paris    R: 82.46727, G: 92.82243, B:  88.05664
    Potsdam  R: 74.85480, G: 77.37761, B:  70.22035
    Tokyo    R: 96.96883, G: 98.44344, B: 108.60135
    Zurich   R: 62.36962, G: 66.11001, B:  60.32863

Ground truth was generated in
    Berlin   Spring 2016
    Chicago  Autumn 2015
    Paris    Autumn 2015
    Potsdam  Spring 2016
    Tokyo    Spring 2017
    Zurich   Autumn 2015

Ground truth of Potsdam covers the same area as the publicly avaialble, manually labeled ISPRS ground 
truth

    ISPRS semantic labeling challenge
    http://www2.isprs.org/commissions/comm3/wg4/semantic-labeling.html



Link to the data: https://zenodo.org/record/1154821#.W5LrDehKhPY

