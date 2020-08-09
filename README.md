<p align="center">
  <a href="https://quantumalert.cosmogic.com">
    <img alt="SweetAlert" src="https://raw.githubusercontent.com/CosmogicOfficial/QuantumAlert/master/MDfiles/Logoalert.svg" width="200" title="QuantumAlert website">
  </a>
</p>

<p align="center" >
A Powerful , Elegant and fully customizable "alert" library using JavaScript that replaces that boring  style of alert. </p>

<p align="center" title="Licence MIT">

  <a href="https://github.com/CosmogicOfficial/QuantumAlert/blob/master/LICENSE">
    <img src="https://raw.githubusercontent.com/CosmogicOfficial/QuantumAlert/master/MDfiles/LICENCE.svg" />
  </a>

<p align="center">
  <img alt="A success modal" src="https://github.com/CosmogicOfficial/QuantumAlert/blob/master/MDfiles/QuantumAlert.gif?raw=true">
</p>

## Installation

1.  Place the below script tag under the head section in your HTML webpage.

##### For  Simple `white` Theme

```javascript
<script src="https://cdn.jsdelivr.net/gh/cosmogicofficial/quantumalert/minijs/quantumalert.js" charset="utf-8"></script>
```

<h4 align="center">or</h4>

##### For   `Black` Theme

```javascript
<script src="https://cdn.jsdelivr.net/gh/cosmogicofficial/quantumalert/minijs/quantumalertdark.js" charset="utf-8"></script>
```

<h4 align="center">or</h4>

##### For  `DarkBlue` Theme

```javascript
<script src="https://cdn.jsdelivr.net/gh/cosmogicofficial/quantumalert/minijs/quantumalertdarkblue.js" charset="utf-8"></script>
```

<br>

2.  Add the `defer` and `sync` keyword in the  script tag of javascript file in which you want to use `QuantumAlert` library. It improves the performance of library and your webpage.

`For Example`

```javascript
<script src="example.js" charset="utf-8" defer async></script>
```

Here  replace the `example.js` with the name of your `Javascript` file in which you want to use the library.

## Usage

For alert with `success` icon.

```javascript
Qual.success("Hello Heading", "Helllo content", succ);
```

## Guides

-   [Installation](https://quantumalert.cosmogic/#installation)
-   [Getting started](https://quantumalert.cosmogic/#getting-started)
-   [Examples](https://quantumalert.cosmogic/#examples)

## Documentation

-   [Configuration](https://quantumalert.cosmogic/#configuration)
-   [Theming](https://quantumalert.cosmogic/#themeing)

## Examples

##### An `error` message:

```javascript
Qual.error("Oops!", "Something went wrong!", err);
```

##### A `Simple` message:

```javascript
Qual.simple("Hello Cosmogic!");
```

##### A `Simple with Heading` message:

```javascript
Qual.simpleHeading("Hello Cosmogic", "We are here to make coding fun!");
```

#### A customizable `confimation` alert box where you can change`icon`  and also attach a function to the buttons :

```javascript
Qual.confirm(
  "Submitted Successfully",
  "Your File has been uploaded successfully",
   war,
  "Ok",
  "Cancel",
  "hello",
  "max",
);
```

#### A prompt modal, with an `input field` where user can enter `text`,`password` or `number` :

```javascript
Qual.confirm(
  "Are you sure you want to continue",
  "Click Ok button to continue and Cancel to Close",
  succ,
  "OK",
  "Cancel",
  "yes_btn_fun",
  "no_btn_fun",
  "text",
  "Enter your age in this field"
);
```

## Contributing

#### If you're changing the core library:

1.  Make changes in the `Javascript` folder.
2.  Make changes in the JavaScript file `quantumalert.js , quantumalertdark.js ,quantumalertdarkblue.js`.
3.  Submit pull request.

## Built with :heart: using Pure  <img src="https://raw.githubusercontent.com/CosmogicOfficial/QuantumAlert/master/MDfiles/javascript.svg" height="40px"></img> and <img src="https://raw.githubusercontent.com/CosmogicOfficial/QuantumAlert/master/MDfiles/css-3.svg" height="40px"></img>

## Follow us on
<br>
<a href="https://www.instagram.com/cosmogicofficial/"><img src="https://github.com/CosmogicOfficial/QuantumAlert/blob/master/MDfiles/instagram.gif?raw=true" height="100px" style="border-radius:50%;margin-left:20px;"/></a> <a href="https://www.linkedin.com/company/cosmogic/?viewAsMember=true"> <img src="https://github.com/CosmogicOfficial/QuantumAlert/blob/master/MDfiles/linkedin.gif?raw=true" height="100px" style="border-radius:750px;width:100px;margin-left:20px;"/></a><a href="https://twitter.com/wearecosmogic"><img src="https://github.com/CosmogicOfficial/QuantumAlert/blob/master/MDfiles/twitter.gif?raw=true" height="100px" style="border-radius:250px; margin-left:20px;"/></a>

---

## Contributors

You can contribute also if you wish to do so.
 \[[Contribute](https://github.com/cosmogicofficial/quantumalert/graphs/contributors)].
<a href="https://github.com/cosmogicofficial/quantumalert/graphs/contributors"><img src="" /></a>
<br>
<a  href="https://github.com/cosmogicofficial/quantumalert/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=cosmogicofficial/quantumalert" />
</a>
