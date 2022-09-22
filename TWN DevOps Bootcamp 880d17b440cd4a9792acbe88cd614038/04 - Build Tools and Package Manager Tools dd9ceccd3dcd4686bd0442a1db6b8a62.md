# 04 - Build Tools and Package Manager Tools

# Course Documents

[04 - Build Tools Checklist.pdf](https://drive.google.com/file/d/1S80JxdAQn4ZMLInLOjaVMXuO_-Ipk4Ou/view?usp=drivesdk)

[04 - Build Tools Handout.pdf](https://drive.google.com/file/d/1SDNz0b5IAIa6YxF-LBv9jb4epSmfVbuk/view?usp=drivesdk)

- for Java we have. maven and gradle
- for JS we have npm and yarn
- npm and yarn are package managers an NOT build tools like maven and gradle
    - they install dependencies but are not used for transpilling JS code
- the JS zip/tar file includes application code, but NOT the dependencies
    - To run on the server we need to install the dependencies first
    - unpack zip/tar
    - run the app
- To create a NodeJS app artifact: $ npm pack
- $ npm start → run the application