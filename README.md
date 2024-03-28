# cintel-04-local
Move projects from web to local machine / cloud

# Terminal Commands:
.venv\Scripts\Activate
-> opens the virtual environment

shiny run --reload --launch-browser penguins/app.py
-> runs the penguins shiny app on a browser

shiny static-assets remove
-> makes the files movable

shinylive export penguins docs
-> builds client-side app to docs folder

py -m http.server --directory docs --bind localhost 8008
-> Create a local web app
-> Link: http://[::1]:8008/

deactivate
-> shuts off the virtual environment
