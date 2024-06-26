## Release notes


### Version 1.0.111 - 24/04/07
- Enhancements
  - Internal optimization
- New features
  - Format tool accepts active shapes.
- Fix bugs
  - Color pickers take effect immediately.
  - Shape style changes undos fallback to the previous style.

### Version 1.0.110 - 24/04/04
- Enhancements
    - Internal optimization
- Changes
      - Change the default project type to Non-Compressed project.
      - End support for Compressed project type.
- New features
    - Searching PDF with text, regex pattern on multiple pages.

### Version 1.0.109 - 24/04/02
- Enhancements
  - Not to re-render when changing view-port size.

### Version 1.0.108 - 24/04/01
- Enhancements
  - Internal optimization

### Version 1.0.107 - 24/03/31
- New features
    - Add the feature of Rotating PDF page.
    - Add the feature of Purging project database.
    - Add text search feature in Draw view
    - Add feature to set page properties such as name, scale in Document view
- Enhancements
    - Internal optimization

### Version 1.0.103 - 24/03/22
- New features
  - Adding the feature of adding versions to a PDF page.
  - Adding the feature of opting a version to open a PDF page.
  Please note that this feature is not available for the Compressed Project type. To utilize this feature, users need to create either Non-Compressed projects or GDX projects.
- Bug fixes
  - Draw board occasionally locked.

### Version 1.0.102 - 24/03/19
- Enhancements
    - Re-layout of the main window of Draw View
    - Improve performance of metric values computation.

### Version 1.0.101 - 24/03/12
- New Features
  - Introduction of non-compress BlueGrid project file format.
  - Introduction of GDX project - incubator stage.

### Version 1.0.100 - 24/02/29
- Enhancements
  - Internal optimizations.

### Version 1.0.99 - 24/02/06
- Enhancements
  - Internal optimizations.


### Version 1.0.98 - 24/01/30
- Enhancements
    - Internal optimizations.

- Bug fixes
    - Fix bugs in pdf shapes selection.
    - Remove osculated thumbnails.
    - Fix bugs in shape clipping.
    - Snap on/off 

### Version 1.0.97 - 24/01/18
- Enhancements
  - Internal optimizations.
- Bug fixes
  - Fix bugs in pdf shapes selection.

### Version 1.0.96 - 24/01/11
- Enhancements
    - Internal optimizations.
    - Support image texture paint.
- Bug fixes
    - Clip images.

### Version 1.0.95 - 24/01/09
- Enhancements
    - Internal optimizations.
- Bug fixes
    - Fix bugs that may cause memory crash when snapping is on.

### Version 1.0.93 - 23/12/22
- Bug fixes
    - Fix the bug of black thumbnail images in some PDF.

### Version 1.0.91 - 23/12/14
- New features
    - Support import/export application setting profiles.
- Enhancements
    - Improve user experience when panning with right mouse.


### Version 1.0.89 - 23/12/07

- New features
    - Add Copy option when applying a new material to the same shape.
- Changes
    - Move select_on_select to bottom bar.
    - <span style="color:orange">Metric values computation is trigger by users.</span>
- Enhancements
    - Reduce page fetching time with cache.
- Bug fixes
    - Fix the bug of not duplicating materials and shapes when duplicate pages.
    - Remove supports of texture, pattern paint on PDF as the implementation is not completed.

### Version 1.0.88 - 23/12/03

- New features

- Changes
- Enhancements
- Bug fixes
    - Fix the bug of fetching PDF references that appeared in version 1.0.87.

### Version 1.0.87 - 23/12/01

- New features

- Changes
- Enhancements
    - Reduce PDF page fetching time.
    - Remove panning effect when zoom finish in on touch screen.
- Bug fixes


### Version 1.0.86 - 23/11/30

- New features
    - Support release to finish draws on shapes that use two-point draw rule.
    - Allow multiple shortcut key modifiers.
- Changes
- Enhancements
    - Enhance rendering performance.
    - Enhance user experience on touch screens.
- Bug fixes
    - Fix bug fetching large PDF page that may cause memory crash or hanging.
    - Fix bug memory crash when rendering very large images in PDF.

### Version 1.0.85 - 23/11/28

- New features
    - Support secondary mouse panning in draw mode.
    - Support primary mouse drag in draw mode.
- Changes
- Enhancements
    - Enhance rendering performance.
    - Enhance user experience on Windows touch screens.
    - Enhance touchpad operation.
    - Keep Selector line width consistent.
    - Keep Selector hand size consistent.
- Bug fixes
    - Fix bug snap infinite loop that may cause memory crash or hanging.
    - Fix bug not-importing material definitions from CSV files that appeared since version 1.0.83.
  

### Version 1.0.84 - 23/11/24
   
- New features 
    - Supports of shortcut keys.
- Enhancements 
- Bug fixes
    - Hot set page scale.
    - Non-supported error in building path from shapes.

### Version 1.0.83  - 23/11/20

- New features
    - Select shapes from PDF model
    - Build path from shapes
    - Take a path as a symbol
- Enhancements
    - Avoid point snapping on texts to improve snap performance
- Bug fixes


  
        