<!DOCTYPE html>
<html>
  <head>
      <meta charset="utf-8" />
      <title>L12</title>
      <style>.markdown-preview:not([data-use-github-style]) { padding: 2em; font-size: 1.2em; color: rgb(171, 178, 191); background-color: rgb(40, 44, 52); overflow: auto; }
.markdown-preview:not([data-use-github-style]) > :first-child { margin-top: 0px; }
.markdown-preview:not([data-use-github-style]) h1, .markdown-preview:not([data-use-github-style]) h2, .markdown-preview:not([data-use-github-style]) h3, .markdown-preview:not([data-use-github-style]) h4, .markdown-preview:not([data-use-github-style]) h5, .markdown-preview:not([data-use-github-style]) h6 { line-height: 1.2; margin-top: 1.5em; margin-bottom: 0.5em; color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) h1 { font-size: 2.4em; font-weight: 300; }
.markdown-preview:not([data-use-github-style]) h2 { font-size: 1.8em; font-weight: 400; }
.markdown-preview:not([data-use-github-style]) h3 { font-size: 1.5em; font-weight: 500; }
.markdown-preview:not([data-use-github-style]) h4 { font-size: 1.2em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) h5 { font-size: 1.1em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) h6 { font-size: 1em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) strong { color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) del { color: rgb(124, 135, 156); }
.markdown-preview:not([data-use-github-style]) a, .markdown-preview:not([data-use-github-style]) a code { color: rgb(82, 139, 255); }
.markdown-preview:not([data-use-github-style]) img { max-width: 100%; }
.markdown-preview:not([data-use-github-style]) > p { margin-top: 0px; margin-bottom: 1.5em; }
.markdown-preview:not([data-use-github-style]) > ul, .markdown-preview:not([data-use-github-style]) > ol { margin-bottom: 1.5em; }
.markdown-preview:not([data-use-github-style]) blockquote { margin: 1.5em 0px; font-size: inherit; color: rgb(124, 135, 156); border-color: rgb(75, 83, 98); border-width: 4px; }
.markdown-preview:not([data-use-github-style]) hr { margin: 3em 0px; border-top: 2px dashed rgb(75, 83, 98); background: none; }
.markdown-preview:not([data-use-github-style]) table { margin: 1.5em 0px; }
.markdown-preview:not([data-use-github-style]) th { color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) th, .markdown-preview:not([data-use-github-style]) td { padding: 0.66em 1em; border: 1px solid rgb(75, 83, 98); }
.markdown-preview:not([data-use-github-style]) code { color: rgb(255, 255, 255); background-color: rgb(58, 63, 75); }
.markdown-preview:not([data-use-github-style]) pre.editor-colors { margin: 1.5em 0px; padding: 1em; font-size: 0.92em; border-radius: 3px; background-color: rgb(49, 54, 63); }
.markdown-preview:not([data-use-github-style]) kbd { color: rgb(255, 255, 255); border-width: 1px 1px 2px; border-style: solid; border-color: rgb(75, 83, 98) rgb(75, 83, 98) rgb(62, 68, 81); border-image: initial; background-color: rgb(58, 63, 75); }
.markdown-preview[data-use-github-style] { font-family: "Helvetica Neue", Helvetica, "Segoe UI", Arial, freesans, sans-serif; line-height: 1.6; word-wrap: break-word; padding: 30px; font-size: 16px; color: rgb(51, 51, 51); background-color: rgb(255, 255, 255); overflow: scroll; }
.markdown-preview[data-use-github-style] > :first-child { margin-top: 0px !important; }
.markdown-preview[data-use-github-style] > :last-child { margin-bottom: 0px !important; }
.markdown-preview[data-use-github-style] a:not([href]) { color: inherit; text-decoration: none; }
.markdown-preview[data-use-github-style] .absent { color: rgb(204, 0, 0); }
.markdown-preview[data-use-github-style] .anchor { position: absolute; top: 0px; left: 0px; display: block; padding-right: 6px; padding-left: 30px; margin-left: -30px; }
.markdown-preview[data-use-github-style] .anchor:focus { outline: none; }
.markdown-preview[data-use-github-style] h1, .markdown-preview[data-use-github-style] h2, .markdown-preview[data-use-github-style] h3, .markdown-preview[data-use-github-style] h4, .markdown-preview[data-use-github-style] h5, .markdown-preview[data-use-github-style] h6 { position: relative; margin-top: 1em; margin-bottom: 16px; font-weight: bold; line-height: 1.4; }
.markdown-preview[data-use-github-style] h1 .octicon-link, .markdown-preview[data-use-github-style] h2 .octicon-link, .markdown-preview[data-use-github-style] h3 .octicon-link, .markdown-preview[data-use-github-style] h4 .octicon-link, .markdown-preview[data-use-github-style] h5 .octicon-link, .markdown-preview[data-use-github-style] h6 .octicon-link { display: none; color: rgb(0, 0, 0); vertical-align: middle; }
.markdown-preview[data-use-github-style] h1:hover .anchor, .markdown-preview[data-use-github-style] h2:hover .anchor, .markdown-preview[data-use-github-style] h3:hover .anchor, .markdown-preview[data-use-github-style] h4:hover .anchor, .markdown-preview[data-use-github-style] h5:hover .anchor, .markdown-preview[data-use-github-style] h6:hover .anchor { padding-left: 8px; margin-left: -30px; text-decoration: none; }
.markdown-preview[data-use-github-style] h1:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h2:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h3:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h4:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h5:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h6:hover .anchor .octicon-link { display: inline-block; }
.markdown-preview[data-use-github-style] h1 tt, .markdown-preview[data-use-github-style] h2 tt, .markdown-preview[data-use-github-style] h3 tt, .markdown-preview[data-use-github-style] h4 tt, .markdown-preview[data-use-github-style] h5 tt, .markdown-preview[data-use-github-style] h6 tt, .markdown-preview[data-use-github-style] h1 code, .markdown-preview[data-use-github-style] h2 code, .markdown-preview[data-use-github-style] h3 code, .markdown-preview[data-use-github-style] h4 code, .markdown-preview[data-use-github-style] h5 code, .markdown-preview[data-use-github-style] h6 code { font-size: inherit; }
.markdown-preview[data-use-github-style] h1 { padding-bottom: 0.3em; font-size: 2.25em; line-height: 1.2; border-bottom: 1px solid rgb(238, 238, 238); }
.markdown-preview[data-use-github-style] h1 .anchor { line-height: 1; }
.markdown-preview[data-use-github-style] h2 { padding-bottom: 0.3em; font-size: 1.75em; line-height: 1.225; border-bottom: 1px solid rgb(238, 238, 238); }
.markdown-preview[data-use-github-style] h2 .anchor { line-height: 1; }
.markdown-preview[data-use-github-style] h3 { font-size: 1.5em; line-height: 1.43; }
.markdown-preview[data-use-github-style] h3 .anchor { line-height: 1.2; }
.markdown-preview[data-use-github-style] h4 { font-size: 1.25em; }
.markdown-preview[data-use-github-style] h4 .anchor { line-height: 1.2; }
.markdown-preview[data-use-github-style] h5 { font-size: 1em; }
.markdown-preview[data-use-github-style] h5 .anchor { line-height: 1.1; }
.markdown-preview[data-use-github-style] h6 { font-size: 1em; color: rgb(119, 119, 119); }
.markdown-preview[data-use-github-style] h6 .anchor { line-height: 1.1; }
.markdown-preview[data-use-github-style] p, .markdown-preview[data-use-github-style] blockquote, .markdown-preview[data-use-github-style] ul, .markdown-preview[data-use-github-style] ol, .markdown-preview[data-use-github-style] dl, .markdown-preview[data-use-github-style] table, .markdown-preview[data-use-github-style] pre { margin-top: 0px; margin-bottom: 16px; }
.markdown-preview[data-use-github-style] hr { height: 4px; padding: 0px; margin: 16px 0px; background-color: rgb(231, 231, 231); border: 0px none; }
.markdown-preview[data-use-github-style] ul, .markdown-preview[data-use-github-style] ol { padding-left: 2em; }
.markdown-preview[data-use-github-style] ul.no-list, .markdown-preview[data-use-github-style] ol.no-list { padding: 0px; list-style-type: none; }
.markdown-preview[data-use-github-style] ul ul, .markdown-preview[data-use-github-style] ul ol, .markdown-preview[data-use-github-style] ol ol, .markdown-preview[data-use-github-style] ol ul { margin-top: 0px; margin-bottom: 0px; }
.markdown-preview[data-use-github-style] li > p { margin-top: 16px; }
.markdown-preview[data-use-github-style] dl { padding: 0px; }
.markdown-preview[data-use-github-style] dl dt { padding: 0px; margin-top: 16px; font-size: 1em; font-style: italic; font-weight: bold; }
.markdown-preview[data-use-github-style] dl dd { padding: 0px 16px; margin-bottom: 16px; }
.markdown-preview[data-use-github-style] blockquote { padding: 0px 15px; color: rgb(119, 119, 119); border-left: 4px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] blockquote > :first-child { margin-top: 0px; }
.markdown-preview[data-use-github-style] blockquote > :last-child { margin-bottom: 0px; }
.markdown-preview[data-use-github-style] table { display: block; width: 100%; overflow: auto; word-break: keep-all; }
.markdown-preview[data-use-github-style] table th { font-weight: bold; }
.markdown-preview[data-use-github-style] table th, .markdown-preview[data-use-github-style] table td { padding: 6px 13px; border: 1px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] table tr { background-color: rgb(255, 255, 255); border-top: 1px solid rgb(204, 204, 204); }
.markdown-preview[data-use-github-style] table tr:nth-child(2n) { background-color: rgb(248, 248, 248); }
.markdown-preview[data-use-github-style] img { max-width: 100%; box-sizing: border-box; }
.markdown-preview[data-use-github-style] .emoji { max-width: none; }
.markdown-preview[data-use-github-style] span.frame { display: block; overflow: hidden; }
.markdown-preview[data-use-github-style] span.frame > span { display: block; float: left; width: auto; padding: 7px; margin: 13px 0px 0px; overflow: hidden; border: 1px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] span.frame span img { display: block; float: left; }
.markdown-preview[data-use-github-style] span.frame span span { display: block; padding: 5px 0px 0px; clear: both; color: rgb(51, 51, 51); }
.markdown-preview[data-use-github-style] span.align-center { display: block; overflow: hidden; clear: both; }
.markdown-preview[data-use-github-style] span.align-center > span { display: block; margin: 13px auto 0px; overflow: hidden; text-align: center; }
.markdown-preview[data-use-github-style] span.align-center span img { margin: 0px auto; text-align: center; }
.markdown-preview[data-use-github-style] span.align-right { display: block; overflow: hidden; clear: both; }
.markdown-preview[data-use-github-style] span.align-right > span { display: block; margin: 13px 0px 0px; overflow: hidden; text-align: right; }
.markdown-preview[data-use-github-style] span.align-right span img { margin: 0px; text-align: right; }
.markdown-preview[data-use-github-style] span.float-left { display: block; float: left; margin-right: 13px; overflow: hidden; }
.markdown-preview[data-use-github-style] span.float-left span { margin: 13px 0px 0px; }
.markdown-preview[data-use-github-style] span.float-right { display: block; float: right; margin-left: 13px; overflow: hidden; }
.markdown-preview[data-use-github-style] span.float-right > span { display: block; margin: 13px auto 0px; overflow: hidden; text-align: right; }
.markdown-preview[data-use-github-style] code, .markdown-preview[data-use-github-style] tt { padding: 0.2em 0px; margin: 0px; font-size: 85%; background-color: rgba(0, 0, 0, 0.04); border-radius: 3px; }
.markdown-preview[data-use-github-style] code::before, .markdown-preview[data-use-github-style] tt::before, .markdown-preview[data-use-github-style] code::after, .markdown-preview[data-use-github-style] tt::after { letter-spacing: -0.2em; content: " "; }
.markdown-preview[data-use-github-style] code br, .markdown-preview[data-use-github-style] tt br { display: none; }
.markdown-preview[data-use-github-style] del code { text-decoration: inherit; }
.markdown-preview[data-use-github-style] pre > code { padding: 0px; margin: 0px; font-size: 100%; word-break: normal; white-space: pre; background: transparent; border: 0px; }
.markdown-preview[data-use-github-style] .highlight { margin-bottom: 16px; }
.markdown-preview[data-use-github-style] .highlight pre, .markdown-preview[data-use-github-style] pre { padding: 16px; overflow: auto; font-size: 85%; line-height: 1.45; background-color: rgb(247, 247, 247); border-radius: 3px; }
.markdown-preview[data-use-github-style] .highlight pre { margin-bottom: 0px; word-break: normal; }
.markdown-preview[data-use-github-style] pre { word-wrap: normal; }
.markdown-preview[data-use-github-style] pre code, .markdown-preview[data-use-github-style] pre tt { display: inline; max-width: initial; padding: 0px; margin: 0px; overflow: initial; line-height: inherit; word-wrap: normal; background-color: transparent; border: 0px; }
.markdown-preview[data-use-github-style] pre code::before, .markdown-preview[data-use-github-style] pre tt::before, .markdown-preview[data-use-github-style] pre code::after, .markdown-preview[data-use-github-style] pre tt::after { content: normal; }
.markdown-preview[data-use-github-style] kbd { display: inline-block; padding: 3px 5px; font-size: 11px; line-height: 10px; color: rgb(85, 85, 85); vertical-align: middle; background-color: rgb(252, 252, 252); border-width: 1px; border-style: solid; border-color: rgb(204, 204, 204) rgb(204, 204, 204) rgb(187, 187, 187); border-image: initial; border-radius: 3px; box-shadow: rgb(187, 187, 187) 0px -1px 0px inset; }
.markdown-preview[data-use-github-style] a { color: rgb(51, 122, 183); }
.markdown-preview[data-use-github-style] code { color: inherit; }
.markdown-preview[data-use-github-style] pre.editor-colors { padding: 0.8em 1em; margin-bottom: 1em; font-size: 0.85em; border-radius: 4px; overflow: auto; }
.markdown-preview pre.editor-colors { user-select: auto; }
.scrollbars-visible-always .markdown-preview pre.editor-colors .vertical-scrollbar, .scrollbars-visible-always .markdown-preview pre.editor-colors .horizontal-scrollbar { visibility: hidden; }
.scrollbars-visible-always .markdown-preview pre.editor-colors:hover .vertical-scrollbar, .scrollbars-visible-always .markdown-preview pre.editor-colors:hover .horizontal-scrollbar { visibility: visible; }
.markdown-preview .task-list-item-checkbox { position: absolute; margin: 0.25em 0px 0px -1.4em; }
.markdown-preview ul label { vertical-align: top; }
@keyframes RotatingBackground {
  0% {
    background-position-x: 0%;
  }
  100% {
    background-position-x: 100%;
  }
}

.debugger-breakpoint-icon::before,
.debugger-shadow-breakpoint-icon::before {
  font-family: 'Octicons Regular';
  font-weight: normal;
  font-style: normal;
  display: inline-block;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  text-decoration: none;
  font-size: 130%;
  width: 130%;
  height: 130%;
  content: "\f052";
}
.debugger-breakpoint-icon,
.debugger-breakpoint-icon-disabled,
.debugger-breakpoint-icon-unresolved,
.debugger-breakpoint-icon-conditional,
.debugger-shadow-breakpoint-icon {
  text-align: center;
  display: block;
  width: 0.8em;
  cursor: pointer;
}
.debugger-breakpoint-icon-nonconditional {
  color: #6494ed;
}
.debugger-breakpoint-icon-conditional {
  color: #e2c08d;
}
.debugger-breakpoint-icon-disabled {
  position: relative;
  top: -4px;
  left: 2px;
}
.debugger-breakpoint-icon-disabled::before {
  font-family: 'Octicons Regular';
  font-weight: normal;
  font-style: normal;
  display: inline-block;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  text-decoration: none;
  font-size: 78%;
  width: 78%;
  height: 78%;
  content: "\f084";
}
.debugger-breakpoint-icon-unresolved {
  position: relative;
  top: -2px;
}
.debugger-breakpoint-icon-unresolved::before {
  font-family: 'Octicons Regular';
  font-weight: normal;
  font-style: normal;
  display: inline-block;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  text-decoration: none;
  font-size: 80%;
  width: 80%;
  height: 80%;
  content: "\f0e8";
}
.debugger-shadow-breakpoint-icon {
  color: rgba(100, 148, 237, 0.4);
}
.debugger-current-line-highlight {
  background: linear-gradient(to bottom, rgba(15, 130, 230, 0.8) 0%, rgba(15, 130, 230, 0.8) 5%, rgba(15, 130, 230, 0.3) 5%, rgba(15, 130, 230, 0.3) 95%, rgba(15, 130, 230, 0.8) 95%, rgba(15, 130, 230, 0.8) 100%);
}

.gutter[gutter-name=diagnostics-gutter] {
  width: 0.7em;
}
.diagnostics-gutter-ui-item {
  display: flex;
}
.diagnostics-gutter-ui-item .icon {
  display: flex;
  width: 0.7em;
  height: 0.7em;
  font-size: 0.7em;
  align-self: center;
}
.diagnostics-gutter-ui-item .icon::before {
  width: 1em;
  height: 1em;
  font-size: 1em;
  margin: 0;
  align-self: center;
}
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-info,
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-review {
  color: #6494ed;
}
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-error {
  color: #ff6347;
}
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-action,
.diagnostics-gutter-ui-item.diagnostics-gutter-ui-gutter-warning {
  color: #e2c08d;
}

.bracket-matcher .region {
  border-bottom: 1px dotted lime;
  position: absolute;
}
.line-number.bracket-matcher.bracket-matcher {
  color: #abb2bf;
  background-color: #3a3f4b;
}

.spell-check-misspelling .region {
  border-bottom: 2px dotted rgba(255, 51, 51, 0.75);
}
.spell-check-corrections {
  width: 25em !important;
}

pre.editor-colors {
  background-color: #282c34;
  color: #abb2bf;
}
pre.editor-colors .line.cursor-line {
  background-color: rgba(153, 187, 255, 0.04);
}
pre.editor-colors .invisible {
  color: #abb2bf;
}
pre.editor-colors .cursor {
  border-left: 2px solid #528bff;
}
pre.editor-colors .selection .region {
  background-color: #3e4451;
}
pre.editor-colors .bracket-matcher .region {
  border-bottom: 1px solid #528bff;
  box-sizing: border-box;
}
pre.editor-colors .invisible-character {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .indent-guide {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .wrap-guide {
  background-color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .find-result .region.region.region,
pre.editor-colors .current-result .region.region.region {
  border-radius: 2px;
  background-color: rgba(82, 139, 255, 0.24);
  transition: border-color 0.4s;
}
pre.editor-colors .find-result .region.region.region {
  border: 2px solid transparent;
}
pre.editor-colors .current-result .region.region.region {
  border: 2px solid #528bff;
  transition-duration: .1s;
}
pre.editor-colors .gutter .line-number {
  color: #636d83;
  -webkit-font-smoothing: antialiased;
}
pre.editor-colors .gutter .line-number.cursor-line {
  color: #abb2bf;
  background-color: #3a3f4b;
}
pre.editor-colors .gutter .line-number.cursor-line-no-selection {
  background-color: transparent;
}
pre.editor-colors .gutter .line-number .icon-right {
  color: #abb2bf;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed.git-line-removed::before {
  bottom: -3px;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed::after {
  content: "";
  position: absolute;
  left: 0px;
  bottom: 0px;
  width: 25px;
  border-bottom: 1px dotted rgba(224, 82, 82, 0.5);
  pointer-events: none;
}
pre.editor-colors .gutter .line-number.folded,
pre.editor-colors .gutter .line-number:after,
pre.editor-colors .fold-marker:after {
  color: #abb2bf;
}
.syntax--comment {
  color: #5c6370;
  font-style: italic;
}
.syntax--comment .syntax--markup.syntax--link {
  color: #5c6370;
}
.syntax--entity.syntax--name.syntax--type {
  color: #e5c07b;
}
.syntax--entity.syntax--other.syntax--inherited-class {
  color: #98c379;
}
.syntax--keyword {
  color: #c678dd;
}
.syntax--keyword.syntax--control {
  color: #c678dd;
}
.syntax--keyword.syntax--operator {
  color: #abb2bf;
}
.syntax--keyword.syntax--other.syntax--special-method {
  color: #61afef;
}
.syntax--keyword.syntax--other.syntax--unit {
  color: #d19a66;
}
.syntax--storage {
  color: #c678dd;
}
.syntax--storage.syntax--type.syntax--annotation,
.syntax--storage.syntax--type.syntax--primitive {
  color: #c678dd;
}
.syntax--storage.syntax--modifier.syntax--package,
.syntax--storage.syntax--modifier.syntax--import {
  color: #abb2bf;
}
.syntax--constant {
  color: #d19a66;
}
.syntax--constant.syntax--variable {
  color: #d19a66;
}
.syntax--constant.syntax--character.syntax--escape {
  color: #56b6c2;
}
.syntax--constant.syntax--numeric {
  color: #d19a66;
}
.syntax--constant.syntax--other.syntax--color {
  color: #56b6c2;
}
.syntax--constant.syntax--other.syntax--symbol {
  color: #56b6c2;
}
.syntax--variable {
  color: #e06c75;
}
.syntax--variable.syntax--interpolation {
  color: #be5046;
}
.syntax--variable.syntax--parameter {
  color: #abb2bf;
}
.syntax--string {
  color: #98c379;
}
.syntax--string > .syntax--source,
.syntax--string .syntax--embedded {
  color: #abb2bf;
}
.syntax--string.syntax--regexp {
  color: #56b6c2;
}
.syntax--string.syntax--regexp .syntax--source.syntax--ruby.syntax--embedded {
  color: #e5c07b;
}
.syntax--string.syntax--other.syntax--link {
  color: #e06c75;
}
.syntax--punctuation.syntax--definition.syntax--comment {
  color: #5c6370;
}
.syntax--punctuation.syntax--definition.syntax--method-parameters,
.syntax--punctuation.syntax--definition.syntax--function-parameters,
.syntax--punctuation.syntax--definition.syntax--parameters,
.syntax--punctuation.syntax--definition.syntax--separator,
.syntax--punctuation.syntax--definition.syntax--seperator,
.syntax--punctuation.syntax--definition.syntax--array {
  color: #abb2bf;
}
.syntax--punctuation.syntax--definition.syntax--heading,
.syntax--punctuation.syntax--definition.syntax--identity {
  color: #61afef;
}
.syntax--punctuation.syntax--definition.syntax--bold {
  color: #e5c07b;
  font-weight: bold;
}
.syntax--punctuation.syntax--definition.syntax--italic {
  color: #c678dd;
  font-style: italic;
}
.syntax--punctuation.syntax--section.syntax--embedded {
  color: #be5046;
}
.syntax--punctuation.syntax--section.syntax--method,
.syntax--punctuation.syntax--section.syntax--class,
.syntax--punctuation.syntax--section.syntax--inner-class {
  color: #abb2bf;
}
.syntax--support.syntax--class {
  color: #e5c07b;
}
.syntax--support.syntax--type {
  color: #56b6c2;
}
.syntax--support.syntax--function {
  color: #56b6c2;
}
.syntax--support.syntax--function.syntax--any-method {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--function {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--class,
.syntax--entity.syntax--name.syntax--type.syntax--class {
  color: #e5c07b;
}
.syntax--entity.syntax--name.syntax--section {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--tag {
  color: #e06c75;
}
.syntax--entity.syntax--other.syntax--attribute-name {
  color: #d19a66;
}
.syntax--entity.syntax--other.syntax--attribute-name.syntax--id {
  color: #61afef;
}
.syntax--meta.syntax--class {
  color: #e5c07b;
}
.syntax--meta.syntax--class.syntax--body {
  color: #abb2bf;
}
.syntax--meta.syntax--method-call,
.syntax--meta.syntax--method {
  color: #abb2bf;
}
.syntax--meta.syntax--definition.syntax--variable {
  color: #e06c75;
}
.syntax--meta.syntax--link {
  color: #d19a66;
}
.syntax--meta.syntax--require {
  color: #61afef;
}
.syntax--meta.syntax--selector {
  color: #c678dd;
}
.syntax--meta.syntax--separator {
  color: #abb2bf;
}
.syntax--meta.syntax--tag {
  color: #abb2bf;
}
.syntax--underline {
  text-decoration: underline;
}
.syntax--none {
  color: #abb2bf;
}
.syntax--invalid.syntax--deprecated {
  color: #523d14 !important;
  background-color: #e0c285 !important;
}
.syntax--invalid.syntax--illegal {
  color: white !important;
  background-color: #e05252 !important;
}
.syntax--markup.syntax--bold {
  color: #d19a66;
  font-weight: bold;
}
.syntax--markup.syntax--changed {
  color: #c678dd;
}
.syntax--markup.syntax--deleted {
  color: #e06c75;
}
.syntax--markup.syntax--italic {
  color: #c678dd;
  font-style: italic;
}
.syntax--markup.syntax--heading {
  color: #e06c75;
}
.syntax--markup.syntax--heading .syntax--punctuation.syntax--definition.syntax--heading {
  color: #61afef;
}
.syntax--markup.syntax--link {
  color: #56b6c2;
}
.syntax--markup.syntax--inserted {
  color: #98c379;
}
.syntax--markup.syntax--quote {
  color: #d19a66;
}
.syntax--markup.syntax--raw {
  color: #98c379;
}
.syntax--source.syntax--c .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--cpp .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--cs .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--css .syntax--property-name,
.syntax--source.syntax--css .syntax--property-value {
  color: #828997;
}
.syntax--source.syntax--css .syntax--property-name.syntax--support,
.syntax--source.syntax--css .syntax--property-value.syntax--support {
  color: #abb2bf;
}
.syntax--source.syntax--elixir .syntax--source.syntax--embedded.syntax--source {
  color: #abb2bf;
}
.syntax--source.syntax--elixir .syntax--constant.syntax--language,
.syntax--source.syntax--elixir .syntax--constant.syntax--numeric,
.syntax--source.syntax--elixir .syntax--constant.syntax--definition {
  color: #61afef;
}
.syntax--source.syntax--elixir .syntax--variable.syntax--definition,
.syntax--source.syntax--elixir .syntax--variable.syntax--anonymous {
  color: #c678dd;
}
.syntax--source.syntax--elixir .syntax--parameter.syntax--variable.syntax--function {
  color: #d19a66;
  font-style: italic;
}
.syntax--source.syntax--elixir .syntax--quoted {
  color: #98c379;
}
.syntax--source.syntax--elixir .syntax--keyword.syntax--special-method,
.syntax--source.syntax--elixir .syntax--embedded.syntax--section,
.syntax--source.syntax--elixir .syntax--embedded.syntax--source.syntax--empty {
  color: #e06c75;
}
.syntax--source.syntax--elixir .syntax--readwrite.syntax--module .syntax--punctuation {
  color: #e06c75;
}
.syntax--source.syntax--elixir .syntax--regexp.syntax--section,
.syntax--source.syntax--elixir .syntax--regexp.syntax--string {
  color: #be5046;
}
.syntax--source.syntax--elixir .syntax--separator,
.syntax--source.syntax--elixir .syntax--keyword.syntax--operator {
  color: #d19a66;
}
.syntax--source.syntax--elixir .syntax--variable.syntax--constant {
  color: #e5c07b;
}
.syntax--source.syntax--elixir .syntax--array,
.syntax--source.syntax--elixir .syntax--scope,
.syntax--source.syntax--elixir .syntax--section {
  color: #828997;
}
.syntax--source.syntax--gfm .syntax--markup {
  -webkit-font-smoothing: auto;
}
.syntax--source.syntax--gfm .syntax--link .syntax--entity {
  color: #61afef;
}
.syntax--source.syntax--go .syntax--storage.syntax--type.syntax--string {
  color: #c678dd;
}
.syntax--source.syntax--ini .syntax--keyword.syntax--other.syntax--definition.syntax--ini {
  color: #e06c75;
}
.syntax--source.syntax--java .syntax--storage.syntax--modifier.syntax--import {
  color: #e5c07b;
}
.syntax--source.syntax--java .syntax--storage.syntax--type {
  color: #e5c07b;
}
.syntax--source.syntax--java .syntax--keyword.syntax--operator.syntax--instanceof {
  color: #c678dd;
}
.syntax--source.syntax--java-properties .syntax--meta.syntax--key-pair {
  color: #e06c75;
}
.syntax--source.syntax--java-properties .syntax--meta.syntax--key-pair > .syntax--punctuation {
  color: #abb2bf;
}
.syntax--source.syntax--js .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--delete,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--in,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--of,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--instanceof,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--new,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--typeof,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--void {
  color: #c678dd;
}
.syntax--source.syntax--ts .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--flow .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--string.syntax--quoted.syntax--json {
  color: #e06c75;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation.syntax--string {
  color: #e06c75;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation {
  color: #98c379;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--constant.syntax--language.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--constant.syntax--language.syntax--json {
  color: #56b6c2;
}
.syntax--ng.syntax--interpolation {
  color: #e06c75;
}
.syntax--ng.syntax--interpolation.syntax--begin,
.syntax--ng.syntax--interpolation.syntax--end {
  color: #61afef;
}
.syntax--ng.syntax--interpolation .syntax--function {
  color: #e06c75;
}
.syntax--ng.syntax--interpolation .syntax--function.syntax--begin,
.syntax--ng.syntax--interpolation .syntax--function.syntax--end {
  color: #61afef;
}
.syntax--ng.syntax--interpolation .syntax--bool {
  color: #d19a66;
}
.syntax--ng.syntax--interpolation .syntax--bracket {
  color: #abb2bf;
}
.syntax--ng.syntax--pipe,
.syntax--ng.syntax--operator {
  color: #abb2bf;
}
.syntax--ng.syntax--tag {
  color: #56b6c2;
}
.syntax--ng.syntax--attribute-with-value .syntax--attribute-name {
  color: #e5c07b;
}
.syntax--ng.syntax--attribute-with-value .syntax--string {
  color: #c678dd;
}
.syntax--ng.syntax--attribute-with-value .syntax--string.syntax--begin,
.syntax--ng.syntax--attribute-with-value .syntax--string.syntax--end {
  color: #abb2bf;
}
.syntax--source.syntax--ruby .syntax--constant.syntax--other.syntax--symbol > .syntax--punctuation {
  color: inherit;
}
.syntax--source.syntax--php .syntax--class.syntax--bracket {
  color: #abb2bf;
}
.syntax--source.syntax--python .syntax--keyword.syntax--operator.syntax--logical.syntax--python {
  color: #c678dd;
}
.syntax--source.syntax--python .syntax--variable.syntax--parameter {
  color: #d19a66;
}
</style>
  </head>
  <body class='markdown-preview' data-use-github-style><h1 id="l1-introduction-history-terminology-time-state-"><a href="https://simulation.tudelft.nl/SEN9110/lecture1.php">L1 Introduction: History, Terminology, Time &amp; State </a></h1>
<h4 id="what-is-a-simulation-">What is a simulation?</h4>
<p>Shannon, 1975 defines it as:<br>(Shannon, R.E., 1975. Systems Simulation – The Art and<br>Science, Prentice-Hall.) --&gt; can't find this anywhere without payment wahh</p>
<blockquote>
<p>"The process of designing a model of a real system and conducting experiments with this model <strong>for the purpose</strong> either of understanding the behavior of the system or of evaluating various strategies (within the limits imposed y a criterion or set of criteria) for the operation of the system."</p>
</blockquote>
<p>Purpose of simulation (from slide 10) can be further specified as as quantative analysis, what-if analysis, having a <strong>safe testing environment</strong>.</p>
<ul>
<li>Animation is <strong>not</strong> essential to simulation, but can give additional insight... slide 21</li>
</ul>
<h4 id="dess-dtss-devs-defined-slides-28-29-30">DESS/DTSS/DEVS defined slides 28/29/30</h4>
<ul>
<li><strong>"Formalism"</strong> -  System Dynamics or Agent Based Modeling or Discrete Event Modeling</li>
<li>Don't misuse formalism and paradigm</li>
<li>"Simulation model" is a type of <strong>"model family"</strong></li>
</ul>
<h3 id="nance-1981-the-time-and-state-relationships-in-simulation-modeling">Nance, 1981: <em>The time and state relationships in simulation modeling</em></h3>
<ul>
<li>page 1 @ myNotebook</li>
<li>slide 38 @ Alexander</li>
</ul>
<h4 id="the-definitional-disorder">The Definitional Disorder</h4>
<p>Some key definitions (just copy from the paper if asked):</p>
<ul>
<li><strong>state</strong></li>
<li><strong>instant</strong></li>
<li><strong>interval</strong></li>
<li><strong>event</strong></li>
<li><strong>span</strong></li>
<li><strong>activity</strong></li>
<li><strong>process</strong></li>
</ul>
<h4 id="the-3-worldviews">The 3 Worldviews</h4>
<ul>
<li>defined page 1 Nance, p1 myNotebook<ul>
<li>Developed as <em>f(Geographical communication gap, language success, randomness)</em></li>
<li><strong>Problem</strong> is that variation in interpretation of formalism is mistaken for variation in the formalisms themselves.</li>
<li>This adds to image of M&amp;S as <strong>unscientific</strong>, lacking convergence of core concepts, uncertain, expensive.</li>
</ul>
</li>
</ul>
<h4 id="the-significance-of-the-disorder">The significance of the disorder</h4>
<ul>
<li><strong>Isolation</strong> of researchers in M&amp;S</li>
<li>Relegation of concepts to a minor role in programming/training.</li>
<li>Lack of importability of Models</li>
</ul>
<h4 id="state-sequenced-simulation">State-sequenced simulation</h4>
<p><em>see paper and page 2 of myNotebook</em></p>
<h1 id="l2-system-theory-klir-rosen-ackoff-ashby"><a href="https://simulation.tudelft.nl/SEN9110/lecture2.php">L2 System Theory: Klir, Rosen, Ackoff, Ashby</a></h1>
<p><em>Cybernatics:</em> science of communications and automatic control systems in both machines and living things. Provides good formal concepts of (dynamic) system theory in an independent, abstract way that M&amp;S does not provide. (see Ashby)</p>
<p><em>Set Theory</em> see slide 28 if need in exam and cheat sheet</p>
<p><img alt="" src="/Users/lauracrowley/Documents/EPA Archive/Simulation Masterclass/images/SetTheory.jpg"></p>
<h3 id="klir-s-definition-does-is-non-temperal-">Klir's definition does is non-temperal!</h3>
<ul>
<li>S = (T,R)</li>
<li>T = {things}</li>
<li>R = {relations between things in T}</li>
<li>abstract, generic</li>
</ul>
<h3 id="ackoff-s-definition-is-purpose-centric">Ackoff's definition is purpose-centric</h3>
<ul>
<li>Definition (slide 7) introduces concept of <strong>essential parts</strong> ... behavior, state, subsystem</li>
<li>Focus is on the <strong>interaction effects</strong> between parts etc</li>
<li>Dangers of decomposition or the "Engineering approach"</li>
<li><strong>4 Types</strong> of systems are hierarchical ... purposeful</li>
<li>The <strong>mismatch</strong> between systems and their models...</li>
</ul>
<h3 id="rosen-s-definition-is-probably-biased-but-pragmatic">Rosen's definition is probably biased but pragmatic</h3>
<p>Have seen this in every class since Q2... encoding, implicitation, decoding, commutative etc etc</p>
<blockquote>
<p>Modeling is the essence of science and the habitat of epistemology.</p>
</blockquote>
<h3 id="ashby-is-focused-on-transformations">Ashby is focused on transformations</h3>
<ul>
<li><strong>Transformation:</strong> <em>what</em> happens is more imporant than <em>why</em> it happens. A set of tranistions (changes).</li>
<li>Terminology: operands, operator ... etc.</li>
<li>Relations are sets of pairs e.g. time advance function.</li>
<li>A transformation is <strong>closed</strong> <em>iff</em> Range is a subset of Domain.</li>
<li>Function is a <strong>single-valued</strong> relation which can have <strong>one-to-one</strong> mapping.</li>
<li>Transitions/transformations/relations/mappings ... do not mix-up! (Deceptively confusing...)</li>
</ul>
<h1 id="l3-system-specification-klir-s-levels-devs"><a href="https://simulation.tudelft.nl/SEN9110/lecture3.php">L3 System Specification: Klir's Levels, DEVS</a></h1>
<h3 id="klir-s-system-specification">Klir's system Specification</h3>
<blockquote>
<p>From his paper <em>"Facets of Systems Science",</em> 2001</p>
</blockquote>
<ul>
<li>S = (T,R) with R - <em>relation</em> - as defined by Common Sense (see L2).</li>
<li>Slide 8 has example of expressing a system with set notation in case the exam also asks for a similar example!</li>
<li>Deductive vs Inductive system frameworks (paper).</li>
<li>Levels (for definitions use Zeigler paper/ Klir slides 11-13).</li>
</ul>
<p>Key points:</p>
<ul>
<li>Difference between the two is the <strong>temporal element</strong> of Zeigler's levels.</li>
<li>Simulation is a process of <strong>data generation</strong> froma <strong>time-invariant representation</strong> of an object of interest (<strong>a generative system</strong>).</li>
<li><strong>Structure Systems:</strong> couple systems and outputs, whereas <strong>meta systems</strong> can switch behavior e.g. schedules for workers etc.</li>
</ul>
<h3 id="how-does-discrete-event-simulation-work-">How does discrete event simulation work?</h3>
<blockquote>
<p>From <strong>Schriber &amp; Brunner's</strong> paper <em>"Inside Discrete-Event Simulation Software: how it works and why it matters.",</em> 2015<br>... which is based on their paper published in 1998 <em>"Ch.24 How Discrete-Event Simulation works."</em>)</p>
</blockquote>
<h3 id="worldviews">Worldviews</h3>
<ul>
<li>Definitions in Nance (p1) or myNotebook (p1)</li>
<li>Each WV can be described using the concept of <em>locality</em> (Overstreet, 1986) --&gt; describes how behavioral logic is grouped e.g. time, state, object.</li>
<li>See slide 19/20 for good example of proccess interaction and activity scanning.</li>
</ul>
<h3 id="inside-des-software-tricky-section">Inside DES software - TRICKY section</h3>
<ul>
<li>Slides 21-30</li>
<li>Future event list Delay list - is the only true distinction the point at which each of the items on these become deterministic within the simulation run ...?</li>
<li><p>Describe how DEVS can be described as Activity scanning e.g. time advance function and event list is scanning...?</p>
</li>
<li><p>Exam question 1b Jan 2019</p>
<ul>
<li>ABM is activity scanning but in terms of Brunner &amp; Schriber it operates with entities in time delay states.</li>
<li>Queues can be seen as entities in condition delayed states. DEVS can be expressed as Queues. Therefore...</li>
<li>Process Interaction combines both time-delay states (an object is waiting in between its different states) and condition-delayed states (an object is waiting for other objects to be in a certain state).</li>
</ul>
</li>
</ul>
<h1 id="l4-the-devs-formalism-zeigler-s-levels-devs"><a href="https://simulation.tudelft.nl/SEN9110/lecture4.php">L4 The DEVS Formalism: Zeigler's Levels, DEVS</a></h1>
<h1 id="l5-devs-extensions"><a href="https://simulation.tudelft.nl/SEN9110/lecture5.php">L5 DEVS Extensions</a></h1>
<h1 id="l6-object-oriented-simulation"><a href="https://simulation.tudelft.nl/SEN9110/lecture6.php">L6 Object Oriented Simulation</a></h1>
<h1 id="l11-notes-monday-14th-october"><a href="https://simulation.tudelft.nl/SEN9110/lecture11.php">L11 notes</a> - Monday 14th October</h1>
<p>-see word doc</p>
<h1 id="l12-notes"><a href="https://simulation.tudelft.nl/SEN9110/lecture12.php">L12 notes</a></h1>
<h1 id="l13-notes-monday-14th-october"><a href="https://simulation.tudelft.nl/SEN9110/lecture13.php">L13 notes</a> - Monday 14th October</h1>
<h2 id="review-last-lecture-multi-resolution-modeling">Review last lecture: <a href="https://simulation.tudelft.nl/SEN9110/slides/SEN9110_12_MultiResolutionSimulation.pdf">Multi-Resolution modeling</a></h2>
<h3 id="aggregation">Aggregation</h3>
<ul>
<li>use meta-model of <a href="W. J. H. Van Groenendaal and J. P. C. Kleijnen. 1996. “Regression metamodels and design of experiments”">Kleijnen</a> for the aggregation part of multi-resolution Modeling<ul>
<li>note: this kind of deterministic regression ignores <strong>STOCHASTICS</strong></li>
<li>can add a constant error term to account for the distribution that you see in your equations (a single one instead of one for every variable etc to save time)</li>
</ul>
</li>
</ul>
<h3 id="disaggregation">Disaggregation</h3>
<ul>
<li>Difficult: no longer know what these constant parameters relate to in the 'real world'/original model.</li>
</ul>
<h3 id="is-this-valid-">Is this valid?</h3>
<ul>
<li>the <strong>connection</strong> between the aggregate to the disaggregate model has to show realistic behavior</li>
<li><em><a href="https://simulation.tudelft.nl/SEN9110/background/12%20Davis%20RAND-WR-224%20Multirsolution%20Multiperspective%20Modeling.pdf">Davis Report WR-224, 2005</a></em> from RAND has a method for checking the validity of these implementations.</li>
</ul>
<p><img alt="" src="/Users/lauracrowley/Documents/EPA Archive/Simulation Masterclass/images/L13.png"></p>
<p>Only works if the states in the disaggregate and aggregate model are actually <em>comparable</em> !! e.g. car model/density function are not comparable (directly)</p>
<ul>
<li>Weak commonality: comparing the states on the <strong>dis-</strong> aggregate level</li>
<li>Strong commonality/consistency: on the aggregate level</li>
</ul>
<h3 id="data-assimilation-into-simulation-models">Data Assimilation into Simulation Models</h3>
<p>Consider being able to observe <strong>partial states</strong> at high accuracy -- how do we assimilate the data from the past into the model? e.g. Weather forecasting / control a system for best response / ML to understand a system better.</p>
<ul>
<li><strong>digital twin</strong></li>
<li>For <strong>understanding/controlling/prediction</strong></li>
</ul>
<p>1) <em>Kalman filter (LQE)</em> used for continuous models to account for the errors and fitting parameters onto observations assuming linearity, normal distribution etc...<br>Can't use in DEVS due to discreteness/jumps/piecewise constant etc duh</p>
<p>2) DEVS uses <em>Monte Carlo</em>: particles, importance sample, has history, drift. Also being used in continuous systems more and more e.g. weather forecasting --&gt; try to 'find' the anomalies in weather (continuous systems)</p>
<h2 id="exam-tips">EXAM TIPS</h2>
<p>Answer 3 out of 4, bring anything you want (non electronic)</p>
<ul>
<li>Questions that come up each time (Q2 - DEVS) is a variation on a theme each year.</li>
<li>Other questions are combinations of topics from classes - not the exact same as we did in class.</li>
<li>"How" questions - high level of reasoning.</li>
<li>Could be a question about the language we studied and relate to a paper etc.</li>
<li>Point to slide X in class or figure of papers (page and paper etc).</li>
</ul>
<h2 id="l13-simulation-languages-1-2-">L13 - Simulation Languages (1/2)</h2>
<p>A simulation language is based on a worldview:</p>
<ul>
<li><strong><a href="Weinberg 1971">Locality</a> of object</strong> - process interaction, fully contained within each object etc e.g. Salabim describes a Lifecycle of an object. That is why it is susceptible to dead locks. Then for interactions each object needs to be able to 'see' other objects - need a global list so what was the point of hiding them in the first place?</li>
<li>Tough <strong>trade off</strong> between scope at large scale models e.g. memory/deadlock/starvation.</li>
<li>Common misconception - defining the process of an entire model (and not just an object) is NOT process interaction but event scheduling.</li>
<li><strong>ABM</strong> - pure activity scanning (locality of state). Each activity routine descries all actions that occur because a particular state is reached.</li>
<li><strong>DEVS</strong> - <em>is pure event scheduling in the way that behavior is defined. But internally, activity scanning (not continuously scanning but piecewise) is used to determine the next state (think about this one?)...</em></li>
</ul></body>
</html>
