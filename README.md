# lab02-debugging
I am Avi Serebrenik, I worked with Dan Gerhardt.
Solution: 
Found each bug: first was a compiler error for vec2, then not using uv2 over there. Then I found that the warping was due to dividing x by x at the top instead of x by y to get the right screen size. Next we saw that we wanted the floor to extend further, so we extended ray marching loop count. Finally we knew the reflections were wrong and it was somewhere in the specular area, but needed help to point out that we were reflecting eye instead of dir.

Link: https://www.shadertoy.com/view/tclBWf
# Setup 

Create a [Shadertoy account](https://www.shadertoy.com/). Either fork this shadertoy, or create a new shadertoy and copy the code from the [Debugging Puzzle](https://www.shadertoy.com/view/flGfRc).

Let's practice debugging! We have a broken shader. It should produce output that looks like this:
[Unbelievably beautiful shader](https://user-images.githubusercontent.com/1758825/200729570-8e10a37a-345d-4aff-8eff-6baf54a32a40.webm)

It don't do that. Correct THREE of the FIVE bugs that are messing up the output. You are STRONGLY ENCOURAGED to work with a partner and pair program to force you to talk about your debugging thought process out loud.

Extra credit if you can find all FIVE bugs.

# Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solution with the bugs corrected
- In the README, describe each bug you found and include a sentence about HOW you found it.
- Make sure all three of your shadertoys are set to UNLISTED or PUBLIC (so we can see them!)
