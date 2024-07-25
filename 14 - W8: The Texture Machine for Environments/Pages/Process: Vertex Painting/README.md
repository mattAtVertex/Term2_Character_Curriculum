# Process: Vertex Painting

<h2>Overview</h2>
<p>In the videos below, you'll be introduced to Vertex Painting and learn how to set up a simple Vertex Paintable material.</p>
<hr>
<h3>Part 1: Setting up for Vertex Painting</h3>
<p><iframe src="https://www.youtube.com/embed/l4piMRgup6s?rel=0" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe></p>
<hr>
<h3>Part 2: Creating the Texture Parameters</h3>
<p><iframe src="https://www.youtube.com/embed/3yqKmiVboFo?rel=0" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe></p>
<hr>
<h2>Vertex Painting</h2>
<p dir="ltr"><img style="float: right; padding: 0 0 20px 20px;" src="https://vertexschool.instructure.com/courses/17/files/860/preview" alt="VertexPainting.jpg" width="600" height="305" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/17/files/860" data-api-returntype="File"></p>
<p style="text-align: left;">Vertex painting is the act of painting directly on the mesh. As you paint, it is associating that color with the vertex point you are painting on. How we take advantage of Vertex Painting in Unreal Engine is by treating these vertex colors as masks. This means we can blend between different materials on a single mesh by painting the blends. This is really useful for creating variation in your scene and breaking up repetition.</p>
<p><strong>Things to Remember:</strong></p>
<ul>
<li>For Vertex Painting to work, your mesh needs to have enough vertices to be able to paint</li>
<li>A vertex paintable material is only one draw call, but all textures for each layer still have to be loaded into memory</li>
<li>Vertex painting lets seamlessly blend between two texture sets</li>
</ul>
<p>&nbsp;</p>