# Sprite-UV-Transform
This script will return a transform array that can be used in a shader to remap the UVs of one sprite to the UVs of another regardless of scaling or cropping.

This script takes 4 arguments, the sprite and subimage you want to map the uv to and the sprite and subimage containing the UVs you want to remap

Returns an array with: x offset, y offset, x scale, y scale. To see how it's used in a shader take a peek at: "UVTransformVertexShader"

The raw script text is avaliable "UVTransformScript", the raw vertex shader is also available "UVTransformVertexShader"

To see it in action and how it is used there is also a demo project "UVTransform.yyz"
