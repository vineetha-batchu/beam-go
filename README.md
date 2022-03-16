
### Intall GoLang and check for the forsion
`go version`

### Get the SDK and the examples
`go get -u github.com/apache/beam/sdks/v2/go/pkg/beam`

### Run wordcount (the below comand didn't work for me)
`go install github.com/apache/beam/sdks/v2/go/examples/wordcount`

###  So, I used the following command to run
 `go run wordcount.go --input sample.txt --output counts`

 #### After running the above command, it asked me to get the following 
 `go get github.com/apache/beam/sdks/v2/go/pkg/beam/runners/dataflow/dataflowlib@v2.37.0`
 ` go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0`

 ###  Now, Run the Word Count 
 `go run wordcount.go --input sample.txt --output counts`
