# START Hack 2021 - Mammut Case

### Case Introduction
Climbax is the worlds first dedicated tracker for rock climbing. 
The product utilizes two wrist worn sensors that contain
 - An IMU
 - Pressure sensor
 - NFC tag reader
 - Input button

The data captured from sensors is post-processed to detect
 - Climbing
 - Moves within climbs

From these, a range of metrics can be calculated and displayed to the users in a companion APP. 

Thus far, a simplistic approach has been taken on data visualization. Main efforts have been made refining usability, robustness and defining the business case of this brand new product.

This project is to explore further opportunities for visualizing the data. Since the user has the ability to take video during climbing sessions from a the companion app, we would like to explore the opportunities for integrating this. In the ideal case, composite visualizations of data-video could be "instagrammable" and compelling to friends/followers.

We expect the winning team to creatively use the example data sets given. The winning team should think carefully about:

- How the sensor data can be used to make the video "more exciting/compelling" and deliver a "fuller picture" of the effort/performance of the athlete

- How their chosen approach might handle difficult edge cases where there is little/lots of movement

- How intuitive their chosen approach is. How would an onlooker understand difficulty, height, gradient etc at a glance

The winning team will be judged on 
 - Creativity and visual appeal
 - How well the chosen approach could be generalized to any case

Each team should provide:

- A readme file describing the the chosen approach (with justification), technical hurdles overcome, how to install/compile/run their project
- A compiled version or output files that can be viewed directly
- Commented Source code and list of dependencies or mkfile


Mammut IS interested in developing submissions of high quality further. If members of the team are happy to be contacted, please leave contact details easily accessible.

### Case Pitch

https://vimeo.com/520868355/99615258dd

### Deep Dive Slides

[Mammut Climbax - Deep Dive.pdf](https://github.com/START-Global/MAMMUT-STARTHACK21/files/6159513/Mammut.Climbax.-.Deep.Dive.pdf)

### Further Information
Three example climbs are included; a traverse, a vertical climb and an overhang. For each climb there is included:
 - a video (.mp4)
 - a raw HDF5 file containing sensor data (xxx_raw.h5.)
 - csv file containing accelerometry (`time(s),Left_AP,Left_UR,Left_DP,Right_AP,Right_UR,Right_DP`)
 - csv files containing segmented climb start and end
 - csv file containing detected moves within the climbing period
 - an EAF file that synchronizes the video to the accelerometery


### Resources
The ELAN (.eaf) file will open with [Elan](https://archive.mpi.nl/tla/elan/download). The EAF file is in XML format and contains the offset (in ms) that should be applied to synchronize the video and accelerometry csv file. It can be useful to get a handle on what the data looks like in time with the video

An image file is included to explain the coordinate system used to describe the accelerometry axis

A `dataformat.md` document describes the hierarchical HDF5 format used for the sensor data.


### Judging Criteria
Insert a description of your grading scheme here! What are you looking for? What outcome do you expect?
@stefan

### Point of Contact
List all available mentors here.

### Time Slots at the Booth
List the expected times of availability at the booth here.

### Prize
Let the participants know what will be expecting the winning Team!
