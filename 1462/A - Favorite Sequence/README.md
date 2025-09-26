<h3><a href="https://codeforces.com/contest/1462/problem/A" target="_blank" rel="noopener noreferrer">Favorite Sequence</a></h3>

<div class="header"><div class="title">A. Favorite Sequence</div><div class="time-limit"><div class="property-title">time limit per test</div>2 seconds</div><div class="memory-limit"><div class="property-title">memory limit per test</div>256 megabytes</div><div class="input-file input-standard"><div class="property-title">input</div>standard input</div><div class="output-file output-standard"><div class="property-title">output</div>standard output</div></div><div><p>Polycarp has a favorite sequence $$$a[1 \dots n]$$$ consisting of $$$n$$$ integers. He wrote it out on the whiteboard as follows:</p><ul> <li> he wrote the number $$$a_1$$$ to the left side (at the beginning of the whiteboard); </li><li> he wrote the number $$$a_2$$$ to the right side (at the end of the whiteboard); </li><li> then as far to the left as possible (but to the right from $$$a_1$$$), he wrote the number $$$a_3$$$; </li><li> then as far to the right as possible (but to the left from $$$a_2$$$), he wrote the number $$$a_4$$$; </li><li> Polycarp continued to act as well, until he wrote out the entire sequence on the whiteboard. </li></ul><center> <img class="tex-graphics" src="https://espresso.codeforces.com/48ba4be78a2791cb41cacffdddd67fff2dcd812f.png" style="max-width: 100.0%;max-height: 100.0%;">   <span class="tex-font-size-small">The beginning of the result looks like this (of course, if $$$n \ge 4$$$).</span> </center><p>For example, if $$$n=7$$$ and $$$a=[3, 1, 4, 1, 5, 9, 2]$$$, then Polycarp will write a sequence on the whiteboard $$$[3, 4, 5, 2, 9, 1, 1]$$$.</p><p>You saw the sequence written on the whiteboard and now you want to restore Polycarp's favorite sequence.</p></div><div class="input-specification"><div class="section-title">Input</div><p>The first line contains a single positive integer $$$t$$$ ($$$1 \le t \le 300$$$) — the number of test cases in the test. Then $$$t$$$ test cases follow.</p><p>The first line of each test case contains an integer $$$n$$$ ($$$1 \le n \le 300$$$) — the length of the sequence written on the whiteboard.</p><p>The next line contains $$$n$$$ integers $$$b_1, b_2,\ldots, b_n$$$ ($$$1 \le b_i \le 10^9$$$) — the sequence written on the whiteboard.</p></div><div class="output-specification"><div class="section-title">Output</div><p>Output $$$t$$$ answers to the test cases. Each answer — is a sequence $$$a$$$ that Polycarp wrote out on the whiteboard.</p></div><div class="sample-tests"><div class="section-title">Example</div><div class="sample-test"><div class="input"><div class="title">Input<div title="Copy" data-clipboard-target="#id005458773287656739" id="id008138010870049402" class="input-output-copier">Copy</div></div><pre id="id005458773287656739">6
7
3 4 5 2 9 1 1
4
9 2 7 1
11
8 4 3 1 2 7 8 7 9 4 2
1
42
2
11 7
8
1 1 1 1 1 1 1 1
</pre></div><div class="output"><div class="title">Output<div title="Copy" data-clipboard-target="#id0019384377191507207" id="id005605779207699192" class="input-output-copier">Copy</div></div><pre id="id0019384377191507207">3 1 4 1 5 9 2 
9 1 2 7 
8 2 4 4 3 9 1 7 2 8 7 
42 
11 7 
1 1 1 1 1 1 1 1 
</pre></div></div></div><div class="note"><div class="section-title">Note</div><p>In the first test case, the sequence $$$a$$$ matches the sequence from the statement. The whiteboard states after each step look like this:</p><p>$$$[3] \Rightarrow [3, 1] \Rightarrow [3, 4, 1] \Rightarrow [3, 4, 1, 1] \Rightarrow [3, 4, 5, 1, 1] \Rightarrow [3, 4, 5, 9, 1, 1] \Rightarrow [3, 4, 5, 2, 9, 1, 1]$$$.</p></div>