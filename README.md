
# Usage
The YAML file can be viewed and edited with Swagger Editor. Swagger Editor can be installed via NPM: 
* Install nodeJS
* Install the required dependencies:
```
npm install
```

Start the swagger-editor:
```
npm run editor
```
* Then open: http://localhost:8080/  -  when it doesn't run on port 8080, look in the log for: "Available on:"
* In Swagger Editor go to File -> Import File -> select the blog.yaml


# Create PDF
* Save the YAML to blog.json in the current folder. 
* Run the command `npm run pdf`
* In the current folder a new file `blog.export.pdf` should be created. 

# Create HTML
To create a single HTML file (without dependencies):
* Run the command `npm run html`
* In the current folder a new file blog.export.html should be created.

