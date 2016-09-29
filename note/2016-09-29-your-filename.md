## A New Post

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
## [**A IPython Notebook to analyze the Gaza-Israel 2012 crisis**](https://nbviewer.jupyter.org/gist/darribas/4121857)
### tricks:
	-dataset have date features:
    	change to pandas datetime format:
        db['Date'] = db['Date'].apply(pd.to_datetime)
        
    -get split() all member:
   		lon,lat = dataset['location'].split(',')
        lon,lat = map(float,[lon,lat])
### [Cartopy](http://scitools.org.uk/cartopy/docs/latest/index.html) :
	cartopy is a Python package designed to make drawing maps for data analysis visualisation as easy as possible.
	
