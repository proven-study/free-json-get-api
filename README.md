# free-json-get-api

Get data by updating json file.

- api url: <https://raw.githubusercontent.com/proven-study/free-json-get-api/main/learn-list.json>


  ```js
  fetch('https://raw.githubusercontent.com/proven-study/free-json-get-api/main/learn-list.json')
    .then(res => res.json())
    .then(data => console.log(data))
  ```
