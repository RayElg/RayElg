# Raynor Elgie

### Studying CS @ Ryerson University & Interning @ WSIB

## Projects

<details><summary>processor (Custom assembly language & interpreter)</summary>
 
```
    JNZ, 15, PAD, //Jump past characters
    b'h', b'e', b'l', //put 'helloworld!' in memory
    b'l', b'o', b'w',
    b'o', b'r', b'l',
    b'd', b'!', b'\n',
    LD_BYTE, 0, 3, //PTR=3
    LD_BYTE, 1, 15, //TARGET=15
    PRNTC_LOC, 0, PAD, //PRNT PTR
    INC, 0, PAD, //PTR++
    SUB, 0b0001_0000, 14, //DIFF = TARGET-PTR
    JNZ, 21 //Jump to PRNTC_LOC location if DIFF != 0
```
 
This is what I'm working on right now. Taking *some* inspiration from x86, this is an assembly language and 16-register, 32-bit processor emulator.  
[Check it out](https://github.com/RayElg/processor)
 </details>

<details><summary>WikiPredict (NLP & ML Project)</summary>
<img src="https://raw.githubusercontent.com/RayElg/WikiPredict/main/wikipredict.png" alt="Prediction report" width=334 height="244">

An NLP & Machine Learning model deployed with Django. Trained with data from movie dialogue & Wikipedia articles, it evaluates text for proper Wikipedia tone. Built using Spacy, Scikit-learn.
 
[Try it out](https://raynorelgie.com/django/wikipredict/entry)
</details>

<details><summary>PictureThis (Web image repository)</summary>

<img src="https://camo.githubusercontent.com/8459220394003d3a0934d131c116393c18f4bd4e9a6dc0af818317eb9487ccff/68747470733a2f2f692e696d6775722e636f6d2f6b61376c7a554b2e706e67" alt="images uploaded by raynor" width="500" height="250">

An image repository that handles access control, authentication, searching, and automatic tagging (through an image classification API)
[Try it out](https://raynorelgie.com/PictureThis/?search=snow)
 </details>

<details><summary>plotGeoJson (Heat map generator)</summary>
<img src="https://raw.githubusercontent.com/RayElg/plotGeoJson/master/justDots.png" alt="plotmap" width="334" height="194">

A python script that will generate a heatmap or plot features from a GeoJson file
[Check it out](https://github.com/RayElg/plotGeoJson)
 </details>
 
<details><summary>Massives (N-Body simulation)</summary>
<img src="https://camo.githubusercontent.com/1812260cedc2119ede355a9e5e1ae3e44748396eafb2fdaab6533fc437cc5d2b/68747470733a2f2f7261796e6f72656c6769652e636f6d2f73686f77636173652e676966", width="300", alt="a gif showing a moon orbiting a planet that orbits a larger body">

An N-Body physics simulation written with Rust and Python. Reads universe starting state from JSON, uses Rust to do the heavy lifting, and Python for the display.
[Check it out](https://github.com/RayElg/massives)

</details>

## Languages & Interests

I like Python, Rust, C, and Dart. I also use Java, R, PHP, and more.  

I'm interested in data science, computer architecture, systems programming, and app development.

## Links, etc.

[raynorelgie.com](https://raynorelgie.com)  
[Linkedin](https://www.linkedin.com/in/raynor-e/)  

