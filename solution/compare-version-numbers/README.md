## 165. Compare Version Numbers (Medium)

<p>Compare two version numbers <em>version1</em> and <em>version2</em>.<br />
If <code><em>version1</em> &gt; <em>version2</em></code> return <code>1;</code>&nbsp;if <code><em>version1</em> &lt; <em>version2</em></code> return <code>-1;</code>otherwise return <code>0</code>.</p>

<p>You may assume that the version strings are non-empty and contain only digits and the <code>.</code> character.<br />
The <code>.</code> character does not represent a decimal point and is used to separate number sequences.<br />
For instance, <code>2.5</code> is not &quot;two and a half&quot; or &quot;half way to version three&quot;, it is the fifth second-level revision of the second first-level revision.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> <code><em>version1</em></code> = &quot;0.1&quot;, <code><em>version2</em></code> = &quot;1.1&quot;
<strong>Output:</strong> -1</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><code><em>version1</em></code> = &quot;1.0.1&quot;, <code><em>version2</em></code> = &quot;1&quot;
<strong>Output:</strong> 1</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> <code><em>version1</em></code> = &quot;7.5.2.4&quot;, <code><em>version2</em></code> = &quot;7.5.3&quot;
<strong>Output:</strong> -1</pre>