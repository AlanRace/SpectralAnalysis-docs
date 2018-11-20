+++
title = "Basic Use"
+++

#### Table of Contents  
* [SpectralAnalysis](#spectralAnalysis)
* [Opening Data](#openData)  
* [Data Visualisation](#dataVisualisation)  

<a name="spectralAnalysis"/>

## SpectralAnalysis

![SpectralAnalysis Interface](https://i.imgur.com/a5lLeVM.png)

1. [Open Data](#openData)
2. Convert data to SpectralAnalysis format
3. View memory usage interface
4. Progress bar
5. Log of activities that have been and are currently being performed

<a name="openData"/>

## Opening Data
When selecting the 'Open' menu, the list of currently implemented [parsers](Parser) will be shown, select the appropriate parser for the type of data to be opened.

![Select file type to open](https://i.imgur.com/uIHUqOG.png)

After selecting the file to open, the 'Select Data Representation' interface will be shown. This enables loading all data in memory (most memory intensive, fastest processing), loading only a subset of the data (limited spectral range and/or a selected region of interest) into memory or leaving the data on the disk (very little memory consumed, slower processing).

![Select Data Representation interface](https://i.imgur.com/VZgBeXm.png)

1. Select the [data representation](DataRepresentation) to use to load the data (this interface is specific to Data In Memory).
2. Optional spectral channel range to impose when loading data.
3. Optionally select a [region of interest](Region Of Interest) to load. Default is the entire dataset.
4. Optionally select a method for [ensuring a consistent spectral axis](Ensure-Consistent-Spectral-Axis). If data is [not continuous](Continuous-vs-Profile) then a method must be selected or the data will not load.
5. Load data with selected options.

<a name="dataVisualisation"/>
## Data Visualisation

![Data Visualisation Interface](https://i.imgur.com/209NDrs.png)

1. Generate a [spectral representation](SpectralRepresentation)
2. Perform [data reduction](DataReduction)
3. Perform [clustering](Clustering)
4. [Image List](ImageList)
5. Selected image display

## Spectral Zooming
* Zooming into a spectrum is performed by click-and-drag below the spectrum axis (see below)
* Zooming out is performed by double clicking below the spectrum axis

![Spectral Zooming](https://i.imgur.com/xGenxPZ.gif)

## Image Generation

![Image Generation](https://i.imgur.com/J7ZxGd4.gif)
