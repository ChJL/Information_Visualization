<h1 align="center">Your Best Country to Live After Retiring in Europe</h1>

<p align="center">
    <img src="document/UvA.png" width="300" align="center">
</p>

<p align="center">
    <i>
        <b>
        Group Members: <br>
        Chaoran Li, Chih-Chieh Lin, Haochen Wang, Linxiao Zhu, Xiang Li 
        </b>
    </i>
</p>

## Play this application right now
Update: Jan 5th, 2023
#### Deploy using Vercel
I tried to deploy this application using <a href="https://vercel.com/">Vercel</a>.
You can now play around with our application online :)

Link to use the application <a href="https://information-visualization-chjl.vercel.app/">here</a>.

## Demo Video
<table>
    <tbody>
<!-- YOUTUBE:START --><tr><td><a href="https://www.youtube.com/watch?v=zHhZQshANS8"><img width="140px" src="document/demo.png"></a></td>
<td><a href="https://www.youtube.com/watch?v=zHhZQshANS8">Your Best Country to Retire in Europe</a><br/>April, 2021</td></tr>
<!-- YOUTUBE:END -->
    </tbody>
</table>

## Short Description
Retirement occupies an important place in everyone's life plan. Living in another country after retirement is becoming more attractive than ever. Our work aims to develop a visual application to help users choose the most suitable country for them among 31 European countries. We develop a multiview interface with Flask based web service, and add interactivity to it. After the users input their personal preferences on five indicators, our system can calculate the corresponding recommendation results and rankings, and visually present them on the web for easy comparison.

## Information Visualization Overview
<p align="center">
    <img src="document/demo.png" id="img-demo" width="850" height="500"/>
    <span style>Initial Look</span>
</p>

## Usage to run the application locally
__Pre-requirements:__ Python3.7

* Install the packages
    ```
    pip3 install -r requirements.txt
    ```
* Run the program
    ```
    python3 test.py
    ```
* Open the browser and run http://127.0.0.1:5000/

## Interactive Functions
- Indicator Weight Control (Slider): 
User can allocate the different weights of indicators by sliding the corresponding sliders. 

- Indicator Weighted Condition (Donut plot): 
According to the indicator weights chose from user, we also offers a donut plot in order to make user easier figure out the percentage condition of each indicator.

- Choropleth map (center part)
    - It will show the country’s score and highlight the area when the mouse is hover over such country.
    - It also presents the score by color-hue gradient in real time (whenever user slide the sliders).

- Bar plot  (right part)
    - It would change(sort) in real time when the user slide the sliders.
    - It popups a window showing the country’s rank, name, and score; and also highlight the bar when the mouse hover over such rectangle. Moreover, in the meantime, it would also highlight the corresponding country’s area in the map

## Key words
Information visualization, Geospatial analysis, Retirement, Europe, D3.js


