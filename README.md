# ArParallax.js
ArParallax.js is a lightweight customizable jQuery plugin which utilizes CSS3 3D transforms to create a smooth parallax	effect on your images when scrolling down or up. [Demo page](https://rodzyk.github.io/arparallax.js/)

## Installation
Download and include arparallax.min.js in your document after including jQuery.
```
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="js/arparallax.min.js"></script>
```

## Useage

### HTML
```
<div class="arparallax">
	<div class="imageContainer">
		<!-- image or video -->
	</div>
</div>
```

### JS

```
$('.arparallax').arparallax();
```

## Options

<table class="table table-bordered table-striped">
<thead>
    <tr>
<th style="width: 100px;">Name</th>
<th style="width: 100px;">type</th>
<th style="width: 50px;">default</th>
<th>description</th>
</tr>
</thead>
<tbody>
				<tr>
					<td>
						<code>speed</code>
					</td>
					<td>
						<code>float</code>
					</td>
					<td>
						<code>0.32</code>
					</td>
					<td>The speed at which the parallax effect runs.
						<code>0.0</code> means the image will appear fixed in place, and
						<code>1.0</code> the image will flow at the same speed as the page content.</td>
				</tr>
				<tr>
					<td>
						<code>imageContainer</code>
					</td>
					<td>
						<code>jQuery Selector</code>
					</td>
					<td>
						<code>.image</code>
					</td>
					<td>The parallax fx will be prepended into this container.</td>
				</tr>
				<tr>
					<td>
						<code>blur</code>
					</td>
					<td>
						<code>string</code>
					</td>
					<td>
						<code>auto</code>
					</td>
					<td>You can provide the blur effect for your image.
						<br>Values:
						<code>auto</code> |
						<code>both</code> |
						<code>up</code> |
						<code>bottom</code> |
						<code>none</code>.</td>
				</tr>
<tr>
					<td>
						<code>blurMultiplier</code>
					</td>
					<td>
						<code>number</code>
					</td>
					<td>
						<code>1</code>
					</td>
					<td>You can specify a multiplier for the blur effect.</td>
				</tr>
<tr>
					<td>
						<code>scaleMultiplier</code>
					</td>
					<td>
						<code>number</code>
					</td>
					<td>
						<code>0.05</code>
					</td>
					<td>You can specify a multiplier for the scale effect.
						<br>
						<code>0</code>for disable effect.</td>
				</tr>
<tr>
					<td>
						<code>depth</code>
					</td>
					<td>
						<code>string</code>
					</td>
					<td>
						<code>direct</code>
					</td>
					<td>You can provide the perspective for your image.
						<br>Values:
						<code>direct</code> |
						<code>reverse</code> |
						<code>none</code>.
					</td>
</tr>
</tbody>
		
</table>
