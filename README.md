<h2>Стек Stack<t> и&nbsp;Очередь Queue<t></t></t></h2>
<p>Очереди и&nbsp;стеки полезны,&nbsp;когда нужно временно хранить какие-то элементы, то&nbsp;есть удалять элемент после его извлечения. Также они позволяют определить строгую очередность записи и&nbsp;извлечения элементов.</p>
<p>Стеки Stack<t>&nbsp;— реализуют подход LIFO (last in&nbsp;— first out).</t></p>
<pre class="e2-text-code"><code class="hljs cpp">var <span class="hljs-built_in">stack</span> = <span class="hljs-keyword">new</span> Stack&lt;<span class="hljs-keyword">int</span>&gt;();
<span class="hljs-built_in">stack</span>.Push(<span class="hljs-number">1</span>); <span class="hljs-comment">// stack = [1]</span>
<span class="hljs-built_in">stack</span>.Push(<span class="hljs-number">2</span>); <span class="hljs-comment">// stack = [1,2]</span>
var item = <span class="hljs-built_in">stack</span>.Pop(); <span class="hljs-comment">// stack = [1], item = 2</span></code></pre><p>Очереди Queue<t>&nbsp;— реализуют подход (first in&nbsp;— first out).</t></p>
<pre class="e2-text-code"><code class="hljs cpp">var <span class="hljs-built_in">queue</span> = <span class="hljs-keyword">new</span> Queue&lt;<span class="hljs-keyword">int</span>&gt;();
<span class="hljs-built_in">queue</span>.Enqueue(<span class="hljs-number">1</span>); <span class="hljs-comment">// queue = [1]</span>
<span class="hljs-built_in">queue</span>.Enqueue(<span class="hljs-number">2</span>); <span class="hljs-comment">// queue = [1,2]</span>
item = <span class="hljs-built_in">queue</span>.Dequeue(); <span class="hljs-comment">// queue = [2], item = 1</span></code></pre><p>Внутри они реализованы с&nbsp;помощью обычных массивов.</p>
