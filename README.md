<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Plotting the Plot Twists: Mapping Book Bans in Schools Across the USA</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="0ef93862-320f-4822-b4db-d2f348e3cea0" class="page serif"><header><h1 class="page-title">Plotting the Plot Twists: Mapping Book Bans in Schools Across the USA</h1><p class="page-description"></p></header><div class="page-body"><hr id="a83bf72c-2ec8-486d-a13a-cd743567c879"/><p id="c5379867-7d4a-46c2-ae21-6678d1029382" class="">Cecelia Crumlish <br/>05/06/2024<br/></p><h2 id="59ccc15e-873c-4303-bc9d-d7ce15b374e4" class="">Introduction</h2><hr id="d7687f6e-0305-4138-8366-3f2ab996087a"/><p id="21c5140a-acd1-4f9b-8dff-9186d5afa7ce" class=""> Poets, Essayists, and Novelists, an advocacy group for freedom of speech and expression, published an index of School Book Bans in America from 2021 to 2023. The report recorded 5,894 instances of book bans across 41 states and 247 school districts (Baêta, S., &amp; Meehan). From 2021 to 2022, the country has seen an astronomical increase in the number of challenged books, from 223 in 2020 to 2,571 unique titles challenged in 2022.</p><p id="b0ecae85-b77a-4e75-9d19-730e715c57b1" class="">Although PEN’s Index and report of book bans and challenges contain <strong>some</strong> information about bans in the states, there is very little geospatial analysis of trends. My goal with this report is to perform an exploratory analysis of the PEN book ban dataset, along with another more recent dataset from <strong>EveryLibrary</strong>, another popular advocacy group (<em>Book censorship database by dr. Tasslyn Magnusson</em>). My analysis aims to explore trends in the data in terms of the distribution of bans over the location and time axis, in addition to exploring other socioeconomic factors that may be correlated with book bans, such as average income.</p><h2 id="5b8ea308-f407-4f0f-ac61-666ff77c61c9" class="">What is a School Book Ban?</h2><hr id="820d4183-e48d-464e-bf45-53364ed6bc41"/><p id="c9334da7-2543-4aa5-b113-e1e54ba80688" class=""><strong>School Book Ban PEN Definition : </strong></p><blockquote id="1234bb48-6d29-427b-8283-a9a65c43b9f9" class="block-color-orange_background">“any action taken against a book based on its content and as a result of parent or community challenges, administrative decisions, or in response to direct or threatened action by lawmakers or other governmental officials, that leads to a previously accessible book being either completely removed from availability to students, or where access to a book is <strong>restricted</strong> or <strong>diminished</strong>. <strong>Diminished access is a form of censorship and has educational implications that extend beyond a title’s removal</strong>” - (PEN, Baêta, S., &amp; Meehan)</blockquote><div id="932f4dbf-139d-45fa-aedd-5d515a7ad971" class="column-list"><div id="60584043-e2b7-4c53-aeb1-9a6d72a28b1e" style="width:50%" class="column"><p id="9b65eeec-dc0f-4a78-8e05-f20ac678ef77" class=""><strong>Book bans variants (non exhaustive list) : </strong><div class="indented"><ul id="1e02f51b-2c81-4e7d-a19f-b8e88fb8a887" class="bulleted-list"><li style="list-style-type:disc">Prohibitions on books in libraries or Classrooms. </li></ul><ul id="b20887a9-e66e-41f8-a049-d41a4afadec6" class="bulleted-list"><li style="list-style-type:disc">Requiring parental permission. </li></ul><ul id="8d0f7f2b-b6d0-4cfd-a3aa-5a40ab22506f" class="bulleted-list"><li style="list-style-type:disc">Restricted to a higher grade.</li></ul><ul id="ce4fee06-45a9-4479-95a4-b6ff20c560ee" class="bulleted-list"><li style="list-style-type:disc">Removed from review but pending on return (timeline can be undetermined). </li></ul><ul id="46e7d7c0-57a6-4f3d-a7cf-cf7533063214" class="bulleted-list"><li style="list-style-type:disc">Moved to a different section in the library. </li></ul><p id="b6a3d134-fbb8-4433-8ec6-569dcbf0e02f" class="">
</p></div></p></div><div id="bf20ae38-e243-4395-b816-c9cfe717ee71" style="width:50%" class="column"><p id="a5259881-2669-441d-9b35-affe13449fed" class=""><strong>Banning just a single title can have a large impact:</strong></p><ul id="eafd7cf7-5503-4589-b22d-1bd29fb9e640" class="bulleted-list"><li style="list-style-type:disc">Banning one title in one district can mean that hundreds of that title are pulled from libraries and classrooms in that district.</li></ul><p id="777936ad-4aec-4bf4-af41-894bc9b6a1c2" class=""><strong>Who can ban a book?:</strong> </p><ul id="5dd223a0-af75-41a9-9196-b5a6a222c66a" class="bulleted-list"><li style="list-style-type:disc">A ban occurs when school boards, administrators, teachers, or politicians override the book choices of librarians and educators that create curriculums.</li></ul><ul id="01b75cc3-5bbc-4b92-bd0e-b8f30f3c2a6b" class="bulleted-list"><li style="list-style-type:disc">Banning one title in one District can mean that Hundreds of that title are pulled from libraries and classrooms in that district</li></ul><p id="2d3e4d76-20b5-4f3f-bae1-335b9b9790af" class="">
</p></div></div><p id="373f75a3-04bc-4095-b8d8-302a00717fe6" class=""><strong>School Book Challenge Definition: </strong></p><blockquote id="736b6c8b-1364-4bfb-a355-70a7e67a013a" class="block-color-orange_background">“A book challenge is any attempt to restrict or remove a book based on objections to its content. A book ban is the removal or restriction of those materials.” -(PEN, Baêta, S., &amp; Meehan )</blockquote><h2 id="9c05b6aa-ba3d-4bf3-a42d-9d9ab3a088ba" class="">Methods</h2><hr id="e0c251a4-14b5-4ada-a9c8-83a184774034"/><p id="4c1ea594-94cd-4fa9-8fd8-ae52dd3f2fe5" class=""><strong>Cleaning/ Initial Visualizations</strong></p><div id="02bf117b-567e-4492-9156-fb8894a17bd8" class="column-list"><div id="952084e1-e20d-45c5-b9b3-d0bf55160f16" style="width:50%" class="column"><ol type="1" id="90973fde-ce99-4bac-8dc3-d7b03150a2f8" class="numbered-list" start="1"><li>I began by creating a third aggregate dataset of the ‘<em>PEN book bans from 2022-2023’</em>, and 2021-2022 using <strong>excel entry</strong>. </li></ol><ol type="1" id="1b6967d8-26f0-4ea2-898e-1dc2e7661c78" class="numbered-list" start="2"><li>Once I did that I looked to see what the distribution was for the total bans per each state: I noticed that for the most part most of the States had very little bans with 16 of them having 0 as a whole. This is also due to a lack of sampling. Otherwise larger states and some more southern states had a large part of the samples bans with Arkansas leading with largest number of total bans at 1,015 bans total, followed by <strong>Georgia, Wisconsin, Maine, Oklahoma, Pennsylvania, Virginia, Florida, Texas, New York and Rhode island.</strong></li></ol></div><div id="64327236-51e6-416a-a344-b272553e7b93" style="width:50%" class="column"><figure id="f0d868b2-c884-4392-9f33-23bd120b58af" class="image"><a href="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/Distro_total_bans.svg"><img style="width:720px" src="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/Distro_total_bans.svg"/></a><figcaption> As a whole thought the distribution did not follow the normal distribution, more of a logarithmic distribution so I kept this in mind during symbology.</figcaption></figure><p id="41c218c1-31ea-44ed-9154-2cbf42d47c56" class="">
</p></div></div><ol type="1" id="f08c4693-1c6b-40ea-903a-7e4844ec2306" class="numbered-list" start="3"><li> Then I used a python script to clean  the data and<strong> create  summary tables </strong>for the totals of each ban entry for each State/District using the fields described in the Methods Section  for the PEN dataset. </li></ol><ol type="1" id="fe0aefe1-e770-4212-852e-4a9f96c5b80d" class="numbered-list" start="4"><li>Once I had the summary tables describing the number of total banned books and the most banned book for each geographic resolution (State, and School Districts in Florida). I joined each summary with its corresponding census shape file in ArcGis using the <strong>Join</strong> method <em>&#x27;U.S. Census State Boundaries 2018 ’</em> and<em> &#x27;Florida School Districts 2018’</em>  . </li></ol><ol type="1" id="d9e3cda3-1565-4181-9a02-345e63ac5846" class="numbered-list" start="5"><li>I chose to <strong>normalize</strong> using the number of total districts per state, in order  to do this I joined ‘<em>Total School District Enrollment, and School Districts per each state 2013-2014’  </em>to each layer. I chose to normalize this way because bans are executed at the school district level for the PEN dataset. For example one state can have many bans of the same book as it is multiple different school districts with this ban. </li></ol><ol type="1" id="7eb62013-668c-4667-b36d-6be0466d791f" class="numbered-list" start="6"><li>Once I had everything in a table For Florida School Districts, and for States for 2021-2022, and 2022-2023, and 2021-2023, I used graduated symbology to display the number of books. When symbolizing I did custom formula: Sum Total Bans / Total Districts Per State. </li></ol><p id="92f244a6-9316-4218-bf4d-4d0bb2f702b0" class="">
</p><h1 id="5d865aa5-6b1e-4b6a-baf2-4ab1c4392168" class="">Initial Visualizations</h1><hr id="bf6a2da3-8aa8-4eb1-90dc-c04f3feadaa7"/><figure id="ef8608b5-6779-4f7a-b4be-753d1b27e9f2" class="image"><a href="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/FIN_AVG_BANS_NO_LABELS.png"><img style="width:1248px" src="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/FIN_AVG_BANS_NO_LABELS.png"/></a></figure><p id="b2ee8c2c-bc23-4b38-b63a-b0596aef4cc7" class=""><strong>Results:<br/> <br/></strong>The first map of average bans, illustrates an overall tend of the number of bans growing over the course of 2 years. With the average bans per district  increasing over that period of time. Notable takeaways: average bans per district for California, Oregon, Colorado, Minnesota, and Michigan all became greater than zero. Florida, Georgia, and Wisconsin all increased their total bans per District to become greater than 2. Additionally the map saw increased data coverage in Alaska. </p><figure id="41c73c71-f69e-4dad-8745-10c3c5648201" class="image"><a href="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/aggregate_and_florida.png"><img style="width:1248px" src="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/aggregate_and_florida.png"/></a><figcaption>Fig 2. Visualization at State and School District Level</figcaption></figure><h2 id="52158957-fd0f-4818-b778-179bab596c64" class=""><strong>Visualizing over Demographic Factors </strong></h2><hr id="4413426d-793d-4ee7-9d35-05636507f3ce"/><ol type="1" id="955f9af4-c36e-4138-953c-bc264d32e383" class="numbered-list" start="1"><li>To visualize over demographic factors for all the states, I joined<span style="border-bottom:0.05em solid"> </span><em><span style="border-bottom:0.05em solid">‘ACS financial Demographics Median Income Data’</span></em> with the existing State map of the aggregate bans 2021-2023.</li></ol><ol type="1" id="c6819145-ecb0-450b-a495-e296038b76cb" class="numbered-list" start="2"><li>After Cleaning and joining  together the data, I was able to add demographic factors on to the Datasets. I chose to look at the median income per each state and the number of bans.</li></ol><ol type="1" id="3c2127ad-eb47-4711-8833-554379164f5e" class="numbered-list" start="3"><li>To do this I used a spatial join with the<span style="border-bottom:0.05em solid"> </span><em><span style="border-bottom:0.05em solid">‘ACS Financial Demographics for Medium Income Data</span></em><span style="border-bottom:0.05em solid">’</span>. </li></ol><ol type="1" id="223f0bb1-b07d-4bb6-b7c1-f87c945c0a3f" class="numbered-list" start="4"><li>After the join I symbolized over the demographic information and the average of bans per district using a bivariate color scheme, resulting in this graphic. <figure id="517feccb-9258-4fcb-8b98-a647109d7990" class="image"><a href="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/final_bivariate.png"><img style="width:3300px" src="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/final_bivariate.png"/></a></figure></li></ol><p id="f5163223-7851-42cb-99aa-0dbb1a54125b" class=""><strong>Results: </strong>Of the whole there was only 1 low income high ban state which was Arkansas. There were 7 low ban low income states. Notably the high income high ban states only included Rhode Island. There were only 2 median income high ban states which were Florida and Georgia. And the high income median ban states included: Alaska, Virginia and Maryland.  </p><figure id="da46c578-1f7e-4817-b2b4-e08d036fce52" class="image"><a href="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/Most_banned_state.png"><img style="width:1200px" src="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/Most_banned_state.png"/></a><figcaption>Title of the Most Banned Book per Each State 2021-2023 over the Average Bans  per School District Per State </figcaption></figure><figure id="b651922e-ca73-4498-b229-66e2b95e1f94" class="image"><a href="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/Most_banned.svg"><img style="width:1248px" src="Plotting%20the%20Plot%20Twists%20Mapping%20Book%20Bans%20in%20Scho%200ef93862320f4822b4dbd2f348e3cea0/Most_banned.svg"/></a><figcaption>Sum of the Most Banned Books for each State</figcaption></figure><p id="8f80b693-62d9-4f48-9138-0d2c7ef6a200" class=""><strong>Above is a map of the most Banned books per State:</strong>  To the side is a diagram of the most banned book for each state. Notably ‘Gender Queer: A Memoir’ made up 17% of the most banned books per each state. Followed by the ‘Absolutely True Diary of a Part time Indian’ at 9.8%. of the most banned books per state. </p><p id="927c2b80-b0db-4829-a431-a3bd57ad9784" class=""><strong>Note</strong>: If there was a tie the alphabetically highest book would be chosen as the most banned book for each state. </p><h2 id="6970c814-8faa-454f-85cc-b8b83d61d884" class="">Discussion / Limitations </h2><hr id="8499f18c-397e-482b-9ba8-4351f71aa6e8"/><p id="7e5ba825-45d1-47c5-99bd-9dc043acdab8" class=""><strong>Data Limitations: </strong></p><p id="a067611d-d377-438b-a6da-b74753637561" class="">Through the whole projects the largest hurdle has been resolving location data, with the<span style="border-bottom:0.05em solid"> Magnussun Dataset</span>. I tried many different things to resolve the District names to actual School Districts, manually changing the strings according to trends I was noticing, or just trying to see how many matched already, but whatever I did I couldn’t resolve enough entries to school districts to make meaningful geographic information. </p><p id="60390e16-4331-4b8f-8f0d-172e13127ec4" class="">I was able to reconcile some of the problems with the Magnussen dataset  to the PEN Index ban’s dataset as it had better documentation for methods of obtainment and had properly  formatted location fields. Even so,  I needed to re-process the data  to format it for GIS, but I still wasn’t able to resolve School Districts to locations, except for a few states (namely Florida). </p><p id="faa93966-adc8-4d26-899a-43f3d0d361cd" class=""><strong>Model limitations: </strong></p><p id="695a0a5b-1687-40a1-9d71-ecf3a8a7ede3" class="">Because the geographic resolution had to be generalized to State level, states with more school districts (larger student populations) had skewed bans. In order to fix this I normalized over the <strong>total number of districts</strong> per each state but resolution was still lost. Normalizing over total districts was the choice I made, but the arguments could be made for normalizing over student populations, or general populations.  For example: normalizing over student populations could offer a more accurate representation of the impact on students, as it accounts for the actual number of individuals affected. This method may reveal disparities in how bans are distributed across states with varying student populations. Normalizing over general populations could further contextualize the data within the broader demographic landscape, highlighting potential socioeconomic and demographic factors influencing the bans.</p><p id="4889fa62-17a5-4929-9d85-53a5750d5dd5" class=""><strong>Many books in a single ban? : </strong>Depending on the district and how many books are in that district, a single ban could entail multiple hundred books of a single title coming off of shelves. There is nothing in the data that I could get to account for the total number of books or schools affected by a ban. </p><p id="2840e2ac-0be5-4ba4-afc9-6ffe58c8112a" class=""> <strong>Further work that could be done:</strong> If more time had allowed I would have liked to have resolved School Districts for more of the counties to be able to do an interpolation analysis of the trend of banned books. And also possibly a hotspot analysis. I was also toying with the idea of tagging the genre of the books and doing a visualization of the occurrences of the bans and their genres. </p><h2 id="9ed44626-1f88-493e-bd2c-9ff806bea404" class="">Conclusions </h2><hr id="14d5a654-1a42-4859-8fa7-d00198c1aef0"/><p id="7010689f-65f1-445f-90e5-5efb2c0b7630" class="">Despite these limitations, the analysis provides valuable insights into the troubling phenomenon of book bans in American schools. The observed increase in bans over the study period underscores the urgent need to protect intellectual freedom and promote diverse perspectives in education centering People of Color and Trans People. Including furthering the  protection of speech in schools, and for the decisions of school librarians and educators to be trusted. </p><p id="b0038ace-70a8-4ff1-b6b3-507afff977fa" class="">
</p><h2 id="b8e580a9-c36d-4d5a-a9fa-20293abb4640" class="">Source Scripts: </h2><hr id="5189d88b-7294-47fa-91ac-735eee2534ac"/><p id="4b87e147-39f6-4ff1-b871-8ac2d53e04b2" class="">
</p><h2 id="9f75e2c8-cddc-42e9-9d63-51427316c7f4" class="">Data and Data Sources </h2><hr id="3425a851-66c1-40b9-b819-5d3387381746"/><table id="070cc60d-c748-4b0f-98f5-b0588c0e6ef2" class="simple-table"><thead class="simple-table-header"><tr id="5964368c-1ca8-4cd5-b3ad-946cb306c9d2"><th id="Syvo" class="simple-table-header-color simple-table-header" style="width:211.7867431640625px"><strong>Data Source Name</strong></th><th id="yylq" class="simple-table-header-color simple-table-header" style="width:168.7867431640625px"><strong>Source authors</strong></th><th id="&lt;vBA" class="simple-table-header-color simple-table-header" style="width:303.8007080078125px"><strong>Data Source Link</strong></th><th id="^^Ka" class="simple-table-header-color simple-table-header" style="width:247.7867431640625px"><strong>Data format (Polygon, Vector, Point)</strong></th><th id="JJO_" class="simple-table-header-color simple-table-header" style="width:539.7463073730469px"><strong>Description</strong></th></tr></thead><tbody><tr id="7b0b3769-eba7-4b1e-8bb5-88970d23d2a6"><td id="Syvo" class="" style="width:211.7867431640625px">2023 Censorship Attacks Book Bans In America</td><td id="yylq" class="" style="width:168.7867431640625px">Dr. Tasslyn Magnusson</td><td id="&lt;vBA" class="" style="width:303.8007080078125px"><a href="https://docs.google.com/spreadsheets/d/1am1vKU3MR1209AanJVqySFtRYe3IiB1k/edit#gid=2126860040">https://docs.google.com/spreadsheets/d/1am1vKU3MR1209AanJVqySFtRYe3IiB1k/edit#gid=2126860040</a></td><td id="^^Ka" class="" style="width:247.7867431640625px">.XLSM table</td><td id="JJO_" class="" style="width:539.7463073730469px">A larger less-structured report of book bans from 2021-2024.  </td></tr><tr id="31ea00b8-9188-4e96-a610-6b8aa221d024"><td id="Syvo" class="" style="width:211.7867431640625px">PEN Index of Banned Books Dataset 2022-23</td><td id="yylq" class="" style="width:168.7867431640625px">PEN</td><td id="&lt;vBA" class="" style="width:303.8007080078125px"></td><td id="^^Ka" class="" style="width:247.7867431640625px">google spreadsheet, .csv file </td><td id="JJO_" class="" style="width:539.7463073730469px">Semi large structured data report of book bans in the U.S. from 2022 to 2023. </td></tr><tr id="986a3c8c-3681-4ee6-afd9-e31d66ff4443"><td id="Syvo" class="" style="width:211.7867431640625px">PEN Index of Banned books Dataset 2021-22</td><td id="yylq" class="" style="width:168.7867431640625px">PEN </td><td id="&lt;vBA" class="" style="width:303.8007080078125px"></td><td id="^^Ka" class="" style="width:247.7867431640625px">google spreadsheet, .xlsm file</td><td id="JJO_" class="" style="width:539.7463073730469px">Semi large structured data report of book bans in the U.S. from 2021 to 2022.</td></tr><tr id="c2934dab-f9c8-44b1-877b-7e2716d8619d"><td id="Syvo" class="" style="width:211.7867431640625px">Florida School Districts</td><td id="yylq" class="" style="width:168.7867431640625px">US Census</td><td id="&lt;vBA" class="" style="width:303.8007080078125px"><a href="https://www.fldoe.org/accountability/data-sys/school-dis-data/">https://www.fldoe.org/accountability/data-sys/school-dis-data/</a></td><td id="^^Ka" class="" style="width:247.7867431640625px">.SHP File</td><td id="JJO_" class="" style="width:539.7463073730469px">Shape file for Florida’s school districts. </td></tr><tr id="201c4f98-4aaf-4980-ba28-4bc58f307c7e"><td id="Syvo" class="" style="width:211.7867431640625px">Financial Demographics for Medium Income</td><td id="yylq" class="" style="width:168.7867431640625px">US Census ACS</td><td id="&lt;vBA" class="" style="width:303.8007080078125px"><a href="https://data.census.gov/table/ACSST1Y2022.S2503?q=acs%20income&amp;g=010XX00US$0400000">https://data.census.gov/table/ACSST1Y2022.S2503?q=acs%20income&amp;g=010XX00US$0400000</a></td><td id="^^Ka" class="" style="width:247.7867431640625px">.xlsm file</td><td id="JJO_" class="" style="width:539.7463073730469px">To join with state information for bivariate map.</td></tr><tr id="9e183382-d581-499d-a0c0-7b207b53d3de"><td id="Syvo" class="" style="width:211.7867431640625px">SAIPE (Small Area Income and Poverty Estimates) Projection for 2022</td><td id="yylq" class="" style="width:168.7867431640625px">US Census SAIPE</td><td id="&lt;vBA" class="" style="width:303.8007080078125px"><a href="https://www.census.gov/data/datasets/2022/demo/saipe/2022-school-districts.html">https://www.census.gov/data/datasets/2022/demo/saipe/2022-school-districts.html</a></td><td id="^^Ka" class="" style="width:247.7867431640625px">.xlsm file </td><td id="JJO_" class="" style="width:539.7463073730469px">Provides the total population of students in a given county and the total living in poverty in that county, used to get percentage portion of students in poverty ages 5-17. </td></tr><tr id="8ced792c-75e9-4b13-a488-8890cddddf1a"><td id="Syvo" class="" style="width:211.7867431640625px">Total School District Enrollment, and School Districts per each state 2013-2014</td><td id="yylq" class="" style="width:168.7867431640625px">Governing Advocacy Group, aggregate of data from the National Center of Education Statistics survey <strong>Local Education Agency Universe Survey </strong></td><td id="&lt;vBA" class="" style="width:303.8007080078125px">aggregated analysis of this dataset <a href="https://nces.ed.gov/ccd/pubagency.asp">https://nces.ed.gov/ccd/pubagency.asp</a> from this advocacy group here: <a href="https://www.governing.com/archive/school-district-totals-average-enrollment-statistics-for-states-metro-areas.html">https://www.governing.com/archive/school-district-totals-average-enrollment-statistics-for-states-metro-areas.html</a></td><td id="^^Ka" class="" style="width:247.7867431640625px">copied into a .csv file via excel </td><td id="JJO_" class="" style="width:539.7463073730469px">Table of the total School District enrollment and number of school districts per each state. </td></tr><tr id="c86b0ebe-0529-4a69-aa9b-03008d970d13"><td id="Syvo" class="" style="width:211.7867431640625px">U.S. Census State Boundaries 2018 </td><td id="yylq" class="" style="width:168.7867431640625px">US Census 2018</td><td id="&lt;vBA" class="" style="width:303.8007080078125px"><strong>US Census Tiger and Shape files: </strong><strong><a href="https://www2.census.gov/geo/tiger/GENZ2018/shp/cb_2018_us_state_500k.zip">cb_2018_us_state_500k.zip [3.2 MB]</a></strong></td><td id="^^Ka" class="" style="width:247.7867431640625px">.shp </td><td id="JJO_" class="" style="width:539.7463073730469px">Shape file from the U.S. Census of current State boundaries </td></tr></tbody></table><h2 id="17c070e9-95f0-45e3-8b96-12b50c4df66e" class="">References </h2><hr id="87f131b1-ddaa-4b39-8d71-736e02e37805"/><p id="d05a5f4e-77b3-4c62-89ac-9e3788c98867" class="">Baêta, S., &amp; Meehan, K. (2023, December 13). <em>Spineless shelves: Two years of Book banning</em>. PEN America. https://pen.org/spineless-shelves/</p><p id="d8e0f1aa-386c-4cb4-aa41-d0f00716cd26" class="">
</p><p id="41726229-54c5-4e84-8aee-13b6e8ecb78f" class=""><em>Book censorship database by dr. Tasslyn Magnusson</em>. EveryLibrary Institute. (n.d.). https://www.everylibraryinstitute.org/book_censorship_database_magnusson</p><p id="3d0d2857-ee90-4778-8013-e9655f8effcf" class="">
</p><p id="2d6d9179-0a42-4c3d-b103-bfd78ffc9136" class="">Google. (n.d.-a). <em>PEN America’s Index of School Book bans (July 1, 2021 - June 30, 2022)</em>. Google Sheets. </p><p id="65d333cb-af60-426a-ada3-97e073ddb6e2" class="">https://docs.google.com/spreadsheets/d/1hTs_PB7KuTMBtNMESFEGuK-0abzhNxVv4tgpI5-iKe8/edit#gid=1397437044</p><p id="fa6a70de-ed86-44db-9ce0-cf35d1184e83" class="">
</p><p id="a3068d0e-cc4f-477e-a7cf-c178947a5e31" class="">Google. (n.d.-b). <em>PEN America’s Index of School Book bans (July 1, 2021 - June 30, 2022)</em>. Google Sheets. https://docs.google.com/spreadsheets/d/1hTs_PB7KuTMBtNMESFEGuK-0abzhNxVv4tgpI5-iKe8/edit#gid=1263265416</p><p id="bc7effaf-6469-4668-a233-9c00e06d2711" class="">
</p><p id="3f3ce36c-2037-4ba4-bd24-afbb2605afcb" class=""><em>What is a book Ban? and more frequently asked questions</em>. PEN America. (2024, April 15). https://pen.org/book-bans-frequently-asked-questions/</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>





## Plotting the Plot Twists 

This Repo Contains: 

1. The final HTML report

1. Two folders for one for each of the Book Bans Data bases. Each contain:

  * cleaned data: data that is the result of the cleaning and summarizing scripts
  *  data: the original table of bans
  * A juypter notebook: contains seperate scripts and Markdown information, about how they are run



