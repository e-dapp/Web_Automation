# Web_Automation
A little class template to be used for web automation using Selenium Webdriver, Python API.

Currently included functions:

  - find_element_by_locator
      abstracts seleniums multiple finding functions under one moniker
  
  - wait_for_findable
      customizable wait functionality for find_element_by_locator
  
  - wait_for_clickable
      customizable wait functionality for Selenium's click function
      (requires element has already been found and assumes click should change url)
