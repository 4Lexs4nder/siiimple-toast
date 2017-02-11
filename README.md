# siiimple-Toast

**vanilla JS(ES6)**

easily replace console.log and alert in toast message
inspired by material design

## Demo
[https://gomonk3037.github.io/siiimple-Toast/](https://gomonk3037.github.io/siiimple-Toast/)

## Available
IE Edge, Chrome, Opera

## Usage

```javascript

const toast = new siiimpleToast({
  rootElement: 'body'
});

// default message
toast.message('Hello there'); 

// success message
toast.message('Successfully processed');

// alert message
toast.alert('Something seems to be wrong');

```