# Responsive Smart Admin Template
Free Responsive Admin Dashboard Template Using Bootstrap4 jQuery HTML5 CSS3. 

If want to customize this Free Responsive Admin Template Using Bootstrap4, jQuery, HTML5 & CSS3. Then follow the below steps

## Step -1: 

Download Free Responsive Admin Template from [SmartTutorials.net](https://smarttutorials.net/responsive-admin-template-using-html5-css3-javascript-bootstrap-4-jquery/)


## Step -2: 

Unzip the downloaded bootstrap reponsive admin template. Now open your command terminal and go to the template folder.


> Note: **NodeJS** must have installed in your system, I am using **webpack build system for developemt**. I am going release separte series of tutorials on **Webpack**.


## Step -3:

Next install necessary node packages using following node commands.

```
npm install
```

## Step -4:

Next run the follwoing command development server in your local.

```
npm start
```

## Step -5:

To generate final build, then run the following command.

```
npm run prod
```

> Note: If you want add new HTML file for devleopment using webpack build system, then create HTML file and inform **Webpack build system** in the **webpack.config.js** file like this. In the plugin section you need to add the following config.

```javascript
new HtmlWebpackPlugin({
    template: "your-new-html-filename.html",
    filename: "your-new-html-filename.html",
    inject: "body"
}),
```

Once you have added this config changes, then you need to stop the development and restart again to take config changes.

