---
layout: project
category: materialize
title: Materialize Pickers
---
<h3 class="header">Date Picker</h3>
<div class="input-field"><img src="/wdarchive/materialize/images/materializeDatePicker.png" alt="materializeDatePicker.png" width="600" height="410" data-api-endpoint="https://hilliard.instructure.com/api/v1/courses/31582/files/12207582" data-api-returntype="File"></div>
<p> 
</p><div class="input-field">The Materialize datepicker class allows users to select a date from an interactive calendar.</div>
<pre class=" language-markup"><code class=" language-markup">  <span class="token tag"><span class="token punctuation">&lt;</span>input <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>text<span class="token punctuation">"</span></span> <span class="token attr-name">class</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>datepicker<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>        </code></pre>
<div class="section">
<h5>You must include the following Javascript:</h5>
<pre class=" language-javascript"><code class=" language-javascript">  document<span class="token punctuation">.</span><span class="token function">addEventListener</span><span class="token punctuation">(</span><span class="token string">'DOMContentLoaded'</span><span class="token punctuation">,</span> <span class="token keyword">function</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">var</span> elems <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">querySelectorAll</span><span class="token punctuation">(</span><span class="token string">'.datepicker'</span><span class="token punctuation">)</span><span class="token punctuation">;<br></span>    var options = {};
    <span class="token keyword">var</span> instances <span class="token operator">=</span> M<span class="token punctuation">.</span>Datepicker<span class="token punctuation">.</span><span class="token function">init</span><span class="token punctuation">(</span>elems<span class="token punctuation">,</span> options<span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</code></pre>
</div>
<h3 class="header">Time Picker</h3>
<div class="input-field"><img src="/wdarchive/materialize/images/materializeTimePicker.png" alt="materializeTimePicker.png" width="600" height="369" data-api-endpoint="https://hilliard.instructure.com/api/v1/courses/31582/files/12207596" data-api-returntype="File"></div>
<p> </p>
<div class="input-field">The Materialize timepicker class allows users to select a date from an interactive clock.</div>
<pre class=" language-markup"><code class=" language-markup">  <span class="token tag"><span class="token punctuation">&lt;</span>input <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>text<span class="token punctuation">"</span></span> <span class="token attr-name">class</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>timepicker<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span></code></pre>
<div class="section">
<h5>Include the following Javascript:</h5>
<pre class=" language-javascript"><code class=" language-javascript">  document<span class="token punctuation">.</span><span class="token function">addEventListener</span><span class="token punctuation">(</span><span class="token string">'DOMContentLoaded'</span><span class="token punctuation">,</span> <span class="token keyword">function</span><span class="token punctuation">(</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">var</span> elems <span class="token operator">=</span> document<span class="token punctuation">.</span><span class="token function">querySelectorAll</span><span class="token punctuation">(</span><span class="token string">'.timepicker'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token keyword">var</span> instances <span class="token operator">=</span> M<span class="token punctuation">.</span>Timepicker<span class="token punctuation">.</span><span class="token function">init</span><span class="token punctuation">(</span>elems<span class="token punctuation">,</span> options<span class="token punctuation">)</span><span class="token punctuation">;</span>
  <span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span></code></pre>
</div>
<h3>Basic HTML5 Date and Time Pickers</h3>
<p>You don't need Materialize to create date and time pickers, but the Materialize versions look <span style="text-decoration: underline;">MUCH</span> better.</p>
<h3>input type="date"</h3>
<p><img src="/wdarchive/materialize/images/html5DatePicker.png" alt="html5DatePicker.png" width="600" height="298" data-api-endpoint="https://hilliard.instructure.com/api/v1/courses/31582/files/12207541" data-api-returntype="File"></p>
<p>&lt;input type="date"&gt; defines a date picker. The resulting value includes the year, month, and day.</p>
<pre><span class="tagnamecolor"><span class="tagcolor">&lt;</span>label<span class="attributecolor"><span> </span>for<span class="attributevaluecolor">="birthday"</span></span><span class="tagcolor">&gt;</span></span><span>Birthday:</span><span class="tagnamecolor"><span class="tagcolor">&lt;</span>/label<span class="tagcolor">&gt;</span></span><br><span class="tagnamecolor"><span class="tagcolor">&lt;</span>input<span class="attributecolor"><span> </span>type<span class="attributevaluecolor">="date"</span><span> </span>id<span class="attributevaluecolor">="birthday"</span><span> </span>name<span class="attributevaluecolor">="birthday"</span></span><span class="tagcolor">&gt;</span></span></pre>
<h3>input type="datetime-local"</h3>
<p><img src="/wdarchive/materialize/images/html5DateTimePicker.png" alt="html5DateTimePicker.png" width="600" height="118" data-api-endpoint="https://hilliard.instructure.com/api/v1/courses/31582/files/12207563" data-api-returntype="File"></p>
<p>&lt;input type="datetime-local"&gt; creates a widget to display and pick a date with time with no specific time zone information.</p>
<pre class="brush: html line-numbers language-html"><code class=" language-html"><span class="token tag"><span class="token punctuation">&lt;</span>input <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>datetime-local<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>datetime<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>datetime<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span></code></pre>
<h3>input type="month"</h3>
<p>&lt;input type="month"&gt; creates a widget to display and pick a month with a year.</p>
<pre class="brush: html line-numbers language-html"><code class=" language-html"><span class="token tag"><span class="token punctuation">&lt;</span>input <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>month<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>month<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>month<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span></code></pre>
<h3>input type="time"</h3>
<p><img src="/wdarchive/materialize/images/html5TimePicker.png" alt="html5TimePicker.png" width="600" height="79" data-api-endpoint="https://hilliard.instructure.com/api/v1/courses/31582/files/12207664" data-api-returntype="File"></p>
<p>&lt;input type="time"&gt; creates a widget to display and pick a time value. While time may<span> </span><em>display</em><span> </span>in 12-hour format, the<span> </span><em>value returned</em><span> </span>is in 24-hour format.</p>
<pre class="brush: html line-numbers language-html"><code class=" language-html"><span class="token tag"><span class="token punctuation">&lt;</span>input <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>time<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>time<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>time<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span></code></pre>
<h3>input type="week"</h3>
<p>&lt;input type="week"&gt; creates a widget to display and pick a week number and its year.</p>
<p>Weeks start on Monday and run to Sunday. Additionally, the first week 1 of each year contains the first Thursday of that year—which may not include the first day of the year, or may include the last few days of the previous year.</p>
<pre class="brush: html line-numbers language-html"><code class=" language-html"><span class="token tag"><span class="token punctuation">&lt;</span>input <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>week<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>week<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>week<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span></code></pre>