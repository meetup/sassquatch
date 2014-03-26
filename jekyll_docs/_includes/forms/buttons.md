<div class="line-gutters">
	<div class="unit size1of3">
		<h2>Buttons</h2>
		<p>As a rule, buttons are for actions, not navigation. This style applies to {% highlight html %}<input type="submit" />, <button> {% endhighlight %}, and anything with the class <code>.button</code>.</p> 
		<p>The default is a simple gray button. There is also red <code>.primary</code> class for "do this one thing" actions.</p>		
		<p>For side-by-side inputs and buttons, you'll probably want something a little smaller than the default button. For this, you can use the <code>.small</code> class.</p>		
		<p class="highlighted"><strong>Note:</strong> a full list of button types can be found on <a href="tests/buttons.html" target="_blank">this test page</a></p>
	</div>
	<div class="unit lastUnit">
        <h3>Default buttons</h3>
		<div class="doc-box">
			<div class="doc-content">
				<h4>Submit inputs</h4>
				<input type="submit" class="button--primary" value="Primary" /> 
				<input type="submit" value="Default" />
				<input type="submit" class="button--active" value="Active" />
			</div>
			<div class="doc-content">
				<h4>Anchors with button classes</h4>
				<a href="#" class="button--primary">Primary</a>
				<a href="#" class="button">Default</a>
				<a href="#" class="button--primary button--active">Primary Active</a>
			</div>
		</div>
        <h3>Inline button next to an input (<code>.button--primary.inline</code>)</h3> 
		<div class="doc-box">
			<div class="doc-content">
                <input type="text" class="inline" />
				<input class="inline button--primary" type="submit" value="Default" />
			</div>
		</div>
	</div>
</div>
