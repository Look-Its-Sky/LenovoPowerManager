<h1>Lenovo Power Manager Script</h1>

<p>LenovoPowerManager is designed to activate different power management modes
on Lenovo laptops that support ACPI power management.</p>

<h2>Prerequisites</h2>
<p>Before using this script, ensure that you meet the following prerequisites:</p>
<ul>
<li>Have <code>acpi_calls</code> installed</li>
<li>Always give this script root access. It won't work without it</li>
</ul>

<h2>Usage</h2>
<p>Run the script with appropriate options to activate the desired power management mode:</p>
<pre><code>python LenovoPowerManager.py [options]</code></pre>
<h3>Options</h3>

<ul>
  <li><code>-bs, --battery-saver</code>: Activates Battery Saver mode.</li>
  <li><code>-ic, --intelligent-cooling</code>: Activates Intelligent Cooling mode.</li>
  <li><code>-ep, --extreme-performance</code>: Activates Extreme Performance mode.</li>
</ul>

<h2>Example Usage</h2>
<p>To activate Intelligent Cooling mode, run:</p>
<pre><code>python LenovoPowerManager.py --ic</code></pre>

<p>To activate Extreme Performance mode, run:</p>
<pre><code>python LenovoPowerManager.py --ep</code></pre>

<p>To activate Battery Saver mode, run:</p>
<pre><code>python LenovoPowerManager.py --bs</code></pre>
