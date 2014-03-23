Folder Structure

|-core                core modules
  |---block
  |---controller
  |---model
  |---view
  |---database
  |---config
  
|-community             community packages
  |---package           grouped package
    |---module          module name
      |---block         block will be called from view
      |---controller    controller folder
      |---config        config folder
      |---model         model folder
      |---view          view folder
        |---base        base view ( will be customized on global view folder )
        
|-public                public folder ( almost for customize themes/skin )
  |---assets
    |---base
  |---view      
    |---base
      |---package
        |---module
          |---view
            |---view_file
  
