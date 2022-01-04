# React-pdf-devto
### An example for using react-pdf npm package

![](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/n4ndpypvc3i5bzjahbwn.JPG)

<br />

- Do not use :

`import ... from 'react-pdf' `

- Instead in <b>create-react-app, </b> it works under the hood:

`import ... from "react-pdf/dist/esm/entry.webpack"`

- For activating links 

`import 'react-pdf/dist/esm/Page/AnnotationLayer.css';`
