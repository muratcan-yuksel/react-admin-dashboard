# React admin dashboard notes

## Installations

- Install material ui with additional data grid andicons package=> npm install @mui/material @emotion/react @emotion/styled @mui/icons-material @mui/x-data-grid
- Install react router dom=> npm install react-router-dom@6
- install react pro sidebar => npm install react-pro-sidebar
- install formik => npm install formik yup
- install fullcalendrar => npm install @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list
- install nivo charts => @nivo/core @nivo/pie @nivo/bar @nivo/geo

## Starting the project

After installations, we'll add `import { BrowserRouter } from "react-router-dom"; ` to `index.js` and wrap our app like so =>

```js
import React from "react";
import ReactDOM from "react-dom/client";
import "./index.css";
import App from "./App";
import { BrowserRouter } from "react-router-dom";

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(
  <React.StrictMode>
    <BrowserRouter>
      <App />
    </BrowserRouter>
  </React.StrictMode>
);
```
