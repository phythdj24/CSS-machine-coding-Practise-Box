# CSS-machine-coding-Practise-Box
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  background-color: aqua;
  border: 2px solid black;
  height: 70vh;
}
.small {
  display: flex;
  justify-content: space-between;
}
.big {
  display: flex;
  justify-content: space-between;
  margin-top: 28vh;
}
.center {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-55%, -120%);
}

.box1 {
  border: 3px solid red;
  height: 20vh;
  width: 20vh;
}
.box2 {
  border: 3px solid rgb(53, 255, 13);
  height: 20vh;
  width: 20vh;
}
.box3 {
  border: 3px solid rgb(0, 140, 255);
  height: 20vh;
  width: 20vh;
}
.box4 {
  border: 3px solid rgb(255, 0, 247);
  height: 20vh;
  width: 20vh;
}
.box5 {
  border: 3px solid rgb(0, 0, 0);
  height: 20vh;
  width: 20vh;
}

