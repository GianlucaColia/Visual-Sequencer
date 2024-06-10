# Visual Sequencer 
<a href="https://github.com/GianlucaColia/Visual-Sequencer/releases/download/v1.6.0/Visual.Sequencer.v-1.6.0.zip"><img src="Download Button.png" alt="Download"></a>
## Presentation
<img alt="Snapshot 2" src="https://github.com/GianlucaColia/Visual-Sequencer/blob/main/Trademark%20contents/Snapshot%202.png" width="300px" img>
<img alt="Content 1" src="https://github.com/GianlucaColia/Visual-Sequencer/blob/main/Trademark%20contents/Contenuto%201.png" width="300px" img>

<video width="720" height="720" controls>
  <source src="https://github.com/GianlucaColia/Visual-Sequencer/blob/main/Trademark%20contents/Video%20Teaser%20visual%20sequencer.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<img alt="Content 3" src="https://github.com/GianlucaColia/Visual-Sequencer/blob/main/Trademark%20contents/Contenuto%203.png" width="300px" img>
<img alt="Snapshot 1" src="https://github.com/GianlucaColia/Visual-Sequencer/blob/main/Trademark%20contents/Snapshot%201.png" width="300px" img>
## Installation

1. Download the folder 
2. Unzip the folder
3. Install [TouchPlayer](https://derivative.ca/download) (part of TouchDesigner)
4. Install Brutt Grotesque TEST font (trial version) included in the folder or download the full version from [Brutt Grotesque Font](https://bureaubrut.com/en/product/brut-grotesque/)
5. Open [Visual Sequencer](#Visual-Sequencer) and enjoy!

## Documentation 
*Visual Sequencer* was developed using [TouchDesigner](https://derivative.ca/) and *Python* visual scripting nodes.

### User Interface Sections

- [Import](#import)
- [Parameters](#parameters)
- [Export](#export)

### Import

- [Folder Input](#folder-input)
- [Driving Video](#driving-video)
- [Audio](#audio)

### Parameters

##### Grid & Resolution

- Grid
- Resolution

##### Dynamic Grid

- Speed
- Displacement 
- Randomize Grid

##### Animation Mode

- Global Image
- Interpolation

##### Transformation

- Translate
- Rotate
- Scale

##### Additional Effects

- Invert Color

### Export

##### Transparency

- Alpha
- Green Screen
- Invert Alpha

##### Output

- [File Name](#file-name)
- [Record](#record)
- [Save Frame](#save-frame)

### Import Compatibility

##### Folder Input

Currently imports image & video file folders with .jpg, .png, .tiff, .mov, and .mp4 extensions.

You can import folders with files with mixed extensions, however, it is recommended to prepare files with the same resolution such as 1080x1080 or 1920x1080.

##### Driving Video

It is possible to import folders with files with mixed extensions, however, it is recommended to prepare the files to be imported with the same resolution, e.g., 1080x1080 or 1920x1080.

##### Audio

File import is available in .wav, .mp3, and .mp4 formats.

### Export Compatibility

##### File Name

To get the output files, you need to set the path of where you want to get the file and the file name.

##### Record

Export via recording is available in uncompressed .mov format for video files.

##### Save Frame

Export of individual frames is available in .png format.

### Shortcut

##### Clear Canvas

Press the "c" key to clean the canvas.

##### Close & Open User Interface

Press "shift" key + "p" to close and open the user interface.

## Upcoming Features

- All local transformation
- Preset patterns
- Audio synchronization with preset patterns
- Independent driving video for additional effects
- Exporting tiles

## Credits

The entire project was born as *open source* to reflect the values of James Wallbank's [Low Tech Manifesto](http://lowtech.org/projects/n5m3/), therefore anyone can access the code by opening [Visual Sequencer](#Visual-Sequencer) within [TouchDesigner](https://derivative.ca/).

###### Designed & developed by Gianluca Colia
