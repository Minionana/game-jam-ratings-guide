<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>ADT’s Guide To Getting Ratings in Jams</title><style>
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

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
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
.highlight-default_background {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray_background {
	background: rgba(248, 248, 247, 1);
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
	background: rgba(248, 243, 252, 1);
}
.highlight-pink_background {
	background: rgba(252, 241, 246, 1);
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
.block-color-default_background {
	color: inherit;
	fill: inherit;
}
.block-color-gray_background {
	background: rgba(248, 248, 247, 1);
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
	background: rgba(248, 243, 252, 1);
}
.block-color-pink_background {
	background: rgba(252, 241, 246, 1);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: undefined; }
.select-value-color-pink { background-color: rgba(225, 136, 179, 0.27); }
.select-value-color-purple { background-color: rgba(168, 129, 197, 0.27); }
.select-value-color-green { background-color: rgba(123, 183, 129, 0.27); }
.select-value-color-gray { background-color: rgba(84, 72, 49, 0.15); }
.select-value-color-transparentGray { background-color: undefined; }
.select-value-color-translucentGray { background-color: undefined; }
.select-value-color-orange { background-color: rgba(224, 124, 57, 0.27); }
.select-value-color-brown { background-color: rgba(210, 162, 141, 0.35); }
.select-value-color-red { background-color: rgba(244, 171, 159, 0.4); }
.select-value-color-yellow { background-color: rgba(236, 191, 66, 0.39); }
.select-value-color-blue { background-color: rgba(93, 165, 206, 0.27); }
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
	
</style></head><body><article id="1ad03a48-9839-8029-a78e-d1802dfd704b" class="page sans"><header><div class="page-header-icon undefined"><img class="icon" src="https://www.notion.so/icons/chart-line_gray.svg"/></div><h1 class="page-title">ADT’s Guide To Getting Ratings in Jams</h1><p class="page-description"></p><table class="properties"><tbody></tbody></table></header><div class="page-body"><blockquote id="1ad03a48-9839-8080-baae-ff93f22627e7" class="block-color-default">Author: <a href="https://youtube.com/@adtdev">ADT</a></blockquote><p id="1ae03a48-9839-80a7-8cdf-e7aa7468d7ad" class="">
</p><p id="1ad03a48-9839-802e-995f-d3b57458dd96" class=""><strong><span style="border-bottom:0.05em solid">Table of Contents</span></strong></p><nav id="1ad03a48-9839-80ca-820b-eda3c0045b4e" class="block-color-default table_of_contents"><div class="table_of_contents-item table_of_contents-indent-0"><a class="table_of_contents-link" href="#1ae03a48-9839-803f-b9ae-c58b003b638b">Introduction</a></div><div class="table_of_contents-item table_of_contents-indent-0"><a class="table_of_contents-link" href="#1ad03a48-9839-8043-84af-da43cc3b2a27">Method 1: Good Game Cover</a></div><div class="table_of_contents-item table_of_contents-indent-0"><a class="table_of_contents-link" href="#1ae03a48-9839-80f5-b80d-ddf368eec28e">Method 2: Rate For Rate</a></div><div class="table_of_contents-item table_of_contents-indent-0"><a class="table_of_contents-link" href="#1ae03a48-9839-8077-a23d-d1cc0ffd5916">Method 3: Engagement Tactics</a></div><div class="table_of_contents-item table_of_contents-indent-0"><a class="table_of_contents-link" href="#1af03a48-9839-803d-ab6f-cebd7a2be98f">Sequence of Application</a></div><div class="table_of_contents-item table_of_contents-indent-0"><a class="table_of_contents-link" href="#1af03a48-9839-8060-be99-db0c88a8c7e4">Final Words</a></div></nav><p id="1ad03a48-9839-80ce-b9d1-fe8b9267a884" class="">
</p><figure class="block-color-blue_background callout" style="white-space:pre-wrap;display:flex" id="1ad03a48-9839-8074-be7b-eabd9e3d42a4"><div style="font-size:1.5em"><img class="icon" src="https://www.notion.so/icons/warning_gray.svg"/></div><div style="width:100%"><p id="1ad03a48-9839-803c-95b6-e0cc9d25461a" class="">Before we start: Please know that an increased number ratings of a game in a game jam does <em>not </em>necessarily positively affect its final ranking, and you shouldn&#x27;t make this all that you care about. More ratings however, does usually mean more comments, thus more feedbacks for your game.</p></div></figure><h2 id="1ae03a48-9839-803f-b9ae-c58b003b638b" class="">Introduction</h2><p id="1ad03a48-9839-8057-96cc-f368aad08231" class="">So, it always feels amazing when you have a high amount of ratings, when so many people have played your game that you&#x27;ve spent hours working on. But sometimes things doesn&#x27;t go this way and your rating count plummets. With a low amount of ratings as compared to others, you wonder what&#x27;s wrong. You wonder, how do I <strong>get more ratings?</strong></p><p id="1ad03a48-9839-807b-9eb8-da9a4fc2f5b6" class="">
</p><p id="1ad03a48-9839-80e9-9f23-d2d6a710df79" class="">In this guide, I&#x27;ll teach my methods to gain ratings. To establish myself as being credible, my game, <em><mark class="highlight-blue"><a href="https://adtdev.itch.io/awef">AWEF</a></mark></em>, has gotten 60 ratings in the <em><mark class="highlight-blue"><a href="https://itch.io/jam/gmtk-2024">GMTK Game Jam 2024</a></mark></em>, whilst my other game, <em><mark class="highlight-blue"><a href="https://adtdev.itch.io/storm-reaper">Storm Reaper</a></mark></em>, has gotten 78 ratings in the <em><mark class="highlight-blue"><a href="https://itch.io/jam/brackeys-12">Brackeys Game Jam 2024.2</a></mark></em>, and finally my game, <em><mark class="highlight-blue"><a href="https://adtdev.itch.io/too-late-to-brake">Too Late To Brake</a></mark></em>, has gotten 116 ratings in the<em><mark class="highlight-blue"> </mark></em><em><mark class="highlight-blue"><a href="https://itch.io/jam/brackeys-13">Brackeys Game Jam 2025.1</a></mark></em>.</p><p id="1ad03a48-9839-80ad-b600-eb6d4c6cd87a" class="">
</p><p id="1ad03a48-9839-80a4-b392-d06f62187d01" class="">Alright, there are a few ways that you can use to gain more ratings. I&#x27;ve used these methods and they&#x27;ve brought the results I mentioned above.</p><p id="1ae03a48-9839-80bd-a8a4-e51b72e8200c" class="">
</p><h2 id="1ad03a48-9839-8043-84af-da43cc3b2a27" class="">Method 1: Good Game Cover</h2><p id="1ad03a48-9839-80be-a80a-d1b933311149" class="">Perhaps one of the most important aspects of your game would be the game cover. After all, this is what others would see when browsing for games.</p><p id="1ae03a48-9839-80d3-b368-e80da01ed509" class="">
</p><div id="1ae03a48-9839-80f1-a73a-ec674c2bb7be" class="column-list"><div id="1ae03a48-9839-80de-9b11-fc8298743ccd" style="width:33.33333333333333%" class="column"><figure id="1ae03a48-9839-80f0-9eb3-fa091719ee5d" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/HiPaint_1726366336553.png"><img style="width:337.99169921875px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/HiPaint_1726366336553.png"/></a><figcaption>Storm Reaper game cover</figcaption></figure></div><div id="1ae03a48-9839-806e-b4f0-ff53610a571a" style="width:33.33333333333333%" class="column"><figure id="1ae03a48-9839-808f-8f33-d661fea29373" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/7a2bf858-cd7d-444a-943d-d274af25e728.png"><img style="width:410.3703703703703px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/7a2bf858-cd7d-444a-943d-d274af25e728.png"/></a><figcaption>Too Late To Brake game cover</figcaption></figure></div><div id="1ae03a48-9839-802f-a2ea-e4b7e721f410" style="width:33.33333333333333%" class="column"><figure id="1ae03a48-9839-8009-9125-c57ff3f3ce1d" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/Cover_V2.png"><img style="width:2625px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/Cover_V2.png"/></a><figcaption>AWEF game cover</figcaption></figure></div></div><p id="1ae03a48-9839-80d3-bb69-c51c4d68ca63" class="">
</p><p id="1ad03a48-9839-808b-9133-e0575e2fb761" class="">Now, it can be difficult determining which covers are considered “good”, but there are a few rules and tips that you could follow. Keep in mind that you don&#x27;t necessarily have to follow everything and there could be outliers that breaks these “rules” and are still good covers. Anyways let&#x27;s begin.</p><p id="1ad03a48-9839-8036-b59b-dae61c253f17" class="">
</p><p id="1ad03a48-9839-805c-b129-cd881d51bb2f" class="">First of all, here&#x27;s a list of <mark class="highlight-red">DON’Ts</mark> that you should ideally <em>not</em> do. </p><figure class="block-color-red_background callout" style="white-space:pre-wrap;display:flex" id="1ae03a48-9839-8077-bd7e-f76ae5964cf2"><div style="font-size:1.5em"><img class="icon" src="https://www.notion.so/icons/exclamation-mark-double_red.svg"/></div><div style="width:100%"><p id="1ad03a48-9839-80d2-8204-f6b4fa4d4192" class="block-color-red">DON’T:</p><ul id="1ad03a48-9839-80e6-bb38-d54b2ff655d0" class="block-color-red bulleted-list"><li style="list-style-type:disc">Use a screenshot as a game cover</li></ul><ul id="1ad03a48-9839-80c3-811f-e0e3ac91ccbe" class="block-color-red bulleted-list"><li style="list-style-type:disc">Use a weird aspect ratio/resolution </li></ul><ul id="1ad03a48-9839-8089-bce9-c89f7b2a9ecb" class="block-color-red bulleted-list"><li style="list-style-type:disc">Put too many elements in the cover</li></ul><ul id="1ad03a48-9839-8094-851b-dc3fae32d6a4" class="block-color-red bulleted-list"><li style="list-style-type:disc">Make elements too small</li></ul></div></figure><p id="1ad03a48-9839-80ed-b992-d3fb97baeb63" class="">
</p><p id="1ad03a48-9839-80ef-bc15-d852beb9e89b" class="">Let&#x27;s expand on each point and show you what you should do instead:</p><p id="1ad03a48-9839-8003-806a-f70e2ebfb652" class="">
</p><ol type="1" id="1ad03a48-9839-80f3-ad5e-e110326d830d" class="numbered-list" start="1"><li><mark class="highlight-red">Don&#x27;t use a screenshot.</mark> <p id="1af03a48-9839-8059-b36f-cd88467d5cf5" class="">Covers using screenshots usually look low-quality and lazy, unless it&#x27;s a really amazing screenshot. You should instead make a cover from scratch either by drawing it from scratch or using assets from the game itself.</p></li></ol><p id="1ad03a48-9839-80f5-a2c2-ccf9a97c5734" class="">
</p><ol type="1" id="1ad03a48-9839-8044-824a-c9d089ceb958" class="numbered-list" start="2"><li><mark class="highlight-red">Don&#x27;t use a weird aspect ratio/resolution.</mark><p id="1af03a48-9839-80a8-a197-f8d78775381f" class="">The cover could look weird when expanded or shrunk to fit itch.io’s size. The recommended resolution is <strong>630x500</strong>, so you should always make your covers with this.</p></li></ol><p id="1ad03a48-9839-8037-919b-c337ad0a7139" class="">
</p><ol type="1" id="1ad03a48-9839-80af-972c-dda46ea80436" class="numbered-list" start="3"><li><mark class="highlight-red">Don&#x27;t put too many elements in the cover.</mark><p id="1af03a48-9839-805f-948e-ce63ef661679" class="">The game cover is <em>small</em> when displayed on itch and if you pack too many things into there, it would be unclear on what to focus on and overall just look… messy. A good rule of thumb is to not have more than 5 elements. </p></li></ol><p id="1ad03a48-9839-80b6-b33e-f898e7d889b7" class="">
</p><ol type="1" id="1ad03a48-9839-8067-95f3-ebc7d03bf4a9" class="numbered-list" start="4"><li><mark class="highlight-red">Don&#x27;t make elements too small.</mark> <p id="1af03a48-9839-804a-bc13-cd22ea43d6d9" class="">Again, game covers are small when displayed on itch, so if you make them too small, people might have to squint to figure out what it is. Most likely, people won&#x27;t even squint if the elements are too small, choosing to ignore it instead. However, the sizes still must not be too big if you want to have more elements to not make it seem packed.</p></li></ol><p id="1ad03a48-9839-809b-83ff-d63e841932bb" class="">
</p><p id="1ad03a48-9839-8047-8abb-e427f067331b" class="">All of these are turn offs for people sometimes, so definitely avoid doing this. Now, we&#x27;ve talked about the <mark class="highlight-red">DON&#x27;Ts</mark> what about the <mark class="highlight-teal">DOs</mark>? How could we get people to <em>stop scrolling</em> and <em>click</em> on our game? How do we make our game cover <em>appealing</em>?</p><p id="1ad03a48-9839-801b-aaf6-e55f9075d111" class="">
</p><figure class="block-color-teal_background callout" style="white-space:pre-wrap;display:flex" id="1ae03a48-9839-80f4-8839-d2ae39c5e678"><div style="font-size:1.5em"><img class="icon" src="https://www.notion.so/icons/checkmark-line_green.svg"/></div><div style="width:100%"><p id="1ad03a48-9839-806c-8edf-d06be6fc3cff" class=""><mark class="highlight-teal">DO:</mark></p><ul id="1ad03a48-9839-804f-9013-c2a4e20d1dec" class="block-color-teal bulleted-list"><li style="list-style-type:disc">Follow the principles of design</li></ul><ul id="1ad03a48-9839-808c-8f23-fb2dacf46936" class="block-color-teal bulleted-list"><li style="list-style-type:disc">Make use of color psychology </li></ul><ul id="1ad03a48-9839-8093-be48-f461279600c6" class="block-color-teal bulleted-list"><li style="list-style-type:disc">Reflect what your game contains</li></ul><ul id="1ad03a48-9839-80c7-a3eb-e237c2037295" class="block-color-teal bulleted-list"><li style="list-style-type:disc">Make it <em>unique</em></li></ul></div></figure><p id="1ad03a48-9839-8037-aa30-cb809d0553d4" class="">
</p><ol type="1" id="1ad03a48-9839-80d2-a5ef-ff436809bf71" class="numbered-list" start="1"><li><mark class="highlight-teal">Follow the </mark><em><mark class="highlight-teal"><a href="https://www.kittl.com/article/the-12-principles-of-design">principles of design</a></mark></em><mark class="highlight-teal">.</mark> <p id="1af03a48-9839-80cf-b236-d1321238bb3a" class="">Positioning of the elements using grids makes the overall layout look neat and natural. Contrast between the point of focus and the background makes the foreground pop. These are just two examples and there&#x27;s more, so give the article linked above a read.</p></li></ol><p id="1ae03a48-9839-809f-8fe9-daa97179a8ff" class="">
</p><ol type="1" id="1ae03a48-9839-80a3-814b-fe6abb8054b8" class="numbered-list" start="2"><li><mark class="highlight-teal">Make use of color psychology.</mark> <p id="1af03a48-9839-801e-8424-e33571e1303f" class="">Think about it: what <em>emotions</em> do you want to evoke in the viewers?</p><figure id="1af03a48-9839-803f-80e7-e722f141185c" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103469.jpg"><img style="width:681.984375px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103469.jpg"/></a><figcaption>https://uxplanet.org/ux-design-colour-psychology-theory-accessibility-40c095cc1077</figcaption></figure><p id="1ae03a48-9839-801d-91a3-de0b9ae9f86b" class="">This can be a really powerful tool that gives your viewer a sense of what your game contains. You could of course also opt for using your game&#x27;s color palette for your cover and that&#x27;s completely acceptable as it gives the players a sense of the style. Just make sure the cover <em>pops</em>.</p></li></ol><p id="1ae03a48-9839-8065-8ffb-cfc2003b1b62" class="">
</p><ol type="1" id="1ae03a48-9839-8088-8ad8-cd8d1a711983" class="numbered-list" start="3"><li><mark class="highlight-teal">Reflect what your game contains.</mark> <p id="1af03a48-9839-8001-924f-c0e9dcd54525" class="">In the above point, I talked about color, and it helps in reflecting your game contents. To expand on this, you could use elements from your game in your thumbnail to further solidify the concept of your game.</p></li></ol><p id="1ae03a48-9839-8069-9bfa-ff3d5b32b930" class="">
</p><ol type="1" id="1ae03a48-9839-80ad-9b9b-c47902ad8793" class="numbered-list" start="4"><li><mark class="highlight-teal">Make it </mark><em><mark class="highlight-teal">unique</mark></em><mark class="highlight-teal">.</mark> <p id="1af03a48-9839-8051-baa6-f65012a18b9a" class="">Now, “unique” can be quite a broad word. It isn&#x27;t simply a fixed definition or rule in most cases. After all, if you follow a rule, would it be unique? But in this case, unique is to simply be <em>different</em>. Research the usual game covers that your game is going to be shown together with. For jams, this usually means jam games. Essentially, you aim to be different from those. However, this can be quite a hard aspect to get right, and oftentimes, “right” is really hard to define. So, you don&#x27;t necessarily need to do this, but of course if you can, go ahead.</p></li></ol><p id="1ae03a48-9839-80aa-b854-ed1ec30c9596" class="">
</p><h2 id="1ae03a48-9839-80f5-b80d-ddf368eec28e" class="">Method 2: Rate For Rate</h2><p id="1ae03a48-9839-8061-b8a1-e385fceaafe9" class="">This method isn’t a pretty one, but hey, it works. So, rate for rate usually involves a person rating another’s game in exchange for a rate. There are a few ways to do this:</p><p id="1ae03a48-9839-8041-bc4e-e9f0459e8984" class="">
</p><ol type="1" id="1ae03a48-9839-80ad-a636-e8dfcc66f293" class="numbered-list" start="1"><li><mark class="highlight-teal">Post in the community tab of the jam.</mark> <p id="1af03a48-9839-80ac-9d41-d2aa31233f65" class="">When you’re posting, be sure to make your title <em>clear and concise</em>. You need to deliver of the message that you’re doing rate for rate fast. After all, you’re competing with hundreds of posts made by others. Here’s an example post:</p><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="1ae03a48-9839-8052-905b-ff853711ce16"><div style="font-size:1.5em"><img class="icon" src="https://www.notion.so/icons/push-pin_gray.svg"/></div><div style="width:100%"><p id="1ae03a48-9839-8011-bd7b-e6a32b1ca46a" class=""><mark class="highlight-gray"><strong>[Title]</strong></mark><mark class="highlight-gray"> </mark></p><p id="1ae03a48-9839-8059-a17b-faa6232502e8" class="">I’ll rate your game if you rate mine!</p><p id="1ae03a48-9839-808f-b60c-e24958e1702f" class=""><mark class="highlight-gray"><strong>[Content]</strong></mark><mark class="highlight-gray"> </mark></p><p id="1ae03a48-9839-8069-97f0-dae24e4b477a" class="">Here’s my game link: &lt;link&gt;</p><p id="1ae03a48-9839-807a-adc3-e0a41fa0d1bc" class="">Please post your game link in the comments so I can check it out. Thanks!</p></div></figure></li></ol><p id="1ae03a48-9839-805f-a71a-e3f2e9e504f8" class="">
</p><ol type="1" id="1ae03a48-9839-8046-8b91-e84d9ad7683c" class="numbered-list" start="2"><li><mark class="highlight-teal">Promote through Discord.</mark><mark class="highlight-default"> </mark><p id="1af03a48-9839-80d1-859c-f2ad435a68f4" class=""><mark class="highlight-default">If the jam has a Discord server, I highly recommend you to join it. Not only is this a good way to interact with the community, it could also be a good place to source for rates. In the jam advertising channel of the server, post a message with your link and make it clear that you’re doing rate for rate:</mark></p><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="1ae03a48-9839-808d-824c-eeba4961d941"><div style="font-size:1.5em"><img class="icon" src="https://www.notion.so/icons/push-pin_gray.svg"/></div><div style="width:100%"><p id="1ae03a48-9839-80a4-84bf-e5d845e0a363" class="">&lt;Promotional text for your game&gt;</p><p id="1ae03a48-9839-803a-b8e6-cb7b6b707ade" class="">I’ll be rating back anyone who rates me, just comment on my game page!</p><p id="1ae03a48-9839-800a-95e0-e4f6df8c9cac" class="">Here’s my game link: &lt;link&gt;</p></div></figure></li></ol><p id="1af03a48-9839-804b-a96b-d57bbcc08cf6" class="">
</p><ol type="1" id="1af03a48-9839-8019-80e1-dc8965108a0d" class="numbered-list" start="3"><li><mark class="highlight-teal">Interact with others&#x27; community posts.</mark><p id="1af03a48-9839-808f-896a-f22594d8e879" class="">So, we talked about posting in the community tab. But instead of waiting for responses, you could also actively post your game links in others&#x27; rate for rate posts and rate their game so that they&#x27;ll rate yours back. This could be more troublesome, but it&#x27;s quite effective too.</p><p id="1af03a48-9839-80dc-a376-e9557c88bfc2" class="">
</p></li></ol><ol type="1" id="1af03a48-9839-80f6-9d80-f080448e378e" class="numbered-list" start="4"><li><mark class="highlight-teal">Rate and comment on others&#x27; games.</mark><p id="1af03a48-9839-801b-9d4f-ce700a05e531" class="">Instead of posting and interacting with posts, another method is to just… rate others&#x27; games and leave a good feedback! The developers might just return this favor of rating without you asking for it. Now, this can be less effective and it&#x27;s not guaranteed to work, as you&#x27;re not requesting for what you want, but you can always give this a shot. After all, it&#x27;s always good to rate others&#x27; games and provide feedback. </p></li></ol><p id="1af03a48-9839-806d-9201-fc791069f1f0" class="">
</p><p id="1ae03a48-9839-8082-b860-ff30ab5b09e3" class="">The rate for rate method is a really fast way to get ratings since a lot of people want ratings for their own games. However, keep in mind that this can get tiring sometimes if you get too many games to rate back, so you could impose a limit, and mention this limit on the post, e.g. I’ll stop rating back once my game reaches 100. This would make sure others would know when to stop. </p><p id="1af03a48-9839-80df-9743-dcc568359250" class="">Finally, please refrain from breaking any promises with this method. Don’t just post this and not rate back or rate the games without playing!</p><h2 id="1ae03a48-9839-8077-a23d-d1cc0ffd5916" class="">Method 3: Engagement Tactics</h2><p id="1ae03a48-9839-80d8-9a21-e48c99e1afa7" class="">This is a pretty powerful method, from what I’ve experienced, and this is the main way I use. Honestly, this method feels the most <em>fun</em> too, so I’d be lying if I said I do this just for the ratings; I do this for fun as well. However, this method does require the jam to have a Discord server, or basically a place to chat.</p><p id="1ae03a48-9839-80f7-878d-c24c823bfd1d" class="">
</p><p id="1ae03a48-9839-8052-b49b-c6dc1f0620bb" class="">Essentially, you’re going to constantly interact with the community (the fun part) and as you do so, you could basically get other more active members of the community to play your game. There are 2 ways that I’ve used to this:</p><p id="1ae03a48-9839-801c-b7f5-e692534ff5ef" class="">
</p><ol type="1" id="1ae03a48-9839-8061-8170-ffde74e153d0" class="numbered-list" start="1"><li><mark class="highlight-teal">Reward engagement.</mark><p id="1ae03a48-9839-8054-810d-d603dceb1c30" class="">This method basically makes use of some sort of achievement that&#x27;s hard to get in your game. Take my game Storm Reaper for example. Whilst chatting in the Brackeys Discord server, the game has established itself to have a reputation of being extremely <em>difficult</em>. </p><figure id="1af03a48-9839-80ea-a7ae-f1c0543dbf47" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/image-11.png"><img style="width:682px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/image-11.png"/></a><figcaption>The bulls tower (one bull on top of another) wasn&#x27;t intended when developing the game.</figcaption></figure><p id="1af03a48-9839-80f1-9826-e1a3eebbd52f" class="">Now, there&#x27;s 5 waves in the game, and it was pretty much <em>nearly</em> impossible to beat. Thus, in the Discord server, I made it clear to others that whoever could beat the game, would receive a virtual cookie 🍪 from me.</p><p id="1af03a48-9839-80af-97c3-ce808e9d8865" class="">I also actively challenged people to beat it in there and made sure to include this “cookie perk” when posting in the jam advertising channels.</p></li></ol><p id="1ae03a48-9839-8018-b1c8-eb2b6903f8a7" class="">
</p><ol type="1" id="1ae03a48-9839-804a-be4c-dd2216a7130d" class="numbered-list" start="2"><li><mark class="highlight-teal">Leaderboard engagement.</mark><p id="1af03a48-9839-8018-bdbd-d7f6dd5c74a0" class="">This method only works if you have some measurement of how well the player did I&#x27;m your game. For instance, a score or a speedrun timer. My game Too Late To Brake had a speedrun timer. And well, some people went crazy getting incredible times.</p><figure id="1af03a48-9839-8078-960e-dc64e7539f80" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103467.png"><img style="width:681.984375px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103467.png"/></a></figure><p id="1af03a48-9839-804d-ac65-c25f27439104" class="">5.9s is astoundingly difficult to get. This player maxed out the upgrades and in total played for probably an hour or so. </p><p id="1af03a48-9839-80dd-9468-c2235f8b0d87" class="">This leaderboard strategy got a lot of people playing Too Late To Brake at one point, with countless images of their times sent in the chat.</p><figure id="1af03a48-9839-80eb-a6d4-d02ee3af425d" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103371.png"><img style="width:681.984375px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103371.png"/></a><figcaption>Leaderboard can be found in my <em><a href="https://discord.gg/TKNuBS7X28">Discord server</a></em></figcaption></figure><p id="1ae03a48-9839-80a0-b507-e54cb26bee68" class="">Well, I can&#x27;t miss the fact that I got kicked out of my own game&#x27;s leaderboard…</p><p id="1af03a48-9839-8073-8cbb-cc7df85f295b" class="">
</p></li></ol><p id="1af03a48-9839-80c7-9703-f4a18bc6c2e0" class="">Both of these methods garnered a lot of plays and rates for my games, and I might be wrong, but believe it was these methods that also gained my game a lot of popularity. If you don&#x27;t know what that is, popularity is essentially an itch sorting metric. My game, Too Late To Brake reached a peak of rank 9 at one point.</p><figure id="1af03a48-9839-8025-bcbd-c6f75ae4abe4" class="image"><a href="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103470.png"><img style="width:338.0000305175781px" src="ADT%E2%80%99s%20Guide%20To%20Getting%20Ratings%20in%20Jams%201ad03a4898398029a78ed1802dfd704b/1000103470.png"/></a><figcaption>Graph generated in <em><a href="https://discord.gg/KDNvKnqjBK">Jamlytics</a></em> Discord server</figcaption></figure><p id="1af03a48-9839-8063-b607-f7ecfa037011" class="">As the game is really high in popularity, people would see it when sorting by popularity in the jam page, thus potentially bringing more rates.</p><p id="1af03a48-9839-80cf-a6a0-dcb9cece88c0" class="">
</p><h2 id="1af03a48-9839-803d-ab6f-cebd7a2be98f" class="">Sequence of Application</h2><p id="1af03a48-9839-80b3-9cc0-c77dfe279b4d" class="">These 3 methods may be good, but if you pair all of them together, it becomes greater. And here&#x27;s my usual sequence of using these methods:</p><ol type="1" id="1af03a48-9839-8070-a1b5-c60308e320a1" class="numbered-list" start="1"><li><mark class="highlight-teal">Good Game Cover</mark> is necessary for people to want to play your game initially, so it needs to come first, ideally being done </li></ol><ol type="1" id="1af03a48-9839-8009-a801-dd07a556928a" class="numbered-list" start="2"><li><mark class="highlight-teal">Rate For Rate</mark> kicks start the influx of ratings, and if you&#x27;re successful enough using this method, there&#x27;s a chance that your game would be pushed to the top ranks of the “most rated” sorting option in itch, potentially bringing more players. </li></ol><ol type="1" id="1af03a48-9839-80f7-9619-e4edc61d3f2b" class="block-color-default numbered-list" start="3"><li><mark class="highlight-teal">Engagement Tactics</mark> can serve as a powerful and fun way if you do it right. But you have to make sure that your game has some sort of quality that makes it unique. Like Storm Reaper’s chaos and broken difficulty balance, or Too Late To Brake’s explosive upgrades.</li></ol><p id="1af03a48-9839-80e1-a5a2-ff38bf2056f9" class="">
</p><h2 id="1af03a48-9839-8060-be99-db0c88a8c7e4" class="">Final Words</h2><p id="1af03a48-9839-8033-96fa-e0c0d470eba0" class="">Again, jams are in the end about having fun and learning, so don&#x27;t overly focus on the ratings. </p><p id="1af03a48-9839-8031-966f-d7a65745e900" class="">Also, just to be clear, I don&#x27;t not guarantee that these methods will work, they&#x27;re just ways that I&#x27;ve discovered to work for my case.</p><p id="1af03a48-9839-8021-b85e-dbb84ba6cbcb" class="">Finally, happy jamming!<br/><br/></p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
