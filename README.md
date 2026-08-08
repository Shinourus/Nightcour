/* ==========================================================
   LORD NÉNUPHAR — THE BONE COLLECTOR
   Royal Court / Dark Moon Theme
   ========================================================== */

/* ---------- COLOURS ---------- */

:root {
    --bone: #ddd8c8;
    --bone-light: #f0ece0;
    --bone-dark: #9d998c;

    --night: #080b12;
    --night-2: #0d121d;
    --night-3: #131b29;

    --blue: #6689a8;
    --blue-light: #9bb8cf;
    --blue-dark: #30465d;

    --green: #718f83;

    --line: rgba(190, 205, 215, 0.25);
    --shadow: rgba(0, 0, 0, 0.75);
}


/* ==========================================================
   PAGE
   ========================================================== */

body {
    background:
        radial-gradient(
            circle at 50% 0%,
            rgba(67, 91, 117, 0.28),
            transparent 45%
        ),
        linear-gradient(
            180deg,
            #05070b 0%,
            #090d15 45%,
            #05070b 100%
        );

    background-attachment: fixed;

    color: var(--bone);

    font-family:
        Georgia,
        "Times New Roman",
        serif;

    text-shadow:
        0 1px 2px #000;
}


/* ==========================================================
   MAIN CONTENT
   ========================================================== */

.container,
#container {
    background: transparent !important;
}


/* ==========================================================
   NAVIGATION
   ========================================================== */

.navbar,
.navbar-default,
#navbar {
    background:
        linear-gradient(
            180deg,
            #111925,
            #080b11
        ) !important;

    border-bottom:
        1px solid var(--line) !important;

    box-shadow:
        0 4px 20px rgba(0,0,0,.65);
}

.navbar a,
.navbar-default .navbar-nav > li > a {
    color: var(--bone) !important;
}

.navbar a:hover {
    color: var(--blue-light) !important;
    text-shadow:
        0 0 8px rgba(130,170,200,.5);
}


/* ==========================================================
   PAGE PANELS
   ========================================================== */

.panel,
.well,
.box,
.thumbnail {

    background:
        linear-gradient(
            145deg,
            rgba(17,24,36,.97),
            rgba(7,10,16,.98)
        ) !important;

    border:
        1px solid var(--line) !important;

    border-radius: 2px !important;

    box-shadow:
        0 8px 25px var(--shadow),
        inset 0 0 30px rgba(90,120,150,.04);
}


/* ==========================================================
   PANEL HEADERS
   ========================================================== */

.panel-heading {

    background:
        linear-gradient(
            90deg,
            #111b29,
            #182638,
            #111b29
        ) !important;

    color: var(--bone-light) !important;

    border-bottom:
        1px solid var(--line) !important;

    text-align: center;

    text-transform: uppercase;

    letter-spacing: 2px;

    font-family:
        Georgia,
        "Times New Roman",
        serif;

    font-weight: bold;

    text-shadow:
        0 0 7px rgba(150,180,205,.25);
}


/* ==========================================================
   TEXT
   ========================================================== */

h1,
h2,
h3,
h4,
h5,
h6 {

    color: var(--bone-light) !important;

    font-family:
        Georgia,
        "Times New Roman",
        serif;

    letter-spacing: 1px;

    text-shadow:
        0 2px 5px #000,
        0 0 10px rgba(100,140,175,.15);
}


p,
li {
    color: var(--bone);
}


/* ==========================================================
   LINKS
   ========================================================== */

a {
    color: var(--blue-light);

    transition:
        color .25s ease,
        text-shadow .25s ease;
}

a:hover {
    color: #d6e5ef;

    text-decoration: none;

    text-shadow:
        0 0 8px rgba(130,180,215,.65);
}


/* ==========================================================
   BUTTONS
   ========================================================== */

.btn,
button,
input[type="submit"] {

    background:
        linear-gradient(
            180deg,
            #1d2d40,
            #0c131e
        ) !important;

    color: var(--bone-light) !important;

    border:
        1px solid rgba(180,200,215,.25) !important;

    border-radius: 2px !important;

    box-shadow:
        0 3px 10px rgba(0,0,0,.5);

    text-shadow:
        0 1px 2px #000;
}

.btn:hover,
button:hover,
input[type="submit"]:hover {

    background:
        linear-gradient(
            180deg,
            #294057,
            #101b28
        ) !important;

    border-color:
        rgba(190,215,235,.5) !important;

    box-shadow:
        0 0 12px rgba(90,140,180,.25);
}


/* ==========================================================
   TABLES — ROYAL ARCHIVES
   ========================================================== */

table {

    background:
        rgba(7,10,16,.75) !important;

    color: var(--bone);

    border-color:
        var(--line) !important;
}

th {

    background:
        linear-gradient(
            180deg,
            #182638,
            #101823
        ) !important;

    color: var(--bone-light) !important;

    text-transform: uppercase;

    letter-spacing: 1px;

    border-color:
        var(--line) !important;
}

td {

    background:
        rgba(10,14,21,.72) !important;

    border-color:
        rgba(190,205,215,.12) !important;
}

tr:hover td {

    background:
        rgba(36,52,70,.55) !important;
}


/* ==========================================================
   FORMS
   ========================================================== */

input,
textarea,
select {

    background:
        #080c13 !important;

    color:
        var(--bone-light) !important;

    border:
        1px solid rgba(170,190,205,.25) !important;

    border-radius: 2px !important;
}

input:focus,
textarea:focus,
select:focus {

    border-color:
        var(--blue) !important;

    box-shadow:
        0 0 8px rgba(90,135,175,.3) !important;

    outline: none;
}


/* ==========================================================
   PROGRESS BARS / STAT ELEMENTS
   ========================================================== */

.progress {

    background:
        #05070b !important;

    border:
        1px solid rgba(180,195,205,.18) !important;

    box-shadow:
        inset 0 2px 6px rgba(0,0,0,.7);
}

.progress-bar {

    background:
        linear-gradient(
            90deg,
            #30475f,
            #7395b1
        ) !important;

    box-shadow:
        0 0 8px rgba(100,150,190,.25);
}


/* ==========================================================
   LION / IMAGE CONTAINERS
   ========================================================== */

img {

    border-color:
        rgba(190,205,215,.18);
}


/* Add a subtle frame to common lion image containers */

.thumbnail img,
.panel-body img {

    filter:
        drop-shadow(0 5px 8px rgba(0,0,0,.65));
}


/* ==========================================================
   DECORATIVE DIVIDERS
   ========================================================== */

hr {

    border: 0;

    border-top:
        1px solid rgba(190,205,215,.22);

    position: relative;

    margin: 25px 0;
}

hr:after {

    content: "☾  ✦  ☽";

    display: block;

    position: relative;

    top: -13px;

    width: 130px;

    margin: auto;

    background: #090d15;

    color: var(--bone-dark);

    text-align: center;

    letter-spacing: 5px;
}


/* ==========================================================
   ALERTS
   ========================================================== */

.alert {

    background:
        rgba(13,19,29,.9) !important;

    color:
        var(--bone) !important;

    border:
        1px solid var(--line) !important;

    border-radius: 2px !important;
}


/* ==========================================================
   BREADCRUMBS
   ========================================================== */

.breadcrumb {

    background:
        rgba(5,8,13,.75) !important;

    border:
        1px solid rgba(190,205,215,.12);

    color:
        var(--bone-dark);
}


/* ==========================================================
   FOOTER
   ========================================================== */

footer {

    background:
        rgba(5,7,11,.95) !important;

    border-top:
        1px solid var(--line);

    color:
        var(--bone-dark);
}


/* ==========================================================
   ROYAL GLOW
   ========================================================== */

.text-primary,
.text-info {

    color:
        var(--blue-light) !important;
}

.text-success {

    color:
        var(--green) !important;
}


/* ==========================================================
   SELECTION
   ========================================================== */

::selection {

    background:
        rgba(95,130,160,.45);

    color:
        #fff;
}


/* ==========================================================
   SCROLLBAR
   ========================================================== */

::-webkit-scrollbar {
    width: 9px;
}

::-webkit-scrollbar-track {

    background:
        #05070b;
}

::-webkit-scrollbar-thumb {

    background:
        #26384b;

    border:
        1px solid #101722;
}

::-webkit-scrollbar-thumb:hover {

    background:
        #3e5870;
}


/* ==========================================================
   ROYAL ATMOSPHERE
   ========================================================== */

body:before {

    content: "☾";

    position: fixed;

    top: 70px;

    right: 35px;

    font-size: 55px;

    color:
        rgba(210,220,220,.07);

    pointer-events: none;

    z-index: 0;
}

body:after {

    content: "♜";

    position: fixed;

    bottom: 25px;

    left: 30px;

    font-size: 42px;

    color:
        rgba(210,220,220,.045);

    pointer-events: none;

    z-index: 0;
}


/* ==========================================================
   THE BONE COLLECTOR
   ========================================================== */

.panel-heading:before {

    content: "✦  ";

    color:
        var(--bone-dark);
}

.panel-heading:after {

    content: "  ✦";

    color:
        var(--bone-dark);
}
