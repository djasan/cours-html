# cours-htmlhttps://www.codeur.com/tuto/css/menu-burger-html-css/
/* Sidenav menu */
.sidenav {
  height: 100%;
  width: 250px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: -250px;
  background-color: #e8e8e8;
  padding-top: 60px;
  transition: left 0.5s ease;
}

/* Sidenav menu links */
.sidenav a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: block;
  transition: 0.3s;
}

.sidenav a:hover {
  color: #111;
}

.sidenav ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

/* Active class */
.sidenav.active {
  left: 0;
}

/* Close btn */
.sidenav .close {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
}

/* Icône burger */
.burger-icon span {
  display: block;
  width: 35px;
  height: 5px;
  background-color: black;
  margin: 6px 0;
}

html

<div id="mySidenav" class="sidenav">
  <a id="closeBtn" href="#" class="close">×</a>
  <ul>
    <li><a href="#">A propos</a></li>
    <li><a href="#">Nos services</a></li>
    <li><a href="#">Témoignages</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</div>

<a href="#" id="openBtn">
  <span class="burger-icon">
    <span></span>
    <span></span>
    <span></span>
  </span>
</a>
