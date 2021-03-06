# designkit-buttons
1.1.1

A Sass module for buttons used in RightScale apps.

## Install
```
npm i --save designkit-buttons
```

## CSS

```css
.btn {
  position: relative;
  display: inline-block;
  -webkit-appearance: none;
  padding: 10px 15px;
  font-size: 13px;
  font-weight: bold;
  line-height: 1;
  color: #444;
  text-decoration: none;
  text-shadow: none;
  white-space: nowrap;
  vertical-align: middle;
  cursor: pointer;
  -webkit-user-select: none;
     -moz-user-select: none;
      -ms-user-select: none;
          user-select: none;
  background-repeat: repeat-x;
  background-position: -1px -1px;
  background-size: 110% 110%;
  background-color: #eee;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#fcfcfc), to(#eee));
  background-image: linear-gradient(#fcfcfc, #eee);
  border: 1px solid rgba(27, 31, 35, 0.2);
  border-radius: 2px;
  -webkit-transition: opacity .2s ease-out;
  transition: opacity .2s ease-out;
}

.btn:focus {
  outline: none;
}

.btn:hover, .btn:active {
  text-decoration: none;
}

.btn:disabled, .btn:disabled:hover, .btn.disabled, .btn.disabled:hover {
  cursor: default;
  cursor: not-allowed;
  background-image: none;
  border-color: rgba(20, 20, 20, 0.2);
  -webkit-box-shadow: none;
          box-shadow: none;
  opacity: .65;
}

.btn {
  border-color: rgba(30, 30, 30, 0.2) rgba(30, 30, 30, 0.2) rgba(0, 0, 0, 0.25);
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15);
          box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15);
}

.btn:focus {
  border-color: rgba(30, 30, 30, 0.2) rgba(30, 30, 30, 0.2) rgba(0, 0, 0, 0.25);
}

.btn:hover, .btn:active {
  border-color: rgba(30, 30, 30, 0.35) rgba(30, 30, 30, 0.35) rgba(0, 0, 0, 0.4);
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15), inset 0 -20px 65px -40px rgba(0, 0, 0, 0.9);
          box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15), inset 0 -20px 65px -40px rgba(0, 0, 0, 0.9);
}

.btn:active {
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1), inset 0 2px 3px rgba(0, 0, 0, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15), inset 0 -20px 65px -40px rgba(0, 0, 0, 0.9);
          box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1), inset 0 2px 3px rgba(0, 0, 0, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15), inset 0 -20px 65px -40px rgba(0, 0, 0, 0.9);
}

.btn.btn-sm {
  padding: 2px 10px;
  font-size: 12px;
  line-height: 20px;
}

.btn.btn-lg {
  padding: 10px 16px;
  font-size: 15px;
  line-height: 1.3333333;
}

.btn-default {
  color: #57626c;
  background-color: #e2e4e6;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#fff), to(#e2e4e6));
  background-image: linear-gradient(#fff, #e2e4e6);
}

.btn-default:hover, .btn-default:active {
  color: #57626c;
}

.btn-default:disabled, .btn-default:disabled:hover, .btn-default.disabled, .btn-default.disabled:hover {
  background-color: #e2e4e6;
  border-color: rgba(20, 20, 20, 0.2);
}

.btn-primary {
  color: #fff;
  background-color: #0871d4;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#0f86f6), to(#0871d4));
  background-image: linear-gradient(#0f86f6, #0871d4);
}

.btn-primary:hover, .btn-primary:active {
  background-color: #0871d4;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#0f86f6), to(#0871d4));
  background-image: linear-gradient(#0f86f6, #0871d4);
}

.btn-primary:disabled, .btn-primary:disabled:hover, .btn-primary.disabled, .btn-primary.disabled:hover {
  background-color: #0871d4;
  border-color: rgba(20, 20, 20, 0.2);
}

.btn-success {
  color: #fff;
  background-color: #5fb000;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#70cf00), to(#59a500));
  background-image: linear-gradient(#70cf00, #59a500);
}

.btn-success:hover, .btn-success:active {
  background-color: #5fb000;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#6dca00), to(#4c8c00));
  background-image: linear-gradient(#6dca00, #4c8c00);
}

.btn-success:disabled, .btn-success:disabled:hover, .btn-success.disabled, .btn-success.disabled:hover {
  background-color: #5fb000;
  border-color: rgba(20, 20, 20, 0.2);
}

.btn-danger {
  color: #fff;
  background-color: #d82f2f;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#d82f2f), to(#b72323));
  background-image: linear-gradient(#d82f2f, #b72323);
}

.btn-danger:hover, .btn-danger:active {
  background-color: #d82f2f;
  background-image: -webkit-gradient(linear, left top, left bottom, from(#d41414), to(#a60f0f));
  background-image: linear-gradient(#d41414, #a60f0f);
}

.btn-danger:disabled, .btn-danger:disabled:hover, .btn-danger.disabled, .btn-danger.disabled:hover {
  background-color: #d82f2f;
  border-color: rgba(20, 20, 20, 0.2);
}

.btn-group {
  display: inline-block;
  vertical-align: middle;
}

.btn-group::before, .btn-group::after {
  display: table;
  content: "";
}

.btn-group .btn {
  position: relative;
  float: left;
}

.btn-group .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}

.btn-group .btn:last-child:not(:first-child) {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0;
}

.btn-group .btn:first-child:not(:last-child) {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0;
}

.btn-group .btn:hover, .btn-group .btn:active {
  z-index: 2;
}

.btn-group .btn + .btn {
  margin-left: -1px;
}

.btn-toolbar {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
  -webkit-box-pack: start;
      -ms-flex-pack: start;
          justify-content: flex-start;
}

```

## Author

Jason Melgoza

## License

MIT
