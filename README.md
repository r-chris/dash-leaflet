# Dash Leaflet

Dash Leaflet is a light wrapper around React-Leaflet. The syntax is similar to other Dash components, with naming conventions following the React-Leaflet API. 

## Getting started

The easiest way to get started is to install the latest version of Dash and Dash Leaflet via pip.

```
pip install dash==1.12.0
pip install dash-leaflet
```

Once the installation is completed, paste the following lines of code into a .py file and run it.

````
import dash
import dash_leaflet as dl

app = dash.Dash()
app.layout = dl.Map(dl.TileLayer(), style={'width': '1000px', 'height': '500px'})

if __name__ == '__main__':
    app.run_server()    
````

If you visit http://127.0.0.1:8050/ in your browser, you should see a Leaflet map.

## Documentation

The documentation has been moved to [Heroku](https://dash-leaflet.herokuapp.com/) to enable an interactive example gallery. 