---


---

<h3 id="combat-calculation">Combat Calculation</h3>
<h3 id="raid-loot-calculation">Raid (Loot calculation)</h3>
<ul>
<li>
<p>Calculate lootable resources separate for each resource type<br>
<code>total resources - hidden resources * (1-plunder value)</code></p>
<ul>
<li>Station has 1.000 metal, 1.500 gas &amp; 2.500 crystal</li>
<li>Station has 2.000 <strong>hidden resources</strong></li>
<li>Fleets have 40% <strong>average plunder value</strong></li>
<li>Fleets can take up to 0 metal, 300 gas &amp; 1.300 crystal</li>
</ul>
</li>
<li>
<p>If the lootable resources are more than the fleets combined capacity they take from some each resource based on the total amount. Decimals are rounded up until the capacity is reached.</p>
<ul>
<li>Fleets can take up to 0 metal, 300 gas &amp; 1.300 crystal</li>
<li>Fleets have 1.000 <strong>combined cargo</strong></li>
<li>Fleets take 0 metal, 188 gas &amp; 812 crystal</li>
</ul>
</li>
</ul>
<h3 id="assault-bomb-calculation">Assault (Bomb calculation)</h3>
<p>The following steps are done once per combat phase, so <strong>3 times</strong> in total.<br>
Each fleet can target the same buildings each phase, but it doesn’t have to.</p>
<ul>
<li>Each attacking fleet…
<ul>
<li>it targets 2 separate buildings at random. (3 with military policy)</li>
<li>it deals his full <strong>Station Bombing</strong> value as damage to each of them.</li>
</ul>
</li>
<li>Each building checks its remaining health and …
<ul>
<li>if it’s 0 or less the building is completely destroyed.</li>
<li>if it’s between the max health of two building levels it’s downgraded to the higher one of these and regenerates the health up this level.</li>
</ul>
</li>
</ul>
<h3 id="sabotage-sabotage-calculation">Sabotage (Sabotage calculation)</h3>

