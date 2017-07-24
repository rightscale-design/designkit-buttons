# Designkit Buttons

## Install

```bash
npm i designkit-buttons --save
```

## Usage

```html
<button class="btn btn-default" type="button">Button</button>

<a href="#" class="btn btn-default">Default Link</a>

<button class="btn btn-default btn-sm" type="button">Small Button</button>

<button class="btn btn-default btn-lg" type="button">Large Button</button>
```

## The CSS

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
  border: 1px solid rgba(27, 31, 35, 0.2);
  border-radius: 2px;
  background-color: #fcfcfc;
  background-image: linear-gradient(#fcfcfc, #eee);
  transition: opacity 0.2s ease-out;
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
  box-shadow: none;
  opacity: .65;
}

.btn {
  border-color: rgba(30, 30, 30, 0.2) rgba(30, 30, 30, 0.2) rgba(0, 0, 0, 0.25);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15);
}

.btn:focus {
  border-color: rgba(30, 30, 30, 0.2) rgba(30, 30, 30, 0.2) rgba(0, 0, 0, 0.25);
}

.btn:hover, .btn:active {
  border-color: rgba(30, 30, 30, 0.35) rgba(30, 30, 30, 0.35) rgba(0, 0, 0, 0.4);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.25), 0 1px 1px rgba(0, 0, 0, 0.15), inset 0 -20px 65px -40px rgba(0, 0, 0, 0.9);
}

.btn:active {
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
  background-color: #fff;
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
  background-color: #0f86f6;
  background-image: linear-gradient(#0f86f6, #0871d4);
}

.btn-primary:hover, .btn-primary:active {
  background-color: #0871d4;
  background-color: #0f86f6;
  background-image: linear-gradient(#0f86f6, #0871d4);
}

.btn-primary:disabled, .btn-primary:disabled:hover, .btn-primary.disabled, .btn-primary.disabled:hover {
  background-color: #0871d4;
  border-color: rgba(20, 20, 20, 0.2);
}

.btn-success {
  color: #fff;
  background-color: #5fb000;
  background-color: #70cf00;
  background-image: linear-gradient(#70cf00, #59a500);
}

.btn-success:hover, .btn-success:active {
  background-color: #5fb000;
  background-color: #6dca00;
  background-image: linear-gradient(#6dca00, #4c8c00);
}

.btn-success:disabled, .btn-success:disabled:hover, .btn-success.disabled, .btn-success.disabled:hover {
  background-color: #5fb000;
  border-color: rgba(20, 20, 20, 0.2);
}

.btn-danger {
  color: #fff;
  background-color: #d82f2f;
  background-color: #d82f2f;
  background-image: linear-gradient(#d82f2f, #b72323);
}

.btn-danger:hover, .btn-danger:active {
  background-color: #d82f2f;
  background-color: #d41414;
  background-image: linear-gradient(#d41414, #a60f0f);
}

.btn-danger:disabled, .btn-danger:disabled:hover, .btn-danger.disabled, .btn-danger.disabled:hover {
  background-color: #d82f2f;
  border-color: rgba(20, 20, 20, 0.2);
}
```

## Author

Jason Melgoza

## License

MIT
