# go-packfolder
A helper tool for go-sciter. Go version of sciters packfolder tool.

The only thing you need to change in your code is adding a comment line anywhere you like:

`//go:generate go-packfolder -o=res.go -p=main res`

and this line as before: `handleDataLoad(w.Sciter)`

That's it, now you can call `go generate` and have your .go file with all the resources and helper code.
