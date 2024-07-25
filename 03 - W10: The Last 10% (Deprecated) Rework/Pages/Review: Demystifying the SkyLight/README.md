# Review: Demystifying the SkyLight

<h2>Overview</h2>
<p>In this review, we're going to take an even deeper dive into working with the Sky Light and using HDRIs</p>
<p><iframe src="https://www.youtube.com/embed/4oZgB04Fy9s" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe></p>
<hr>
<h2>Demystifying the Sky Light</h2>
<p><span>The Sky Light is a powerful component that defines a large part of our lighting. It acts very much as an HDRI light setup. It can do this in two different ways:</span></p>
<ol>
<li><strong>Captured Scene</strong> <span> - In this mode, the sky light takes a screen capture of the sky and uses that as an HDRI.</span></li>
<li><strong style="font-family: inherit; font-size: 1rem;">Specified Cubemap</strong> <span> - In this mode, you assign an HDRI map.</span></li>
</ol>
<p><span>One of the primary purposes of the Skylight is to <strong>add detail in the shadows</strong>.</span></p>
<h3>Common Settings</h3>
<ul>
<li><span>When using the Captured Scene mode, the </span><strong>Sky Distance Threshold</strong> <span> sets distance from the sky light where any geometry is treated as the sky. Anything beyond this will contribute to the overall captured scene. This also affects the reflection captures as well.</span></li>
<li><strong>Light Color</strong> <span> works in both modes and affects the overall color tint. This can also affect the intensity of the light when adjusting the color value. This can drive the color of your shadows.</span></li>
<li><strong>Indirect Lighting Intensity</strong> <span> controls how much the sky light affects indirect light in the global illumination. This has a noticeable effect in the shadowed areas.</span></li>
<li><strong>Volumetric Scattering Intensity</strong> <span> controls the scattering of this light when using Volumetric Fog</span></li>
</ul>
<p><img src="https://vertexschool.instructure.com/courses/464/files/27974/preview?verifier=afTDmVoAgVksFvDTaCN8CVwa0YIgXQZhJVSs6NTt" alt="SkylightSettings.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/464/files/27974" data-api-returntype="File">&nbsp;&nbsp;</p>
<p>&nbsp;</p>
<hr>
<h2>Setting Up Your HDRI</h2>
<p>The HDRI is one of the most important aspects of the sky light. It's going to help define the atmosphere the underlying tone of your scene and emphasize the color scheme in your shadows. Setting it up involves just a few steps:</p>
<ol>
<li>Set the Sky Light to use Specified Cubemap</li>
<li>Assign your HDRI texture to the Cubemap property</li>
<li>Adjust the Cubemap Angle to get the desired lighting effect</li>
</ol>
<p><img src="https://vertexschool.instructure.com/courses/464/files/27975/preview?verifier=24OUNr1Dwxrf2s2GpcClvvnqc2OUBmRDnWeWQw10" alt="Setting up Cubemap.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/464/files/27975" data-api-returntype="File">&nbsp;&nbsp;</p>
<p>&nbsp;</p>
<p>For a Step-by-Step, you can <a href="https://docs.google.com/document/d/1yyqoMfMgTRz6v9MTTles7BY8v-bQMBsJJaRK8bsofFg/edit#heading=h.c8ebf2cd3y2p">Follow This Guide</a></p>
<hr>
<h2>Finding an HDRI</h2>
<p>The HDRI is important to your mood, so finding the right one is vital. Having options to test out is even more vital. A good place to find free HDRI images to use is <a href="https://hdrihaven.com/"> <span>https://hdrihaven.com/</span> </a> . They have a lot of options in there that will usually cover all needs.</p>
<p><img src="https://vertexschool.instructure.com/courses/464/files/27977/preview?verifier=KJ3adcvSCbW5Gn2CDqc2GNo1Tzm7pRhipecMZzx2" alt="HDRIHaven.png" width="640" height="514" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/464/files/27977" data-api-returntype="File">&nbsp;&nbsp;</p>
<p>&nbsp;</p>
<p>The files that you download should import into Unreal just fine as is and can be immediately plugged into your sky light. You don't need to grab a huge resolution either.&nbsp; The 2k size is more than efficient.&nbsp; Remember to choose an HDRI that is going to match the lighting scenario of your scene. Don't be afraid to try a couple of different ones until you get the right setup.&nbsp;</p>
<p>&nbsp;</p>