# go-templates-example
An example of using go templates in a file server.

1. Run server with "go run main.go"
2. In a separate terminal "wget localhost:4000" to get the template result

In "tmpl" folder we have base.layout.tmpl and home.page.tmpl. 
* Base contains base content, default content, and expects another template to define the main content.
* Home overrides the default content and defines the main content.

In main.go we set the files to define the base template, and the home page template for the request.
