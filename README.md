@media (max-width: 1440px) and (orientation: portrait) {
  * {
    font-size: 1.5rem;
  }
  .nav-left {
    padding-top: 2.5%;
    flex: 1;
  }
  nav a {
    margin: 0;
    display: block;
  }
  section {
    justify-content: center;
  }
  .card {
    width: 98%;
  }
}

@media (max-width: 1080px) and (orientation: landscape) {
  .nav-left {
    flex: 3;
    padding: 4%;
  }
  nav a {
    margin: 1%;
  }
}

@media (max-width: 768px) and (orientation: landscape) {
  .nav-left {
    flex: 2;
    padding: 3%;
  }
  nav a {
    margin: 1%;
    display: block;
  }
  section {
    justify-content: space-around;
  }
  .card {
    width: 32%;
    margin: 0 .5% 1.5% .5%;
  }
}

@media (max-width: 480px) {
  .nav-left {
    flex: 1;
  }
  .card {
    width: 98%;
  }
}