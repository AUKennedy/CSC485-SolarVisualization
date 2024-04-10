`Project Proposal — CSC485: Visualization`

`Dylan & Kennedy`

`04.08.2024`

`SHEET 0: DOMAIN & DATA`

    Domain: Sattalite Imagery

    Type of Data: Image Data, Timeseries

    Items & Attributes: Images + Meta–Data (Date, Spectral Info)

    Size: Variable, Images Come in Multiple Scales & Can Be Downloaded at Given Frequncy

    In Hand?: Some, But Some Downloading Will Likely Be Needed as the Project Is Refined
    
    Our project focuses on the visualization of solar dynamics using images from the Helioseismic and Magnetic Imager (HMI) and the Solar Dynamics Observatory (SDO).
    These instruments provide a large dataset of solar images taken at different wavelengths, revealing sunspots, solar flares, and magnetic field changes.
    The dataset includes numerous HMI and SDO images captured at various times, each containing timestamps, and spectral information.

`SHEET 1: BRAINSTORM`
    
    IDEA 1: Time-Lapse Animations (D)
    
    Description: 
    This concept revolves around creating time-lapse animations of the solar activities captured by HMI and SDO.
    The animations will provide a visual narrative of significant solar events such as transit events, sunspot formation, solar flares, and coronal mass ejections (CMEs) over specific time intervals.
    [These time intervals will be handpicked for the presence of such events]

    Interactivity:
    Users can control playback speed, pause, and rewind functionalities to observe solar dynamics at their own pace.
    * Possible: Interactive overlays or annotations can highlight notable events for enhanced comprehension.
    [Can we do this...?] 

    –––––––––––––––––––––––––––––

    IDEA 2: Interactive Solar Map (D)

    Description: 
    An interactive "map" interface will be developed to visualize sunspots and magnetic fields on the solar surface.
    Users can navigate this solar "map" to explore different regions of interest and obtain detailed information about sunspot characteristics and magnetic field strengths.

    Interactivity:
    Zooming and panning functionalities will enable users to zoom in on specific regions for closer inspection.
    Hovering over map markers or regions will trigger tooltips displaying relevant data, such as sunspot area, polarity, and magnetic field intensity.
    [Seems more do–able]

    –––––––––––––––––––––––––––––

    IDEA 3: Visualization of Composite Images ––– Merging HMI and SDO Data (D)
    
    Description:
    This concept entails creating composite visualizations by overlaying HMI and SDO images to provide an ehnaced view of solar phenomena.
    Combining images captured at different wavelengths and frequencies, users can gain insights into the relationships between various solar features and activities.

    Interactivity:
    Users will have the ability to adjust the transparency levels of individual layers, allowing them to selectively emphasize specific solar features or phenomena.
    * Possible: Interactive tooltips will provide detailed information about the solar structures depicted in the composite images, enhancing understanding and interpretation.

    –––––––––––––––––––––––––––––


    IDEA 4: Spectral Analysis Visualizer (K)
    
    Description:
    A spectral analysis tool to visualize the variations in solar spectral data captured by HMI and SDO. By plotting spectral profiles over time, users can identify characteristic signatures associated with sunspots, flares, and other         solar events.
    
    Interactivity:
    One will be able to select specific wavelengths or spectral bands to display, allowing for comparative analysis and identification of correlations between different spectral features and solar activities. 

    –––––––––––––––––––––––––––––

    IDEA 5:Solar Cycle Sunspot Number Progression (K)
    
    Description:
    Linear graph of the number of sunspots over time. Will require to count sunspot from HMI images over time, combining dates, aggregating them, and finally putting them on a linear graph which still conmtaints relevant information 
    from each point. Will allow for th eobservation of patterns over time.
   
    Interactivity:
    Left-clicking on the data and holding while dragging will activate a zoom window, allowing users to define a specific time range for closer inspection. The plot will then adjust to display the selected zoomed-in data. Hovering your 
    cursor over the plots will dynamically display the relevant data values corresponding to the date indicated by the cursor.

`SHEET 2 & 3 & 4: FURTHER EXPLORATION`

    CHOSE TO NOT PERSUE VIDEO / ANIMATION BASED SYSTEM. AS IT MAY BE ESSPEICALLY DIFFICULT CODE–WISE.

    –––––––––––––––––––––––––––––

    2. SOLAR MAP (D)

    Layout:
    The interface would consist of a map displaying solar surface regions with overlay markers representing sunspots and magnetic field distributions.
    A legend will provide a key for interpreting marker colors and symbols.

    Details:
    Each marker will display relevant information upon interaction, such as sunspot size, magnetic polarity, and field strength.
    Users can toggle overlays for different solar parameters to customize their viewing experience.
    This could include the viewing of different wavelength channels —— IE: Switching between HMI & one or two SDO datasets.

    Interactions:
    Zooming and panning gestures will allow users to explore different regions of the solar surface in detail.
    Hovering over markers will trigger tooltips with detailed information, enhancing understanding.

    Benefits:
    Non–Timeseries which makes the coding easier.

    Difficulties:
    The annotation of markers.
    Zooming and panning features.

    –––––––––––––––––––––––––––––

    3. COMPOSITE IMAGES (D)

    Layout:
    Composite images will be created by overlaying HMI and SDO images and utilize transparency adjustments to blend the layers.
    A control panel will allow users to modify transparency levels and toggle between different image combinations.

    Details:
    Information about the composition and characteristics of the displayed solar structures will be provided through interactive tooltips.
    Users can interact with specific regions of interest to access additional data and analysis. (Similar to idea 2)

    Interactions:
    Slider controls will enable users to adjust the transparency levels of individual layers in real-time.
    Clicking on specific regions will trigger tooltips displaying relevant information about the solar features depicted.

    Benefits:
    Composite image visualization offer a more complete view of solar phenomena and each layer provides differing details.

    Difficulties:
    Quick processing of large data.
    Potentially the tooltip feature.

    –––––––––––––––––––––––––––––

    4. THE DODO (K)

    Layout:
    Was rather small. Had a strange–ish beak.

    Details:
    Often refered to by normal people as Raphus cucullatus.

    Interactions:
    It prefered not to interact with people, as it was generally hunted by them.
    It had a very lovely disposition and being hunted rather than socialized with made the species rather sad.

    Benefits:
    Its small wings offered little to no benifits. Its evolution was generally regarded as a poor choice.
    
    Challenges:
    Not flying was one. Extinction was the largest.

`SHEET 5: REALIZATION`

    For our final visualization, we propose a dynamic interactive solar map that combines the features of both Sheets 3 and 4.
    This solar map will allow users to explore different channels of information, including:
        Magnetic Field Information
        Sunspot Activity
    And if present, including:
        Flares
        Transit Events

    –––––––––––––––––––––––––––––

    Layout:

    The solar map interface will present a comprehensive view of the solar surface, with overlays representing various channels of information.
    Users will have the ability to toggle between different channels using a control panel.
    Users will also have the ability to use a tooltip feature to view magnetic field information & intensity value data.
    Other solar phenomenon, if present, will be annotated.
    * If possible, animation should be included.

    –––––––––––––––––––––––––––––

    Details:

    Each channel provides unique information of solar dynamics.
    The magnetic field distribution channel will visualize the strength and polarity of magnetic fields across the solar surface. (HMI Magnetogram)
    The sunspot activity channel will highlight regions of intense sunspot activity, providing information about sunspot sizes and distributions. (HMI)
    Other channels may include solar flare occurrences, coronal mass ejections (CMEs), and prominence activity. (SDO Channels)

    –––––––––––––––––––––––––––––

    Interactions:

    Users can interact with the solar map by toggling between different channels using dropdown menus or buttons on the control panel.
    Hovering over specific regions will display tooltips with detailed information about the selected channel, such as magnetic field strength, sunspot characteristics, or other relevant parameters.
    Users can also select between images with a variety of hand picked solar events of interest.

    –––––––––––––––––––––––––––––

    Benifits:

    This combined visualization offers a visually pleasing and intuitive way to explore various aspects of solar dynamics.
    Users can easily switch between different channels to gain insights into different phenomena.

    –––––––––––––––––––––––––––––

    Difficulties:

    Creating a host website.
    Getting all the data and finding ways to display it.
    Tooltip.
    Annotations.

`SHEET 6: PROJECT PLAN`
    
    1. Pick & Get Data 
    2. Create Visualizations (Process Data)
    3. Create Website
    4. Create Backend to Handle Data
    5. Create JavaScript to Handle Interactions [ + D3, Vega Lite]
    6. Polish

    * TO BE DIVIDED UP BETWEEN US *
    
    

    
    
    

    



    
    
    

    
    
    







    
