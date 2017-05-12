Coding language used: JAVA with Maven
Database used: MongoDB

To run the program, import the project as maven project in eclipse and run:

mvn clean install

After successful build run the main class "FaceDetectResource" with 7 arguments:

args[0]: url of the image
args[1]: mongo host
args[2]: mongo port
args[3]: mongo database name
args[4]: true (if authentication is enabled in mongodb else false)
args[5]: mongo username (if authentication is enabled else give dummy value)
args[6]: mongo password (if authentication is enabled else give dummy value)

After successful run, program will create a new collection called "image" in mongo database
and will save 3 fields in that collection: 

imageUrl, age and gender.


