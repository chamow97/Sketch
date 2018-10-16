<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<title>Sketch</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
[dir="rtl"] #ipython_notebook {
  float: right !important;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
[dir="rtl"] #tabs li {
  float: right;
}
ul#tabs {
  margin-bottom: 4px;
}
[dir="rtl"] ul#tabs {
  margin-right: 0px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons {
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-right {
  padding-top: 1px;
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-left {
  float: right !important;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
[dir="rtl"] #tree-selector a {
  float: right;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
[dir="rtl"] #new-menu {
  text-align: right;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
[dir="rtl"] #running .col-sm-8 {
  float: right !important;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
	<h1>Sketch</h1>
	<p>A snippet to convert images to pencil sketches. The code is pretty simple and have been attached below.</p>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[110]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">imageio</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">scipy.ndimage</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[111]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">grayscale</span><span class="p">(</span><span class="n">rgb</span><span class="p">):</span>
    <span class="k">return</span> <span class="n">np</span><span class="o">.</span><span class="n">dot</span><span class="p">(</span><span class="n">rgb</span><span class="p">[</span><span class="o">...</span><span class="p">,:</span><span class="mi">3</span><span class="p">],</span> <span class="p">[</span><span class="mf">0.299</span><span class="p">,</span> <span class="mf">0.587</span><span class="p">,</span> <span class="mf">0.114</span><span class="p">])</span>    
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[123]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">img_src</span><span class="o">=</span><span class="s2">&quot;https://qph.fs.quoracdn.net/main-qimg-1ceb3334bfa876de2ff743079328e195&quot;</span>
<span class="n">img</span><span class="o">=</span><span class="n">imageio</span><span class="o">.</span><span class="n">imread</span><span class="p">(</span><span class="n">img_src</span><span class="p">)</span>
<span class="n">gray_image</span><span class="o">=</span><span class="n">grayscale</span><span class="p">(</span><span class="n">img</span><span class="p">)</span>
<span class="n">inverted_image</span><span class="o">=</span><span class="mi">255</span><span class="o">-</span><span class="n">gray_image</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[124]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#blur image</span>
<span class="n">blur_image</span><span class="o">=</span><span class="n">scipy</span><span class="o">.</span><span class="n">ndimage</span><span class="o">.</span><span class="n">filters</span><span class="o">.</span><span class="n">gaussian_filter</span><span class="p">(</span><span class="n">inverted_image</span><span class="p">,</span> <span class="n">sigma</span><span class="o">=</span><span class="mi">5</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[125]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">dodge</span><span class="p">(</span><span class="n">front</span><span class="p">,</span> <span class="n">back</span><span class="p">):</span>
    <span class="n">result</span><span class="o">=</span><span class="n">front</span><span class="o">*</span><span class="mi">255</span><span class="o">/</span><span class="p">(</span><span class="mi">255</span><span class="o">-</span><span class="n">back</span><span class="p">)</span>
    <span class="n">result</span><span class="p">[</span><span class="n">result</span> <span class="o">&gt;</span> <span class="mi">255</span><span class="p">]</span><span class="o">=</span><span class="mi">255</span>
    <span class="n">result</span><span class="p">[</span><span class="n">back</span><span class="o">==</span><span class="mi">255</span><span class="p">]</span><span class="o">=</span><span class="mi">255</span>
    <span class="k">return</span> <span class="n">result</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="s1">&#39;uint8&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[126]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sketched_image</span><span class="o">=</span><span class="n">dodge</span><span class="p">(</span><span class="n">blur_image</span><span class="p">,</span> <span class="n">gray_image</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">sketched_image</span><span class="p">,</span> <span class="n">cmap</span><span class="o">=</span><span class="s2">&quot;gray&quot;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[126]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.image.AxesImage at 0x7fee4dd0ed68&gt;</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
