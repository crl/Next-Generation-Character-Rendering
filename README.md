# Next-Generation-Character-Rendering
My implementation for character rendering in unity URP, including eyes、face and hair.

For face I will try to render with 4s and Pre-integration algrithmn.

For eyes, I will take a multi-layer eye structures method to render for a more realistic representation.Since I can't share the model and texture resources, I will only share the algorithm and shader code.

![image](https://user-images.githubusercontent.com/56297955/178153442-a370562f-6767-4f0a-83a5-53deed8fc9a6.png)

And for hair, it is actually the most difficult one, I think Kajia's anisotropic algorithm has been enough to achieve a good results.But if you want more details, the hair model have to be more complicated, then the alpha blend will cause a serious problem: transparency sorting.

So far, OIT has been a good solution.
