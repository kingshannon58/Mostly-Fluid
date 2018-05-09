# Mostly-Fluid
Project for school that I had to make the colors take a certain percentage of the page. 
<html lang="en">
  <head>
    <title>Mostly Fluid - Quiz</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style type="text/css">
      /*
      These are the default styles. No need to change these.
      */
      @import url(https://fonts.googleapis.com/css?family=Roboto);
      html, body {
        margin: 0;
        padding: 0;
      }

      body {
        font-family: 'Roboto', sans-serif;
      }

      .title {
        font-size: 2.5em;
        text-align: center;
      }

      .box {
        min-height: 150px;
      }

      .dark_blue {
        background-color: #2A457A;
        color: #efefef;
      }

      .light_blue {
        background-color: #099DD9;
      }

      .green {
        background-color: #0C8542;
      }

      .lime {
        background-color: rgb(179, 210, 52);
      }

      .seafoam {
        background-color: rgb(77, 190, 161);
      }

      .red {
        background-color: #EC1D3B;
      }

      .orange {
        background-color: #F79420;
      }
    </style>
    <style type="text/css">
      /*
      These are the responsive styles. Throw some breakpoints in here!
      */
      .container {
        display: flex;
        flex-wrap: wrap;
      }

      .box {
        width: 50%;
      }

      @media screen and (max-width: 450px) {
        .light_blue, .green {
          width: 50%;
        }
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="box dark_blue"></div>
      <div class="box light_blue"></div>
      <div class="box green"></div>
      <div class="box red"></div>
      <div class="box orange"></div>
    </div>
  </body>
</html>
