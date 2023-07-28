# File-sharing-app

Simplified 'File Sharing Application'-  an application that facilitates the files into link ,download and share it anyway. Made using MongoDB, Express, React, Node (MERN) stack.

# Screenshot

![image](https://github.com/Harshkh87/File-sharing-app/assets/110453465/cc835d74-7bd1-404e-82e3-92f631ff2495)

# Info

The app is built using the MERN stack and uses the multer node package to handle file uploads. React hooks are used in the client-side and not class-based components.

The file formats that are supported by the app include png, jpg, jpeg, gif, webp, svg, ppt, pptx, doc, docx, pdf, xls and xlsx. The maximum size limit is set to 5 MB per file.

The app doesn't currently allow multiple file uploads at once, instead it is designed to upload only a single file at a time.

The links provided after the successful file upload include a download link, which can download the file immediately, and a shareable link which allows the user to easily share the file at a fraction of the original filesize. The shareable link, when clicked, will lead to the original file being downloaded.

The files can be uploaded to the client-side and download through server-side.

# Technologies Used

Some of the technologies used in the development of this web application are as follow:

MongoDB Atlas: It provides a free cloud service to store MongoDB collections.

React.js: A JavaScript library for building user interfaces. In particular, React hooks are used in the clientside of the application.

Node.js: A runtime environment to help build fast server applications using JS.

Express.js: A popular Node.js framework to build scalable server-side for web applications.

Mongoose: An ODM(Object Data Modelling)library for MongoDB and Node.js.

Multer and Multer-S3: Node.js packages that help in dealing with file uploads.

Axios: It is a promise-based HTTP library that lets you consume an API service.

Nodemon: A module based applications by automatically restarting the node application when file changes in the directory are detected.





