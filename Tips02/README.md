# FoundationZurbTips - 02

> Alerts with opaque backgrounds and icon fonts..

#### Using .SSCS
```sh
body {
  margin: 5rem 0; //for demo only
  background-image: radial-gradient(
                    circle at top right,
                    #34495E,
                    #999
  );
}

.alert-box.alert {
  border: 3px solid #D91E18;
  border-radius: 5px;
  background-color:rgba(217, 30, 24, 0.2);
}

.alert-box.warning {
  border: 3px solid #D35400;
  border-radius: 5px;
  background-color:rgba(211, 84, 0, 0.2);
}

.alert-box.success {
  border: 3px solid #1E824C;
  border-radius: 5px;
  background-color:rgba(30, 130, 76, 0.2);
}

.alert-box.info {
  border: 3px solid #3498DB;
  border-radius: 5px;
  color: #fff;
  background-color:rgba(52, 152, 219, 0.2);
}

.alert-box {
  i {
    border: 2px solid #fff;
    border-radius: 50%;
    padding: .2em .4em;
    margin-right: 0.8rem;
  }
  .close {
    background: transparent;
    color: #fff;
    font-size: 2rem;
    top: 19px
  }
}
```