const express = require('express');
const bodyParser = require('body-parser');
const { Sequelize, DataTypes } = require('sequelize');
const { Api, Resource } = require('express-restful');
const fs = require('fs');

const app = express();
app.use(bodyParser.json());

// Read HTML and CSS content from files
const htmlCss = fs.readFileSync('path/to/your/html_css_file.html', 'utf-8');

// ... (rest of the code remains unchanged)
