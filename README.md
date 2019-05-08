---


---

<h1 id="react">React</h1>
<pre class=" language-js"><code class="prism  language-js"><span class="token keyword">function</span>  <span class="token function">handleSubmit</span><span class="token punctuation">(</span>event<span class="token punctuation">)</span> <span class="token punctuation">{</span>
	event<span class="token punctuation">.</span><span class="token function">preventDefault</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
	<span class="token keyword">const</span> <span class="token punctuation">{</span>
		username<span class="token punctuation">:</span> <span class="token punctuation">{</span> value<span class="token punctuation">:</span> username <span class="token punctuation">}</span><span class="token punctuation">,</span>
		password<span class="token punctuation">:</span> <span class="token punctuation">{</span> value<span class="token punctuation">:</span> password <span class="token punctuation">}</span>
	<span class="token punctuation">}</span> <span class="token operator">=</span>  event<span class="token punctuation">.</span>target
	<span class="token function">onLogin</span><span class="token punctuation">(</span>username<span class="token punctuation">,</span> password<span class="token punctuation">)</span>

<span class="token punctuation">}</span>
</code></pre>
# teamknowledge
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTMyNjAwNTUzMl19
-->