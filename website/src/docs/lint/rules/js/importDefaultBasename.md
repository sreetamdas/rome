---
title: Lint Rule js/importDefaultBasename
layout: layouts/rule.liquid
description: MISSING DOCUMENTATION
eleventyNavigation:
	key: lint-rules/js/importDefaultBasename
	parent: lint-rules
	title: js/importDefaultBasename
---

# js/importDefaultBasename

MISSING DOCUMENTATION

<!-- GENERATED:START(hash:989756c31b6bc82f6d5ae668177d845b7a042c68,id:main) Everything below is automatically generated. DO NOT MODIFY. Run `./rome run scripts/generated-files/lint-rules-docs` to update. -->
## Examples
### Invalid
{% raw %}<pre class="language-text"><code class="language-text"><span class="token keyword">import</span> <span class="token variable">foo</span> <span class="token keyword">from</span> <span class="token string">&apos;./bar&apos;</span><span class="token punctuation">;</span></code></pre>{% endraw %}
{% raw %}<pre class="language-text"><code class="language-text">
 <span style="text-decoration-style: dashed; text-decoration-line: underline;">file.ts:1</span> <strong>lint/js/importDefaultBasename</strong> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  <strong><span style="color: Tomato;">✖ </span></strong><span style="color: Tomato;">Use the basename </span><span style="color: Tomato;"><strong>bar</strong></span><span style="color: Tomato;">, or </span><span style="color: Tomato;"><strong>Bar</strong></span><span style="color: Tomato;"> when importing the default.</span>

    <span class="token keyword">import</span> <span class="token variable">foo</span> <span class="token keyword">from</span> <span class="token string">&apos;./bar&apos;</span><span class="token punctuation">;</span>
    <span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span><span style="color: Tomato;"><strong>^</strong></span>

  <strong><span style="color: DodgerBlue;">ℹ </span></strong><span style="color: DodgerBlue;">If you really meant to use a named import, use the following:</span>

    <span class="token keyword">import</span> <span class="token punctuation">{</span><span class="token keyword">default</span> <span class="token variable">as</span> <span class="token variable">foo</span><span class="token punctuation">}</span>

</code></pre>{% endraw %}
### Valid
{% raw %}<pre class="language-text"><code class="language-text"><span class="token keyword">import</span> <span class="token variable">foo</span> <span class="token keyword">from</span> <span class="token string">&apos;./foo&apos;</span><span class="token punctuation">;</span></code></pre>{% endraw %}
<!-- GENERATED:END(id:main) -->
