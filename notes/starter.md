# React admin dashboard notes

## Installations

- Install material ui with additional data grid andicons package=> npm install @mui/material @emotion/react @emotion/styled @mui/icons-material @mui/x-data-grid
- Install react router dom=> npm install react-router-dom@6
- install react pro sidebar => npm install react-pro-sidebar
- install formik => npm install formik yup
- install fullcalendrar => npm install @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list
- install nivo charts => @nivo/core @nivo/pie @nivo/bar @nivo/geo
- install react pro sidebar => npm i react-pro-sidebar

#### NOTE that in order for nivo carths to work, you need to install the core first and then the other charts

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

### Adding google fonts

We go to fonts.google.com and choose the `source sans pro` font and add some of them. We choose the `import` section, copy the link, and paste it as such to `index.css` => `@import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@200&family=Source+Sans+Pro:wght@400;600;700&display=swap');`
