# ApacheTikaServer
`The Apache Tika™ toolkit detects and extracts metadata and text from over a thousand different file types (such as PPT, XLS, and PDF). All of these file types can be parsed through a single interface, making Tika useful for search engine indexing, content analysis, translation, and much more.`
<br>
* >Install JDK 1.8 or Above
* >Download Tika JAR -> https://tika.apache.org/download.html
* >To Run Tika Server go to path were you have downloaded the file
`java -jar tika-server-1.21.jar -p <PortNumber> Default port:9998`
* >To Test Apache Tika Server and extract data from file<br>
`curl -T path-to-file/file http://127.0.0.1:<port>/tika`
* >To Get meta data of file and save it to file<br>
`curl -T path-to-file/file http://127.0.0.1:<port>/meta > path-to-file/file.txt ` 
