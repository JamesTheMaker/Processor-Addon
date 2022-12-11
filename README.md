# READ ME
 **This read me exists for a reason, so please read it all the way through.**
 
 This Example Addon for the Processors mod provides examples for everything you can do with processors, including:
  - A new processor machine.
  - A new processor recipe config.
  - Modifying a pre-existing output of a pre-existing recipe in a pre-existing config.
  - Adding a new output to a pre-existing recipe in a pre-existing config.
  - Adding a new recipe to a pre-existing config.
  
  The following two sections will go over required elements of making a processor addon.
# REQUIRING PROCESSORS
 **If your mod does not add a new processor machine, this is not required. Please skip to the next section.**
 
 (Don't follow this section. Required is bad.) 
 ~~For those of you who do plan on adding a new processor machine, you must require Processors by adding this to your ```.metadata``` file:~~
  
  ```"required" : [ "processors" ]```~~
  
 ~~This makes sure nobody has the mod active while not also having Processors active.~~
# INCLUDING PROCESSORS
 **If your mod adds a new processor machine, you must require the mod instead. Please go to the section above.**
 
 For those of you who ddo not plan on adding a new processor machine, and are simply adding, removing or modifying recipes from the recipe tables, you must include Processors by adding this to your ```.metadata``` file:
  
  ```"includes" : [ "processors" ]```
  
 This makes sure your mod is loaded after Processors, so your patch operations can work.
