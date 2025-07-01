body {
  background: url('rakhi.gif') no-repeat center center fixed;
  background-size: cover;
}
#start-screen {
  position: fixed;
  background: rgba(0,0,0,0.8);
  display: flex;
  ...
}
#start-screen button {
  background: #ff5c8d;
  border-radius: 8px;
  ...
}
#content {
  opacity: 0;
  transition: opacity 2s ease-in-out;
}
#content.fade-in {
  opacity: 1;
}
