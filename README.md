# craftbeerpi-plugins

### To change the original repository for list of plugins and include your onw plugins plus the ones of the original repository:

#### Change the file `modules\addon\endpoints.py`
The `/list` blueprint is the responsible for the request to Craftbeerpi original plugins.yaml file 

Clone the the repo https://github.com/Manuel83/craftbeerpi-plugins,
on your clone include new records to the plugins you want on the file plugins.yaml:

Each Plugin needs:

UniquePluginName:   
  description: Description of the plugin that will showed at the plugin screen  
  api: 3.0  
  author: Your name 
  repo_url: https://github.com/YourRepo/YourPluginCode.git  

  This way you can combine the original list with the original urls allowing you to update your plugins and including your own.   
  YOU will never see new records from original Craftbeerpi repository. But you may watch the original one and see when it changes.

If you wanto to combine the original ones plus the ones on your repository I have created a Craftbeerpi plugin to it:
https://github.com/MarcioMonego/ChangePluginsRepository
There you can find instructions on how to proced.