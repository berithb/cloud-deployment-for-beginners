# Cloud Computing for Beginners in Rwanda 🇷🇼

Author: Mushikiwabo Belite  

## Purpose
This repository is a beginner-friendly technical tutorial created to introduce cloud computing concepts to students, junior developers, and startups in Rwanda. The goal is to simplify cloud adoption by explaining core ideas in a practical and accessible way.

## What This Tutorial Covers
- Introduction to cloud computing
- Why cloud technology matters for African startups
- Running a simple web application
- Understanding how applications are deployed to the cloud

## Sample Application (Node.js)
Below is a simple Node.js server example used for learning purposes:

```js
const http = require('http');

const server = http.createServer((req, res) => {
  res.write('Hello from the Cloud!');
  res.end();
});

server.listen(3000, () => {
  console.log('Server running on port 3000');
});
