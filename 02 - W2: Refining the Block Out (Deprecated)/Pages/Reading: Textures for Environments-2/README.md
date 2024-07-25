# Reading: Textures for Environments-2

<h2>Overview: Breaking Down Your Textures</h2>
<p>In the previous sprint, we took a first pass at breaking the materials down for our scene. We started planning out what can be tileable, what can be a trim sheet, and what needs to be unique. With this basic plan in hand, let's have a deeper look into materials.</p>
<p>Planning ahead will always make your scenes come together more quickly and efficiently. It's good to figure out your material breakdown early so you are never questioning what to make next.</p>
<hr>
<h2>The Three Types of Textures</h2>
<div style="float: right; margin: 0 0 20px 20px;"><img src="https://vertexschool.instructure.com/courses/464/files/27994/preview?verifier=z6Vkc2TciPOnWxO5zZM6XlIjWu40MM7iolldt1w5" width="700" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/464/files/27994" data-api-returntype="File">&nbsp;</div>
<p>When planning out your texture breakdown, there are three primary types of textures you'll typically use.&nbsp; The type of texture used for an asset affects how you build it and what level of effort needs to be spent.</p>
<p>&nbsp;</p>
<p><em><strong>You want to break it down into the 3 main types of textures:</strong></em></p>
<ol>
<li><strong>Tileable</strong> - Your tileable materials are going to utilize tiling textures and will typically be placed on either simple primitives or mid-poly geometry.</li>
<li><strong>Trim Sheet</strong> - Trim sheets use a technique where the textures are divided up into slim areas so you have multiple tiling textures in one UV set. These are typically then mapped onto trim pieces.</li>
<li><strong>Unique</strong> - Unique materials are what you are already used to with prop modeling where you unwrap your UVs into a unique non-overlapping texture set.</li>
</ol>
<p>&nbsp;</p>
<hr style="clear: both;">
<h2>Consolidation</h2>
<div style="float: right; padding: 0 0 20px 20px;"><img src="https://vertexschool.instructure.com/courses/464/files/27995/preview?verifier=dx22DDKz235weACcGJik7ZKK7HfEQ2TTOqLkhYUr" width="700" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/464/files/27995" data-api-returntype="File"></div>
<p>Something to keep in mind for unique assets is consolidation of texture sheets to maximize UV space. The easiest place to start with is similar assets.</p>
<p>For example, you might have two pillars. It would make sense to have these share a single texture sheet. As another example, you might have a table and a chair. It would make sense for them to share a texture sheet as well.&nbsp;</p>
<p>The primary goal is to maximize UV space usage to minimize wasted texture space, so you want to consolidate in ways that will accomplish that while still maintaining proper Texel Density. This means in many scenarios, a single prop will likely have its own texture sheet.</p>
<div>&nbsp;</div>